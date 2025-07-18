# Graphiant SDK Go

[![Go Version](https://img.shields.io/badge/go-1.18+-blue.svg)](https://golang.org/dl/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Go Reference](https://pkg.go.dev/badge/github.com/Graphiant-Inc/graphiant-sdk-go.svg)](https://pkg.go.dev/github.com/Graphiant-Inc/graphiant-sdk-go)
[![Go Report Card](https://goreportcard.com/badge/github.com/Graphiant-Inc/graphiant-sdk-go)](https://goreportcard.com/report/github.com/Graphiant-Inc/graphiant-sdk-go)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://docs.graphiant.com/docs/graphiant-sdk-go)

A comprehensive Go SDK for [Graphiant Network-as-a-Service (NaaS)](https://www.graphiant.com), providing seamless integration with Graphiant's network automation platform.

## 📚 Documentation

- **Official Documentation**: [Graphiant SDK Go Guide](https://docs.graphiant.com/docs/graphiant-sdk-go)
- **API Reference**: [Go Package Documentation](https://pkg.go.dev/github.com/Graphiant-Inc/graphiant-sdk-go)
- **Examples**: [Generated Examples](docs/examples/)

## ✨ Features

- **Complete API Coverage**: Full access to all Graphiant REST API endpoints
- **Type Safety**: Generated from OpenAPI specification for complete type safety
- **Authentication**: Built-in bearer token authentication
- **Device Management**: Comprehensive device configuration and monitoring
- **Network Operations**: Circuit management, BGP configuration, and routing
- **Monitoring**: Real-time network monitoring and metrics collection
- **Error Handling**: Robust error handling with detailed error messages
- **Extranet Management**: Extranet service configuration and monitoring
- **Integration Ready**: Third-party integration capabilities

## 🚀 Quick Start

### Installation

Install the SDK using Go modules:

```bash
go get github.com/Graphiant-Inc/graphiant-sdk-go
```

### Basic Usage

```go
package main

import (
	"context"
	"encoding/json"
	"fmt"
	"log"
	"os"

	"github.com/Graphiant-Inc/graphiant-sdk-go"
)

func main() {
	// Create configuration
	config := graphiant_sdk.NewConfiguration()
	config.Host = "https://portal.graphiant.com" // or your custom host
	
	// Create API client
	client := graphiant_sdk.NewAPIClient(config)
	
	// Authentication request
	authReq := graphiant_sdk.NewV1AuthLoginPostRequest()
	authReq.SetUsername("your-username")
	authReq.SetPassword("your-password")
	
	// Get authentication token
	_, httpRes, err := client.DefaultAPI.
		V1AuthLoginPost(context.Background()).
		V1AuthLoginPostRequest(*authReq).
		Execute()
	
	if err != nil {
		log.Fatalf("Authentication failed: %v", err)
	}
	defer httpRes.Body.Close()
	
	// Parse authentication response
	var authResult struct {
		Auth        bool   `json:"auth"`
		AccountType string `json:"accountType"`
		Token       string `json:"token"`
	}
	
	if err := json.NewDecoder(httpRes.Body).Decode(&authResult); err != nil {
		log.Fatalf("Failed to decode auth response: %v", err)
	}
	
	if !authResult.Auth {
		log.Fatal("Authentication failed")
	}
	
	bearerToken := "Bearer " + authResult.Token
	
	// Get edge devices summary
	resp, _, err := client.DefaultAPI.
		V1EdgesSummaryGet(context.Background()).
		Authorization(bearerToken).
		Execute()
	
	if err != nil {
		log.Fatalf("Failed to get edge summary: %v", err)
	}
	
	// Print edge devices
	edges := resp.GetEdgesSummary()
	fmt.Printf("Found %d edge devices:\n", len(edges))
	for _, edge := range edges {
		fmt.Printf("- Device ID: %d, Hostname: %s, Status: %s\n",
			edge.GetDeviceId(), edge.GetHostname(), edge.GetStatus())
	}
}
```

## 🔧 Advanced Usage

### Device Configuration Management

```go
// Verify device portal status before configuration
func verifyDevicePortalStatus(client *graphiant_sdk.APIClient, bearerToken string, deviceID int64) error {
	resp, _, err := client.DefaultAPI.
		V1EdgesSummaryGet(context.Background()).
		Authorization(bearerToken).
		Execute()
	
	if err != nil {
		return fmt.Errorf("failed to get edges summary: %v", err)
	}
	
	for _, edge := range resp.GetEdgesSummary() {
		if edge.GetDeviceId() == deviceID {
			if edge.GetPortalStatus() == "Ready" && edge.GetTtConnCount() == 2 {
				return nil
			} else {
				return fmt.Errorf("device %d not ready. Status: %s, TT Connections: %d",
					deviceID, edge.GetPortalStatus(), edge.GetTtConnCount())
			}
		}
	}
	return fmt.Errorf("device %d not found", deviceID)
}

// Configure device interfaces
func configureDeviceInterfaces(client *graphiant_sdk.APIClient, bearerToken string, deviceID int64) error {
	// Define circuits
	circuits := map[string]graphiant_sdk.V1DevicesDeviceIdConfigPutRequestEdgeCircuitsValue{
		"c-gigabitethernet5-0-0": {
			Name:              graphiant_sdk.PtrString("c-gigabitethernet5-0-0"),
			Description:       graphiant_sdk.PtrString("c-gigabitethernet5-0-0"),
			LinkUpSpeedMbps:   graphiant_sdk.PtrInt32(50),
			LinkDownSpeedMbps: graphiant_sdk.PtrInt32(100),
			ConnectionType:    graphiant_sdk.PtrString("internet_dia"),
			Label:             graphiant_sdk.PtrString("internet_dia_4"),
			QosProfile:        graphiant_sdk.PtrString("gold25"),
			QosProfileType:    graphiant_sdk.PtrString("balanced"),
			DiaEnabled:        graphiant_sdk.PtrBool(false),
			LastResort:        graphiant_sdk.PtrBool(false),
		},
	}
	
	// Define interfaces
	interfaces := map[string]graphiant_sdk.V1DevicesDeviceIdConfigPutRequestEdgeInterfacesValue{
		"GigabitEthernet5/0/0": {
			Interface: &graphiant_sdk.V1DevicesDeviceIdConfigPutRequestEdgeInterfacesValueInterface{
				AdminStatus:       graphiant_sdk.PtrBool(true),
				MaxTransmissionUnit: graphiant_sdk.PtrInt32(1500),
				Circuit:           graphiant_sdk.PtrString("c-gigabitethernet5-0-0"),
				Description:       graphiant_sdk.PtrString("wan_1"),
				Alias:             graphiant_sdk.PtrString("primary_wan"),
				Ipv4: &graphiant_sdk.V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw{
					Dhcp: &graphiant_sdk.V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGwDhcp{
						DhcpClient: graphiant_sdk.PtrBool(true),
					},
				},
				Ipv6: &graphiant_sdk.V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw{
					Dhcp: &graphiant_sdk.V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGwDhcp{
						DhcpClient: graphiant_sdk.PtrBool(true),
					},
				},
			},
		},
	}
	
	// Create configuration request
	edgeConfig := graphiant_sdk.V1DevicesDeviceIdConfigPutRequestEdge{
		Circuits:   &circuits,
		Interfaces: &interfaces,
	}
	
	configRequest := graphiant_sdk.V1DevicesDeviceIdConfigPutRequest{
		Edge: &edgeConfig,
	}
	
	// Verify device is ready
	if err := verifyDevicePortalStatus(client, bearerToken, deviceID); err != nil {
		return fmt.Errorf("device not ready: %v", err)
	}
	
	// Push configuration
	_, _, err := client.DefaultAPI.
		V1DevicesDeviceIdConfigPut(context.Background(), deviceID).
		Authorization(bearerToken).
		V1DevicesDeviceIdConfigPutRequest(configRequest).
		Execute()
	
	if err != nil {
		return fmt.Errorf("configuration failed: %v", err)
	}
	
	fmt.Printf("Configuration job submitted for device %d\n", deviceID)
	return nil
}
```

### BGP Monitoring

```go
func getBgpMonitoring(client *graphiant_sdk.APIClient, bearerToken string) error {
	// Create BGP monitoring request
	bgpReq := graphiant_sdk.NewV2MonitoringBgpPostRequest()
	
	// Configure selectors
	selectors := []graphiant_sdk.V2MonitoringBgpPostRequestSelectorsInner{
		{
			Type:  graphiant_sdk.PtrString("enterprise"),
			Value: graphiant_sdk.PtrString("your-enterprise-id"),
		},
	}
	bgpReq.SetSelectors(selectors)
	
	// Get BGP monitoring data
	bgpResp, _, err := client.DefaultAPI.
		V2MonitoringBgpPost(context.Background()).
		Authorization(bearerToken).
		V2MonitoringBgpPostRequest(*bgpReq).
		Execute()
	
	if err != nil {
		return fmt.Errorf("BGP monitoring failed: %v", err)
	}
	
	// Process BGP data
	bgpData := bgpResp.GetData()
	fmt.Printf("Retrieved %d BGP monitoring records\n", len(bgpData))
	
	for _, record := range bgpData {
		fmt.Printf("BGP Session: %s, State: %s\n", 
			record.GetSessionId(), record.GetState())
	}
	
	return nil
}
```

### Circuit Monitoring

```go
func getCircuitMonitoring(client *graphiant_sdk.APIClient, bearerToken string) error {
	// Create circuit monitoring request
	circuitReq := graphiant_sdk.NewV2MonitoringCircuitsSummaryPostRequest()
	
	// Configure selectors
	selectors := []graphiant_sdk.V2MonitoringCircuitsSummaryPostRequestSelectorsInner{
		{
			Type:  graphiant_sdk.PtrString("enterprise"),
			Value: graphiant_sdk.PtrString("your-enterprise-id"),
		},
	}
	circuitReq.SetSelectors(selectors)
	
	// Get circuit monitoring data
	circuitResp, _, err := client.DefaultAPI.
		V2MonitoringCircuitsSummaryPost(context.Background()).
		Authorization(bearerToken).
		V2MonitoringCircuitsSummaryPostRequest(*circuitReq).
		Execute()
	
	if err != nil {
		return fmt.Errorf("circuit monitoring failed: %v", err)
	}
	
	// Process circuit data
	circuitData := circuitResp.GetData()
	fmt.Printf("Retrieved %d circuit monitoring records\n", len(circuitData))
	
	for _, circuit := range circuitData {
		fmt.Printf("Circuit: %s, Status: %s, Bandwidth: %d Mbps\n",
			circuit.GetCircuitId(), circuit.GetStatus(), circuit.GetBandwidthMbps())
	}
	
	return nil
}
```

### Error Handling

```go
func handleApiErrors(client *graphiant_sdk.APIClient, bearerToken string) {
	resp, httpRes, err := client.DefaultAPI.
		V1EdgesSummaryGet(context.Background()).
		Authorization(bearerToken).
		Execute()
	
	if err != nil {
		// Handle different types of errors
		if apiErr, ok := err.(*graphiant_sdk.GenericOpenAPIError); ok {
			fmt.Printf("API Error: %s\n", apiErr.Error())
			fmt.Printf("Response Body: %s\n", string(apiErr.Body()))
			
			// Check HTTP status code
			if httpRes != nil {
				switch httpRes.StatusCode {
				case 401:
					fmt.Println("Unauthorized: Check your credentials")
				case 403:
					fmt.Println("Forbidden: Check your permissions")
				case 404:
					fmt.Println("Not Found: Resource doesn't exist")
				case 500:
					fmt.Println("Server Error: Try again later")
				}
			}
		} else {
			fmt.Printf("Unexpected error: %v\n", err)
		}
		return
	}
	defer httpRes.Body.Close()
	
	// Process successful response
	edges := resp.GetEdgesSummary()
	fmt.Printf("Successfully retrieved %d edges\n", len(edges))
}
```

## 🛠️ Development

### Prerequisites

- Go 1.18 or higher
- Git
- OpenAPI Generator (for code generation)

### Building from Source

```bash
# Clone repository
git clone https://github.com/Graphiant-Inc/graphiant-sdk-go
cd graphiant-sdk-go

# Install dependencies
go mod tidy

# Build the project
go build ./...

# Run tests
go test ./...
```

### Code Generation

To regenerate the SDK from the latest API specification:

```bash
# Install OpenAPI Generator
brew install openapi-generator  # macOS
# or download from: https://github.com/OpenAPITools/openapi-generator

# Generate SDK
openapi-generator generate \
  -i graphiant_api_docs_v25.7.1.json \
  -g go \
  --git-user-id Graphiant-Inc \
  --git-repo-id graphiant-sdk-go \
  --package-name graphiant_sdk \
  --additional-properties=packageVersion=25.7.1
```

> **Note**: Latest API documentation can be downloaded from the Graphiant portal under "Support Hub" > "Developer Tools".

### Testing

```bash
# Set environment variables for testing
export username="your-test-username"
export password="your-test-password"

# Run all tests
go test ./...

# Run specific test
go test -v -run Test_edge_summary

# Run tests with coverage
go test -cover ./...

# Run tests with verbose output
go test -v ./test/
```

### Project Structure

```
graphiant-sdk-go/
├── api_default.go              # Main API service
├── client.go                   # HTTP client implementation
├── configuration.go            # Configuration management
├── model_*.go                  # Generated data models
├── response.go                 # Response handling
├── utils.go                    # Utility functions
├── version.go                  # Version information
├── test/                       # Test files
│   ├── sanity_test.go          # Basic functionality tests
│   ├── api_default_test.go     # API tests
│   └── version_test.go         # Version tests
├── docs/                       # Generated documentation
│   ├── api/                    # API documentation
│   ├── examples/               # Usage examples
│   └── *.md                    # Model documentation
├── go.mod                      # Go module definition
└── README.md                   # This file
```

## 📖 API Reference

### Core Classes

- **`Configuration`**: Client configuration with authentication
- **`APIClient`**: HTTP client for API requests
- **`DefaultAPI`**: Main API interface with all endpoints

### Key Models

- **`V1AuthLoginPostRequest`**: Authentication request
- **`V1EdgesSummaryGet200Response`**: Device summary response
- **`V1DevicesDeviceIdConfigPutRequest`**: Device configuration request
- **`V2MonitoringBgpPostRequest`**: BGP monitoring request
- **`V2MonitoringCircuitsSummaryPostRequest`**: Circuit monitoring request

### Common Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/v1/auth/login` | POST | Authenticate and get bearer token |
| `/v1/edges/summary` | GET | Get all device summaries |
| `/v1/devices/{device_id}` | GET | Get device details |
| `/v1/devices/{device_id}/config` | PUT | Update device configuration |
| `/v2/monitoring/bgp` | POST | Get BGP monitoring data |
| `/v2/monitoring/circuits/summary` | POST | Get circuit monitoring data |

## 🔐 Security

- **Authentication**: Bearer token-based authentication
- **HTTPS**: All API communications use HTTPS
- **Credentials**: Store credentials securely using environment variables
- **Token Management**: Bearer tokens expire and should be refreshed as needed

### Environment Variables

```bash
export GRAPHIANT_HOST="https://portal.graphiant.com"
export GRAPHIANT_USERNAME="your_username"
export GRAPHIANT_PASSWORD="your_password"
```

```go
username := os.Getenv("GRAPHIANT_USERNAME")
password := os.Getenv("GRAPHIANT_PASSWORD")
host := os.Getenv("GRAPHIANT_HOST")
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Documentation**: [Graphiant Docs](https://docs.graphiant.com/)
- **API Reference**: [Go Package Documentation](https://pkg.go.dev/github.com/Graphiant-Inc/graphiant-sdk-go)
- **Issues**: [GitHub Issues](https://github.com/Graphiant-Inc/graphiant-sdk-go/issues)
- **Community**: [Graphiant Community](https://community.graphiant.com/)
- **Email**: support@graphiant.com

## 🔗 Related Projects

- [Graphiant SDK Python](https://github.com/Graphiant-Inc/graphiant-sdk-python)
- [Graphiant Portal REST API](https://docs.graphiant.com/docs/graphiant-portal-rest-api)
- [Graphiant Playbooks](https://github.com/Graphiant-Inc/graphiant-playbooks)

---

**Made with ❤️ by the Graphiant Team**

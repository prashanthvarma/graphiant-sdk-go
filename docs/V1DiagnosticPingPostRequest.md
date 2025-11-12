# V1DiagnosticPingPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **int64** | Valid Provisioned device ID (required) | 
**Params** | Pointer to [**DiagnosticToolsDiagnosticParams**](DiagnosticToolsDiagnosticParams.md) |  | [optional] 
**Token** | Pointer to **string** | Identifier which was received in initial response | [optional] 
**TransportType** | **string** | ICMP or TCP (required) | 

## Methods

### NewV1DiagnosticPingPostRequest

`func NewV1DiagnosticPingPostRequest(deviceId int64, transportType string, ) *V1DiagnosticPingPostRequest`

NewV1DiagnosticPingPostRequest instantiates a new V1DiagnosticPingPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticPingPostRequestWithDefaults

`func NewV1DiagnosticPingPostRequestWithDefaults() *V1DiagnosticPingPostRequest`

NewV1DiagnosticPingPostRequestWithDefaults instantiates a new V1DiagnosticPingPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1DiagnosticPingPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1DiagnosticPingPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1DiagnosticPingPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.


### GetParams

`func (o *V1DiagnosticPingPostRequest) GetParams() DiagnosticToolsDiagnosticParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *V1DiagnosticPingPostRequest) GetParamsOk() (*DiagnosticToolsDiagnosticParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *V1DiagnosticPingPostRequest) SetParams(v DiagnosticToolsDiagnosticParams)`

SetParams sets Params field to given value.

### HasParams

`func (o *V1DiagnosticPingPostRequest) HasParams() bool`

HasParams returns a boolean if a field has been set.

### GetToken

`func (o *V1DiagnosticPingPostRequest) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DiagnosticPingPostRequest) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DiagnosticPingPostRequest) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DiagnosticPingPostRequest) HasToken() bool`

HasToken returns a boolean if a field has been set.

### GetTransportType

`func (o *V1DiagnosticPingPostRequest) GetTransportType() string`

GetTransportType returns the TransportType field if non-nil, zero value otherwise.

### GetTransportTypeOk

`func (o *V1DiagnosticPingPostRequest) GetTransportTypeOk() (*string, bool)`

GetTransportTypeOk returns a tuple with the TransportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransportType

`func (o *V1DiagnosticPingPostRequest) SetTransportType(v string)`

SetTransportType sets TransportType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



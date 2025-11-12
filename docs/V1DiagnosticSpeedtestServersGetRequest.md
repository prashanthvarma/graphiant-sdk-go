# V1DiagnosticSpeedtestServersGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **int64** | Unique identifier for a specific device (required) | 
**Provider** | Pointer to **string** | supported provider for speedtest utility | [optional] 
**VrfName** | Pointer to **string** | Configured VRF Name | [optional] 

## Methods

### NewV1DiagnosticSpeedtestServersGetRequest

`func NewV1DiagnosticSpeedtestServersGetRequest(deviceId int64, ) *V1DiagnosticSpeedtestServersGetRequest`

NewV1DiagnosticSpeedtestServersGetRequest instantiates a new V1DiagnosticSpeedtestServersGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticSpeedtestServersGetRequestWithDefaults

`func NewV1DiagnosticSpeedtestServersGetRequestWithDefaults() *V1DiagnosticSpeedtestServersGetRequest`

NewV1DiagnosticSpeedtestServersGetRequestWithDefaults instantiates a new V1DiagnosticSpeedtestServersGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1DiagnosticSpeedtestServersGetRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1DiagnosticSpeedtestServersGetRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1DiagnosticSpeedtestServersGetRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.


### GetProvider

`func (o *V1DiagnosticSpeedtestServersGetRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *V1DiagnosticSpeedtestServersGetRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *V1DiagnosticSpeedtestServersGetRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *V1DiagnosticSpeedtestServersGetRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetVrfName

`func (o *V1DiagnosticSpeedtestServersGetRequest) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *V1DiagnosticSpeedtestServersGetRequest) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *V1DiagnosticSpeedtestServersGetRequest) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *V1DiagnosticSpeedtestServersGetRequest) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



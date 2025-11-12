# V1DiagnosticGnmiPingGetResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** | Address of the device on which the test was performed | [optional] 
**Error** | Pointer to **string** | If error is empty, the ping is success | [optional] 
**Rtt** | Pointer to [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**TtDeviceId** | Pointer to **int64** |  | [optional] 

## Methods

### NewV1DiagnosticGnmiPingGetResponseResult

`func NewV1DiagnosticGnmiPingGetResponseResult() *V1DiagnosticGnmiPingGetResponseResult`

NewV1DiagnosticGnmiPingGetResponseResult instantiates a new V1DiagnosticGnmiPingGetResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticGnmiPingGetResponseResultWithDefaults

`func NewV1DiagnosticGnmiPingGetResponseResultWithDefaults() *V1DiagnosticGnmiPingGetResponseResult`

NewV1DiagnosticGnmiPingGetResponseResultWithDefaults instantiates a new V1DiagnosticGnmiPingGetResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *V1DiagnosticGnmiPingGetResponseResult) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *V1DiagnosticGnmiPingGetResponseResult) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetError

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *V1DiagnosticGnmiPingGetResponseResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *V1DiagnosticGnmiPingGetResponseResult) HasError() bool`

HasError returns a boolean if a field has been set.

### GetRtt

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetRtt() GoogleProtobufDuration`

GetRtt returns the Rtt field if non-nil, zero value otherwise.

### GetRttOk

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetRttOk() (*GoogleProtobufDuration, bool)`

GetRttOk returns a tuple with the Rtt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRtt

`func (o *V1DiagnosticGnmiPingGetResponseResult) SetRtt(v GoogleProtobufDuration)`

SetRtt sets Rtt field to given value.

### HasRtt

`func (o *V1DiagnosticGnmiPingGetResponseResult) HasRtt() bool`

HasRtt returns a boolean if a field has been set.

### GetTtDeviceId

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetTtDeviceId() int64`

GetTtDeviceId returns the TtDeviceId field if non-nil, zero value otherwise.

### GetTtDeviceIdOk

`func (o *V1DiagnosticGnmiPingGetResponseResult) GetTtDeviceIdOk() (*int64, bool)`

GetTtDeviceIdOk returns a tuple with the TtDeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtDeviceId

`func (o *V1DiagnosticGnmiPingGetResponseResult) SetTtDeviceId(v int64)`

SetTtDeviceId sets TtDeviceId field to given value.

### HasTtDeviceId

`func (o *V1DiagnosticGnmiPingGetResponseResult) HasTtDeviceId() bool`

HasTtDeviceId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



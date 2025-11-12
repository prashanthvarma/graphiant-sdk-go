# V1DiagnosticPacketcaptureStartPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **int64** | Unique identifier for a specific device (required) | 
**Duration** | **int32** | Packet capture duration. Accepted values are 30, 60, 180 (required) | 
**Filter** | Pointer to [**DiagnosticToolsPCapFilter**](DiagnosticToolsPCapFilter.md) |  | [optional] 
**MaxPacketCounter** | Pointer to **int32** | Packet capture limit. | [optional] 
**Target** | [**DiagnosticToolsTargetType**](DiagnosticToolsTargetType.md) |  | 

## Methods

### NewV1DiagnosticPacketcaptureStartPostRequest

`func NewV1DiagnosticPacketcaptureStartPostRequest(deviceId int64, duration int32, target DiagnosticToolsTargetType, ) *V1DiagnosticPacketcaptureStartPostRequest`

NewV1DiagnosticPacketcaptureStartPostRequest instantiates a new V1DiagnosticPacketcaptureStartPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticPacketcaptureStartPostRequestWithDefaults

`func NewV1DiagnosticPacketcaptureStartPostRequestWithDefaults() *V1DiagnosticPacketcaptureStartPostRequest`

NewV1DiagnosticPacketcaptureStartPostRequestWithDefaults instantiates a new V1DiagnosticPacketcaptureStartPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1DiagnosticPacketcaptureStartPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.


### GetDuration

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *V1DiagnosticPacketcaptureStartPostRequest) SetDuration(v int32)`

SetDuration sets Duration field to given value.


### GetFilter

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetFilter() DiagnosticToolsPCapFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetFilterOk() (*DiagnosticToolsPCapFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *V1DiagnosticPacketcaptureStartPostRequest) SetFilter(v DiagnosticToolsPCapFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *V1DiagnosticPacketcaptureStartPostRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### GetMaxPacketCounter

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetMaxPacketCounter() int32`

GetMaxPacketCounter returns the MaxPacketCounter field if non-nil, zero value otherwise.

### GetMaxPacketCounterOk

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetMaxPacketCounterOk() (*int32, bool)`

GetMaxPacketCounterOk returns a tuple with the MaxPacketCounter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPacketCounter

`func (o *V1DiagnosticPacketcaptureStartPostRequest) SetMaxPacketCounter(v int32)`

SetMaxPacketCounter sets MaxPacketCounter field to given value.

### HasMaxPacketCounter

`func (o *V1DiagnosticPacketcaptureStartPostRequest) HasMaxPacketCounter() bool`

HasMaxPacketCounter returns a boolean if a field has been set.

### GetTarget

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetTarget() DiagnosticToolsTargetType`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *V1DiagnosticPacketcaptureStartPostRequest) GetTargetOk() (*DiagnosticToolsTargetType, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *V1DiagnosticPacketcaptureStartPostRequest) SetTarget(v DiagnosticToolsTargetType)`

SetTarget sets Target field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



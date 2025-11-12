# V1EventDeviceGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **int64** | Well known device_id (required) | 
**Filter** | Pointer to [**EventEventFilter**](EventEventFilter.md) |  | [optional] 

## Methods

### NewV1EventDeviceGetRequest

`func NewV1EventDeviceGetRequest(deviceId int64, ) *V1EventDeviceGetRequest`

NewV1EventDeviceGetRequest instantiates a new V1EventDeviceGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EventDeviceGetRequestWithDefaults

`func NewV1EventDeviceGetRequestWithDefaults() *V1EventDeviceGetRequest`

NewV1EventDeviceGetRequestWithDefaults instantiates a new V1EventDeviceGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1EventDeviceGetRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1EventDeviceGetRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1EventDeviceGetRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.


### GetFilter

`func (o *V1EventDeviceGetRequest) GetFilter() EventEventFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *V1EventDeviceGetRequest) GetFilterOk() (*EventEventFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *V1EventDeviceGetRequest) SetFilter(v EventEventFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *V1EventDeviceGetRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



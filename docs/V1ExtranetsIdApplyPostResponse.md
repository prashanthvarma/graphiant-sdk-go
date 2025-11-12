# V1ExtranetsIdApplyPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Devices** | Pointer to [**[]ManaV2ExtranetDeviceStatus**](ManaV2ExtranetDeviceStatus.md) |  | [optional] 
**JobId** | Pointer to **int64** |  | [optional] 

## Methods

### NewV1ExtranetsIdApplyPostResponse

`func NewV1ExtranetsIdApplyPostResponse() *V1ExtranetsIdApplyPostResponse`

NewV1ExtranetsIdApplyPostResponse instantiates a new V1ExtranetsIdApplyPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsIdApplyPostResponseWithDefaults

`func NewV1ExtranetsIdApplyPostResponseWithDefaults() *V1ExtranetsIdApplyPostResponse`

NewV1ExtranetsIdApplyPostResponseWithDefaults instantiates a new V1ExtranetsIdApplyPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevices

`func (o *V1ExtranetsIdApplyPostResponse) GetDevices() []ManaV2ExtranetDeviceStatus`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *V1ExtranetsIdApplyPostResponse) GetDevicesOk() (*[]ManaV2ExtranetDeviceStatus, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *V1ExtranetsIdApplyPostResponse) SetDevices(v []ManaV2ExtranetDeviceStatus)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *V1ExtranetsIdApplyPostResponse) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetJobId

`func (o *V1ExtranetsIdApplyPostResponse) GetJobId() int64`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *V1ExtranetsIdApplyPostResponse) GetJobIdOk() (*int64, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *V1ExtranetsIdApplyPostResponse) SetJobId(v int64)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *V1ExtranetsIdApplyPostResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



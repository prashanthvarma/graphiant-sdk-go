# V1DeviceStatusPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceIds** | Pointer to **[]int64** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 

## Methods

### NewV1DeviceStatusPostRequest

`func NewV1DeviceStatusPostRequest() *V1DeviceStatusPostRequest`

NewV1DeviceStatusPostRequest instantiates a new V1DeviceStatusPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceStatusPostRequestWithDefaults

`func NewV1DeviceStatusPostRequestWithDefaults() *V1DeviceStatusPostRequest`

NewV1DeviceStatusPostRequestWithDefaults instantiates a new V1DeviceStatusPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceIds

`func (o *V1DeviceStatusPostRequest) GetDeviceIds() []int64`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *V1DeviceStatusPostRequest) GetDeviceIdsOk() (*[]int64, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *V1DeviceStatusPostRequest) SetDeviceIds(v []int64)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *V1DeviceStatusPostRequest) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.

### GetRole

`func (o *V1DeviceStatusPostRequest) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *V1DeviceStatusPostRequest) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *V1DeviceStatusPostRequest) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *V1DeviceStatusPostRequest) HasRole() bool`

HasRole returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



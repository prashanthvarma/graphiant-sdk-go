# V1HealthcheckDevicesGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceIds** | Pointer to **[]int64** |  | [optional] 
**FilterAnomolies** | Pointer to **bool** |  | [optional] 

## Methods

### NewV1HealthcheckDevicesGetRequest

`func NewV1HealthcheckDevicesGetRequest() *V1HealthcheckDevicesGetRequest`

NewV1HealthcheckDevicesGetRequest instantiates a new V1HealthcheckDevicesGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1HealthcheckDevicesGetRequestWithDefaults

`func NewV1HealthcheckDevicesGetRequestWithDefaults() *V1HealthcheckDevicesGetRequest`

NewV1HealthcheckDevicesGetRequestWithDefaults instantiates a new V1HealthcheckDevicesGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceIds

`func (o *V1HealthcheckDevicesGetRequest) GetDeviceIds() []int64`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *V1HealthcheckDevicesGetRequest) GetDeviceIdsOk() (*[]int64, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *V1HealthcheckDevicesGetRequest) SetDeviceIds(v []int64)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *V1HealthcheckDevicesGetRequest) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.

### GetFilterAnomolies

`func (o *V1HealthcheckDevicesGetRequest) GetFilterAnomolies() bool`

GetFilterAnomolies returns the FilterAnomolies field if non-nil, zero value otherwise.

### GetFilterAnomoliesOk

`func (o *V1HealthcheckDevicesGetRequest) GetFilterAnomoliesOk() (*bool, bool)`

GetFilterAnomoliesOk returns a tuple with the FilterAnomolies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterAnomolies

`func (o *V1HealthcheckDevicesGetRequest) SetFilterAnomolies(v bool)`

SetFilterAnomolies sets FilterAnomolies field to given value.

### HasFilterAnomolies

`func (o *V1HealthcheckDevicesGetRequest) HasFilterAnomolies() bool`

HasFilterAnomolies returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



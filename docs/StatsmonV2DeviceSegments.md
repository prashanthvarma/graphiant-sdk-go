# StatsmonV2DeviceSegments

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**VrfRoutes** | Pointer to [**[]StatsmonV2VrfRoutes**](StatsmonV2VrfRoutes.md) |  | [optional] 

## Methods

### NewStatsmonV2DeviceSegments

`func NewStatsmonV2DeviceSegments() *StatsmonV2DeviceSegments`

NewStatsmonV2DeviceSegments instantiates a new StatsmonV2DeviceSegments object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2DeviceSegmentsWithDefaults

`func NewStatsmonV2DeviceSegmentsWithDefaults() *StatsmonV2DeviceSegments`

NewStatsmonV2DeviceSegmentsWithDefaults instantiates a new StatsmonV2DeviceSegments object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *StatsmonV2DeviceSegments) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *StatsmonV2DeviceSegments) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *StatsmonV2DeviceSegments) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *StatsmonV2DeviceSegments) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetVrfRoutes

`func (o *StatsmonV2DeviceSegments) GetVrfRoutes() []StatsmonV2VrfRoutes`

GetVrfRoutes returns the VrfRoutes field if non-nil, zero value otherwise.

### GetVrfRoutesOk

`func (o *StatsmonV2DeviceSegments) GetVrfRoutesOk() (*[]StatsmonV2VrfRoutes, bool)`

GetVrfRoutesOk returns a tuple with the VrfRoutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfRoutes

`func (o *StatsmonV2DeviceSegments) SetVrfRoutes(v []StatsmonV2VrfRoutes)`

SetVrfRoutes sets VrfRoutes field to given value.

### HasVrfRoutes

`func (o *StatsmonV2DeviceSegments) HasVrfRoutes() bool`

HasVrfRoutes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



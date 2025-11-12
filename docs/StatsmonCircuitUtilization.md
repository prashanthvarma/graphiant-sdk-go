# StatsmonCircuitUtilization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConfigLinkUpSpeedMbps** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**QueueUtilization** | Pointer to [**[]StatsmonQueueUtilization**](StatsmonQueueUtilization.md) |  | [optional] 

## Methods

### NewStatsmonCircuitUtilization

`func NewStatsmonCircuitUtilization() *StatsmonCircuitUtilization`

NewStatsmonCircuitUtilization instantiates a new StatsmonCircuitUtilization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonCircuitUtilizationWithDefaults

`func NewStatsmonCircuitUtilizationWithDefaults() *StatsmonCircuitUtilization`

NewStatsmonCircuitUtilizationWithDefaults instantiates a new StatsmonCircuitUtilization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigLinkUpSpeedMbps

`func (o *StatsmonCircuitUtilization) GetConfigLinkUpSpeedMbps() int32`

GetConfigLinkUpSpeedMbps returns the ConfigLinkUpSpeedMbps field if non-nil, zero value otherwise.

### GetConfigLinkUpSpeedMbpsOk

`func (o *StatsmonCircuitUtilization) GetConfigLinkUpSpeedMbpsOk() (*int32, bool)`

GetConfigLinkUpSpeedMbpsOk returns a tuple with the ConfigLinkUpSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigLinkUpSpeedMbps

`func (o *StatsmonCircuitUtilization) SetConfigLinkUpSpeedMbps(v int32)`

SetConfigLinkUpSpeedMbps sets ConfigLinkUpSpeedMbps field to given value.

### HasConfigLinkUpSpeedMbps

`func (o *StatsmonCircuitUtilization) HasConfigLinkUpSpeedMbps() bool`

HasConfigLinkUpSpeedMbps returns a boolean if a field has been set.

### GetName

`func (o *StatsmonCircuitUtilization) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StatsmonCircuitUtilization) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StatsmonCircuitUtilization) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *StatsmonCircuitUtilization) HasName() bool`

HasName returns a boolean if a field has been set.

### GetQueueUtilization

`func (o *StatsmonCircuitUtilization) GetQueueUtilization() []StatsmonQueueUtilization`

GetQueueUtilization returns the QueueUtilization field if non-nil, zero value otherwise.

### GetQueueUtilizationOk

`func (o *StatsmonCircuitUtilization) GetQueueUtilizationOk() (*[]StatsmonQueueUtilization, bool)`

GetQueueUtilizationOk returns a tuple with the QueueUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueueUtilization

`func (o *StatsmonCircuitUtilization) SetQueueUtilization(v []StatsmonQueueUtilization)`

SetQueueUtilization sets QueueUtilization field to given value.

### HasQueueUtilization

`func (o *StatsmonCircuitUtilization) HasQueueUtilization() bool`

HasQueueUtilization returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



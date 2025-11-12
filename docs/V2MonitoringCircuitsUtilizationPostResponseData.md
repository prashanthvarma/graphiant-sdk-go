# V2MonitoringCircuitsUtilizationPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConfigLinkUpSpeedMbps** | Pointer to **int32** |  | [optional] 
**QueueUtilization** | Pointer to [**[]StatsmonV2QueueUtilization**](StatsmonV2QueueUtilization.md) |  | [optional] 
**Selector** | Pointer to [**StatsmonV2CircuitUtilizationSelector**](StatsmonV2CircuitUtilizationSelector.md) |  | [optional] 

## Methods

### NewV2MonitoringCircuitsUtilizationPostResponseData

`func NewV2MonitoringCircuitsUtilizationPostResponseData() *V2MonitoringCircuitsUtilizationPostResponseData`

NewV2MonitoringCircuitsUtilizationPostResponseData instantiates a new V2MonitoringCircuitsUtilizationPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringCircuitsUtilizationPostResponseDataWithDefaults

`func NewV2MonitoringCircuitsUtilizationPostResponseDataWithDefaults() *V2MonitoringCircuitsUtilizationPostResponseData`

NewV2MonitoringCircuitsUtilizationPostResponseDataWithDefaults instantiates a new V2MonitoringCircuitsUtilizationPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigLinkUpSpeedMbps

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) GetConfigLinkUpSpeedMbps() int32`

GetConfigLinkUpSpeedMbps returns the ConfigLinkUpSpeedMbps field if non-nil, zero value otherwise.

### GetConfigLinkUpSpeedMbpsOk

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) GetConfigLinkUpSpeedMbpsOk() (*int32, bool)`

GetConfigLinkUpSpeedMbpsOk returns a tuple with the ConfigLinkUpSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigLinkUpSpeedMbps

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) SetConfigLinkUpSpeedMbps(v int32)`

SetConfigLinkUpSpeedMbps sets ConfigLinkUpSpeedMbps field to given value.

### HasConfigLinkUpSpeedMbps

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) HasConfigLinkUpSpeedMbps() bool`

HasConfigLinkUpSpeedMbps returns a boolean if a field has been set.

### GetQueueUtilization

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) GetQueueUtilization() []StatsmonV2QueueUtilization`

GetQueueUtilization returns the QueueUtilization field if non-nil, zero value otherwise.

### GetQueueUtilizationOk

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) GetQueueUtilizationOk() (*[]StatsmonV2QueueUtilization, bool)`

GetQueueUtilizationOk returns a tuple with the QueueUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueueUtilization

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) SetQueueUtilization(v []StatsmonV2QueueUtilization)`

SetQueueUtilization sets QueueUtilization field to given value.

### HasQueueUtilization

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) HasQueueUtilization() bool`

HasQueueUtilization returns a boolean if a field has been set.

### GetSelector

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) GetSelector() StatsmonV2CircuitUtilizationSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) GetSelectorOk() (*StatsmonV2CircuitUtilizationSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) SetSelector(v StatsmonV2CircuitUtilizationSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V2MonitoringCircuitsUtilizationPostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2MonitoringQueuePostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Samples** | Pointer to [**[]StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**Selector** | Pointer to [**StatsmonV2QueueStatsSelector**](StatsmonV2QueueStatsSelector.md) |  | [optional] 

## Methods

### NewV2MonitoringQueuePostResponseData

`func NewV2MonitoringQueuePostResponseData() *V2MonitoringQueuePostResponseData`

NewV2MonitoringQueuePostResponseData instantiates a new V2MonitoringQueuePostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringQueuePostResponseDataWithDefaults

`func NewV2MonitoringQueuePostResponseDataWithDefaults() *V2MonitoringQueuePostResponseData`

NewV2MonitoringQueuePostResponseDataWithDefaults instantiates a new V2MonitoringQueuePostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSamples

`func (o *V2MonitoringQueuePostResponseData) GetSamples() []StatsmonV2StatsSample`

GetSamples returns the Samples field if non-nil, zero value otherwise.

### GetSamplesOk

`func (o *V2MonitoringQueuePostResponseData) GetSamplesOk() (*[]StatsmonV2StatsSample, bool)`

GetSamplesOk returns a tuple with the Samples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamples

`func (o *V2MonitoringQueuePostResponseData) SetSamples(v []StatsmonV2StatsSample)`

SetSamples sets Samples field to given value.

### HasSamples

`func (o *V2MonitoringQueuePostResponseData) HasSamples() bool`

HasSamples returns a boolean if a field has been set.

### GetSelector

`func (o *V2MonitoringQueuePostResponseData) GetSelector() StatsmonV2QueueStatsSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V2MonitoringQueuePostResponseData) GetSelectorOk() (*StatsmonV2QueueStatsSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V2MonitoringQueuePostResponseData) SetSelector(v StatsmonV2QueueStatsSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V2MonitoringQueuePostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



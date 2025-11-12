# V2MonitoringBfdPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Samples** | Pointer to [**[]StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**Selector** | Pointer to [**StatsmonV2BfdStatsSelector**](StatsmonV2BfdStatsSelector.md) |  | [optional] 

## Methods

### NewV2MonitoringBfdPostResponseData

`func NewV2MonitoringBfdPostResponseData() *V2MonitoringBfdPostResponseData`

NewV2MonitoringBfdPostResponseData instantiates a new V2MonitoringBfdPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringBfdPostResponseDataWithDefaults

`func NewV2MonitoringBfdPostResponseDataWithDefaults() *V2MonitoringBfdPostResponseData`

NewV2MonitoringBfdPostResponseDataWithDefaults instantiates a new V2MonitoringBfdPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSamples

`func (o *V2MonitoringBfdPostResponseData) GetSamples() []StatsmonV2StatsSample`

GetSamples returns the Samples field if non-nil, zero value otherwise.

### GetSamplesOk

`func (o *V2MonitoringBfdPostResponseData) GetSamplesOk() (*[]StatsmonV2StatsSample, bool)`

GetSamplesOk returns a tuple with the Samples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamples

`func (o *V2MonitoringBfdPostResponseData) SetSamples(v []StatsmonV2StatsSample)`

SetSamples sets Samples field to given value.

### HasSamples

`func (o *V2MonitoringBfdPostResponseData) HasSamples() bool`

HasSamples returns a boolean if a field has been set.

### GetSelector

`func (o *V2MonitoringBfdPostResponseData) GetSelector() StatsmonV2BfdStatsSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V2MonitoringBfdPostResponseData) GetSelectorOk() (*StatsmonV2BfdStatsSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V2MonitoringBfdPostResponseData) SetSelector(v StatsmonV2BfdStatsSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V2MonitoringBfdPostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



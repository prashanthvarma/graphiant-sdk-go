# V2MonitoringTwampPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Samples** | Pointer to [**[]StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**Selector** | Pointer to [**StatsmonV2TwampStatsSelector**](StatsmonV2TwampStatsSelector.md) |  | [optional] 

## Methods

### NewV2MonitoringTwampPostResponseData

`func NewV2MonitoringTwampPostResponseData() *V2MonitoringTwampPostResponseData`

NewV2MonitoringTwampPostResponseData instantiates a new V2MonitoringTwampPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringTwampPostResponseDataWithDefaults

`func NewV2MonitoringTwampPostResponseDataWithDefaults() *V2MonitoringTwampPostResponseData`

NewV2MonitoringTwampPostResponseDataWithDefaults instantiates a new V2MonitoringTwampPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSamples

`func (o *V2MonitoringTwampPostResponseData) GetSamples() []StatsmonV2StatsSample`

GetSamples returns the Samples field if non-nil, zero value otherwise.

### GetSamplesOk

`func (o *V2MonitoringTwampPostResponseData) GetSamplesOk() (*[]StatsmonV2StatsSample, bool)`

GetSamplesOk returns a tuple with the Samples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamples

`func (o *V2MonitoringTwampPostResponseData) SetSamples(v []StatsmonV2StatsSample)`

SetSamples sets Samples field to given value.

### HasSamples

`func (o *V2MonitoringTwampPostResponseData) HasSamples() bool`

HasSamples returns a boolean if a field has been set.

### GetSelector

`func (o *V2MonitoringTwampPostResponseData) GetSelector() StatsmonV2TwampStatsSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V2MonitoringTwampPostResponseData) GetSelectorOk() (*StatsmonV2TwampStatsSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V2MonitoringTwampPostResponseData) SetSelector(v StatsmonV2TwampStatsSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V2MonitoringTwampPostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



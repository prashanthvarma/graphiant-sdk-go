# V2MonitoringIpsecPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Samples** | Pointer to [**[]StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**Selector** | Pointer to [**StatsmonV2IpSecStatsSelector**](StatsmonV2IpSecStatsSelector.md) |  | [optional] 

## Methods

### NewV2MonitoringIpsecPostResponseData

`func NewV2MonitoringIpsecPostResponseData() *V2MonitoringIpsecPostResponseData`

NewV2MonitoringIpsecPostResponseData instantiates a new V2MonitoringIpsecPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringIpsecPostResponseDataWithDefaults

`func NewV2MonitoringIpsecPostResponseDataWithDefaults() *V2MonitoringIpsecPostResponseData`

NewV2MonitoringIpsecPostResponseDataWithDefaults instantiates a new V2MonitoringIpsecPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSamples

`func (o *V2MonitoringIpsecPostResponseData) GetSamples() []StatsmonV2StatsSample`

GetSamples returns the Samples field if non-nil, zero value otherwise.

### GetSamplesOk

`func (o *V2MonitoringIpsecPostResponseData) GetSamplesOk() (*[]StatsmonV2StatsSample, bool)`

GetSamplesOk returns a tuple with the Samples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamples

`func (o *V2MonitoringIpsecPostResponseData) SetSamples(v []StatsmonV2StatsSample)`

SetSamples sets Samples field to given value.

### HasSamples

`func (o *V2MonitoringIpsecPostResponseData) HasSamples() bool`

HasSamples returns a boolean if a field has been set.

### GetSelector

`func (o *V2MonitoringIpsecPostResponseData) GetSelector() StatsmonV2IpSecStatsSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V2MonitoringIpsecPostResponseData) GetSelectorOk() (*StatsmonV2IpSecStatsSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V2MonitoringIpsecPostResponseData) SetSelector(v StatsmonV2IpSecStatsSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V2MonitoringIpsecPostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1MonitoringCircuitsBandwidthPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Selector** | Pointer to [**CommonCircuitBandwidthStatsSelector**](CommonCircuitBandwidthStatsSelector.md) |  | [optional] 
**Stats** | Pointer to [**[]CommonCircuitBandwidthStats**](CommonCircuitBandwidthStats.md) |  | [optional] 

## Methods

### NewV1MonitoringCircuitsBandwidthPostResponseData

`func NewV1MonitoringCircuitsBandwidthPostResponseData() *V1MonitoringCircuitsBandwidthPostResponseData`

NewV1MonitoringCircuitsBandwidthPostResponseData instantiates a new V1MonitoringCircuitsBandwidthPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1MonitoringCircuitsBandwidthPostResponseDataWithDefaults

`func NewV1MonitoringCircuitsBandwidthPostResponseDataWithDefaults() *V1MonitoringCircuitsBandwidthPostResponseData`

NewV1MonitoringCircuitsBandwidthPostResponseDataWithDefaults instantiates a new V1MonitoringCircuitsBandwidthPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSelector

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) GetSelector() CommonCircuitBandwidthStatsSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) GetSelectorOk() (*CommonCircuitBandwidthStatsSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) SetSelector(v CommonCircuitBandwidthStatsSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.

### GetStats

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) GetStats() []CommonCircuitBandwidthStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) GetStatsOk() (*[]CommonCircuitBandwidthStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) SetStats(v []CommonCircuitBandwidthStats)`

SetStats sets Stats field to given value.

### HasStats

`func (o *V1MonitoringCircuitsBandwidthPostResponseData) HasStats() bool`

HasStats returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



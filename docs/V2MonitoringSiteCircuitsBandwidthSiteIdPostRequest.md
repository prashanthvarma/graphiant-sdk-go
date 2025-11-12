# V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Selectors** | Pointer to [**[]StatsmonV2CircuitBandwidthStatsSelector**](StatsmonV2CircuitBandwidthStatsSelector.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonV2TimeWindow**](StatsmonV2TimeWindow.md) |  | [optional] 

## Methods

### NewV2MonitoringSiteCircuitsBandwidthSiteIdPostRequest

`func NewV2MonitoringSiteCircuitsBandwidthSiteIdPostRequest() *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest`

NewV2MonitoringSiteCircuitsBandwidthSiteIdPostRequest instantiates a new V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringSiteCircuitsBandwidthSiteIdPostRequestWithDefaults

`func NewV2MonitoringSiteCircuitsBandwidthSiteIdPostRequestWithDefaults() *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest`

NewV2MonitoringSiteCircuitsBandwidthSiteIdPostRequestWithDefaults instantiates a new V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSelectors

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) GetSelectors() []StatsmonV2CircuitBandwidthStatsSelector`

GetSelectors returns the Selectors field if non-nil, zero value otherwise.

### GetSelectorsOk

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) GetSelectorsOk() (*[]StatsmonV2CircuitBandwidthStatsSelector, bool)`

GetSelectorsOk returns a tuple with the Selectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectors

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) SetSelectors(v []StatsmonV2CircuitBandwidthStatsSelector)`

SetSelectors sets Selectors field to given value.

### HasSelectors

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) HasSelectors() bool`

HasSelectors returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) GetTimeWindow() StatsmonV2TimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) GetTimeWindowOk() (*StatsmonV2TimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) SetTimeWindow(v StatsmonV2TimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V2MonitoringSiteCircuitsBandwidthSiteIdPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



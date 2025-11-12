# V1MonitoringCircuitsBandwidthPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Selectors** | Pointer to [**[]CommonCircuitBandwidthStatsSelector**](CommonCircuitBandwidthStatsSelector.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Methods

### NewV1MonitoringCircuitsBandwidthPostRequest

`func NewV1MonitoringCircuitsBandwidthPostRequest() *V1MonitoringCircuitsBandwidthPostRequest`

NewV1MonitoringCircuitsBandwidthPostRequest instantiates a new V1MonitoringCircuitsBandwidthPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1MonitoringCircuitsBandwidthPostRequestWithDefaults

`func NewV1MonitoringCircuitsBandwidthPostRequestWithDefaults() *V1MonitoringCircuitsBandwidthPostRequest`

NewV1MonitoringCircuitsBandwidthPostRequestWithDefaults instantiates a new V1MonitoringCircuitsBandwidthPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1MonitoringCircuitsBandwidthPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1MonitoringCircuitsBandwidthPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1MonitoringCircuitsBandwidthPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1MonitoringCircuitsBandwidthPostRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetSelectors

`func (o *V1MonitoringCircuitsBandwidthPostRequest) GetSelectors() []CommonCircuitBandwidthStatsSelector`

GetSelectors returns the Selectors field if non-nil, zero value otherwise.

### GetSelectorsOk

`func (o *V1MonitoringCircuitsBandwidthPostRequest) GetSelectorsOk() (*[]CommonCircuitBandwidthStatsSelector, bool)`

GetSelectorsOk returns a tuple with the Selectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectors

`func (o *V1MonitoringCircuitsBandwidthPostRequest) SetSelectors(v []CommonCircuitBandwidthStatsSelector)`

SetSelectors sets Selectors field to given value.

### HasSelectors

`func (o *V1MonitoringCircuitsBandwidthPostRequest) HasSelectors() bool`

HasSelectors returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1MonitoringCircuitsBandwidthPostRequest) GetTimeWindow() StatsmonTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1MonitoringCircuitsBandwidthPostRequest) GetTimeWindowOk() (*StatsmonTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1MonitoringCircuitsBandwidthPostRequest) SetTimeWindow(v StatsmonTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1MonitoringCircuitsBandwidthPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2MonitoringCircuitsBandwidthPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | Pointer to **string** |  | [optional] 
**DeviceId** | Pointer to **int64** |  | [optional] 
**DlBwKbpsSamples** | Pointer to [**[]StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**Selector** | Pointer to [**StatsmonV2CircuitBandwidthStatsSelector**](StatsmonV2CircuitBandwidthStatsSelector.md) |  | [optional] 
**UlBwKbpsSamples** | Pointer to [**[]StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 

## Methods

### NewV2MonitoringCircuitsBandwidthPostResponseData

`func NewV2MonitoringCircuitsBandwidthPostResponseData() *V2MonitoringCircuitsBandwidthPostResponseData`

NewV2MonitoringCircuitsBandwidthPostResponseData instantiates a new V2MonitoringCircuitsBandwidthPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringCircuitsBandwidthPostResponseDataWithDefaults

`func NewV2MonitoringCircuitsBandwidthPostResponseDataWithDefaults() *V2MonitoringCircuitsBandwidthPostResponseData`

NewV2MonitoringCircuitsBandwidthPostResponseDataWithDefaults instantiates a new V2MonitoringCircuitsBandwidthPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetDeviceId

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetDlBwKbpsSamples

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetDlBwKbpsSamples() []StatsmonV2StatsSample`

GetDlBwKbpsSamples returns the DlBwKbpsSamples field if non-nil, zero value otherwise.

### GetDlBwKbpsSamplesOk

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetDlBwKbpsSamplesOk() (*[]StatsmonV2StatsSample, bool)`

GetDlBwKbpsSamplesOk returns a tuple with the DlBwKbpsSamples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDlBwKbpsSamples

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) SetDlBwKbpsSamples(v []StatsmonV2StatsSample)`

SetDlBwKbpsSamples sets DlBwKbpsSamples field to given value.

### HasDlBwKbpsSamples

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) HasDlBwKbpsSamples() bool`

HasDlBwKbpsSamples returns a boolean if a field has been set.

### GetSelector

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetSelector() StatsmonV2CircuitBandwidthStatsSelector`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetSelectorOk() (*StatsmonV2CircuitBandwidthStatsSelector, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) SetSelector(v StatsmonV2CircuitBandwidthStatsSelector)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) HasSelector() bool`

HasSelector returns a boolean if a field has been set.

### GetUlBwKbpsSamples

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetUlBwKbpsSamples() []StatsmonV2StatsSample`

GetUlBwKbpsSamples returns the UlBwKbpsSamples field if non-nil, zero value otherwise.

### GetUlBwKbpsSamplesOk

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) GetUlBwKbpsSamplesOk() (*[]StatsmonV2StatsSample, bool)`

GetUlBwKbpsSamplesOk returns a tuple with the UlBwKbpsSamples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUlBwKbpsSamples

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) SetUlBwKbpsSamples(v []StatsmonV2StatsSample)`

SetUlBwKbpsSamples sets UlBwKbpsSamples field to given value.

### HasUlBwKbpsSamples

`func (o *V2MonitoringCircuitsBandwidthPostResponseData) HasUlBwKbpsSamples() bool`

HasUlBwKbpsSamples returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



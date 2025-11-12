# V2MonitoringCircuitsUtilizationPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Selectors** | Pointer to [**[]StatsmonV2CircuitUtilizationSelector**](StatsmonV2CircuitUtilizationSelector.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonV2TimeWindow**](StatsmonV2TimeWindow.md) |  | [optional] 

## Methods

### NewV2MonitoringCircuitsUtilizationPostRequest

`func NewV2MonitoringCircuitsUtilizationPostRequest() *V2MonitoringCircuitsUtilizationPostRequest`

NewV2MonitoringCircuitsUtilizationPostRequest instantiates a new V2MonitoringCircuitsUtilizationPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringCircuitsUtilizationPostRequestWithDefaults

`func NewV2MonitoringCircuitsUtilizationPostRequestWithDefaults() *V2MonitoringCircuitsUtilizationPostRequest`

NewV2MonitoringCircuitsUtilizationPostRequestWithDefaults instantiates a new V2MonitoringCircuitsUtilizationPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V2MonitoringCircuitsUtilizationPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V2MonitoringCircuitsUtilizationPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V2MonitoringCircuitsUtilizationPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V2MonitoringCircuitsUtilizationPostRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetSelectors

`func (o *V2MonitoringCircuitsUtilizationPostRequest) GetSelectors() []StatsmonV2CircuitUtilizationSelector`

GetSelectors returns the Selectors field if non-nil, zero value otherwise.

### GetSelectorsOk

`func (o *V2MonitoringCircuitsUtilizationPostRequest) GetSelectorsOk() (*[]StatsmonV2CircuitUtilizationSelector, bool)`

GetSelectorsOk returns a tuple with the Selectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectors

`func (o *V2MonitoringCircuitsUtilizationPostRequest) SetSelectors(v []StatsmonV2CircuitUtilizationSelector)`

SetSelectors sets Selectors field to given value.

### HasSelectors

`func (o *V2MonitoringCircuitsUtilizationPostRequest) HasSelectors() bool`

HasSelectors returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V2MonitoringCircuitsUtilizationPostRequest) GetTimeWindow() StatsmonV2TimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V2MonitoringCircuitsUtilizationPostRequest) GetTimeWindowOk() (*StatsmonV2TimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V2MonitoringCircuitsUtilizationPostRequest) SetTimeWindow(v StatsmonV2TimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V2MonitoringCircuitsUtilizationPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



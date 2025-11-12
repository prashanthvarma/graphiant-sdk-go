# V2MonitoringSystemGenericPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Selectors** | Pointer to [**[]StatsmonV2GenericSystemStatsSelector**](StatsmonV2GenericSystemStatsSelector.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonV2TimeWindow**](StatsmonV2TimeWindow.md) |  | [optional] 

## Methods

### NewV2MonitoringSystemGenericPostRequest

`func NewV2MonitoringSystemGenericPostRequest() *V2MonitoringSystemGenericPostRequest`

NewV2MonitoringSystemGenericPostRequest instantiates a new V2MonitoringSystemGenericPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringSystemGenericPostRequestWithDefaults

`func NewV2MonitoringSystemGenericPostRequestWithDefaults() *V2MonitoringSystemGenericPostRequest`

NewV2MonitoringSystemGenericPostRequestWithDefaults instantiates a new V2MonitoringSystemGenericPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V2MonitoringSystemGenericPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V2MonitoringSystemGenericPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V2MonitoringSystemGenericPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V2MonitoringSystemGenericPostRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetSelectors

`func (o *V2MonitoringSystemGenericPostRequest) GetSelectors() []StatsmonV2GenericSystemStatsSelector`

GetSelectors returns the Selectors field if non-nil, zero value otherwise.

### GetSelectorsOk

`func (o *V2MonitoringSystemGenericPostRequest) GetSelectorsOk() (*[]StatsmonV2GenericSystemStatsSelector, bool)`

GetSelectorsOk returns a tuple with the Selectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectors

`func (o *V2MonitoringSystemGenericPostRequest) SetSelectors(v []StatsmonV2GenericSystemStatsSelector)`

SetSelectors sets Selectors field to given value.

### HasSelectors

`func (o *V2MonitoringSystemGenericPostRequest) HasSelectors() bool`

HasSelectors returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V2MonitoringSystemGenericPostRequest) GetTimeWindow() StatsmonV2TimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V2MonitoringSystemGenericPostRequest) GetTimeWindowOk() (*StatsmonV2TimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V2MonitoringSystemGenericPostRequest) SetTimeWindow(v StatsmonV2TimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V2MonitoringSystemGenericPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1MonitoringCircuitsIncidentsPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Selectors** | Pointer to [**[]StatsmonCircuitsIncidentsSelector**](StatsmonCircuitsIncidentsSelector.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Methods

### NewV1MonitoringCircuitsIncidentsPostRequest

`func NewV1MonitoringCircuitsIncidentsPostRequest() *V1MonitoringCircuitsIncidentsPostRequest`

NewV1MonitoringCircuitsIncidentsPostRequest instantiates a new V1MonitoringCircuitsIncidentsPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1MonitoringCircuitsIncidentsPostRequestWithDefaults

`func NewV1MonitoringCircuitsIncidentsPostRequestWithDefaults() *V1MonitoringCircuitsIncidentsPostRequest`

NewV1MonitoringCircuitsIncidentsPostRequestWithDefaults instantiates a new V1MonitoringCircuitsIncidentsPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1MonitoringCircuitsIncidentsPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1MonitoringCircuitsIncidentsPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1MonitoringCircuitsIncidentsPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1MonitoringCircuitsIncidentsPostRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetSelectors

`func (o *V1MonitoringCircuitsIncidentsPostRequest) GetSelectors() []StatsmonCircuitsIncidentsSelector`

GetSelectors returns the Selectors field if non-nil, zero value otherwise.

### GetSelectorsOk

`func (o *V1MonitoringCircuitsIncidentsPostRequest) GetSelectorsOk() (*[]StatsmonCircuitsIncidentsSelector, bool)`

GetSelectorsOk returns a tuple with the Selectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectors

`func (o *V1MonitoringCircuitsIncidentsPostRequest) SetSelectors(v []StatsmonCircuitsIncidentsSelector)`

SetSelectors sets Selectors field to given value.

### HasSelectors

`func (o *V1MonitoringCircuitsIncidentsPostRequest) HasSelectors() bool`

HasSelectors returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1MonitoringCircuitsIncidentsPostRequest) GetTimeWindow() StatsmonTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1MonitoringCircuitsIncidentsPostRequest) GetTimeWindowOk() (*StatsmonTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1MonitoringCircuitsIncidentsPostRequest) SetTimeWindow(v StatsmonTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1MonitoringCircuitsIncidentsPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



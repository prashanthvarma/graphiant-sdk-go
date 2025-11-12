# V1MonitoringCircuitsUtilizationPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Selectors** | Pointer to [**[]StatsmonCircuitsUtilizationSelector**](StatsmonCircuitsUtilizationSelector.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Methods

### NewV1MonitoringCircuitsUtilizationPostRequest

`func NewV1MonitoringCircuitsUtilizationPostRequest() *V1MonitoringCircuitsUtilizationPostRequest`

NewV1MonitoringCircuitsUtilizationPostRequest instantiates a new V1MonitoringCircuitsUtilizationPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1MonitoringCircuitsUtilizationPostRequestWithDefaults

`func NewV1MonitoringCircuitsUtilizationPostRequestWithDefaults() *V1MonitoringCircuitsUtilizationPostRequest`

NewV1MonitoringCircuitsUtilizationPostRequestWithDefaults instantiates a new V1MonitoringCircuitsUtilizationPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1MonitoringCircuitsUtilizationPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1MonitoringCircuitsUtilizationPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1MonitoringCircuitsUtilizationPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1MonitoringCircuitsUtilizationPostRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetSelectors

`func (o *V1MonitoringCircuitsUtilizationPostRequest) GetSelectors() []StatsmonCircuitsUtilizationSelector`

GetSelectors returns the Selectors field if non-nil, zero value otherwise.

### GetSelectorsOk

`func (o *V1MonitoringCircuitsUtilizationPostRequest) GetSelectorsOk() (*[]StatsmonCircuitsUtilizationSelector, bool)`

GetSelectorsOk returns a tuple with the Selectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectors

`func (o *V1MonitoringCircuitsUtilizationPostRequest) SetSelectors(v []StatsmonCircuitsUtilizationSelector)`

SetSelectors sets Selectors field to given value.

### HasSelectors

`func (o *V1MonitoringCircuitsUtilizationPostRequest) HasSelectors() bool`

HasSelectors returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1MonitoringCircuitsUtilizationPostRequest) GetTimeWindow() StatsmonTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1MonitoringCircuitsUtilizationPostRequest) GetTimeWindowOk() (*StatsmonTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1MonitoringCircuitsUtilizationPostRequest) SetTimeWindow(v StatsmonTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1MonitoringCircuitsUtilizationPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



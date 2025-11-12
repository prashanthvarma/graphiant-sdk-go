# V1MonitoringCircuitsSummaryPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Methods

### NewV1MonitoringCircuitsSummaryPostRequest

`func NewV1MonitoringCircuitsSummaryPostRequest() *V1MonitoringCircuitsSummaryPostRequest`

NewV1MonitoringCircuitsSummaryPostRequest instantiates a new V1MonitoringCircuitsSummaryPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1MonitoringCircuitsSummaryPostRequestWithDefaults

`func NewV1MonitoringCircuitsSummaryPostRequestWithDefaults() *V1MonitoringCircuitsSummaryPostRequest`

NewV1MonitoringCircuitsSummaryPostRequestWithDefaults instantiates a new V1MonitoringCircuitsSummaryPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1MonitoringCircuitsSummaryPostRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1MonitoringCircuitsSummaryPostRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1MonitoringCircuitsSummaryPostRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1MonitoringCircuitsSummaryPostRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1MonitoringCircuitsSummaryPostRequest) GetTimeWindow() StatsmonTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1MonitoringCircuitsSummaryPostRequest) GetTimeWindowOk() (*StatsmonTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1MonitoringCircuitsSummaryPostRequest) SetTimeWindow(v StatsmonTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1MonitoringCircuitsSummaryPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1BwtrackerRegionEdgeDetailsPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegionId** | Pointer to **int64** |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonBandwidthtrackerTimeWindow**](StatsmonBandwidthtrackerTimeWindow.md) |  | [optional] 

## Methods

### NewV1BwtrackerRegionEdgeDetailsPostRequest

`func NewV1BwtrackerRegionEdgeDetailsPostRequest() *V1BwtrackerRegionEdgeDetailsPostRequest`

NewV1BwtrackerRegionEdgeDetailsPostRequest instantiates a new V1BwtrackerRegionEdgeDetailsPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1BwtrackerRegionEdgeDetailsPostRequestWithDefaults

`func NewV1BwtrackerRegionEdgeDetailsPostRequestWithDefaults() *V1BwtrackerRegionEdgeDetailsPostRequest`

NewV1BwtrackerRegionEdgeDetailsPostRequestWithDefaults instantiates a new V1BwtrackerRegionEdgeDetailsPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegionId

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) GetRegionId() int64`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) GetRegionIdOk() (*int64, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) SetRegionId(v int64)`

SetRegionId sets RegionId field to given value.

### HasRegionId

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) HasRegionId() bool`

HasRegionId returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) GetTimeWindow() StatsmonBandwidthtrackerTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) GetTimeWindowOk() (*StatsmonBandwidthtrackerTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) SetTimeWindow(v StatsmonBandwidthtrackerTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1BwtrackerRegionEdgeDetailsPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



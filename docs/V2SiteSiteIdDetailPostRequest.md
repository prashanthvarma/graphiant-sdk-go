# V2SiteSiteIdDetailPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SnapshotTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonV2TimeWindow**](StatsmonV2TimeWindow.md) |  | [optional] 

## Methods

### NewV2SiteSiteIdDetailPostRequest

`func NewV2SiteSiteIdDetailPostRequest() *V2SiteSiteIdDetailPostRequest`

NewV2SiteSiteIdDetailPostRequest instantiates a new V2SiteSiteIdDetailPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2SiteSiteIdDetailPostRequestWithDefaults

`func NewV2SiteSiteIdDetailPostRequestWithDefaults() *V2SiteSiteIdDetailPostRequest`

NewV2SiteSiteIdDetailPostRequestWithDefaults instantiates a new V2SiteSiteIdDetailPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSnapshotTime

`func (o *V2SiteSiteIdDetailPostRequest) GetSnapshotTime() GoogleProtobufTimestamp`

GetSnapshotTime returns the SnapshotTime field if non-nil, zero value otherwise.

### GetSnapshotTimeOk

`func (o *V2SiteSiteIdDetailPostRequest) GetSnapshotTimeOk() (*GoogleProtobufTimestamp, bool)`

GetSnapshotTimeOk returns a tuple with the SnapshotTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotTime

`func (o *V2SiteSiteIdDetailPostRequest) SetSnapshotTime(v GoogleProtobufTimestamp)`

SetSnapshotTime sets SnapshotTime field to given value.

### HasSnapshotTime

`func (o *V2SiteSiteIdDetailPostRequest) HasSnapshotTime() bool`

HasSnapshotTime returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V2SiteSiteIdDetailPostRequest) GetTimeWindow() StatsmonV2TimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V2SiteSiteIdDetailPostRequest) GetTimeWindowOk() (*StatsmonV2TimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V2SiteSiteIdDetailPostRequest) SetTimeWindow(v StatsmonV2TimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V2SiteSiteIdDetailPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



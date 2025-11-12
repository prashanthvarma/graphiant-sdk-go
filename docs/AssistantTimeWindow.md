# AssistantTimeWindow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BucketSizeSec** | Pointer to **int32** |  | [optional] 
**OldTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**RecentTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewAssistantTimeWindow

`func NewAssistantTimeWindow() *AssistantTimeWindow`

NewAssistantTimeWindow instantiates a new AssistantTimeWindow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssistantTimeWindowWithDefaults

`func NewAssistantTimeWindowWithDefaults() *AssistantTimeWindow`

NewAssistantTimeWindowWithDefaults instantiates a new AssistantTimeWindow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBucketSizeSec

`func (o *AssistantTimeWindow) GetBucketSizeSec() int32`

GetBucketSizeSec returns the BucketSizeSec field if non-nil, zero value otherwise.

### GetBucketSizeSecOk

`func (o *AssistantTimeWindow) GetBucketSizeSecOk() (*int32, bool)`

GetBucketSizeSecOk returns a tuple with the BucketSizeSec field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketSizeSec

`func (o *AssistantTimeWindow) SetBucketSizeSec(v int32)`

SetBucketSizeSec sets BucketSizeSec field to given value.

### HasBucketSizeSec

`func (o *AssistantTimeWindow) HasBucketSizeSec() bool`

HasBucketSizeSec returns a boolean if a field has been set.

### GetOldTs

`func (o *AssistantTimeWindow) GetOldTs() GoogleProtobufTimestamp`

GetOldTs returns the OldTs field if non-nil, zero value otherwise.

### GetOldTsOk

`func (o *AssistantTimeWindow) GetOldTsOk() (*GoogleProtobufTimestamp, bool)`

GetOldTsOk returns a tuple with the OldTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldTs

`func (o *AssistantTimeWindow) SetOldTs(v GoogleProtobufTimestamp)`

SetOldTs sets OldTs field to given value.

### HasOldTs

`func (o *AssistantTimeWindow) HasOldTs() bool`

HasOldTs returns a boolean if a field has been set.

### GetRecentTs

`func (o *AssistantTimeWindow) GetRecentTs() GoogleProtobufTimestamp`

GetRecentTs returns the RecentTs field if non-nil, zero value otherwise.

### GetRecentTsOk

`func (o *AssistantTimeWindow) GetRecentTsOk() (*GoogleProtobufTimestamp, bool)`

GetRecentTsOk returns a tuple with the RecentTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentTs

`func (o *AssistantTimeWindow) SetRecentTs(v GoogleProtobufTimestamp)`

SetRecentTs sets RecentTs field to given value.

### HasRecentTs

`func (o *AssistantTimeWindow) HasRecentTs() bool`

HasRecentTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AssuranceTimeWindow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BucketSizeSec** | Pointer to **int32** |  | [optional] 
**OldTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**RecentTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewAssuranceTimeWindow

`func NewAssuranceTimeWindow() *AssuranceTimeWindow`

NewAssuranceTimeWindow instantiates a new AssuranceTimeWindow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceTimeWindowWithDefaults

`func NewAssuranceTimeWindowWithDefaults() *AssuranceTimeWindow`

NewAssuranceTimeWindowWithDefaults instantiates a new AssuranceTimeWindow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBucketSizeSec

`func (o *AssuranceTimeWindow) GetBucketSizeSec() int32`

GetBucketSizeSec returns the BucketSizeSec field if non-nil, zero value otherwise.

### GetBucketSizeSecOk

`func (o *AssuranceTimeWindow) GetBucketSizeSecOk() (*int32, bool)`

GetBucketSizeSecOk returns a tuple with the BucketSizeSec field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketSizeSec

`func (o *AssuranceTimeWindow) SetBucketSizeSec(v int32)`

SetBucketSizeSec sets BucketSizeSec field to given value.

### HasBucketSizeSec

`func (o *AssuranceTimeWindow) HasBucketSizeSec() bool`

HasBucketSizeSec returns a boolean if a field has been set.

### GetOldTs

`func (o *AssuranceTimeWindow) GetOldTs() GoogleProtobufTimestamp`

GetOldTs returns the OldTs field if non-nil, zero value otherwise.

### GetOldTsOk

`func (o *AssuranceTimeWindow) GetOldTsOk() (*GoogleProtobufTimestamp, bool)`

GetOldTsOk returns a tuple with the OldTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldTs

`func (o *AssuranceTimeWindow) SetOldTs(v GoogleProtobufTimestamp)`

SetOldTs sets OldTs field to given value.

### HasOldTs

`func (o *AssuranceTimeWindow) HasOldTs() bool`

HasOldTs returns a boolean if a field has been set.

### GetRecentTs

`func (o *AssuranceTimeWindow) GetRecentTs() GoogleProtobufTimestamp`

GetRecentTs returns the RecentTs field if non-nil, zero value otherwise.

### GetRecentTsOk

`func (o *AssuranceTimeWindow) GetRecentTsOk() (*GoogleProtobufTimestamp, bool)`

GetRecentTsOk returns a tuple with the RecentTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentTs

`func (o *AssuranceTimeWindow) SetRecentTs(v GoogleProtobufTimestamp)`

SetRecentTs sets RecentTs field to given value.

### HasRecentTs

`func (o *AssuranceTimeWindow) HasRecentTs() bool`

HasRecentTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



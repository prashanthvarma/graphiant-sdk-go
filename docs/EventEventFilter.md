# EventEventFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OldTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**RecentTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewEventEventFilter

`func NewEventEventFilter() *EventEventFilter`

NewEventEventFilter instantiates a new EventEventFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventEventFilterWithDefaults

`func NewEventEventFilterWithDefaults() *EventEventFilter`

NewEventEventFilterWithDefaults instantiates a new EventEventFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOldTs

`func (o *EventEventFilter) GetOldTs() GoogleProtobufTimestamp`

GetOldTs returns the OldTs field if non-nil, zero value otherwise.

### GetOldTsOk

`func (o *EventEventFilter) GetOldTsOk() (*GoogleProtobufTimestamp, bool)`

GetOldTsOk returns a tuple with the OldTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldTs

`func (o *EventEventFilter) SetOldTs(v GoogleProtobufTimestamp)`

SetOldTs sets OldTs field to given value.

### HasOldTs

`func (o *EventEventFilter) HasOldTs() bool`

HasOldTs returns a boolean if a field has been set.

### GetRecentTs

`func (o *EventEventFilter) GetRecentTs() GoogleProtobufTimestamp`

GetRecentTs returns the RecentTs field if non-nil, zero value otherwise.

### GetRecentTsOk

`func (o *EventEventFilter) GetRecentTsOk() (*GoogleProtobufTimestamp, bool)`

GetRecentTsOk returns a tuple with the RecentTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentTs

`func (o *EventEventFilter) SetRecentTs(v GoogleProtobufTimestamp)`

SetRecentTs sets RecentTs field to given value.

### HasRecentTs

`func (o *EventEventFilter) HasRecentTs() bool`

HasRecentTs returns a boolean if a field has been set.

### GetSeverity

`func (o *EventEventFilter) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *EventEventFilter) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *EventEventFilter) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *EventEventFilter) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetType

`func (o *EventEventFilter) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EventEventFilter) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EventEventFilter) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EventEventFilter) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



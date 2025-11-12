# AuditmonActivityDetailsTarget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DetailedFailureReason** | Pointer to **string** |  | [optional] 
**EndTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Events** | Pointer to [**[]AuditmonActivityDetailsTargetEvent**](AuditmonActivityDetailsTargetEvent.md) |  | [optional] 
**FailureReason** | Pointer to **string** |  | [optional] 
**Ids** | Pointer to [**[]AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**StartTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewAuditmonActivityDetailsTarget

`func NewAuditmonActivityDetailsTarget() *AuditmonActivityDetailsTarget`

NewAuditmonActivityDetailsTarget instantiates a new AuditmonActivityDetailsTarget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditmonActivityDetailsTargetWithDefaults

`func NewAuditmonActivityDetailsTargetWithDefaults() *AuditmonActivityDetailsTarget`

NewAuditmonActivityDetailsTargetWithDefaults instantiates a new AuditmonActivityDetailsTarget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDetailedFailureReason

`func (o *AuditmonActivityDetailsTarget) GetDetailedFailureReason() string`

GetDetailedFailureReason returns the DetailedFailureReason field if non-nil, zero value otherwise.

### GetDetailedFailureReasonOk

`func (o *AuditmonActivityDetailsTarget) GetDetailedFailureReasonOk() (*string, bool)`

GetDetailedFailureReasonOk returns a tuple with the DetailedFailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetailedFailureReason

`func (o *AuditmonActivityDetailsTarget) SetDetailedFailureReason(v string)`

SetDetailedFailureReason sets DetailedFailureReason field to given value.

### HasDetailedFailureReason

`func (o *AuditmonActivityDetailsTarget) HasDetailedFailureReason() bool`

HasDetailedFailureReason returns a boolean if a field has been set.

### GetEndTs

`func (o *AuditmonActivityDetailsTarget) GetEndTs() GoogleProtobufTimestamp`

GetEndTs returns the EndTs field if non-nil, zero value otherwise.

### GetEndTsOk

`func (o *AuditmonActivityDetailsTarget) GetEndTsOk() (*GoogleProtobufTimestamp, bool)`

GetEndTsOk returns a tuple with the EndTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTs

`func (o *AuditmonActivityDetailsTarget) SetEndTs(v GoogleProtobufTimestamp)`

SetEndTs sets EndTs field to given value.

### HasEndTs

`func (o *AuditmonActivityDetailsTarget) HasEndTs() bool`

HasEndTs returns a boolean if a field has been set.

### GetEvents

`func (o *AuditmonActivityDetailsTarget) GetEvents() []AuditmonActivityDetailsTargetEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *AuditmonActivityDetailsTarget) GetEventsOk() (*[]AuditmonActivityDetailsTargetEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *AuditmonActivityDetailsTarget) SetEvents(v []AuditmonActivityDetailsTargetEvent)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *AuditmonActivityDetailsTarget) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetFailureReason

`func (o *AuditmonActivityDetailsTarget) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *AuditmonActivityDetailsTarget) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *AuditmonActivityDetailsTarget) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *AuditmonActivityDetailsTarget) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### GetIds

`func (o *AuditmonActivityDetailsTarget) GetIds() []AuditActivityItem`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *AuditmonActivityDetailsTarget) GetIdsOk() (*[]AuditActivityItem, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *AuditmonActivityDetailsTarget) SetIds(v []AuditActivityItem)`

SetIds sets Ids field to given value.

### HasIds

`func (o *AuditmonActivityDetailsTarget) HasIds() bool`

HasIds returns a boolean if a field has been set.

### GetStartTs

`func (o *AuditmonActivityDetailsTarget) GetStartTs() GoogleProtobufTimestamp`

GetStartTs returns the StartTs field if non-nil, zero value otherwise.

### GetStartTsOk

`func (o *AuditmonActivityDetailsTarget) GetStartTsOk() (*GoogleProtobufTimestamp, bool)`

GetStartTsOk returns a tuple with the StartTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTs

`func (o *AuditmonActivityDetailsTarget) SetStartTs(v GoogleProtobufTimestamp)`

SetStartTs sets StartTs field to given value.

### HasStartTs

`func (o *AuditmonActivityDetailsTarget) HasStartTs() bool`

HasStartTs returns a boolean if a field has been set.

### GetStatus

`func (o *AuditmonActivityDetailsTarget) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuditmonActivityDetailsTarget) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuditmonActivityDetailsTarget) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AuditmonActivityDetailsTarget) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



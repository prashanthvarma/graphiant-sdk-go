# AuditAuditEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Activity** | Pointer to **string** |  | [optional] 
**Actor** | Pointer to **string** |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**End** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**FailedTargetResults** | Pointer to [**[]AuditTargetResult**](AuditTargetResult.md) |  | [optional] 
**Info** | Pointer to **string** |  | [optional] 
**Reason** | Pointer to **string** |  | [optional] 
**Service** | Pointer to **string** |  | [optional] 
**Start** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Targets** | Pointer to [**[]AuditTargetResult**](AuditTargetResult.md) |  | [optional] 

## Methods

### NewAuditAuditEntry

`func NewAuditAuditEntry() *AuditAuditEntry`

NewAuditAuditEntry instantiates a new AuditAuditEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditAuditEntryWithDefaults

`func NewAuditAuditEntryWithDefaults() *AuditAuditEntry`

NewAuditAuditEntryWithDefaults instantiates a new AuditAuditEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivity

`func (o *AuditAuditEntry) GetActivity() string`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *AuditAuditEntry) GetActivityOk() (*string, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *AuditAuditEntry) SetActivity(v string)`

SetActivity sets Activity field to given value.

### HasActivity

`func (o *AuditAuditEntry) HasActivity() bool`

HasActivity returns a boolean if a field has been set.

### GetActor

`func (o *AuditAuditEntry) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *AuditAuditEntry) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *AuditAuditEntry) SetActor(v string)`

SetActor sets Actor field to given value.

### HasActor

`func (o *AuditAuditEntry) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetCategory

`func (o *AuditAuditEntry) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AuditAuditEntry) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AuditAuditEntry) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *AuditAuditEntry) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetEnd

`func (o *AuditAuditEntry) GetEnd() GoogleProtobufTimestamp`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *AuditAuditEntry) GetEndOk() (*GoogleProtobufTimestamp, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *AuditAuditEntry) SetEnd(v GoogleProtobufTimestamp)`

SetEnd sets End field to given value.

### HasEnd

`func (o *AuditAuditEntry) HasEnd() bool`

HasEnd returns a boolean if a field has been set.

### GetFailedTargetResults

`func (o *AuditAuditEntry) GetFailedTargetResults() []AuditTargetResult`

GetFailedTargetResults returns the FailedTargetResults field if non-nil, zero value otherwise.

### GetFailedTargetResultsOk

`func (o *AuditAuditEntry) GetFailedTargetResultsOk() (*[]AuditTargetResult, bool)`

GetFailedTargetResultsOk returns a tuple with the FailedTargetResults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedTargetResults

`func (o *AuditAuditEntry) SetFailedTargetResults(v []AuditTargetResult)`

SetFailedTargetResults sets FailedTargetResults field to given value.

### HasFailedTargetResults

`func (o *AuditAuditEntry) HasFailedTargetResults() bool`

HasFailedTargetResults returns a boolean if a field has been set.

### GetInfo

`func (o *AuditAuditEntry) GetInfo() string`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *AuditAuditEntry) GetInfoOk() (*string, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *AuditAuditEntry) SetInfo(v string)`

SetInfo sets Info field to given value.

### HasInfo

`func (o *AuditAuditEntry) HasInfo() bool`

HasInfo returns a boolean if a field has been set.

### GetReason

`func (o *AuditAuditEntry) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuditAuditEntry) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuditAuditEntry) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AuditAuditEntry) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetService

`func (o *AuditAuditEntry) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *AuditAuditEntry) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *AuditAuditEntry) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *AuditAuditEntry) HasService() bool`

HasService returns a boolean if a field has been set.

### GetStart

`func (o *AuditAuditEntry) GetStart() GoogleProtobufTimestamp`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *AuditAuditEntry) GetStartOk() (*GoogleProtobufTimestamp, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *AuditAuditEntry) SetStart(v GoogleProtobufTimestamp)`

SetStart sets Start field to given value.

### HasStart

`func (o *AuditAuditEntry) HasStart() bool`

HasStart returns a boolean if a field has been set.

### GetStatus

`func (o *AuditAuditEntry) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuditAuditEntry) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuditAuditEntry) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AuditAuditEntry) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTargets

`func (o *AuditAuditEntry) GetTargets() []AuditTargetResult`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *AuditAuditEntry) GetTargetsOk() (*[]AuditTargetResult, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *AuditAuditEntry) SetTargets(v []AuditTargetResult)`

SetTargets sets Targets field to given value.

### HasTargets

`func (o *AuditAuditEntry) HasTargets() bool`

HasTargets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



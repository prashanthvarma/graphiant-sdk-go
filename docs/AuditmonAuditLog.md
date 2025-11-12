# AuditmonAuditLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] 
**ActivityId** | Pointer to **string** |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**Entity** | Pointer to [**AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**JobType** | Pointer to **string** |  | [optional] 
**Target** | Pointer to [**AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**User** | Pointer to **string** |  | [optional] 

## Methods

### NewAuditmonAuditLog

`func NewAuditmonAuditLog() *AuditmonAuditLog`

NewAuditmonAuditLog instantiates a new AuditmonAuditLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditmonAuditLogWithDefaults

`func NewAuditmonAuditLogWithDefaults() *AuditmonAuditLog`

NewAuditmonAuditLogWithDefaults instantiates a new AuditmonAuditLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AuditmonAuditLog) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AuditmonAuditLog) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AuditmonAuditLog) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *AuditmonAuditLog) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetActivityId

`func (o *AuditmonAuditLog) GetActivityId() string`

GetActivityId returns the ActivityId field if non-nil, zero value otherwise.

### GetActivityIdOk

`func (o *AuditmonAuditLog) GetActivityIdOk() (*string, bool)`

GetActivityIdOk returns a tuple with the ActivityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityId

`func (o *AuditmonAuditLog) SetActivityId(v string)`

SetActivityId sets ActivityId field to given value.

### HasActivityId

`func (o *AuditmonAuditLog) HasActivityId() bool`

HasActivityId returns a boolean if a field has been set.

### GetCategory

`func (o *AuditmonAuditLog) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AuditmonAuditLog) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AuditmonAuditLog) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *AuditmonAuditLog) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetEntity

`func (o *AuditmonAuditLog) GetEntity() AuditActivityItem`

GetEntity returns the Entity field if non-nil, zero value otherwise.

### GetEntityOk

`func (o *AuditmonAuditLog) GetEntityOk() (*AuditActivityItem, bool)`

GetEntityOk returns a tuple with the Entity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntity

`func (o *AuditmonAuditLog) SetEntity(v AuditActivityItem)`

SetEntity sets Entity field to given value.

### HasEntity

`func (o *AuditmonAuditLog) HasEntity() bool`

HasEntity returns a boolean if a field has been set.

### GetJobType

`func (o *AuditmonAuditLog) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *AuditmonAuditLog) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *AuditmonAuditLog) SetJobType(v string)`

SetJobType sets JobType field to given value.

### HasJobType

`func (o *AuditmonAuditLog) HasJobType() bool`

HasJobType returns a boolean if a field has been set.

### GetTarget

`func (o *AuditmonAuditLog) GetTarget() AuditActivityItem`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *AuditmonAuditLog) GetTargetOk() (*AuditActivityItem, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *AuditmonAuditLog) SetTarget(v AuditActivityItem)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *AuditmonAuditLog) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetTs

`func (o *AuditmonAuditLog) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *AuditmonAuditLog) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *AuditmonAuditLog) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *AuditmonAuditLog) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetUser

`func (o *AuditmonAuditLog) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *AuditmonAuditLog) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *AuditmonAuditLog) SetUser(v string)`

SetUser sets User field to given value.

### HasUser

`func (o *AuditmonAuditLog) HasUser() bool`

HasUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AuditmonActivityDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] 
**Attributes** | Pointer to [**[]AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**DisableAutoTimeout** | Pointer to **bool** |  | [optional] 
**EndTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**InitiatorType** | Pointer to **string** |  | [optional] 
**JobEntities** | Pointer to [**[]AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**JobType** | Pointer to **string** |  | [optional] 
**OriginalEnterpriseId** | Pointer to **int64** |  | [optional] 
**StartTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Targets** | Pointer to [**[]AuditmonActivityDetailsTarget**](AuditmonActivityDetailsTarget.md) |  | [optional] 
**TraceSessionId** | Pointer to **string** |  | [optional] 
**Usage** | Pointer to **string** |  | [optional] 
**User** | Pointer to **string** |  | [optional] 
**UserId** | Pointer to **string** |  | [optional] 

## Methods

### NewAuditmonActivityDetails

`func NewAuditmonActivityDetails() *AuditmonActivityDetails`

NewAuditmonActivityDetails instantiates a new AuditmonActivityDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditmonActivityDetailsWithDefaults

`func NewAuditmonActivityDetailsWithDefaults() *AuditmonActivityDetails`

NewAuditmonActivityDetailsWithDefaults instantiates a new AuditmonActivityDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AuditmonActivityDetails) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AuditmonActivityDetails) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AuditmonActivityDetails) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *AuditmonActivityDetails) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetAttributes

`func (o *AuditmonActivityDetails) GetAttributes() []AuditActivityItem`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *AuditmonActivityDetails) GetAttributesOk() (*[]AuditActivityItem, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *AuditmonActivityDetails) SetAttributes(v []AuditActivityItem)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *AuditmonActivityDetails) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.

### GetCategory

`func (o *AuditmonActivityDetails) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AuditmonActivityDetails) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AuditmonActivityDetails) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *AuditmonActivityDetails) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetDisableAutoTimeout

`func (o *AuditmonActivityDetails) GetDisableAutoTimeout() bool`

GetDisableAutoTimeout returns the DisableAutoTimeout field if non-nil, zero value otherwise.

### GetDisableAutoTimeoutOk

`func (o *AuditmonActivityDetails) GetDisableAutoTimeoutOk() (*bool, bool)`

GetDisableAutoTimeoutOk returns a tuple with the DisableAutoTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisableAutoTimeout

`func (o *AuditmonActivityDetails) SetDisableAutoTimeout(v bool)`

SetDisableAutoTimeout sets DisableAutoTimeout field to given value.

### HasDisableAutoTimeout

`func (o *AuditmonActivityDetails) HasDisableAutoTimeout() bool`

HasDisableAutoTimeout returns a boolean if a field has been set.

### GetEndTs

`func (o *AuditmonActivityDetails) GetEndTs() GoogleProtobufTimestamp`

GetEndTs returns the EndTs field if non-nil, zero value otherwise.

### GetEndTsOk

`func (o *AuditmonActivityDetails) GetEndTsOk() (*GoogleProtobufTimestamp, bool)`

GetEndTsOk returns a tuple with the EndTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTs

`func (o *AuditmonActivityDetails) SetEndTs(v GoogleProtobufTimestamp)`

SetEndTs sets EndTs field to given value.

### HasEndTs

`func (o *AuditmonActivityDetails) HasEndTs() bool`

HasEndTs returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *AuditmonActivityDetails) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *AuditmonActivityDetails) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *AuditmonActivityDetails) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *AuditmonActivityDetails) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetId

`func (o *AuditmonActivityDetails) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuditmonActivityDetails) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuditmonActivityDetails) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AuditmonActivityDetails) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInitiatorType

`func (o *AuditmonActivityDetails) GetInitiatorType() string`

GetInitiatorType returns the InitiatorType field if non-nil, zero value otherwise.

### GetInitiatorTypeOk

`func (o *AuditmonActivityDetails) GetInitiatorTypeOk() (*string, bool)`

GetInitiatorTypeOk returns a tuple with the InitiatorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitiatorType

`func (o *AuditmonActivityDetails) SetInitiatorType(v string)`

SetInitiatorType sets InitiatorType field to given value.

### HasInitiatorType

`func (o *AuditmonActivityDetails) HasInitiatorType() bool`

HasInitiatorType returns a boolean if a field has been set.

### GetJobEntities

`func (o *AuditmonActivityDetails) GetJobEntities() []AuditActivityItem`

GetJobEntities returns the JobEntities field if non-nil, zero value otherwise.

### GetJobEntitiesOk

`func (o *AuditmonActivityDetails) GetJobEntitiesOk() (*[]AuditActivityItem, bool)`

GetJobEntitiesOk returns a tuple with the JobEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobEntities

`func (o *AuditmonActivityDetails) SetJobEntities(v []AuditActivityItem)`

SetJobEntities sets JobEntities field to given value.

### HasJobEntities

`func (o *AuditmonActivityDetails) HasJobEntities() bool`

HasJobEntities returns a boolean if a field has been set.

### GetJobType

`func (o *AuditmonActivityDetails) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *AuditmonActivityDetails) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *AuditmonActivityDetails) SetJobType(v string)`

SetJobType sets JobType field to given value.

### HasJobType

`func (o *AuditmonActivityDetails) HasJobType() bool`

HasJobType returns a boolean if a field has been set.

### GetOriginalEnterpriseId

`func (o *AuditmonActivityDetails) GetOriginalEnterpriseId() int64`

GetOriginalEnterpriseId returns the OriginalEnterpriseId field if non-nil, zero value otherwise.

### GetOriginalEnterpriseIdOk

`func (o *AuditmonActivityDetails) GetOriginalEnterpriseIdOk() (*int64, bool)`

GetOriginalEnterpriseIdOk returns a tuple with the OriginalEnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalEnterpriseId

`func (o *AuditmonActivityDetails) SetOriginalEnterpriseId(v int64)`

SetOriginalEnterpriseId sets OriginalEnterpriseId field to given value.

### HasOriginalEnterpriseId

`func (o *AuditmonActivityDetails) HasOriginalEnterpriseId() bool`

HasOriginalEnterpriseId returns a boolean if a field has been set.

### GetStartTs

`func (o *AuditmonActivityDetails) GetStartTs() GoogleProtobufTimestamp`

GetStartTs returns the StartTs field if non-nil, zero value otherwise.

### GetStartTsOk

`func (o *AuditmonActivityDetails) GetStartTsOk() (*GoogleProtobufTimestamp, bool)`

GetStartTsOk returns a tuple with the StartTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTs

`func (o *AuditmonActivityDetails) SetStartTs(v GoogleProtobufTimestamp)`

SetStartTs sets StartTs field to given value.

### HasStartTs

`func (o *AuditmonActivityDetails) HasStartTs() bool`

HasStartTs returns a boolean if a field has been set.

### GetStatus

`func (o *AuditmonActivityDetails) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuditmonActivityDetails) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuditmonActivityDetails) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AuditmonActivityDetails) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTargets

`func (o *AuditmonActivityDetails) GetTargets() []AuditmonActivityDetailsTarget`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *AuditmonActivityDetails) GetTargetsOk() (*[]AuditmonActivityDetailsTarget, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *AuditmonActivityDetails) SetTargets(v []AuditmonActivityDetailsTarget)`

SetTargets sets Targets field to given value.

### HasTargets

`func (o *AuditmonActivityDetails) HasTargets() bool`

HasTargets returns a boolean if a field has been set.

### GetTraceSessionId

`func (o *AuditmonActivityDetails) GetTraceSessionId() string`

GetTraceSessionId returns the TraceSessionId field if non-nil, zero value otherwise.

### GetTraceSessionIdOk

`func (o *AuditmonActivityDetails) GetTraceSessionIdOk() (*string, bool)`

GetTraceSessionIdOk returns a tuple with the TraceSessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceSessionId

`func (o *AuditmonActivityDetails) SetTraceSessionId(v string)`

SetTraceSessionId sets TraceSessionId field to given value.

### HasTraceSessionId

`func (o *AuditmonActivityDetails) HasTraceSessionId() bool`

HasTraceSessionId returns a boolean if a field has been set.

### GetUsage

`func (o *AuditmonActivityDetails) GetUsage() string`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AuditmonActivityDetails) GetUsageOk() (*string, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AuditmonActivityDetails) SetUsage(v string)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *AuditmonActivityDetails) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetUser

`func (o *AuditmonActivityDetails) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *AuditmonActivityDetails) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *AuditmonActivityDetails) SetUser(v string)`

SetUser sets User field to given value.

### HasUser

`func (o *AuditmonActivityDetails) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetUserId

`func (o *AuditmonActivityDetails) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AuditmonActivityDetails) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AuditmonActivityDetails) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *AuditmonActivityDetails) HasUserId() bool`

HasUserId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# StatsmonTroubleshootingIssue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlertId** | Pointer to **string** |  | [optional] 
**AllowListed** | Pointer to **bool** |  | [optional] 
**Component** | Pointer to **string** |  | [optional] 
**EndTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Entity** | Pointer to **string** |  | [optional] 
**Issue** | Pointer to **string** |  | [optional] 
**MuteListed** | Pointer to **bool** |  | [optional] 
**NotificationCreated** | Pointer to **bool** |  | [optional] 
**Plane** | Pointer to **string** |  | [optional] 
**Reason** | Pointer to **string** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**StartTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonTroubleshootingIssue

`func NewStatsmonTroubleshootingIssue() *StatsmonTroubleshootingIssue`

NewStatsmonTroubleshootingIssue instantiates a new StatsmonTroubleshootingIssue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonTroubleshootingIssueWithDefaults

`func NewStatsmonTroubleshootingIssueWithDefaults() *StatsmonTroubleshootingIssue`

NewStatsmonTroubleshootingIssueWithDefaults instantiates a new StatsmonTroubleshootingIssue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlertId

`func (o *StatsmonTroubleshootingIssue) GetAlertId() string`

GetAlertId returns the AlertId field if non-nil, zero value otherwise.

### GetAlertIdOk

`func (o *StatsmonTroubleshootingIssue) GetAlertIdOk() (*string, bool)`

GetAlertIdOk returns a tuple with the AlertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertId

`func (o *StatsmonTroubleshootingIssue) SetAlertId(v string)`

SetAlertId sets AlertId field to given value.

### HasAlertId

`func (o *StatsmonTroubleshootingIssue) HasAlertId() bool`

HasAlertId returns a boolean if a field has been set.

### GetAllowListed

`func (o *StatsmonTroubleshootingIssue) GetAllowListed() bool`

GetAllowListed returns the AllowListed field if non-nil, zero value otherwise.

### GetAllowListedOk

`func (o *StatsmonTroubleshootingIssue) GetAllowListedOk() (*bool, bool)`

GetAllowListedOk returns a tuple with the AllowListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowListed

`func (o *StatsmonTroubleshootingIssue) SetAllowListed(v bool)`

SetAllowListed sets AllowListed field to given value.

### HasAllowListed

`func (o *StatsmonTroubleshootingIssue) HasAllowListed() bool`

HasAllowListed returns a boolean if a field has been set.

### GetComponent

`func (o *StatsmonTroubleshootingIssue) GetComponent() string`

GetComponent returns the Component field if non-nil, zero value otherwise.

### GetComponentOk

`func (o *StatsmonTroubleshootingIssue) GetComponentOk() (*string, bool)`

GetComponentOk returns a tuple with the Component field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponent

`func (o *StatsmonTroubleshootingIssue) SetComponent(v string)`

SetComponent sets Component field to given value.

### HasComponent

`func (o *StatsmonTroubleshootingIssue) HasComponent() bool`

HasComponent returns a boolean if a field has been set.

### GetEndTime

`func (o *StatsmonTroubleshootingIssue) GetEndTime() GoogleProtobufTimestamp`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *StatsmonTroubleshootingIssue) GetEndTimeOk() (*GoogleProtobufTimestamp, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *StatsmonTroubleshootingIssue) SetEndTime(v GoogleProtobufTimestamp)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *StatsmonTroubleshootingIssue) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### GetEntity

`func (o *StatsmonTroubleshootingIssue) GetEntity() string`

GetEntity returns the Entity field if non-nil, zero value otherwise.

### GetEntityOk

`func (o *StatsmonTroubleshootingIssue) GetEntityOk() (*string, bool)`

GetEntityOk returns a tuple with the Entity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntity

`func (o *StatsmonTroubleshootingIssue) SetEntity(v string)`

SetEntity sets Entity field to given value.

### HasEntity

`func (o *StatsmonTroubleshootingIssue) HasEntity() bool`

HasEntity returns a boolean if a field has been set.

### GetIssue

`func (o *StatsmonTroubleshootingIssue) GetIssue() string`

GetIssue returns the Issue field if non-nil, zero value otherwise.

### GetIssueOk

`func (o *StatsmonTroubleshootingIssue) GetIssueOk() (*string, bool)`

GetIssueOk returns a tuple with the Issue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssue

`func (o *StatsmonTroubleshootingIssue) SetIssue(v string)`

SetIssue sets Issue field to given value.

### HasIssue

`func (o *StatsmonTroubleshootingIssue) HasIssue() bool`

HasIssue returns a boolean if a field has been set.

### GetMuteListed

`func (o *StatsmonTroubleshootingIssue) GetMuteListed() bool`

GetMuteListed returns the MuteListed field if non-nil, zero value otherwise.

### GetMuteListedOk

`func (o *StatsmonTroubleshootingIssue) GetMuteListedOk() (*bool, bool)`

GetMuteListedOk returns a tuple with the MuteListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMuteListed

`func (o *StatsmonTroubleshootingIssue) SetMuteListed(v bool)`

SetMuteListed sets MuteListed field to given value.

### HasMuteListed

`func (o *StatsmonTroubleshootingIssue) HasMuteListed() bool`

HasMuteListed returns a boolean if a field has been set.

### GetNotificationCreated

`func (o *StatsmonTroubleshootingIssue) GetNotificationCreated() bool`

GetNotificationCreated returns the NotificationCreated field if non-nil, zero value otherwise.

### GetNotificationCreatedOk

`func (o *StatsmonTroubleshootingIssue) GetNotificationCreatedOk() (*bool, bool)`

GetNotificationCreatedOk returns a tuple with the NotificationCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationCreated

`func (o *StatsmonTroubleshootingIssue) SetNotificationCreated(v bool)`

SetNotificationCreated sets NotificationCreated field to given value.

### HasNotificationCreated

`func (o *StatsmonTroubleshootingIssue) HasNotificationCreated() bool`

HasNotificationCreated returns a boolean if a field has been set.

### GetPlane

`func (o *StatsmonTroubleshootingIssue) GetPlane() string`

GetPlane returns the Plane field if non-nil, zero value otherwise.

### GetPlaneOk

`func (o *StatsmonTroubleshootingIssue) GetPlaneOk() (*string, bool)`

GetPlaneOk returns a tuple with the Plane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlane

`func (o *StatsmonTroubleshootingIssue) SetPlane(v string)`

SetPlane sets Plane field to given value.

### HasPlane

`func (o *StatsmonTroubleshootingIssue) HasPlane() bool`

HasPlane returns a boolean if a field has been set.

### GetReason

`func (o *StatsmonTroubleshootingIssue) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *StatsmonTroubleshootingIssue) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *StatsmonTroubleshootingIssue) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *StatsmonTroubleshootingIssue) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetSeverity

`func (o *StatsmonTroubleshootingIssue) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *StatsmonTroubleshootingIssue) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *StatsmonTroubleshootingIssue) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *StatsmonTroubleshootingIssue) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetStartTime

`func (o *StatsmonTroubleshootingIssue) GetStartTime() GoogleProtobufTimestamp`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *StatsmonTroubleshootingIssue) GetStartTimeOk() (*GoogleProtobufTimestamp, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *StatsmonTroubleshootingIssue) SetStartTime(v GoogleProtobufTimestamp)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *StatsmonTroubleshootingIssue) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetStatus

`func (o *StatsmonTroubleshootingIssue) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonTroubleshootingIssue) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonTroubleshootingIssue) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonTroubleshootingIssue) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



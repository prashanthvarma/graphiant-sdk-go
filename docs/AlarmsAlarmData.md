# AlarmsAlarmData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcknowledgedBy** | Pointer to **string** | The user who acknowledged this alarm. | [optional] 
**AlarmId** | Pointer to **int64** | Unique ID for an alarm. | [optional] 
**AlarmTypeId** | Pointer to **string** | Type ID for an alarm. | [optional] 
**AlarmTypeQualifier** | Pointer to **string** | Unique qualifier for an alarm. It could be null if the alarm id is enough to distinguish the alarms | [optional] 
**AltComponent** | Pointer to **string** | Used if the alarming resource is available over other interfaces. | [optional] 
**BootId** | Pointer to **string** | The boot id for this alarm in the device if alarm is a device alarm. | [optional] 
**Component** | Pointer to **string** | The component which raised this alarm. | [optional] 
**Created** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Description** | Pointer to **string** | The text representation of this alarm | [optional] 
**IsCleared** | Pointer to **bool** | This flag shows if the alarm is already cleared. | [optional] 
**IsResolved** | Pointer to **bool** | This flag shows if the alarm is already marked as resolved by the customer. | [optional] 
**LastChanged** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**LastRaised** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**PerceivedSeverity** | Pointer to **string** | Severity of this alarm. | [optional] 
**ResolvedBy** | Pointer to **string** | The user who moved this alert to resolved. | [optional] 
**SequenceNumber** | Pointer to **int64** | The sequence number for this alarm in the device if alarm is a device alarm. | [optional] 
**Where** | Pointer to **string** | Hostname, site, etc where this alarm is generated for. | [optional] 

## Methods

### NewAlarmsAlarmData

`func NewAlarmsAlarmData() *AlarmsAlarmData`

NewAlarmsAlarmData instantiates a new AlarmsAlarmData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlarmsAlarmDataWithDefaults

`func NewAlarmsAlarmDataWithDefaults() *AlarmsAlarmData`

NewAlarmsAlarmDataWithDefaults instantiates a new AlarmsAlarmData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcknowledgedBy

`func (o *AlarmsAlarmData) GetAcknowledgedBy() string`

GetAcknowledgedBy returns the AcknowledgedBy field if non-nil, zero value otherwise.

### GetAcknowledgedByOk

`func (o *AlarmsAlarmData) GetAcknowledgedByOk() (*string, bool)`

GetAcknowledgedByOk returns a tuple with the AcknowledgedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedBy

`func (o *AlarmsAlarmData) SetAcknowledgedBy(v string)`

SetAcknowledgedBy sets AcknowledgedBy field to given value.

### HasAcknowledgedBy

`func (o *AlarmsAlarmData) HasAcknowledgedBy() bool`

HasAcknowledgedBy returns a boolean if a field has been set.

### GetAlarmId

`func (o *AlarmsAlarmData) GetAlarmId() int64`

GetAlarmId returns the AlarmId field if non-nil, zero value otherwise.

### GetAlarmIdOk

`func (o *AlarmsAlarmData) GetAlarmIdOk() (*int64, bool)`

GetAlarmIdOk returns a tuple with the AlarmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmId

`func (o *AlarmsAlarmData) SetAlarmId(v int64)`

SetAlarmId sets AlarmId field to given value.

### HasAlarmId

`func (o *AlarmsAlarmData) HasAlarmId() bool`

HasAlarmId returns a boolean if a field has been set.

### GetAlarmTypeId

`func (o *AlarmsAlarmData) GetAlarmTypeId() string`

GetAlarmTypeId returns the AlarmTypeId field if non-nil, zero value otherwise.

### GetAlarmTypeIdOk

`func (o *AlarmsAlarmData) GetAlarmTypeIdOk() (*string, bool)`

GetAlarmTypeIdOk returns a tuple with the AlarmTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmTypeId

`func (o *AlarmsAlarmData) SetAlarmTypeId(v string)`

SetAlarmTypeId sets AlarmTypeId field to given value.

### HasAlarmTypeId

`func (o *AlarmsAlarmData) HasAlarmTypeId() bool`

HasAlarmTypeId returns a boolean if a field has been set.

### GetAlarmTypeQualifier

`func (o *AlarmsAlarmData) GetAlarmTypeQualifier() string`

GetAlarmTypeQualifier returns the AlarmTypeQualifier field if non-nil, zero value otherwise.

### GetAlarmTypeQualifierOk

`func (o *AlarmsAlarmData) GetAlarmTypeQualifierOk() (*string, bool)`

GetAlarmTypeQualifierOk returns a tuple with the AlarmTypeQualifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmTypeQualifier

`func (o *AlarmsAlarmData) SetAlarmTypeQualifier(v string)`

SetAlarmTypeQualifier sets AlarmTypeQualifier field to given value.

### HasAlarmTypeQualifier

`func (o *AlarmsAlarmData) HasAlarmTypeQualifier() bool`

HasAlarmTypeQualifier returns a boolean if a field has been set.

### GetAltComponent

`func (o *AlarmsAlarmData) GetAltComponent() string`

GetAltComponent returns the AltComponent field if non-nil, zero value otherwise.

### GetAltComponentOk

`func (o *AlarmsAlarmData) GetAltComponentOk() (*string, bool)`

GetAltComponentOk returns a tuple with the AltComponent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltComponent

`func (o *AlarmsAlarmData) SetAltComponent(v string)`

SetAltComponent sets AltComponent field to given value.

### HasAltComponent

`func (o *AlarmsAlarmData) HasAltComponent() bool`

HasAltComponent returns a boolean if a field has been set.

### GetBootId

`func (o *AlarmsAlarmData) GetBootId() string`

GetBootId returns the BootId field if non-nil, zero value otherwise.

### GetBootIdOk

`func (o *AlarmsAlarmData) GetBootIdOk() (*string, bool)`

GetBootIdOk returns a tuple with the BootId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootId

`func (o *AlarmsAlarmData) SetBootId(v string)`

SetBootId sets BootId field to given value.

### HasBootId

`func (o *AlarmsAlarmData) HasBootId() bool`

HasBootId returns a boolean if a field has been set.

### GetComponent

`func (o *AlarmsAlarmData) GetComponent() string`

GetComponent returns the Component field if non-nil, zero value otherwise.

### GetComponentOk

`func (o *AlarmsAlarmData) GetComponentOk() (*string, bool)`

GetComponentOk returns a tuple with the Component field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponent

`func (o *AlarmsAlarmData) SetComponent(v string)`

SetComponent sets Component field to given value.

### HasComponent

`func (o *AlarmsAlarmData) HasComponent() bool`

HasComponent returns a boolean if a field has been set.

### GetCreated

`func (o *AlarmsAlarmData) GetCreated() GoogleProtobufTimestamp`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *AlarmsAlarmData) GetCreatedOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *AlarmsAlarmData) SetCreated(v GoogleProtobufTimestamp)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *AlarmsAlarmData) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetDescription

`func (o *AlarmsAlarmData) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AlarmsAlarmData) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AlarmsAlarmData) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AlarmsAlarmData) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsCleared

`func (o *AlarmsAlarmData) GetIsCleared() bool`

GetIsCleared returns the IsCleared field if non-nil, zero value otherwise.

### GetIsClearedOk

`func (o *AlarmsAlarmData) GetIsClearedOk() (*bool, bool)`

GetIsClearedOk returns a tuple with the IsCleared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCleared

`func (o *AlarmsAlarmData) SetIsCleared(v bool)`

SetIsCleared sets IsCleared field to given value.

### HasIsCleared

`func (o *AlarmsAlarmData) HasIsCleared() bool`

HasIsCleared returns a boolean if a field has been set.

### GetIsResolved

`func (o *AlarmsAlarmData) GetIsResolved() bool`

GetIsResolved returns the IsResolved field if non-nil, zero value otherwise.

### GetIsResolvedOk

`func (o *AlarmsAlarmData) GetIsResolvedOk() (*bool, bool)`

GetIsResolvedOk returns a tuple with the IsResolved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsResolved

`func (o *AlarmsAlarmData) SetIsResolved(v bool)`

SetIsResolved sets IsResolved field to given value.

### HasIsResolved

`func (o *AlarmsAlarmData) HasIsResolved() bool`

HasIsResolved returns a boolean if a field has been set.

### GetLastChanged

`func (o *AlarmsAlarmData) GetLastChanged() GoogleProtobufTimestamp`

GetLastChanged returns the LastChanged field if non-nil, zero value otherwise.

### GetLastChangedOk

`func (o *AlarmsAlarmData) GetLastChangedOk() (*GoogleProtobufTimestamp, bool)`

GetLastChangedOk returns a tuple with the LastChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastChanged

`func (o *AlarmsAlarmData) SetLastChanged(v GoogleProtobufTimestamp)`

SetLastChanged sets LastChanged field to given value.

### HasLastChanged

`func (o *AlarmsAlarmData) HasLastChanged() bool`

HasLastChanged returns a boolean if a field has been set.

### GetLastRaised

`func (o *AlarmsAlarmData) GetLastRaised() GoogleProtobufTimestamp`

GetLastRaised returns the LastRaised field if non-nil, zero value otherwise.

### GetLastRaisedOk

`func (o *AlarmsAlarmData) GetLastRaisedOk() (*GoogleProtobufTimestamp, bool)`

GetLastRaisedOk returns a tuple with the LastRaised field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRaised

`func (o *AlarmsAlarmData) SetLastRaised(v GoogleProtobufTimestamp)`

SetLastRaised sets LastRaised field to given value.

### HasLastRaised

`func (o *AlarmsAlarmData) HasLastRaised() bool`

HasLastRaised returns a boolean if a field has been set.

### GetPerceivedSeverity

`func (o *AlarmsAlarmData) GetPerceivedSeverity() string`

GetPerceivedSeverity returns the PerceivedSeverity field if non-nil, zero value otherwise.

### GetPerceivedSeverityOk

`func (o *AlarmsAlarmData) GetPerceivedSeverityOk() (*string, bool)`

GetPerceivedSeverityOk returns a tuple with the PerceivedSeverity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerceivedSeverity

`func (o *AlarmsAlarmData) SetPerceivedSeverity(v string)`

SetPerceivedSeverity sets PerceivedSeverity field to given value.

### HasPerceivedSeverity

`func (o *AlarmsAlarmData) HasPerceivedSeverity() bool`

HasPerceivedSeverity returns a boolean if a field has been set.

### GetResolvedBy

`func (o *AlarmsAlarmData) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *AlarmsAlarmData) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *AlarmsAlarmData) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.

### HasResolvedBy

`func (o *AlarmsAlarmData) HasResolvedBy() bool`

HasResolvedBy returns a boolean if a field has been set.

### GetSequenceNumber

`func (o *AlarmsAlarmData) GetSequenceNumber() int64`

GetSequenceNumber returns the SequenceNumber field if non-nil, zero value otherwise.

### GetSequenceNumberOk

`func (o *AlarmsAlarmData) GetSequenceNumberOk() (*int64, bool)`

GetSequenceNumberOk returns a tuple with the SequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequenceNumber

`func (o *AlarmsAlarmData) SetSequenceNumber(v int64)`

SetSequenceNumber sets SequenceNumber field to given value.

### HasSequenceNumber

`func (o *AlarmsAlarmData) HasSequenceNumber() bool`

HasSequenceNumber returns a boolean if a field has been set.

### GetWhere

`func (o *AlarmsAlarmData) GetWhere() string`

GetWhere returns the Where field if non-nil, zero value otherwise.

### GetWhereOk

`func (o *AlarmsAlarmData) GetWhereOk() (*string, bool)`

GetWhereOk returns a tuple with the Where field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhere

`func (o *AlarmsAlarmData) SetWhere(v string)`

SetWhere sets Where field to given value.

### HasWhere

`func (o *AlarmsAlarmData) HasWhere() bool`

HasWhere returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



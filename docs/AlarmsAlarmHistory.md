# AlarmsAlarmHistory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BootId** | Pointer to **string** | The boot id for this alarm in the device if alarm is a device alarm. | [optional] 
**Description** | Pointer to **string** | The text representation of this alarm | [optional] 
**IsCleared** | Pointer to **bool** | This flag shows if the alarm is already cleared. | [optional] 
**PerceivedSeverity** | Pointer to **string** | Severity of this alarm. | [optional] 
**SequenceNumber** | Pointer to **int64** | The sequence number for this alarm in the device if alarm is a device alarm. | [optional] 
**Time** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewAlarmsAlarmHistory

`func NewAlarmsAlarmHistory() *AlarmsAlarmHistory`

NewAlarmsAlarmHistory instantiates a new AlarmsAlarmHistory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlarmsAlarmHistoryWithDefaults

`func NewAlarmsAlarmHistoryWithDefaults() *AlarmsAlarmHistory`

NewAlarmsAlarmHistoryWithDefaults instantiates a new AlarmsAlarmHistory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBootId

`func (o *AlarmsAlarmHistory) GetBootId() string`

GetBootId returns the BootId field if non-nil, zero value otherwise.

### GetBootIdOk

`func (o *AlarmsAlarmHistory) GetBootIdOk() (*string, bool)`

GetBootIdOk returns a tuple with the BootId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootId

`func (o *AlarmsAlarmHistory) SetBootId(v string)`

SetBootId sets BootId field to given value.

### HasBootId

`func (o *AlarmsAlarmHistory) HasBootId() bool`

HasBootId returns a boolean if a field has been set.

### GetDescription

`func (o *AlarmsAlarmHistory) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AlarmsAlarmHistory) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AlarmsAlarmHistory) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AlarmsAlarmHistory) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsCleared

`func (o *AlarmsAlarmHistory) GetIsCleared() bool`

GetIsCleared returns the IsCleared field if non-nil, zero value otherwise.

### GetIsClearedOk

`func (o *AlarmsAlarmHistory) GetIsClearedOk() (*bool, bool)`

GetIsClearedOk returns a tuple with the IsCleared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCleared

`func (o *AlarmsAlarmHistory) SetIsCleared(v bool)`

SetIsCleared sets IsCleared field to given value.

### HasIsCleared

`func (o *AlarmsAlarmHistory) HasIsCleared() bool`

HasIsCleared returns a boolean if a field has been set.

### GetPerceivedSeverity

`func (o *AlarmsAlarmHistory) GetPerceivedSeverity() string`

GetPerceivedSeverity returns the PerceivedSeverity field if non-nil, zero value otherwise.

### GetPerceivedSeverityOk

`func (o *AlarmsAlarmHistory) GetPerceivedSeverityOk() (*string, bool)`

GetPerceivedSeverityOk returns a tuple with the PerceivedSeverity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerceivedSeverity

`func (o *AlarmsAlarmHistory) SetPerceivedSeverity(v string)`

SetPerceivedSeverity sets PerceivedSeverity field to given value.

### HasPerceivedSeverity

`func (o *AlarmsAlarmHistory) HasPerceivedSeverity() bool`

HasPerceivedSeverity returns a boolean if a field has been set.

### GetSequenceNumber

`func (o *AlarmsAlarmHistory) GetSequenceNumber() int64`

GetSequenceNumber returns the SequenceNumber field if non-nil, zero value otherwise.

### GetSequenceNumberOk

`func (o *AlarmsAlarmHistory) GetSequenceNumberOk() (*int64, bool)`

GetSequenceNumberOk returns a tuple with the SequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequenceNumber

`func (o *AlarmsAlarmHistory) SetSequenceNumber(v int64)`

SetSequenceNumber sets SequenceNumber field to given value.

### HasSequenceNumber

`func (o *AlarmsAlarmHistory) HasSequenceNumber() bool`

HasSequenceNumber returns a boolean if a field has been set.

### GetTime

`func (o *AlarmsAlarmHistory) GetTime() GoogleProtobufTimestamp`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *AlarmsAlarmHistory) GetTimeOk() (*GoogleProtobufTimestamp, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *AlarmsAlarmHistory) SetTime(v GoogleProtobufTimestamp)`

SetTime sets Time field to given value.

### HasTime

`func (o *AlarmsAlarmHistory) HasTime() bool`

HasTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



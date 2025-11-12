# AlertserviceRuleRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlarmClear** | Pointer to **string** | Condition for triggering recovery | [optional] 
**AlarmSet** | Pointer to **string** | Condition for triggering alert (required) | [optional] 
**AllowCount** | Pointer to **int64** | Number of entities  allowed/excluded (required) | [optional] 
**Category** | Pointer to **string** | Category of the rule (required) | [optional] 
**Enabled** | Pointer to **bool** | Whether the rule is enabled or disabled (required) | [optional] 
**Plane** | Pointer to **string** | Plane of the rule (required) | [optional] 
**Priority** | Pointer to **string** | Priority of taking action against the rule (required) | [optional] 
**RuleId** | Pointer to **string** | Unique id of the rule (required) | [optional] 
**RuleName** | Pointer to **string** | Name of the rule (required) | [optional] 

## Methods

### NewAlertserviceRuleRecord

`func NewAlertserviceRuleRecord() *AlertserviceRuleRecord`

NewAlertserviceRuleRecord instantiates a new AlertserviceRuleRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertserviceRuleRecordWithDefaults

`func NewAlertserviceRuleRecordWithDefaults() *AlertserviceRuleRecord`

NewAlertserviceRuleRecordWithDefaults instantiates a new AlertserviceRuleRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlarmClear

`func (o *AlertserviceRuleRecord) GetAlarmClear() string`

GetAlarmClear returns the AlarmClear field if non-nil, zero value otherwise.

### GetAlarmClearOk

`func (o *AlertserviceRuleRecord) GetAlarmClearOk() (*string, bool)`

GetAlarmClearOk returns a tuple with the AlarmClear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmClear

`func (o *AlertserviceRuleRecord) SetAlarmClear(v string)`

SetAlarmClear sets AlarmClear field to given value.

### HasAlarmClear

`func (o *AlertserviceRuleRecord) HasAlarmClear() bool`

HasAlarmClear returns a boolean if a field has been set.

### GetAlarmSet

`func (o *AlertserviceRuleRecord) GetAlarmSet() string`

GetAlarmSet returns the AlarmSet field if non-nil, zero value otherwise.

### GetAlarmSetOk

`func (o *AlertserviceRuleRecord) GetAlarmSetOk() (*string, bool)`

GetAlarmSetOk returns a tuple with the AlarmSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmSet

`func (o *AlertserviceRuleRecord) SetAlarmSet(v string)`

SetAlarmSet sets AlarmSet field to given value.

### HasAlarmSet

`func (o *AlertserviceRuleRecord) HasAlarmSet() bool`

HasAlarmSet returns a boolean if a field has been set.

### GetAllowCount

`func (o *AlertserviceRuleRecord) GetAllowCount() int64`

GetAllowCount returns the AllowCount field if non-nil, zero value otherwise.

### GetAllowCountOk

`func (o *AlertserviceRuleRecord) GetAllowCountOk() (*int64, bool)`

GetAllowCountOk returns a tuple with the AllowCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowCount

`func (o *AlertserviceRuleRecord) SetAllowCount(v int64)`

SetAllowCount sets AllowCount field to given value.

### HasAllowCount

`func (o *AlertserviceRuleRecord) HasAllowCount() bool`

HasAllowCount returns a boolean if a field has been set.

### GetCategory

`func (o *AlertserviceRuleRecord) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AlertserviceRuleRecord) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AlertserviceRuleRecord) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *AlertserviceRuleRecord) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetEnabled

`func (o *AlertserviceRuleRecord) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AlertserviceRuleRecord) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AlertserviceRuleRecord) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *AlertserviceRuleRecord) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPlane

`func (o *AlertserviceRuleRecord) GetPlane() string`

GetPlane returns the Plane field if non-nil, zero value otherwise.

### GetPlaneOk

`func (o *AlertserviceRuleRecord) GetPlaneOk() (*string, bool)`

GetPlaneOk returns a tuple with the Plane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlane

`func (o *AlertserviceRuleRecord) SetPlane(v string)`

SetPlane sets Plane field to given value.

### HasPlane

`func (o *AlertserviceRuleRecord) HasPlane() bool`

HasPlane returns a boolean if a field has been set.

### GetPriority

`func (o *AlertserviceRuleRecord) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *AlertserviceRuleRecord) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *AlertserviceRuleRecord) SetPriority(v string)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *AlertserviceRuleRecord) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetRuleId

`func (o *AlertserviceRuleRecord) GetRuleId() string`

GetRuleId returns the RuleId field if non-nil, zero value otherwise.

### GetRuleIdOk

`func (o *AlertserviceRuleRecord) GetRuleIdOk() (*string, bool)`

GetRuleIdOk returns a tuple with the RuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleId

`func (o *AlertserviceRuleRecord) SetRuleId(v string)`

SetRuleId sets RuleId field to given value.

### HasRuleId

`func (o *AlertserviceRuleRecord) HasRuleId() bool`

HasRuleId returns a boolean if a field has been set.

### GetRuleName

`func (o *AlertserviceRuleRecord) GetRuleName() string`

GetRuleName returns the RuleName field if non-nil, zero value otherwise.

### GetRuleNameOk

`func (o *AlertserviceRuleRecord) GetRuleNameOk() (*string, bool)`

GetRuleNameOk returns a tuple with the RuleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleName

`func (o *AlertserviceRuleRecord) SetRuleName(v string)`

SetRuleName sets RuleName field to given value.

### HasRuleName

`func (o *AlertserviceRuleRecord) HasRuleName() bool`

HasRuleName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



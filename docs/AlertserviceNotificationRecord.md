# AlertserviceNotificationRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlertType** | Pointer to **string** | Type of the alert underlying the notification (required) | [optional] 
**MuteCount** | Pointer to **int64** | Number of entities notificated muted (required) | [optional] 
**Name** | Pointer to **string** | Name given to the notification record (required) | [optional] 
**NotificationBody** | Pointer to [**AlertserviceNotificationBody**](AlertserviceNotificationBody.md) |  | [optional] 
**NotificationId** | Pointer to **string** | Unique id for the notification record (required) | [optional] 
**RuleId** | Pointer to **string** | The id of the rule on which notification is created (required) | [optional] 
**TimesTriggered** | Pointer to **int64** | Number of times notification was triggered for the same alert (required) | [optional] 

## Methods

### NewAlertserviceNotificationRecord

`func NewAlertserviceNotificationRecord() *AlertserviceNotificationRecord`

NewAlertserviceNotificationRecord instantiates a new AlertserviceNotificationRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertserviceNotificationRecordWithDefaults

`func NewAlertserviceNotificationRecordWithDefaults() *AlertserviceNotificationRecord`

NewAlertserviceNotificationRecordWithDefaults instantiates a new AlertserviceNotificationRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlertType

`func (o *AlertserviceNotificationRecord) GetAlertType() string`

GetAlertType returns the AlertType field if non-nil, zero value otherwise.

### GetAlertTypeOk

`func (o *AlertserviceNotificationRecord) GetAlertTypeOk() (*string, bool)`

GetAlertTypeOk returns a tuple with the AlertType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertType

`func (o *AlertserviceNotificationRecord) SetAlertType(v string)`

SetAlertType sets AlertType field to given value.

### HasAlertType

`func (o *AlertserviceNotificationRecord) HasAlertType() bool`

HasAlertType returns a boolean if a field has been set.

### GetMuteCount

`func (o *AlertserviceNotificationRecord) GetMuteCount() int64`

GetMuteCount returns the MuteCount field if non-nil, zero value otherwise.

### GetMuteCountOk

`func (o *AlertserviceNotificationRecord) GetMuteCountOk() (*int64, bool)`

GetMuteCountOk returns a tuple with the MuteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMuteCount

`func (o *AlertserviceNotificationRecord) SetMuteCount(v int64)`

SetMuteCount sets MuteCount field to given value.

### HasMuteCount

`func (o *AlertserviceNotificationRecord) HasMuteCount() bool`

HasMuteCount returns a boolean if a field has been set.

### GetName

`func (o *AlertserviceNotificationRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AlertserviceNotificationRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AlertserviceNotificationRecord) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AlertserviceNotificationRecord) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotificationBody

`func (o *AlertserviceNotificationRecord) GetNotificationBody() AlertserviceNotificationBody`

GetNotificationBody returns the NotificationBody field if non-nil, zero value otherwise.

### GetNotificationBodyOk

`func (o *AlertserviceNotificationRecord) GetNotificationBodyOk() (*AlertserviceNotificationBody, bool)`

GetNotificationBodyOk returns a tuple with the NotificationBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationBody

`func (o *AlertserviceNotificationRecord) SetNotificationBody(v AlertserviceNotificationBody)`

SetNotificationBody sets NotificationBody field to given value.

### HasNotificationBody

`func (o *AlertserviceNotificationRecord) HasNotificationBody() bool`

HasNotificationBody returns a boolean if a field has been set.

### GetNotificationId

`func (o *AlertserviceNotificationRecord) GetNotificationId() string`

GetNotificationId returns the NotificationId field if non-nil, zero value otherwise.

### GetNotificationIdOk

`func (o *AlertserviceNotificationRecord) GetNotificationIdOk() (*string, bool)`

GetNotificationIdOk returns a tuple with the NotificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationId

`func (o *AlertserviceNotificationRecord) SetNotificationId(v string)`

SetNotificationId sets NotificationId field to given value.

### HasNotificationId

`func (o *AlertserviceNotificationRecord) HasNotificationId() bool`

HasNotificationId returns a boolean if a field has been set.

### GetRuleId

`func (o *AlertserviceNotificationRecord) GetRuleId() string`

GetRuleId returns the RuleId field if non-nil, zero value otherwise.

### GetRuleIdOk

`func (o *AlertserviceNotificationRecord) GetRuleIdOk() (*string, bool)`

GetRuleIdOk returns a tuple with the RuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleId

`func (o *AlertserviceNotificationRecord) SetRuleId(v string)`

SetRuleId sets RuleId field to given value.

### HasRuleId

`func (o *AlertserviceNotificationRecord) HasRuleId() bool`

HasRuleId returns a boolean if a field has been set.

### GetTimesTriggered

`func (o *AlertserviceNotificationRecord) GetTimesTriggered() int64`

GetTimesTriggered returns the TimesTriggered field if non-nil, zero value otherwise.

### GetTimesTriggeredOk

`func (o *AlertserviceNotificationRecord) GetTimesTriggeredOk() (*int64, bool)`

GetTimesTriggeredOk returns a tuple with the TimesTriggered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimesTriggered

`func (o *AlertserviceNotificationRecord) SetTimesTriggered(v int64)`

SetTimesTriggered sets TimesTriggered field to given value.

### HasTimesTriggered

`func (o *AlertserviceNotificationRecord) HasTimesTriggered() bool`

HasTimesTriggered returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



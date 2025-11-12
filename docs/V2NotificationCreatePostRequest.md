# V2NotificationCreatePostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotificationBody** | [**AlertserviceNotificationBody**](AlertserviceNotificationBody.md) |  | 
**RuleIdList** | **[]string** |  | 

## Methods

### NewV2NotificationCreatePostRequest

`func NewV2NotificationCreatePostRequest(notificationBody AlertserviceNotificationBody, ruleIdList []string, ) *V2NotificationCreatePostRequest`

NewV2NotificationCreatePostRequest instantiates a new V2NotificationCreatePostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2NotificationCreatePostRequestWithDefaults

`func NewV2NotificationCreatePostRequestWithDefaults() *V2NotificationCreatePostRequest`

NewV2NotificationCreatePostRequestWithDefaults instantiates a new V2NotificationCreatePostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotificationBody

`func (o *V2NotificationCreatePostRequest) GetNotificationBody() AlertserviceNotificationBody`

GetNotificationBody returns the NotificationBody field if non-nil, zero value otherwise.

### GetNotificationBodyOk

`func (o *V2NotificationCreatePostRequest) GetNotificationBodyOk() (*AlertserviceNotificationBody, bool)`

GetNotificationBodyOk returns a tuple with the NotificationBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationBody

`func (o *V2NotificationCreatePostRequest) SetNotificationBody(v AlertserviceNotificationBody)`

SetNotificationBody sets NotificationBody field to given value.


### GetRuleIdList

`func (o *V2NotificationCreatePostRequest) GetRuleIdList() []string`

GetRuleIdList returns the RuleIdList field if non-nil, zero value otherwise.

### GetRuleIdListOk

`func (o *V2NotificationCreatePostRequest) GetRuleIdListOk() (*[]string, bool)`

GetRuleIdListOk returns a tuple with the RuleIdList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleIdList

`func (o *V2NotificationCreatePostRequest) SetRuleIdList(v []string)`

SetRuleIdList sets RuleIdList field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



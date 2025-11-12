# V2AssistantGetConversationsPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConversationList** | Pointer to [**[]AssistantAssistantConversation**](AssistantAssistantConversation.md) |  | [optional] 
**EnableContextHistory** | Pointer to **bool** |  | [optional] 

## Methods

### NewV2AssistantGetConversationsPostResponse

`func NewV2AssistantGetConversationsPostResponse() *V2AssistantGetConversationsPostResponse`

NewV2AssistantGetConversationsPostResponse instantiates a new V2AssistantGetConversationsPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssistantGetConversationsPostResponseWithDefaults

`func NewV2AssistantGetConversationsPostResponseWithDefaults() *V2AssistantGetConversationsPostResponse`

NewV2AssistantGetConversationsPostResponseWithDefaults instantiates a new V2AssistantGetConversationsPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConversationList

`func (o *V2AssistantGetConversationsPostResponse) GetConversationList() []AssistantAssistantConversation`

GetConversationList returns the ConversationList field if non-nil, zero value otherwise.

### GetConversationListOk

`func (o *V2AssistantGetConversationsPostResponse) GetConversationListOk() (*[]AssistantAssistantConversation, bool)`

GetConversationListOk returns a tuple with the ConversationList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationList

`func (o *V2AssistantGetConversationsPostResponse) SetConversationList(v []AssistantAssistantConversation)`

SetConversationList sets ConversationList field to given value.

### HasConversationList

`func (o *V2AssistantGetConversationsPostResponse) HasConversationList() bool`

HasConversationList returns a boolean if a field has been set.

### GetEnableContextHistory

`func (o *V2AssistantGetConversationsPostResponse) GetEnableContextHistory() bool`

GetEnableContextHistory returns the EnableContextHistory field if non-nil, zero value otherwise.

### GetEnableContextHistoryOk

`func (o *V2AssistantGetConversationsPostResponse) GetEnableContextHistoryOk() (*bool, bool)`

GetEnableContextHistoryOk returns a tuple with the EnableContextHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableContextHistory

`func (o *V2AssistantGetConversationsPostResponse) SetEnableContextHistory(v bool)`

SetEnableContextHistory sets EnableContextHistory field to given value.

### HasEnableContextHistory

`func (o *V2AssistantGetConversationsPostResponse) HasEnableContextHistory() bool`

HasEnableContextHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



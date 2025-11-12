# V2AssistantAddToConversationPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConversationId** | Pointer to **string** |  | [optional] 
**DataframeDictionary** | Pointer to [**[]AssistantDataframeDictionary**](AssistantDataframeDictionary.md) |  | [optional] 
**OriginalQuestion** | Pointer to [**AssistantAssistantQuestion**](AssistantAssistantQuestion.md) |  | [optional] 
**ResponseId** | Pointer to **string** |  | [optional] 
**ResponseLanguage** | Pointer to **string** |  | [optional] 
**ResponseText** | Pointer to **string** |  | [optional] 
**ResponseTimestamp** | Pointer to **int64** |  | [optional] 
**ResponseType** | Pointer to **string** |  | [optional] 
**VisualizationSummary** | Pointer to **string** |  | [optional] 

## Methods

### NewV2AssistantAddToConversationPostResponse

`func NewV2AssistantAddToConversationPostResponse() *V2AssistantAddToConversationPostResponse`

NewV2AssistantAddToConversationPostResponse instantiates a new V2AssistantAddToConversationPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssistantAddToConversationPostResponseWithDefaults

`func NewV2AssistantAddToConversationPostResponseWithDefaults() *V2AssistantAddToConversationPostResponse`

NewV2AssistantAddToConversationPostResponseWithDefaults instantiates a new V2AssistantAddToConversationPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConversationId

`func (o *V2AssistantAddToConversationPostResponse) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *V2AssistantAddToConversationPostResponse) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *V2AssistantAddToConversationPostResponse) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *V2AssistantAddToConversationPostResponse) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### GetDataframeDictionary

`func (o *V2AssistantAddToConversationPostResponse) GetDataframeDictionary() []AssistantDataframeDictionary`

GetDataframeDictionary returns the DataframeDictionary field if non-nil, zero value otherwise.

### GetDataframeDictionaryOk

`func (o *V2AssistantAddToConversationPostResponse) GetDataframeDictionaryOk() (*[]AssistantDataframeDictionary, bool)`

GetDataframeDictionaryOk returns a tuple with the DataframeDictionary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataframeDictionary

`func (o *V2AssistantAddToConversationPostResponse) SetDataframeDictionary(v []AssistantDataframeDictionary)`

SetDataframeDictionary sets DataframeDictionary field to given value.

### HasDataframeDictionary

`func (o *V2AssistantAddToConversationPostResponse) HasDataframeDictionary() bool`

HasDataframeDictionary returns a boolean if a field has been set.

### GetOriginalQuestion

`func (o *V2AssistantAddToConversationPostResponse) GetOriginalQuestion() AssistantAssistantQuestion`

GetOriginalQuestion returns the OriginalQuestion field if non-nil, zero value otherwise.

### GetOriginalQuestionOk

`func (o *V2AssistantAddToConversationPostResponse) GetOriginalQuestionOk() (*AssistantAssistantQuestion, bool)`

GetOriginalQuestionOk returns a tuple with the OriginalQuestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalQuestion

`func (o *V2AssistantAddToConversationPostResponse) SetOriginalQuestion(v AssistantAssistantQuestion)`

SetOriginalQuestion sets OriginalQuestion field to given value.

### HasOriginalQuestion

`func (o *V2AssistantAddToConversationPostResponse) HasOriginalQuestion() bool`

HasOriginalQuestion returns a boolean if a field has been set.

### GetResponseId

`func (o *V2AssistantAddToConversationPostResponse) GetResponseId() string`

GetResponseId returns the ResponseId field if non-nil, zero value otherwise.

### GetResponseIdOk

`func (o *V2AssistantAddToConversationPostResponse) GetResponseIdOk() (*string, bool)`

GetResponseIdOk returns a tuple with the ResponseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseId

`func (o *V2AssistantAddToConversationPostResponse) SetResponseId(v string)`

SetResponseId sets ResponseId field to given value.

### HasResponseId

`func (o *V2AssistantAddToConversationPostResponse) HasResponseId() bool`

HasResponseId returns a boolean if a field has been set.

### GetResponseLanguage

`func (o *V2AssistantAddToConversationPostResponse) GetResponseLanguage() string`

GetResponseLanguage returns the ResponseLanguage field if non-nil, zero value otherwise.

### GetResponseLanguageOk

`func (o *V2AssistantAddToConversationPostResponse) GetResponseLanguageOk() (*string, bool)`

GetResponseLanguageOk returns a tuple with the ResponseLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseLanguage

`func (o *V2AssistantAddToConversationPostResponse) SetResponseLanguage(v string)`

SetResponseLanguage sets ResponseLanguage field to given value.

### HasResponseLanguage

`func (o *V2AssistantAddToConversationPostResponse) HasResponseLanguage() bool`

HasResponseLanguage returns a boolean if a field has been set.

### GetResponseText

`func (o *V2AssistantAddToConversationPostResponse) GetResponseText() string`

GetResponseText returns the ResponseText field if non-nil, zero value otherwise.

### GetResponseTextOk

`func (o *V2AssistantAddToConversationPostResponse) GetResponseTextOk() (*string, bool)`

GetResponseTextOk returns a tuple with the ResponseText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseText

`func (o *V2AssistantAddToConversationPostResponse) SetResponseText(v string)`

SetResponseText sets ResponseText field to given value.

### HasResponseText

`func (o *V2AssistantAddToConversationPostResponse) HasResponseText() bool`

HasResponseText returns a boolean if a field has been set.

### GetResponseTimestamp

`func (o *V2AssistantAddToConversationPostResponse) GetResponseTimestamp() int64`

GetResponseTimestamp returns the ResponseTimestamp field if non-nil, zero value otherwise.

### GetResponseTimestampOk

`func (o *V2AssistantAddToConversationPostResponse) GetResponseTimestampOk() (*int64, bool)`

GetResponseTimestampOk returns a tuple with the ResponseTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTimestamp

`func (o *V2AssistantAddToConversationPostResponse) SetResponseTimestamp(v int64)`

SetResponseTimestamp sets ResponseTimestamp field to given value.

### HasResponseTimestamp

`func (o *V2AssistantAddToConversationPostResponse) HasResponseTimestamp() bool`

HasResponseTimestamp returns a boolean if a field has been set.

### GetResponseType

`func (o *V2AssistantAddToConversationPostResponse) GetResponseType() string`

GetResponseType returns the ResponseType field if non-nil, zero value otherwise.

### GetResponseTypeOk

`func (o *V2AssistantAddToConversationPostResponse) GetResponseTypeOk() (*string, bool)`

GetResponseTypeOk returns a tuple with the ResponseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseType

`func (o *V2AssistantAddToConversationPostResponse) SetResponseType(v string)`

SetResponseType sets ResponseType field to given value.

### HasResponseType

`func (o *V2AssistantAddToConversationPostResponse) HasResponseType() bool`

HasResponseType returns a boolean if a field has been set.

### GetVisualizationSummary

`func (o *V2AssistantAddToConversationPostResponse) GetVisualizationSummary() string`

GetVisualizationSummary returns the VisualizationSummary field if non-nil, zero value otherwise.

### GetVisualizationSummaryOk

`func (o *V2AssistantAddToConversationPostResponse) GetVisualizationSummaryOk() (*string, bool)`

GetVisualizationSummaryOk returns a tuple with the VisualizationSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisualizationSummary

`func (o *V2AssistantAddToConversationPostResponse) SetVisualizationSummary(v string)`

SetVisualizationSummary sets VisualizationSummary field to given value.

### HasVisualizationSummary

`func (o *V2AssistantAddToConversationPostResponse) HasVisualizationSummary() bool`

HasVisualizationSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



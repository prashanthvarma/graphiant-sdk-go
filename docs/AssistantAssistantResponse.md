# AssistantAssistantResponse

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

### NewAssistantAssistantResponse

`func NewAssistantAssistantResponse() *AssistantAssistantResponse`

NewAssistantAssistantResponse instantiates a new AssistantAssistantResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssistantAssistantResponseWithDefaults

`func NewAssistantAssistantResponseWithDefaults() *AssistantAssistantResponse`

NewAssistantAssistantResponseWithDefaults instantiates a new AssistantAssistantResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConversationId

`func (o *AssistantAssistantResponse) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *AssistantAssistantResponse) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *AssistantAssistantResponse) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *AssistantAssistantResponse) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### GetDataframeDictionary

`func (o *AssistantAssistantResponse) GetDataframeDictionary() []AssistantDataframeDictionary`

GetDataframeDictionary returns the DataframeDictionary field if non-nil, zero value otherwise.

### GetDataframeDictionaryOk

`func (o *AssistantAssistantResponse) GetDataframeDictionaryOk() (*[]AssistantDataframeDictionary, bool)`

GetDataframeDictionaryOk returns a tuple with the DataframeDictionary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataframeDictionary

`func (o *AssistantAssistantResponse) SetDataframeDictionary(v []AssistantDataframeDictionary)`

SetDataframeDictionary sets DataframeDictionary field to given value.

### HasDataframeDictionary

`func (o *AssistantAssistantResponse) HasDataframeDictionary() bool`

HasDataframeDictionary returns a boolean if a field has been set.

### GetOriginalQuestion

`func (o *AssistantAssistantResponse) GetOriginalQuestion() AssistantAssistantQuestion`

GetOriginalQuestion returns the OriginalQuestion field if non-nil, zero value otherwise.

### GetOriginalQuestionOk

`func (o *AssistantAssistantResponse) GetOriginalQuestionOk() (*AssistantAssistantQuestion, bool)`

GetOriginalQuestionOk returns a tuple with the OriginalQuestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalQuestion

`func (o *AssistantAssistantResponse) SetOriginalQuestion(v AssistantAssistantQuestion)`

SetOriginalQuestion sets OriginalQuestion field to given value.

### HasOriginalQuestion

`func (o *AssistantAssistantResponse) HasOriginalQuestion() bool`

HasOriginalQuestion returns a boolean if a field has been set.

### GetResponseId

`func (o *AssistantAssistantResponse) GetResponseId() string`

GetResponseId returns the ResponseId field if non-nil, zero value otherwise.

### GetResponseIdOk

`func (o *AssistantAssistantResponse) GetResponseIdOk() (*string, bool)`

GetResponseIdOk returns a tuple with the ResponseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseId

`func (o *AssistantAssistantResponse) SetResponseId(v string)`

SetResponseId sets ResponseId field to given value.

### HasResponseId

`func (o *AssistantAssistantResponse) HasResponseId() bool`

HasResponseId returns a boolean if a field has been set.

### GetResponseLanguage

`func (o *AssistantAssistantResponse) GetResponseLanguage() string`

GetResponseLanguage returns the ResponseLanguage field if non-nil, zero value otherwise.

### GetResponseLanguageOk

`func (o *AssistantAssistantResponse) GetResponseLanguageOk() (*string, bool)`

GetResponseLanguageOk returns a tuple with the ResponseLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseLanguage

`func (o *AssistantAssistantResponse) SetResponseLanguage(v string)`

SetResponseLanguage sets ResponseLanguage field to given value.

### HasResponseLanguage

`func (o *AssistantAssistantResponse) HasResponseLanguage() bool`

HasResponseLanguage returns a boolean if a field has been set.

### GetResponseText

`func (o *AssistantAssistantResponse) GetResponseText() string`

GetResponseText returns the ResponseText field if non-nil, zero value otherwise.

### GetResponseTextOk

`func (o *AssistantAssistantResponse) GetResponseTextOk() (*string, bool)`

GetResponseTextOk returns a tuple with the ResponseText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseText

`func (o *AssistantAssistantResponse) SetResponseText(v string)`

SetResponseText sets ResponseText field to given value.

### HasResponseText

`func (o *AssistantAssistantResponse) HasResponseText() bool`

HasResponseText returns a boolean if a field has been set.

### GetResponseTimestamp

`func (o *AssistantAssistantResponse) GetResponseTimestamp() int64`

GetResponseTimestamp returns the ResponseTimestamp field if non-nil, zero value otherwise.

### GetResponseTimestampOk

`func (o *AssistantAssistantResponse) GetResponseTimestampOk() (*int64, bool)`

GetResponseTimestampOk returns a tuple with the ResponseTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTimestamp

`func (o *AssistantAssistantResponse) SetResponseTimestamp(v int64)`

SetResponseTimestamp sets ResponseTimestamp field to given value.

### HasResponseTimestamp

`func (o *AssistantAssistantResponse) HasResponseTimestamp() bool`

HasResponseTimestamp returns a boolean if a field has been set.

### GetResponseType

`func (o *AssistantAssistantResponse) GetResponseType() string`

GetResponseType returns the ResponseType field if non-nil, zero value otherwise.

### GetResponseTypeOk

`func (o *AssistantAssistantResponse) GetResponseTypeOk() (*string, bool)`

GetResponseTypeOk returns a tuple with the ResponseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseType

`func (o *AssistantAssistantResponse) SetResponseType(v string)`

SetResponseType sets ResponseType field to given value.

### HasResponseType

`func (o *AssistantAssistantResponse) HasResponseType() bool`

HasResponseType returns a boolean if a field has been set.

### GetVisualizationSummary

`func (o *AssistantAssistantResponse) GetVisualizationSummary() string`

GetVisualizationSummary returns the VisualizationSummary field if non-nil, zero value otherwise.

### GetVisualizationSummaryOk

`func (o *AssistantAssistantResponse) GetVisualizationSummaryOk() (*string, bool)`

GetVisualizationSummaryOk returns a tuple with the VisualizationSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisualizationSummary

`func (o *AssistantAssistantResponse) SetVisualizationSummary(v string)`

SetVisualizationSummary sets VisualizationSummary field to given value.

### HasVisualizationSummary

`func (o *AssistantAssistantResponse) HasVisualizationSummary() bool`

HasVisualizationSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



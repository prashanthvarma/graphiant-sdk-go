# V2NotificationmutelistCreatePostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlertId** | **string** | Alert id of the alert to create allowlist/mutelist for (required) | 
**NoteText** | Pointer to **string** | Optional note | [optional] 

## Methods

### NewV2NotificationmutelistCreatePostRequest

`func NewV2NotificationmutelistCreatePostRequest(alertId string, ) *V2NotificationmutelistCreatePostRequest`

NewV2NotificationmutelistCreatePostRequest instantiates a new V2NotificationmutelistCreatePostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2NotificationmutelistCreatePostRequestWithDefaults

`func NewV2NotificationmutelistCreatePostRequestWithDefaults() *V2NotificationmutelistCreatePostRequest`

NewV2NotificationmutelistCreatePostRequestWithDefaults instantiates a new V2NotificationmutelistCreatePostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlertId

`func (o *V2NotificationmutelistCreatePostRequest) GetAlertId() string`

GetAlertId returns the AlertId field if non-nil, zero value otherwise.

### GetAlertIdOk

`func (o *V2NotificationmutelistCreatePostRequest) GetAlertIdOk() (*string, bool)`

GetAlertIdOk returns a tuple with the AlertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertId

`func (o *V2NotificationmutelistCreatePostRequest) SetAlertId(v string)`

SetAlertId sets AlertId field to given value.


### GetNoteText

`func (o *V2NotificationmutelistCreatePostRequest) GetNoteText() string`

GetNoteText returns the NoteText field if non-nil, zero value otherwise.

### GetNoteTextOk

`func (o *V2NotificationmutelistCreatePostRequest) GetNoteTextOk() (*string, bool)`

GetNoteTextOk returns a tuple with the NoteText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoteText

`func (o *V2NotificationmutelistCreatePostRequest) SetNoteText(v string)`

SetNoteText sets NoteText field to given value.

### HasNoteText

`func (o *V2NotificationmutelistCreatePostRequest) HasNoteText() bool`

HasNoteText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



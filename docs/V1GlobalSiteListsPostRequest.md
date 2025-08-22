# V1GlobalSiteListsPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Entries** | Pointer to [**[]V1GlobalSiteListsPostRequestEntriesInner**](V1GlobalSiteListsPostRequestEntriesInner.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewV1GlobalSiteListsPostRequest

`func NewV1GlobalSiteListsPostRequest() *V1GlobalSiteListsPostRequest`

NewV1GlobalSiteListsPostRequest instantiates a new V1GlobalSiteListsPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GlobalSiteListsPostRequestWithDefaults

`func NewV1GlobalSiteListsPostRequestWithDefaults() *V1GlobalSiteListsPostRequest`

NewV1GlobalSiteListsPostRequestWithDefaults instantiates a new V1GlobalSiteListsPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *V1GlobalSiteListsPostRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *V1GlobalSiteListsPostRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *V1GlobalSiteListsPostRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *V1GlobalSiteListsPostRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEntries

`func (o *V1GlobalSiteListsPostRequest) GetEntries() []V1GlobalSiteListsPostRequestEntriesInner`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *V1GlobalSiteListsPostRequest) GetEntriesOk() (*[]V1GlobalSiteListsPostRequestEntriesInner, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *V1GlobalSiteListsPostRequest) SetEntries(v []V1GlobalSiteListsPostRequestEntriesInner)`

SetEntries sets Entries field to given value.

### HasEntries

`func (o *V1GlobalSiteListsPostRequest) HasEntries() bool`

HasEntries returns a boolean if a field has been set.

### GetName

`func (o *V1GlobalSiteListsPostRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *V1GlobalSiteListsPostRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *V1GlobalSiteListsPostRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *V1GlobalSiteListsPostRequest) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1GlobalSiteListsIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Entries** | Pointer to [**[]ManaV2SiteListEntry**](ManaV2SiteListEntry.md) |  | [optional] 

## Methods

### NewV1GlobalSiteListsIdGetResponse

`func NewV1GlobalSiteListsIdGetResponse() *V1GlobalSiteListsIdGetResponse`

NewV1GlobalSiteListsIdGetResponse instantiates a new V1GlobalSiteListsIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GlobalSiteListsIdGetResponseWithDefaults

`func NewV1GlobalSiteListsIdGetResponseWithDefaults() *V1GlobalSiteListsIdGetResponse`

NewV1GlobalSiteListsIdGetResponseWithDefaults instantiates a new V1GlobalSiteListsIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *V1GlobalSiteListsIdGetResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *V1GlobalSiteListsIdGetResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *V1GlobalSiteListsIdGetResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *V1GlobalSiteListsIdGetResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEntries

`func (o *V1GlobalSiteListsIdGetResponse) GetEntries() []ManaV2SiteListEntry`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *V1GlobalSiteListsIdGetResponse) GetEntriesOk() (*[]ManaV2SiteListEntry, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *V1GlobalSiteListsIdGetResponse) SetEntries(v []ManaV2SiteListEntry)`

SetEntries sets Entries field to given value.

### HasEntries

`func (o *V1GlobalSiteListsIdGetResponse) HasEntries() bool`

HasEntries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



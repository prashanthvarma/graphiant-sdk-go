# ManaV2SiteListEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Regular** | Pointer to **int64** |  | [optional] 
**Tag** | Pointer to [**ManaV2RouteTagId**](ManaV2RouteTagId.md) |  | [optional] 

## Methods

### NewManaV2SiteListEntry

`func NewManaV2SiteListEntry() *ManaV2SiteListEntry`

NewManaV2SiteListEntry instantiates a new ManaV2SiteListEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SiteListEntryWithDefaults

`func NewManaV2SiteListEntryWithDefaults() *ManaV2SiteListEntry`

NewManaV2SiteListEntryWithDefaults instantiates a new ManaV2SiteListEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegular

`func (o *ManaV2SiteListEntry) GetRegular() int64`

GetRegular returns the Regular field if non-nil, zero value otherwise.

### GetRegularOk

`func (o *ManaV2SiteListEntry) GetRegularOk() (*int64, bool)`

GetRegularOk returns a tuple with the Regular field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegular

`func (o *ManaV2SiteListEntry) SetRegular(v int64)`

SetRegular sets Regular field to given value.

### HasRegular

`func (o *ManaV2SiteListEntry) HasRegular() bool`

HasRegular returns a boolean if a field has been set.

### GetTag

`func (o *ManaV2SiteListEntry) GetTag() ManaV2RouteTagId`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *ManaV2SiteListEntry) GetTagOk() (*ManaV2RouteTagId, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *ManaV2SiteListEntry) SetTag(v ManaV2RouteTagId)`

SetTag sets Tag field to given value.

### HasTag

`func (o *ManaV2SiteListEntry) HasTag() bool`

HasTag returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



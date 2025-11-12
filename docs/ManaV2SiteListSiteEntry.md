# ManaV2SiteListSiteEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**EdgeReferences** | Pointer to **int32** |  | [optional] 
**SiteName** | Pointer to **string** |  | [optional] 
**Tag** | Pointer to [**[]ManaV2RouteTagId**](ManaV2RouteTagId.md) |  | [optional] 

## Methods

### NewManaV2SiteListSiteEntry

`func NewManaV2SiteListSiteEntry() *ManaV2SiteListSiteEntry`

NewManaV2SiteListSiteEntry instantiates a new ManaV2SiteListSiteEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SiteListSiteEntryWithDefaults

`func NewManaV2SiteListSiteEntryWithDefaults() *ManaV2SiteListSiteEntry`

NewManaV2SiteListSiteEntryWithDefaults instantiates a new ManaV2SiteListSiteEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *ManaV2SiteListSiteEntry) GetCreatedAt() GoogleProtobufTimestamp`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManaV2SiteListSiteEntry) GetCreatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManaV2SiteListSiteEntry) SetCreatedAt(v GoogleProtobufTimestamp)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ManaV2SiteListSiteEntry) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetEdgeReferences

`func (o *ManaV2SiteListSiteEntry) GetEdgeReferences() int32`

GetEdgeReferences returns the EdgeReferences field if non-nil, zero value otherwise.

### GetEdgeReferencesOk

`func (o *ManaV2SiteListSiteEntry) GetEdgeReferencesOk() (*int32, bool)`

GetEdgeReferencesOk returns a tuple with the EdgeReferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgeReferences

`func (o *ManaV2SiteListSiteEntry) SetEdgeReferences(v int32)`

SetEdgeReferences sets EdgeReferences field to given value.

### HasEdgeReferences

`func (o *ManaV2SiteListSiteEntry) HasEdgeReferences() bool`

HasEdgeReferences returns a boolean if a field has been set.

### GetSiteName

`func (o *ManaV2SiteListSiteEntry) GetSiteName() string`

GetSiteName returns the SiteName field if non-nil, zero value otherwise.

### GetSiteNameOk

`func (o *ManaV2SiteListSiteEntry) GetSiteNameOk() (*string, bool)`

GetSiteNameOk returns a tuple with the SiteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteName

`func (o *ManaV2SiteListSiteEntry) SetSiteName(v string)`

SetSiteName sets SiteName field to given value.

### HasSiteName

`func (o *ManaV2SiteListSiteEntry) HasSiteName() bool`

HasSiteName returns a boolean if a field has been set.

### GetTag

`func (o *ManaV2SiteListSiteEntry) GetTag() []ManaV2RouteTagId`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *ManaV2SiteListSiteEntry) GetTagOk() (*[]ManaV2RouteTagId, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *ManaV2SiteListSiteEntry) SetTag(v []ManaV2RouteTagId)`

SetTag sets Tag field to given value.

### HasTag

`func (o *ManaV2SiteListSiteEntry) HasTag() bool`

HasTag returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



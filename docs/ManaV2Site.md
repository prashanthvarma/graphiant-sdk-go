# ManaV2Site

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Devices** | Pointer to [**[]ManaV2SiteDeviceStub**](ManaV2SiteDeviceStub.md) |  | [optional] 
**EdgeCount** | Pointer to **int32** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Location** | Pointer to [**ManaV2Location**](ManaV2Location.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Notes** | Pointer to **string** |  | [optional] 
**PolicyReferenceCount** | Pointer to **int32** |  | [optional] 
**PolicyTag** | Pointer to [**ManaV2SingleRouteTag**](ManaV2SingleRouteTag.md) |  | [optional] 
**SegmentCount** | Pointer to **int32** |  | [optional] 
**SiteListReferenceCount** | Pointer to **int32** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**UpdatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewManaV2Site

`func NewManaV2Site() *ManaV2Site`

NewManaV2Site instantiates a new ManaV2Site object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SiteWithDefaults

`func NewManaV2SiteWithDefaults() *ManaV2Site`

NewManaV2SiteWithDefaults instantiates a new ManaV2Site object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ManaV2Site) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ManaV2Site) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ManaV2Site) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ManaV2Site) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ManaV2Site) GetCreatedAt() GoogleProtobufTimestamp`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManaV2Site) GetCreatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManaV2Site) SetCreatedAt(v GoogleProtobufTimestamp)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ManaV2Site) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDevices

`func (o *ManaV2Site) GetDevices() []ManaV2SiteDeviceStub`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *ManaV2Site) GetDevicesOk() (*[]ManaV2SiteDeviceStub, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *ManaV2Site) SetDevices(v []ManaV2SiteDeviceStub)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *ManaV2Site) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetEdgeCount

`func (o *ManaV2Site) GetEdgeCount() int32`

GetEdgeCount returns the EdgeCount field if non-nil, zero value otherwise.

### GetEdgeCountOk

`func (o *ManaV2Site) GetEdgeCountOk() (*int32, bool)`

GetEdgeCountOk returns a tuple with the EdgeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgeCount

`func (o *ManaV2Site) SetEdgeCount(v int32)`

SetEdgeCount sets EdgeCount field to given value.

### HasEdgeCount

`func (o *ManaV2Site) HasEdgeCount() bool`

HasEdgeCount returns a boolean if a field has been set.

### GetId

`func (o *ManaV2Site) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2Site) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2Site) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2Site) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLocation

`func (o *ManaV2Site) GetLocation() ManaV2Location`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ManaV2Site) GetLocationOk() (*ManaV2Location, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ManaV2Site) SetLocation(v ManaV2Location)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ManaV2Site) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetName

`func (o *ManaV2Site) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2Site) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2Site) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2Site) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotes

`func (o *ManaV2Site) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ManaV2Site) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ManaV2Site) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ManaV2Site) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetPolicyReferenceCount

`func (o *ManaV2Site) GetPolicyReferenceCount() int32`

GetPolicyReferenceCount returns the PolicyReferenceCount field if non-nil, zero value otherwise.

### GetPolicyReferenceCountOk

`func (o *ManaV2Site) GetPolicyReferenceCountOk() (*int32, bool)`

GetPolicyReferenceCountOk returns a tuple with the PolicyReferenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyReferenceCount

`func (o *ManaV2Site) SetPolicyReferenceCount(v int32)`

SetPolicyReferenceCount sets PolicyReferenceCount field to given value.

### HasPolicyReferenceCount

`func (o *ManaV2Site) HasPolicyReferenceCount() bool`

HasPolicyReferenceCount returns a boolean if a field has been set.

### GetPolicyTag

`func (o *ManaV2Site) GetPolicyTag() ManaV2SingleRouteTag`

GetPolicyTag returns the PolicyTag field if non-nil, zero value otherwise.

### GetPolicyTagOk

`func (o *ManaV2Site) GetPolicyTagOk() (*ManaV2SingleRouteTag, bool)`

GetPolicyTagOk returns a tuple with the PolicyTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyTag

`func (o *ManaV2Site) SetPolicyTag(v ManaV2SingleRouteTag)`

SetPolicyTag sets PolicyTag field to given value.

### HasPolicyTag

`func (o *ManaV2Site) HasPolicyTag() bool`

HasPolicyTag returns a boolean if a field has been set.

### GetSegmentCount

`func (o *ManaV2Site) GetSegmentCount() int32`

GetSegmentCount returns the SegmentCount field if non-nil, zero value otherwise.

### GetSegmentCountOk

`func (o *ManaV2Site) GetSegmentCountOk() (*int32, bool)`

GetSegmentCountOk returns a tuple with the SegmentCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentCount

`func (o *ManaV2Site) SetSegmentCount(v int32)`

SetSegmentCount sets SegmentCount field to given value.

### HasSegmentCount

`func (o *ManaV2Site) HasSegmentCount() bool`

HasSegmentCount returns a boolean if a field has been set.

### GetSiteListReferenceCount

`func (o *ManaV2Site) GetSiteListReferenceCount() int32`

GetSiteListReferenceCount returns the SiteListReferenceCount field if non-nil, zero value otherwise.

### GetSiteListReferenceCountOk

`func (o *ManaV2Site) GetSiteListReferenceCountOk() (*int32, bool)`

GetSiteListReferenceCountOk returns a tuple with the SiteListReferenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteListReferenceCount

`func (o *ManaV2Site) SetSiteListReferenceCount(v int32)`

SetSiteListReferenceCount sets SiteListReferenceCount field to given value.

### HasSiteListReferenceCount

`func (o *ManaV2Site) HasSiteListReferenceCount() bool`

HasSiteListReferenceCount returns a boolean if a field has been set.

### GetTags

`func (o *ManaV2Site) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ManaV2Site) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ManaV2Site) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ManaV2Site) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ManaV2Site) GetUpdatedAt() GoogleProtobufTimestamp`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ManaV2Site) GetUpdatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ManaV2Site) SetUpdatedAt(v GoogleProtobufTimestamp)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ManaV2Site) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



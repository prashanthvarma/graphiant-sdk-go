# ManaV2NetworkSlice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Peers** | Pointer to [**[]ManaV2NetworkSlicePeer**](ManaV2NetworkSlicePeer.md) |  | [optional] 
**SliceIndex** | Pointer to **int32** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 

## Methods

### NewManaV2NetworkSlice

`func NewManaV2NetworkSlice() *ManaV2NetworkSlice`

NewManaV2NetworkSlice instantiates a new ManaV2NetworkSlice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2NetworkSliceWithDefaults

`func NewManaV2NetworkSliceWithDefaults() *ManaV2NetworkSlice`

NewManaV2NetworkSliceWithDefaults instantiates a new ManaV2NetworkSlice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManaV2NetworkSlice) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2NetworkSlice) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2NetworkSlice) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2NetworkSlice) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPeers

`func (o *ManaV2NetworkSlice) GetPeers() []ManaV2NetworkSlicePeer`

GetPeers returns the Peers field if non-nil, zero value otherwise.

### GetPeersOk

`func (o *ManaV2NetworkSlice) GetPeersOk() (*[]ManaV2NetworkSlicePeer, bool)`

GetPeersOk returns a tuple with the Peers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeers

`func (o *ManaV2NetworkSlice) SetPeers(v []ManaV2NetworkSlicePeer)`

SetPeers sets Peers field to given value.

### HasPeers

`func (o *ManaV2NetworkSlice) HasPeers() bool`

HasPeers returns a boolean if a field has been set.

### GetSliceIndex

`func (o *ManaV2NetworkSlice) GetSliceIndex() int32`

GetSliceIndex returns the SliceIndex field if non-nil, zero value otherwise.

### GetSliceIndexOk

`func (o *ManaV2NetworkSlice) GetSliceIndexOk() (*int32, bool)`

GetSliceIndexOk returns a tuple with the SliceIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliceIndex

`func (o *ManaV2NetworkSlice) SetSliceIndex(v int32)`

SetSliceIndex sets SliceIndex field to given value.

### HasSliceIndex

`func (o *ManaV2NetworkSlice) HasSliceIndex() bool`

HasSliceIndex returns a boolean if a field has been set.

### GetTags

`func (o *ManaV2NetworkSlice) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ManaV2NetworkSlice) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ManaV2NetworkSlice) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ManaV2NetworkSlice) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



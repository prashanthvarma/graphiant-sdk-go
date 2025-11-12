# ManaV2SnmpVacmGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accesses** | Pointer to [**[]ManaV2SnmpVacmGroupAccess**](ManaV2SnmpVacmGroupAccess.md) |  | [optional] 
**GroupMembers** | Pointer to [**[]ManaV2SnmpVacmGroupMember**](ManaV2SnmpVacmGroupMember.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Views** | Pointer to [**[]ManaV2SnmpVacmView**](ManaV2SnmpVacmView.md) |  | [optional] 

## Methods

### NewManaV2SnmpVacmGroup

`func NewManaV2SnmpVacmGroup() *ManaV2SnmpVacmGroup`

NewManaV2SnmpVacmGroup instantiates a new ManaV2SnmpVacmGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpVacmGroupWithDefaults

`func NewManaV2SnmpVacmGroupWithDefaults() *ManaV2SnmpVacmGroup`

NewManaV2SnmpVacmGroupWithDefaults instantiates a new ManaV2SnmpVacmGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccesses

`func (o *ManaV2SnmpVacmGroup) GetAccesses() []ManaV2SnmpVacmGroupAccess`

GetAccesses returns the Accesses field if non-nil, zero value otherwise.

### GetAccessesOk

`func (o *ManaV2SnmpVacmGroup) GetAccessesOk() (*[]ManaV2SnmpVacmGroupAccess, bool)`

GetAccessesOk returns a tuple with the Accesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccesses

`func (o *ManaV2SnmpVacmGroup) SetAccesses(v []ManaV2SnmpVacmGroupAccess)`

SetAccesses sets Accesses field to given value.

### HasAccesses

`func (o *ManaV2SnmpVacmGroup) HasAccesses() bool`

HasAccesses returns a boolean if a field has been set.

### GetGroupMembers

`func (o *ManaV2SnmpVacmGroup) GetGroupMembers() []ManaV2SnmpVacmGroupMember`

GetGroupMembers returns the GroupMembers field if non-nil, zero value otherwise.

### GetGroupMembersOk

`func (o *ManaV2SnmpVacmGroup) GetGroupMembersOk() (*[]ManaV2SnmpVacmGroupMember, bool)`

GetGroupMembersOk returns a tuple with the GroupMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMembers

`func (o *ManaV2SnmpVacmGroup) SetGroupMembers(v []ManaV2SnmpVacmGroupMember)`

SetGroupMembers sets GroupMembers field to given value.

### HasGroupMembers

`func (o *ManaV2SnmpVacmGroup) HasGroupMembers() bool`

HasGroupMembers returns a boolean if a field has been set.

### GetId

`func (o *ManaV2SnmpVacmGroup) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2SnmpVacmGroup) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2SnmpVacmGroup) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2SnmpVacmGroup) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SnmpVacmGroup) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SnmpVacmGroup) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SnmpVacmGroup) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SnmpVacmGroup) HasName() bool`

HasName returns a boolean if a field has been set.

### GetViews

`func (o *ManaV2SnmpVacmGroup) GetViews() []ManaV2SnmpVacmView`

GetViews returns the Views field if non-nil, zero value otherwise.

### GetViewsOk

`func (o *ManaV2SnmpVacmGroup) GetViewsOk() (*[]ManaV2SnmpVacmView, bool)`

GetViewsOk returns a tuple with the Views field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViews

`func (o *ManaV2SnmpVacmGroup) SetViews(v []ManaV2SnmpVacmView)`

SetViews sets Views field to given value.

### HasViews

`func (o *ManaV2SnmpVacmGroup) HasViews() bool`

HasViews returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



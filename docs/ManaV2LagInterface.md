# ManaV2LagInterface

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** |  | [optional] 
**LacpConfig** | Pointer to [**ManaV2LacpConfig**](ManaV2LacpConfig.md) |  | [optional] 
**Members** | Pointer to **[]int64** |  | [optional] 
**MinimumMembers** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2LagInterface

`func NewManaV2LagInterface() *ManaV2LagInterface`

NewManaV2LagInterface instantiates a new ManaV2LagInterface object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2LagInterfaceWithDefaults

`func NewManaV2LagInterfaceWithDefaults() *ManaV2LagInterface`

NewManaV2LagInterfaceWithDefaults instantiates a new ManaV2LagInterface object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManaV2LagInterface) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2LagInterface) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2LagInterface) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2LagInterface) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLacpConfig

`func (o *ManaV2LagInterface) GetLacpConfig() ManaV2LacpConfig`

GetLacpConfig returns the LacpConfig field if non-nil, zero value otherwise.

### GetLacpConfigOk

`func (o *ManaV2LagInterface) GetLacpConfigOk() (*ManaV2LacpConfig, bool)`

GetLacpConfigOk returns a tuple with the LacpConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLacpConfig

`func (o *ManaV2LagInterface) SetLacpConfig(v ManaV2LacpConfig)`

SetLacpConfig sets LacpConfig field to given value.

### HasLacpConfig

`func (o *ManaV2LagInterface) HasLacpConfig() bool`

HasLacpConfig returns a boolean if a field has been set.

### GetMembers

`func (o *ManaV2LagInterface) GetMembers() []int64`

GetMembers returns the Members field if non-nil, zero value otherwise.

### GetMembersOk

`func (o *ManaV2LagInterface) GetMembersOk() (*[]int64, bool)`

GetMembersOk returns a tuple with the Members field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembers

`func (o *ManaV2LagInterface) SetMembers(v []int64)`

SetMembers sets Members field to given value.

### HasMembers

`func (o *ManaV2LagInterface) HasMembers() bool`

HasMembers returns a boolean if a field has been set.

### GetMinimumMembers

`func (o *ManaV2LagInterface) GetMinimumMembers() int32`

GetMinimumMembers returns the MinimumMembers field if non-nil, zero value otherwise.

### GetMinimumMembersOk

`func (o *ManaV2LagInterface) GetMinimumMembersOk() (*int32, bool)`

GetMinimumMembersOk returns a tuple with the MinimumMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumMembers

`func (o *ManaV2LagInterface) SetMinimumMembers(v int32)`

SetMinimumMembers sets MinimumMembers field to given value.

### HasMinimumMembers

`func (o *ManaV2LagInterface) HasMinimumMembers() bool`

HasMinimumMembers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



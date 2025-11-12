# ManaV2VacmGroupConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accesses** | Pointer to [**map[string]ManaV2NullableSnmpVacmGroupAccessValue**](ManaV2NullableSnmpVacmGroupAccessValue.md) |  | [optional] 
**Members** | Pointer to [**map[string]ManaV2NullableSnmpVacmGroupMemberValue**](ManaV2NullableSnmpVacmGroupMemberValue.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2VacmGroupConfig

`func NewManaV2VacmGroupConfig() *ManaV2VacmGroupConfig`

NewManaV2VacmGroupConfig instantiates a new ManaV2VacmGroupConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2VacmGroupConfigWithDefaults

`func NewManaV2VacmGroupConfigWithDefaults() *ManaV2VacmGroupConfig`

NewManaV2VacmGroupConfigWithDefaults instantiates a new ManaV2VacmGroupConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccesses

`func (o *ManaV2VacmGroupConfig) GetAccesses() map[string]ManaV2NullableSnmpVacmGroupAccessValue`

GetAccesses returns the Accesses field if non-nil, zero value otherwise.

### GetAccessesOk

`func (o *ManaV2VacmGroupConfig) GetAccessesOk() (*map[string]ManaV2NullableSnmpVacmGroupAccessValue, bool)`

GetAccessesOk returns a tuple with the Accesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccesses

`func (o *ManaV2VacmGroupConfig) SetAccesses(v map[string]ManaV2NullableSnmpVacmGroupAccessValue)`

SetAccesses sets Accesses field to given value.

### HasAccesses

`func (o *ManaV2VacmGroupConfig) HasAccesses() bool`

HasAccesses returns a boolean if a field has been set.

### GetMembers

`func (o *ManaV2VacmGroupConfig) GetMembers() map[string]ManaV2NullableSnmpVacmGroupMemberValue`

GetMembers returns the Members field if non-nil, zero value otherwise.

### GetMembersOk

`func (o *ManaV2VacmGroupConfig) GetMembersOk() (*map[string]ManaV2NullableSnmpVacmGroupMemberValue, bool)`

GetMembersOk returns a tuple with the Members field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembers

`func (o *ManaV2VacmGroupConfig) SetMembers(v map[string]ManaV2NullableSnmpVacmGroupMemberValue)`

SetMembers sets Members field to given value.

### HasMembers

`func (o *ManaV2VacmGroupConfig) HasMembers() bool`

HasMembers returns a boolean if a field has been set.

### GetName

`func (o *ManaV2VacmGroupConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2VacmGroupConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2VacmGroupConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2VacmGroupConfig) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



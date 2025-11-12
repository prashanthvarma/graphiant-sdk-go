# ManaV2VrrpGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptMode** | Pointer to **bool** |  | [optional] 
**AllowInterOperability** | Pointer to **bool** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**EffectivePriority** | Pointer to **int32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**GroupMembers** | Pointer to [**[]ManaV2VRRPGroupMember**](ManaV2VRRPGroupMember.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Preempt** | Pointer to **bool** |  | [optional] 
**Priority** | Pointer to **int32** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**TrackedInterfaces** | Pointer to [**[]ManaV2VRRPGroupInterfacePriorityDecrement**](ManaV2VRRPGroupInterfacePriorityDecrement.md) |  | [optional] 
**VirtualIpAddress** | Pointer to **string** |  | [optional] 
**VirtualMacAddress** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2VrrpGroup

`func NewManaV2VrrpGroup() *ManaV2VrrpGroup`

NewManaV2VrrpGroup instantiates a new ManaV2VrrpGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2VrrpGroupWithDefaults

`func NewManaV2VrrpGroupWithDefaults() *ManaV2VrrpGroup`

NewManaV2VrrpGroupWithDefaults instantiates a new ManaV2VrrpGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptMode

`func (o *ManaV2VrrpGroup) GetAcceptMode() bool`

GetAcceptMode returns the AcceptMode field if non-nil, zero value otherwise.

### GetAcceptModeOk

`func (o *ManaV2VrrpGroup) GetAcceptModeOk() (*bool, bool)`

GetAcceptModeOk returns a tuple with the AcceptMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptMode

`func (o *ManaV2VrrpGroup) SetAcceptMode(v bool)`

SetAcceptMode sets AcceptMode field to given value.

### HasAcceptMode

`func (o *ManaV2VrrpGroup) HasAcceptMode() bool`

HasAcceptMode returns a boolean if a field has been set.

### GetAllowInterOperability

`func (o *ManaV2VrrpGroup) GetAllowInterOperability() bool`

GetAllowInterOperability returns the AllowInterOperability field if non-nil, zero value otherwise.

### GetAllowInterOperabilityOk

`func (o *ManaV2VrrpGroup) GetAllowInterOperabilityOk() (*bool, bool)`

GetAllowInterOperabilityOk returns a tuple with the AllowInterOperability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowInterOperability

`func (o *ManaV2VrrpGroup) SetAllowInterOperability(v bool)`

SetAllowInterOperability sets AllowInterOperability field to given value.

### HasAllowInterOperability

`func (o *ManaV2VrrpGroup) HasAllowInterOperability() bool`

HasAllowInterOperability returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2VrrpGroup) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2VrrpGroup) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2VrrpGroup) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2VrrpGroup) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEffectivePriority

`func (o *ManaV2VrrpGroup) GetEffectivePriority() int32`

GetEffectivePriority returns the EffectivePriority field if non-nil, zero value otherwise.

### GetEffectivePriorityOk

`func (o *ManaV2VrrpGroup) GetEffectivePriorityOk() (*int32, bool)`

GetEffectivePriorityOk returns a tuple with the EffectivePriority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectivePriority

`func (o *ManaV2VrrpGroup) SetEffectivePriority(v int32)`

SetEffectivePriority sets EffectivePriority field to given value.

### HasEffectivePriority

`func (o *ManaV2VrrpGroup) HasEffectivePriority() bool`

HasEffectivePriority returns a boolean if a field has been set.

### GetEnabled

`func (o *ManaV2VrrpGroup) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManaV2VrrpGroup) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManaV2VrrpGroup) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManaV2VrrpGroup) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetGroupMembers

`func (o *ManaV2VrrpGroup) GetGroupMembers() []ManaV2VRRPGroupMember`

GetGroupMembers returns the GroupMembers field if non-nil, zero value otherwise.

### GetGroupMembersOk

`func (o *ManaV2VrrpGroup) GetGroupMembersOk() (*[]ManaV2VRRPGroupMember, bool)`

GetGroupMembersOk returns a tuple with the GroupMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMembers

`func (o *ManaV2VrrpGroup) SetGroupMembers(v []ManaV2VRRPGroupMember)`

SetGroupMembers sets GroupMembers field to given value.

### HasGroupMembers

`func (o *ManaV2VrrpGroup) HasGroupMembers() bool`

HasGroupMembers returns a boolean if a field has been set.

### GetId

`func (o *ManaV2VrrpGroup) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2VrrpGroup) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2VrrpGroup) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2VrrpGroup) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2VrrpGroup) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2VrrpGroup) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2VrrpGroup) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2VrrpGroup) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPreempt

`func (o *ManaV2VrrpGroup) GetPreempt() bool`

GetPreempt returns the Preempt field if non-nil, zero value otherwise.

### GetPreemptOk

`func (o *ManaV2VrrpGroup) GetPreemptOk() (*bool, bool)`

GetPreemptOk returns a tuple with the Preempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreempt

`func (o *ManaV2VrrpGroup) SetPreempt(v bool)`

SetPreempt sets Preempt field to given value.

### HasPreempt

`func (o *ManaV2VrrpGroup) HasPreempt() bool`

HasPreempt returns a boolean if a field has been set.

### GetPriority

`func (o *ManaV2VrrpGroup) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ManaV2VrrpGroup) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ManaV2VrrpGroup) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ManaV2VrrpGroup) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetState

`func (o *ManaV2VrrpGroup) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ManaV2VrrpGroup) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ManaV2VrrpGroup) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ManaV2VrrpGroup) HasState() bool`

HasState returns a boolean if a field has been set.

### GetTrackedInterfaces

`func (o *ManaV2VrrpGroup) GetTrackedInterfaces() []ManaV2VRRPGroupInterfacePriorityDecrement`

GetTrackedInterfaces returns the TrackedInterfaces field if non-nil, zero value otherwise.

### GetTrackedInterfacesOk

`func (o *ManaV2VrrpGroup) GetTrackedInterfacesOk() (*[]ManaV2VRRPGroupInterfacePriorityDecrement, bool)`

GetTrackedInterfacesOk returns a tuple with the TrackedInterfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackedInterfaces

`func (o *ManaV2VrrpGroup) SetTrackedInterfaces(v []ManaV2VRRPGroupInterfacePriorityDecrement)`

SetTrackedInterfaces sets TrackedInterfaces field to given value.

### HasTrackedInterfaces

`func (o *ManaV2VrrpGroup) HasTrackedInterfaces() bool`

HasTrackedInterfaces returns a boolean if a field has been set.

### GetVirtualIpAddress

`func (o *ManaV2VrrpGroup) GetVirtualIpAddress() string`

GetVirtualIpAddress returns the VirtualIpAddress field if non-nil, zero value otherwise.

### GetVirtualIpAddressOk

`func (o *ManaV2VrrpGroup) GetVirtualIpAddressOk() (*string, bool)`

GetVirtualIpAddressOk returns a tuple with the VirtualIpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualIpAddress

`func (o *ManaV2VrrpGroup) SetVirtualIpAddress(v string)`

SetVirtualIpAddress sets VirtualIpAddress field to given value.

### HasVirtualIpAddress

`func (o *ManaV2VrrpGroup) HasVirtualIpAddress() bool`

HasVirtualIpAddress returns a boolean if a field has been set.

### GetVirtualMacAddress

`func (o *ManaV2VrrpGroup) GetVirtualMacAddress() string`

GetVirtualMacAddress returns the VirtualMacAddress field if non-nil, zero value otherwise.

### GetVirtualMacAddressOk

`func (o *ManaV2VrrpGroup) GetVirtualMacAddressOk() (*string, bool)`

GetVirtualMacAddressOk returns a tuple with the VirtualMacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualMacAddress

`func (o *ManaV2VrrpGroup) SetVirtualMacAddress(v string)`

SetVirtualMacAddress sets VirtualMacAddress field to given value.

### HasVirtualMacAddress

`func (o *ManaV2VrrpGroup) HasVirtualMacAddress() bool`

HasVirtualMacAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



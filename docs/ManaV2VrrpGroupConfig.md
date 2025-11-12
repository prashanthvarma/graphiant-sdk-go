# ManaV2VrrpGroupConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptMode** | Pointer to **bool** |  | [optional] 
**AllowInterOperability** | Pointer to **bool** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Preempt** | Pointer to **bool** |  | [optional] 
**Priority** | Pointer to **int32** |  | [optional] 
**TrackedInterfaces** | Pointer to [**[]ManaV2NullableInterfacePriorityDecrement**](ManaV2NullableInterfacePriorityDecrement.md) |  | [optional] 
**VirtualIp** | Pointer to **string** |  | [optional] 
**VirtualRouterId** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2VrrpGroupConfig

`func NewManaV2VrrpGroupConfig() *ManaV2VrrpGroupConfig`

NewManaV2VrrpGroupConfig instantiates a new ManaV2VrrpGroupConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2VrrpGroupConfigWithDefaults

`func NewManaV2VrrpGroupConfigWithDefaults() *ManaV2VrrpGroupConfig`

NewManaV2VrrpGroupConfigWithDefaults instantiates a new ManaV2VrrpGroupConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptMode

`func (o *ManaV2VrrpGroupConfig) GetAcceptMode() bool`

GetAcceptMode returns the AcceptMode field if non-nil, zero value otherwise.

### GetAcceptModeOk

`func (o *ManaV2VrrpGroupConfig) GetAcceptModeOk() (*bool, bool)`

GetAcceptModeOk returns a tuple with the AcceptMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptMode

`func (o *ManaV2VrrpGroupConfig) SetAcceptMode(v bool)`

SetAcceptMode sets AcceptMode field to given value.

### HasAcceptMode

`func (o *ManaV2VrrpGroupConfig) HasAcceptMode() bool`

HasAcceptMode returns a boolean if a field has been set.

### GetAllowInterOperability

`func (o *ManaV2VrrpGroupConfig) GetAllowInterOperability() bool`

GetAllowInterOperability returns the AllowInterOperability field if non-nil, zero value otherwise.

### GetAllowInterOperabilityOk

`func (o *ManaV2VrrpGroupConfig) GetAllowInterOperabilityOk() (*bool, bool)`

GetAllowInterOperabilityOk returns a tuple with the AllowInterOperability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowInterOperability

`func (o *ManaV2VrrpGroupConfig) SetAllowInterOperability(v bool)`

SetAllowInterOperability sets AllowInterOperability field to given value.

### HasAllowInterOperability

`func (o *ManaV2VrrpGroupConfig) HasAllowInterOperability() bool`

HasAllowInterOperability returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2VrrpGroupConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2VrrpGroupConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2VrrpGroupConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2VrrpGroupConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEnabled

`func (o *ManaV2VrrpGroupConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManaV2VrrpGroupConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManaV2VrrpGroupConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManaV2VrrpGroupConfig) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPreempt

`func (o *ManaV2VrrpGroupConfig) GetPreempt() bool`

GetPreempt returns the Preempt field if non-nil, zero value otherwise.

### GetPreemptOk

`func (o *ManaV2VrrpGroupConfig) GetPreemptOk() (*bool, bool)`

GetPreemptOk returns a tuple with the Preempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreempt

`func (o *ManaV2VrrpGroupConfig) SetPreempt(v bool)`

SetPreempt sets Preempt field to given value.

### HasPreempt

`func (o *ManaV2VrrpGroupConfig) HasPreempt() bool`

HasPreempt returns a boolean if a field has been set.

### GetPriority

`func (o *ManaV2VrrpGroupConfig) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ManaV2VrrpGroupConfig) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ManaV2VrrpGroupConfig) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ManaV2VrrpGroupConfig) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetTrackedInterfaces

`func (o *ManaV2VrrpGroupConfig) GetTrackedInterfaces() []ManaV2NullableInterfacePriorityDecrement`

GetTrackedInterfaces returns the TrackedInterfaces field if non-nil, zero value otherwise.

### GetTrackedInterfacesOk

`func (o *ManaV2VrrpGroupConfig) GetTrackedInterfacesOk() (*[]ManaV2NullableInterfacePriorityDecrement, bool)`

GetTrackedInterfacesOk returns a tuple with the TrackedInterfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackedInterfaces

`func (o *ManaV2VrrpGroupConfig) SetTrackedInterfaces(v []ManaV2NullableInterfacePriorityDecrement)`

SetTrackedInterfaces sets TrackedInterfaces field to given value.

### HasTrackedInterfaces

`func (o *ManaV2VrrpGroupConfig) HasTrackedInterfaces() bool`

HasTrackedInterfaces returns a boolean if a field has been set.

### GetVirtualIp

`func (o *ManaV2VrrpGroupConfig) GetVirtualIp() string`

GetVirtualIp returns the VirtualIp field if non-nil, zero value otherwise.

### GetVirtualIpOk

`func (o *ManaV2VrrpGroupConfig) GetVirtualIpOk() (*string, bool)`

GetVirtualIpOk returns a tuple with the VirtualIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualIp

`func (o *ManaV2VrrpGroupConfig) SetVirtualIp(v string)`

SetVirtualIp sets VirtualIp field to given value.

### HasVirtualIp

`func (o *ManaV2VrrpGroupConfig) HasVirtualIp() bool`

HasVirtualIp returns a boolean if a field has been set.

### GetVirtualRouterId

`func (o *ManaV2VrrpGroupConfig) GetVirtualRouterId() int32`

GetVirtualRouterId returns the VirtualRouterId field if non-nil, zero value otherwise.

### GetVirtualRouterIdOk

`func (o *ManaV2VrrpGroupConfig) GetVirtualRouterIdOk() (*int32, bool)`

GetVirtualRouterIdOk returns a tuple with the VirtualRouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualRouterId

`func (o *ManaV2VrrpGroupConfig) SetVirtualRouterId(v int32)`

SetVirtualRouterId sets VirtualRouterId field to given value.

### HasVirtualRouterId

`func (o *ManaV2VrrpGroupConfig) HasVirtualRouterId() bool`

HasVirtualRouterId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



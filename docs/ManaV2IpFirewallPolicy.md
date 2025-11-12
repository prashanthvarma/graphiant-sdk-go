# ManaV2IpFirewallPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlockLandAttacks** | Pointer to **bool** |  | [optional] 
**SessionLimit** | Pointer to **int32** |  | [optional] 
**Urpf** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2IpFirewallPolicy

`func NewManaV2IpFirewallPolicy() *ManaV2IpFirewallPolicy`

NewManaV2IpFirewallPolicy instantiates a new ManaV2IpFirewallPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IpFirewallPolicyWithDefaults

`func NewManaV2IpFirewallPolicyWithDefaults() *ManaV2IpFirewallPolicy`

NewManaV2IpFirewallPolicyWithDefaults instantiates a new ManaV2IpFirewallPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlockLandAttacks

`func (o *ManaV2IpFirewallPolicy) GetBlockLandAttacks() bool`

GetBlockLandAttacks returns the BlockLandAttacks field if non-nil, zero value otherwise.

### GetBlockLandAttacksOk

`func (o *ManaV2IpFirewallPolicy) GetBlockLandAttacksOk() (*bool, bool)`

GetBlockLandAttacksOk returns a tuple with the BlockLandAttacks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockLandAttacks

`func (o *ManaV2IpFirewallPolicy) SetBlockLandAttacks(v bool)`

SetBlockLandAttacks sets BlockLandAttacks field to given value.

### HasBlockLandAttacks

`func (o *ManaV2IpFirewallPolicy) HasBlockLandAttacks() bool`

HasBlockLandAttacks returns a boolean if a field has been set.

### GetSessionLimit

`func (o *ManaV2IpFirewallPolicy) GetSessionLimit() int32`

GetSessionLimit returns the SessionLimit field if non-nil, zero value otherwise.

### GetSessionLimitOk

`func (o *ManaV2IpFirewallPolicy) GetSessionLimitOk() (*int32, bool)`

GetSessionLimitOk returns a tuple with the SessionLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionLimit

`func (o *ManaV2IpFirewallPolicy) SetSessionLimit(v int32)`

SetSessionLimit sets SessionLimit field to given value.

### HasSessionLimit

`func (o *ManaV2IpFirewallPolicy) HasSessionLimit() bool`

HasSessionLimit returns a boolean if a field has been set.

### GetUrpf

`func (o *ManaV2IpFirewallPolicy) GetUrpf() string`

GetUrpf returns the Urpf field if non-nil, zero value otherwise.

### GetUrpfOk

`func (o *ManaV2IpFirewallPolicy) GetUrpfOk() (*string, bool)`

GetUrpfOk returns a tuple with the Urpf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrpf

`func (o *ManaV2IpFirewallPolicy) SetUrpf(v string)`

SetUrpf sets Urpf field to given value.

### HasUrpf

`func (o *ManaV2IpFirewallPolicy) HasUrpf() bool`

HasUrpf returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



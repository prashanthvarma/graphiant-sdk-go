# ManaV2ZoneFirewallConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ip** | Pointer to [**ManaV2ZoneFirewallIpPolicyConfig**](ManaV2ZoneFirewallIpPolicyConfig.md) |  | [optional] 
**Udp** | Pointer to [**ManaV2ZoneFirewallUdpPolicyConfig**](ManaV2ZoneFirewallUdpPolicyConfig.md) |  | [optional] 

## Methods

### NewManaV2ZoneFirewallConfig

`func NewManaV2ZoneFirewallConfig() *ManaV2ZoneFirewallConfig`

NewManaV2ZoneFirewallConfig instantiates a new ManaV2ZoneFirewallConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ZoneFirewallConfigWithDefaults

`func NewManaV2ZoneFirewallConfigWithDefaults() *ManaV2ZoneFirewallConfig`

NewManaV2ZoneFirewallConfigWithDefaults instantiates a new ManaV2ZoneFirewallConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIp

`func (o *ManaV2ZoneFirewallConfig) GetIp() ManaV2ZoneFirewallIpPolicyConfig`

GetIp returns the Ip field if non-nil, zero value otherwise.

### GetIpOk

`func (o *ManaV2ZoneFirewallConfig) GetIpOk() (*ManaV2ZoneFirewallIpPolicyConfig, bool)`

GetIpOk returns a tuple with the Ip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIp

`func (o *ManaV2ZoneFirewallConfig) SetIp(v ManaV2ZoneFirewallIpPolicyConfig)`

SetIp sets Ip field to given value.

### HasIp

`func (o *ManaV2ZoneFirewallConfig) HasIp() bool`

HasIp returns a boolean if a field has been set.

### GetUdp

`func (o *ManaV2ZoneFirewallConfig) GetUdp() ManaV2ZoneFirewallUdpPolicyConfig`

GetUdp returns the Udp field if non-nil, zero value otherwise.

### GetUdpOk

`func (o *ManaV2ZoneFirewallConfig) GetUdpOk() (*ManaV2ZoneFirewallUdpPolicyConfig, bool)`

GetUdpOk returns a tuple with the Udp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUdp

`func (o *ManaV2ZoneFirewallConfig) SetUdp(v ManaV2ZoneFirewallUdpPolicyConfig)`

SetUdp sets Udp field to given value.

### HasUdp

`func (o *ManaV2ZoneFirewallConfig) HasUdp() bool`

HasUdp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



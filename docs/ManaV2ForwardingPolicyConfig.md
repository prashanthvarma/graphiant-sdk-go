# ManaV2ForwardingPolicyConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DpiApplications** | Pointer to [**map[string]ManaV2NullableDpiApplicationConfig**](ManaV2NullableDpiApplicationConfig.md) |  | [optional] 
**NetworkLists** | Pointer to [**map[string]ManaV2NullableIpNetworkListConfig**](ManaV2NullableIpNetworkListConfig.md) |  | [optional] 
**PortLists** | Pointer to [**map[string]ManaV2NullableL4PortListConfig**](ManaV2NullableL4PortListConfig.md) |  | [optional] 
**SecurityRulesets** | Pointer to [**map[string]ManaV2NullableSecurityPolicyRulesetConfig**](ManaV2NullableSecurityPolicyRulesetConfig.md) |  | [optional] 
**TrafficRulesets** | Pointer to [**map[string]ManaV2NullableTrafficPolicyRulesetConfig**](ManaV2NullableTrafficPolicyRulesetConfig.md) |  | [optional] 
**ZoneFirewalls** | Pointer to [**map[string]ManaV2NullableZoneFirewallConfig**](ManaV2NullableZoneFirewallConfig.md) |  | [optional] 
**Zones** | Pointer to [**map[string]ManaV2NullableSecurityZoneConfig**](ManaV2NullableSecurityZoneConfig.md) |  | [optional] 

## Methods

### NewManaV2ForwardingPolicyConfig

`func NewManaV2ForwardingPolicyConfig() *ManaV2ForwardingPolicyConfig`

NewManaV2ForwardingPolicyConfig instantiates a new ManaV2ForwardingPolicyConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ForwardingPolicyConfigWithDefaults

`func NewManaV2ForwardingPolicyConfigWithDefaults() *ManaV2ForwardingPolicyConfig`

NewManaV2ForwardingPolicyConfigWithDefaults instantiates a new ManaV2ForwardingPolicyConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDpiApplications

`func (o *ManaV2ForwardingPolicyConfig) GetDpiApplications() map[string]ManaV2NullableDpiApplicationConfig`

GetDpiApplications returns the DpiApplications field if non-nil, zero value otherwise.

### GetDpiApplicationsOk

`func (o *ManaV2ForwardingPolicyConfig) GetDpiApplicationsOk() (*map[string]ManaV2NullableDpiApplicationConfig, bool)`

GetDpiApplicationsOk returns a tuple with the DpiApplications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpiApplications

`func (o *ManaV2ForwardingPolicyConfig) SetDpiApplications(v map[string]ManaV2NullableDpiApplicationConfig)`

SetDpiApplications sets DpiApplications field to given value.

### HasDpiApplications

`func (o *ManaV2ForwardingPolicyConfig) HasDpiApplications() bool`

HasDpiApplications returns a boolean if a field has been set.

### GetNetworkLists

`func (o *ManaV2ForwardingPolicyConfig) GetNetworkLists() map[string]ManaV2NullableIpNetworkListConfig`

GetNetworkLists returns the NetworkLists field if non-nil, zero value otherwise.

### GetNetworkListsOk

`func (o *ManaV2ForwardingPolicyConfig) GetNetworkListsOk() (*map[string]ManaV2NullableIpNetworkListConfig, bool)`

GetNetworkListsOk returns a tuple with the NetworkLists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkLists

`func (o *ManaV2ForwardingPolicyConfig) SetNetworkLists(v map[string]ManaV2NullableIpNetworkListConfig)`

SetNetworkLists sets NetworkLists field to given value.

### HasNetworkLists

`func (o *ManaV2ForwardingPolicyConfig) HasNetworkLists() bool`

HasNetworkLists returns a boolean if a field has been set.

### GetPortLists

`func (o *ManaV2ForwardingPolicyConfig) GetPortLists() map[string]ManaV2NullableL4PortListConfig`

GetPortLists returns the PortLists field if non-nil, zero value otherwise.

### GetPortListsOk

`func (o *ManaV2ForwardingPolicyConfig) GetPortListsOk() (*map[string]ManaV2NullableL4PortListConfig, bool)`

GetPortListsOk returns a tuple with the PortLists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortLists

`func (o *ManaV2ForwardingPolicyConfig) SetPortLists(v map[string]ManaV2NullableL4PortListConfig)`

SetPortLists sets PortLists field to given value.

### HasPortLists

`func (o *ManaV2ForwardingPolicyConfig) HasPortLists() bool`

HasPortLists returns a boolean if a field has been set.

### GetSecurityRulesets

`func (o *ManaV2ForwardingPolicyConfig) GetSecurityRulesets() map[string]ManaV2NullableSecurityPolicyRulesetConfig`

GetSecurityRulesets returns the SecurityRulesets field if non-nil, zero value otherwise.

### GetSecurityRulesetsOk

`func (o *ManaV2ForwardingPolicyConfig) GetSecurityRulesetsOk() (*map[string]ManaV2NullableSecurityPolicyRulesetConfig, bool)`

GetSecurityRulesetsOk returns a tuple with the SecurityRulesets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityRulesets

`func (o *ManaV2ForwardingPolicyConfig) SetSecurityRulesets(v map[string]ManaV2NullableSecurityPolicyRulesetConfig)`

SetSecurityRulesets sets SecurityRulesets field to given value.

### HasSecurityRulesets

`func (o *ManaV2ForwardingPolicyConfig) HasSecurityRulesets() bool`

HasSecurityRulesets returns a boolean if a field has been set.

### GetTrafficRulesets

`func (o *ManaV2ForwardingPolicyConfig) GetTrafficRulesets() map[string]ManaV2NullableTrafficPolicyRulesetConfig`

GetTrafficRulesets returns the TrafficRulesets field if non-nil, zero value otherwise.

### GetTrafficRulesetsOk

`func (o *ManaV2ForwardingPolicyConfig) GetTrafficRulesetsOk() (*map[string]ManaV2NullableTrafficPolicyRulesetConfig, bool)`

GetTrafficRulesetsOk returns a tuple with the TrafficRulesets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRulesets

`func (o *ManaV2ForwardingPolicyConfig) SetTrafficRulesets(v map[string]ManaV2NullableTrafficPolicyRulesetConfig)`

SetTrafficRulesets sets TrafficRulesets field to given value.

### HasTrafficRulesets

`func (o *ManaV2ForwardingPolicyConfig) HasTrafficRulesets() bool`

HasTrafficRulesets returns a boolean if a field has been set.

### GetZoneFirewalls

`func (o *ManaV2ForwardingPolicyConfig) GetZoneFirewalls() map[string]ManaV2NullableZoneFirewallConfig`

GetZoneFirewalls returns the ZoneFirewalls field if non-nil, zero value otherwise.

### GetZoneFirewallsOk

`func (o *ManaV2ForwardingPolicyConfig) GetZoneFirewallsOk() (*map[string]ManaV2NullableZoneFirewallConfig, bool)`

GetZoneFirewallsOk returns a tuple with the ZoneFirewalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZoneFirewalls

`func (o *ManaV2ForwardingPolicyConfig) SetZoneFirewalls(v map[string]ManaV2NullableZoneFirewallConfig)`

SetZoneFirewalls sets ZoneFirewalls field to given value.

### HasZoneFirewalls

`func (o *ManaV2ForwardingPolicyConfig) HasZoneFirewalls() bool`

HasZoneFirewalls returns a boolean if a field has been set.

### GetZones

`func (o *ManaV2ForwardingPolicyConfig) GetZones() map[string]ManaV2NullableSecurityZoneConfig`

GetZones returns the Zones field if non-nil, zero value otherwise.

### GetZonesOk

`func (o *ManaV2ForwardingPolicyConfig) GetZonesOk() (*map[string]ManaV2NullableSecurityZoneConfig, bool)`

GetZonesOk returns a tuple with the Zones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZones

`func (o *ManaV2ForwardingPolicyConfig) SetZones(v map[string]ManaV2NullableSecurityZoneConfig)`

SetZones sets Zones field to given value.

### HasZones

`func (o *ManaV2ForwardingPolicyConfig) HasZones() bool`

HasZones returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



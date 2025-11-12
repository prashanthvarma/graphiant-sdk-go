# ManaV2ForwardingPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DpiApplications** | Pointer to [**[]ManaV2DpiCustomApplication**](ManaV2DpiCustomApplication.md) |  | [optional] 
**NetworkLists** | Pointer to [**[]ManaV2IpNetworkList**](ManaV2IpNetworkList.md) |  | [optional] 
**PortLists** | Pointer to [**[]ManaV2L4PortList**](ManaV2L4PortList.md) |  | [optional] 
**SecurityRulesets** | Pointer to [**[]ManaV2SecurityPolicyRuleset**](ManaV2SecurityPolicyRuleset.md) |  | [optional] 
**TrafficRulesets** | Pointer to [**[]ManaV2TrafficPolicyRuleset**](ManaV2TrafficPolicyRuleset.md) |  | [optional] 
**ZoneFirewalls** | Pointer to [**[]ManaV2ZoneFirewallPolicy**](ManaV2ZoneFirewallPolicy.md) |  | [optional] 
**ZonePairs** | Pointer to [**[]ManaV2SecurityZone**](ManaV2SecurityZone.md) |  | [optional] 

## Methods

### NewManaV2ForwardingPolicy

`func NewManaV2ForwardingPolicy() *ManaV2ForwardingPolicy`

NewManaV2ForwardingPolicy instantiates a new ManaV2ForwardingPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ForwardingPolicyWithDefaults

`func NewManaV2ForwardingPolicyWithDefaults() *ManaV2ForwardingPolicy`

NewManaV2ForwardingPolicyWithDefaults instantiates a new ManaV2ForwardingPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDpiApplications

`func (o *ManaV2ForwardingPolicy) GetDpiApplications() []ManaV2DpiCustomApplication`

GetDpiApplications returns the DpiApplications field if non-nil, zero value otherwise.

### GetDpiApplicationsOk

`func (o *ManaV2ForwardingPolicy) GetDpiApplicationsOk() (*[]ManaV2DpiCustomApplication, bool)`

GetDpiApplicationsOk returns a tuple with the DpiApplications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpiApplications

`func (o *ManaV2ForwardingPolicy) SetDpiApplications(v []ManaV2DpiCustomApplication)`

SetDpiApplications sets DpiApplications field to given value.

### HasDpiApplications

`func (o *ManaV2ForwardingPolicy) HasDpiApplications() bool`

HasDpiApplications returns a boolean if a field has been set.

### GetNetworkLists

`func (o *ManaV2ForwardingPolicy) GetNetworkLists() []ManaV2IpNetworkList`

GetNetworkLists returns the NetworkLists field if non-nil, zero value otherwise.

### GetNetworkListsOk

`func (o *ManaV2ForwardingPolicy) GetNetworkListsOk() (*[]ManaV2IpNetworkList, bool)`

GetNetworkListsOk returns a tuple with the NetworkLists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkLists

`func (o *ManaV2ForwardingPolicy) SetNetworkLists(v []ManaV2IpNetworkList)`

SetNetworkLists sets NetworkLists field to given value.

### HasNetworkLists

`func (o *ManaV2ForwardingPolicy) HasNetworkLists() bool`

HasNetworkLists returns a boolean if a field has been set.

### GetPortLists

`func (o *ManaV2ForwardingPolicy) GetPortLists() []ManaV2L4PortList`

GetPortLists returns the PortLists field if non-nil, zero value otherwise.

### GetPortListsOk

`func (o *ManaV2ForwardingPolicy) GetPortListsOk() (*[]ManaV2L4PortList, bool)`

GetPortListsOk returns a tuple with the PortLists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortLists

`func (o *ManaV2ForwardingPolicy) SetPortLists(v []ManaV2L4PortList)`

SetPortLists sets PortLists field to given value.

### HasPortLists

`func (o *ManaV2ForwardingPolicy) HasPortLists() bool`

HasPortLists returns a boolean if a field has been set.

### GetSecurityRulesets

`func (o *ManaV2ForwardingPolicy) GetSecurityRulesets() []ManaV2SecurityPolicyRuleset`

GetSecurityRulesets returns the SecurityRulesets field if non-nil, zero value otherwise.

### GetSecurityRulesetsOk

`func (o *ManaV2ForwardingPolicy) GetSecurityRulesetsOk() (*[]ManaV2SecurityPolicyRuleset, bool)`

GetSecurityRulesetsOk returns a tuple with the SecurityRulesets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityRulesets

`func (o *ManaV2ForwardingPolicy) SetSecurityRulesets(v []ManaV2SecurityPolicyRuleset)`

SetSecurityRulesets sets SecurityRulesets field to given value.

### HasSecurityRulesets

`func (o *ManaV2ForwardingPolicy) HasSecurityRulesets() bool`

HasSecurityRulesets returns a boolean if a field has been set.

### GetTrafficRulesets

`func (o *ManaV2ForwardingPolicy) GetTrafficRulesets() []ManaV2TrafficPolicyRuleset`

GetTrafficRulesets returns the TrafficRulesets field if non-nil, zero value otherwise.

### GetTrafficRulesetsOk

`func (o *ManaV2ForwardingPolicy) GetTrafficRulesetsOk() (*[]ManaV2TrafficPolicyRuleset, bool)`

GetTrafficRulesetsOk returns a tuple with the TrafficRulesets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRulesets

`func (o *ManaV2ForwardingPolicy) SetTrafficRulesets(v []ManaV2TrafficPolicyRuleset)`

SetTrafficRulesets sets TrafficRulesets field to given value.

### HasTrafficRulesets

`func (o *ManaV2ForwardingPolicy) HasTrafficRulesets() bool`

HasTrafficRulesets returns a boolean if a field has been set.

### GetZoneFirewalls

`func (o *ManaV2ForwardingPolicy) GetZoneFirewalls() []ManaV2ZoneFirewallPolicy`

GetZoneFirewalls returns the ZoneFirewalls field if non-nil, zero value otherwise.

### GetZoneFirewallsOk

`func (o *ManaV2ForwardingPolicy) GetZoneFirewallsOk() (*[]ManaV2ZoneFirewallPolicy, bool)`

GetZoneFirewallsOk returns a tuple with the ZoneFirewalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZoneFirewalls

`func (o *ManaV2ForwardingPolicy) SetZoneFirewalls(v []ManaV2ZoneFirewallPolicy)`

SetZoneFirewalls sets ZoneFirewalls field to given value.

### HasZoneFirewalls

`func (o *ManaV2ForwardingPolicy) HasZoneFirewalls() bool`

HasZoneFirewalls returns a boolean if a field has been set.

### GetZonePairs

`func (o *ManaV2ForwardingPolicy) GetZonePairs() []ManaV2SecurityZone`

GetZonePairs returns the ZonePairs field if non-nil, zero value otherwise.

### GetZonePairsOk

`func (o *ManaV2ForwardingPolicy) GetZonePairsOk() (*[]ManaV2SecurityZone, bool)`

GetZonePairsOk returns a tuple with the ZonePairs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZonePairs

`func (o *ManaV2ForwardingPolicy) SetZonePairs(v []ManaV2SecurityZone)`

SetZonePairs sets ZonePairs field to given value.

### HasZonePairs

`func (o *ManaV2ForwardingPolicy) HasZonePairs() bool`

HasZonePairs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



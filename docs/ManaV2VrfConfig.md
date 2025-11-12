# ManaV2VrfConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpAggregations** | Pointer to [**map[string]ManaV2NullableBgpAggregationsConfig**](ManaV2NullableBgpAggregationsConfig.md) |  | [optional] 
**BgpNeighbors** | Pointer to [**map[string]ManaV2NullableBgpNeighborConfig**](ManaV2NullableBgpNeighborConfig.md) |  | [optional] 
**BgpRedistribution** | Pointer to [**map[string]ManaV2NullableBgpRedistributeProtocolConfig**](ManaV2NullableBgpRedistributeProtocolConfig.md) |  | [optional] 
**DhcpSubnets** | Pointer to [**map[string]ManaV2NullableDhcpSubnetConfig**](ManaV2NullableDhcpSubnetConfig.md) |  | [optional] 
**EbgpMultipath** | Pointer to [**ManaV2NullableBgpMultipathConfig**](ManaV2NullableBgpMultipathConfig.md) |  | [optional] 
**IpfixExporters** | Pointer to [**map[string]ManaV2NullableIpfixExporterConfig**](ManaV2NullableIpfixExporterConfig.md) |  | [optional] 
**NatRuleset** | Pointer to [**ManaV2NullableNatPolicyRulesetName**](ManaV2NullableNatPolicyRulesetName.md) |  | [optional] 
**Networks** | Pointer to **[]string** |  | [optional] 
**Ospfv2** | Pointer to [**ManaV2NullableOspfProcessConfig**](ManaV2NullableOspfProcessConfig.md) |  | [optional] 
**Ospfv3** | Pointer to [**ManaV2NullableOspfProcessConfig**](ManaV2NullableOspfProcessConfig.md) |  | [optional] 
**OverlayFilters** | Pointer to [**ManaV2OverlayFilterConfig**](ManaV2OverlayFilterConfig.md) |  | [optional] 
**StaticRoutes** | Pointer to [**map[string]ManaV2NullableStaticRouteConfig**](ManaV2NullableStaticRouteConfig.md) |  | [optional] 
**SyslogTargets** | Pointer to [**map[string]ManaV2NullableSyslogCollectorConfig**](ManaV2NullableSyslogCollectorConfig.md) |  | [optional] 
**TrafficRuleset** | Pointer to [**ManaV2NullableTrafficPolicyRulesetName**](ManaV2NullableTrafficPolicyRulesetName.md) |  | [optional] 

## Methods

### NewManaV2VrfConfig

`func NewManaV2VrfConfig() *ManaV2VrfConfig`

NewManaV2VrfConfig instantiates a new ManaV2VrfConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2VrfConfigWithDefaults

`func NewManaV2VrfConfigWithDefaults() *ManaV2VrfConfig`

NewManaV2VrfConfigWithDefaults instantiates a new ManaV2VrfConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpAggregations

`func (o *ManaV2VrfConfig) GetBgpAggregations() map[string]ManaV2NullableBgpAggregationsConfig`

GetBgpAggregations returns the BgpAggregations field if non-nil, zero value otherwise.

### GetBgpAggregationsOk

`func (o *ManaV2VrfConfig) GetBgpAggregationsOk() (*map[string]ManaV2NullableBgpAggregationsConfig, bool)`

GetBgpAggregationsOk returns a tuple with the BgpAggregations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpAggregations

`func (o *ManaV2VrfConfig) SetBgpAggregations(v map[string]ManaV2NullableBgpAggregationsConfig)`

SetBgpAggregations sets BgpAggregations field to given value.

### HasBgpAggregations

`func (o *ManaV2VrfConfig) HasBgpAggregations() bool`

HasBgpAggregations returns a boolean if a field has been set.

### GetBgpNeighbors

`func (o *ManaV2VrfConfig) GetBgpNeighbors() map[string]ManaV2NullableBgpNeighborConfig`

GetBgpNeighbors returns the BgpNeighbors field if non-nil, zero value otherwise.

### GetBgpNeighborsOk

`func (o *ManaV2VrfConfig) GetBgpNeighborsOk() (*map[string]ManaV2NullableBgpNeighborConfig, bool)`

GetBgpNeighborsOk returns a tuple with the BgpNeighbors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighbors

`func (o *ManaV2VrfConfig) SetBgpNeighbors(v map[string]ManaV2NullableBgpNeighborConfig)`

SetBgpNeighbors sets BgpNeighbors field to given value.

### HasBgpNeighbors

`func (o *ManaV2VrfConfig) HasBgpNeighbors() bool`

HasBgpNeighbors returns a boolean if a field has been set.

### GetBgpRedistribution

`func (o *ManaV2VrfConfig) GetBgpRedistribution() map[string]ManaV2NullableBgpRedistributeProtocolConfig`

GetBgpRedistribution returns the BgpRedistribution field if non-nil, zero value otherwise.

### GetBgpRedistributionOk

`func (o *ManaV2VrfConfig) GetBgpRedistributionOk() (*map[string]ManaV2NullableBgpRedistributeProtocolConfig, bool)`

GetBgpRedistributionOk returns a tuple with the BgpRedistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpRedistribution

`func (o *ManaV2VrfConfig) SetBgpRedistribution(v map[string]ManaV2NullableBgpRedistributeProtocolConfig)`

SetBgpRedistribution sets BgpRedistribution field to given value.

### HasBgpRedistribution

`func (o *ManaV2VrfConfig) HasBgpRedistribution() bool`

HasBgpRedistribution returns a boolean if a field has been set.

### GetDhcpSubnets

`func (o *ManaV2VrfConfig) GetDhcpSubnets() map[string]ManaV2NullableDhcpSubnetConfig`

GetDhcpSubnets returns the DhcpSubnets field if non-nil, zero value otherwise.

### GetDhcpSubnetsOk

`func (o *ManaV2VrfConfig) GetDhcpSubnetsOk() (*map[string]ManaV2NullableDhcpSubnetConfig, bool)`

GetDhcpSubnetsOk returns a tuple with the DhcpSubnets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpSubnets

`func (o *ManaV2VrfConfig) SetDhcpSubnets(v map[string]ManaV2NullableDhcpSubnetConfig)`

SetDhcpSubnets sets DhcpSubnets field to given value.

### HasDhcpSubnets

`func (o *ManaV2VrfConfig) HasDhcpSubnets() bool`

HasDhcpSubnets returns a boolean if a field has been set.

### GetEbgpMultipath

`func (o *ManaV2VrfConfig) GetEbgpMultipath() ManaV2NullableBgpMultipathConfig`

GetEbgpMultipath returns the EbgpMultipath field if non-nil, zero value otherwise.

### GetEbgpMultipathOk

`func (o *ManaV2VrfConfig) GetEbgpMultipathOk() (*ManaV2NullableBgpMultipathConfig, bool)`

GetEbgpMultipathOk returns a tuple with the EbgpMultipath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEbgpMultipath

`func (o *ManaV2VrfConfig) SetEbgpMultipath(v ManaV2NullableBgpMultipathConfig)`

SetEbgpMultipath sets EbgpMultipath field to given value.

### HasEbgpMultipath

`func (o *ManaV2VrfConfig) HasEbgpMultipath() bool`

HasEbgpMultipath returns a boolean if a field has been set.

### GetIpfixExporters

`func (o *ManaV2VrfConfig) GetIpfixExporters() map[string]ManaV2NullableIpfixExporterConfig`

GetIpfixExporters returns the IpfixExporters field if non-nil, zero value otherwise.

### GetIpfixExportersOk

`func (o *ManaV2VrfConfig) GetIpfixExportersOk() (*map[string]ManaV2NullableIpfixExporterConfig, bool)`

GetIpfixExportersOk returns a tuple with the IpfixExporters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpfixExporters

`func (o *ManaV2VrfConfig) SetIpfixExporters(v map[string]ManaV2NullableIpfixExporterConfig)`

SetIpfixExporters sets IpfixExporters field to given value.

### HasIpfixExporters

`func (o *ManaV2VrfConfig) HasIpfixExporters() bool`

HasIpfixExporters returns a boolean if a field has been set.

### GetNatRuleset

`func (o *ManaV2VrfConfig) GetNatRuleset() ManaV2NullableNatPolicyRulesetName`

GetNatRuleset returns the NatRuleset field if non-nil, zero value otherwise.

### GetNatRulesetOk

`func (o *ManaV2VrfConfig) GetNatRulesetOk() (*ManaV2NullableNatPolicyRulesetName, bool)`

GetNatRulesetOk returns a tuple with the NatRuleset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNatRuleset

`func (o *ManaV2VrfConfig) SetNatRuleset(v ManaV2NullableNatPolicyRulesetName)`

SetNatRuleset sets NatRuleset field to given value.

### HasNatRuleset

`func (o *ManaV2VrfConfig) HasNatRuleset() bool`

HasNatRuleset returns a boolean if a field has been set.

### GetNetworks

`func (o *ManaV2VrfConfig) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *ManaV2VrfConfig) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *ManaV2VrfConfig) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *ManaV2VrfConfig) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetOspfv2

`func (o *ManaV2VrfConfig) GetOspfv2() ManaV2NullableOspfProcessConfig`

GetOspfv2 returns the Ospfv2 field if non-nil, zero value otherwise.

### GetOspfv2Ok

`func (o *ManaV2VrfConfig) GetOspfv2Ok() (*ManaV2NullableOspfProcessConfig, bool)`

GetOspfv2Ok returns a tuple with the Ospfv2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOspfv2

`func (o *ManaV2VrfConfig) SetOspfv2(v ManaV2NullableOspfProcessConfig)`

SetOspfv2 sets Ospfv2 field to given value.

### HasOspfv2

`func (o *ManaV2VrfConfig) HasOspfv2() bool`

HasOspfv2 returns a boolean if a field has been set.

### GetOspfv3

`func (o *ManaV2VrfConfig) GetOspfv3() ManaV2NullableOspfProcessConfig`

GetOspfv3 returns the Ospfv3 field if non-nil, zero value otherwise.

### GetOspfv3Ok

`func (o *ManaV2VrfConfig) GetOspfv3Ok() (*ManaV2NullableOspfProcessConfig, bool)`

GetOspfv3Ok returns a tuple with the Ospfv3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOspfv3

`func (o *ManaV2VrfConfig) SetOspfv3(v ManaV2NullableOspfProcessConfig)`

SetOspfv3 sets Ospfv3 field to given value.

### HasOspfv3

`func (o *ManaV2VrfConfig) HasOspfv3() bool`

HasOspfv3 returns a boolean if a field has been set.

### GetOverlayFilters

`func (o *ManaV2VrfConfig) GetOverlayFilters() ManaV2OverlayFilterConfig`

GetOverlayFilters returns the OverlayFilters field if non-nil, zero value otherwise.

### GetOverlayFiltersOk

`func (o *ManaV2VrfConfig) GetOverlayFiltersOk() (*ManaV2OverlayFilterConfig, bool)`

GetOverlayFiltersOk returns a tuple with the OverlayFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlayFilters

`func (o *ManaV2VrfConfig) SetOverlayFilters(v ManaV2OverlayFilterConfig)`

SetOverlayFilters sets OverlayFilters field to given value.

### HasOverlayFilters

`func (o *ManaV2VrfConfig) HasOverlayFilters() bool`

HasOverlayFilters returns a boolean if a field has been set.

### GetStaticRoutes

`func (o *ManaV2VrfConfig) GetStaticRoutes() map[string]ManaV2NullableStaticRouteConfig`

GetStaticRoutes returns the StaticRoutes field if non-nil, zero value otherwise.

### GetStaticRoutesOk

`func (o *ManaV2VrfConfig) GetStaticRoutesOk() (*map[string]ManaV2NullableStaticRouteConfig, bool)`

GetStaticRoutesOk returns a tuple with the StaticRoutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticRoutes

`func (o *ManaV2VrfConfig) SetStaticRoutes(v map[string]ManaV2NullableStaticRouteConfig)`

SetStaticRoutes sets StaticRoutes field to given value.

### HasStaticRoutes

`func (o *ManaV2VrfConfig) HasStaticRoutes() bool`

HasStaticRoutes returns a boolean if a field has been set.

### GetSyslogTargets

`func (o *ManaV2VrfConfig) GetSyslogTargets() map[string]ManaV2NullableSyslogCollectorConfig`

GetSyslogTargets returns the SyslogTargets field if non-nil, zero value otherwise.

### GetSyslogTargetsOk

`func (o *ManaV2VrfConfig) GetSyslogTargetsOk() (*map[string]ManaV2NullableSyslogCollectorConfig, bool)`

GetSyslogTargetsOk returns a tuple with the SyslogTargets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyslogTargets

`func (o *ManaV2VrfConfig) SetSyslogTargets(v map[string]ManaV2NullableSyslogCollectorConfig)`

SetSyslogTargets sets SyslogTargets field to given value.

### HasSyslogTargets

`func (o *ManaV2VrfConfig) HasSyslogTargets() bool`

HasSyslogTargets returns a boolean if a field has been set.

### GetTrafficRuleset

`func (o *ManaV2VrfConfig) GetTrafficRuleset() ManaV2NullableTrafficPolicyRulesetName`

GetTrafficRuleset returns the TrafficRuleset field if non-nil, zero value otherwise.

### GetTrafficRulesetOk

`func (o *ManaV2VrfConfig) GetTrafficRulesetOk() (*ManaV2NullableTrafficPolicyRulesetName, bool)`

GetTrafficRulesetOk returns a tuple with the TrafficRuleset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRuleset

`func (o *ManaV2VrfConfig) SetTrafficRuleset(v ManaV2NullableTrafficPolicyRulesetName)`

SetTrafficRuleset sets TrafficRuleset field to given value.

### HasTrafficRuleset

`func (o *ManaV2VrfConfig) HasTrafficRuleset() bool`

HasTrafficRuleset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



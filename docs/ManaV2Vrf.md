# ManaV2Vrf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpAggregations** | Pointer to [**[]ManaV2BgpAggregation**](ManaV2BgpAggregation.md) |  | [optional] 
**BgpMultipath** | Pointer to [**ManaV2BgpMultipath**](ManaV2BgpMultipath.md) |  | [optional] 
**BgpNeighbors** | Pointer to [**[]ManaV2BgpNeighbor**](ManaV2BgpNeighbor.md) |  | [optional] 
**BgpRedistributions** | Pointer to [**ManaV2BgpRedistribute**](ManaV2BgpRedistribute.md) |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DhcpSubnets** | Pointer to [**[]ManaV2DhcpServerPool**](ManaV2DhcpServerPool.md) |  | [optional] 
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**Function** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**IpfixExporters** | Pointer to [**[]ManaV2IpfixExporter**](ManaV2IpfixExporter.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NatRuleset** | Pointer to **string** |  | [optional] 
**Networks** | Pointer to **[]string** |  | [optional] 
**Ospfv2Process** | Pointer to [**ManaV2OspFv2Process**](ManaV2OspFv2Process.md) |  | [optional] 
**Ospfv3Process** | Pointer to [**ManaV2OspFv3Process**](ManaV2OspFv3Process.md) |  | [optional] 
**OverlayFilters** | Pointer to [**ManaV2OverlayFilters**](ManaV2OverlayFilters.md) |  | [optional] 
**Routable** | Pointer to **bool** |  | [optional] 
**RouteDistinguisher** | Pointer to **string** |  | [optional] 
**StaticRoutes** | Pointer to [**[]ManaV2StaticRoute**](ManaV2StaticRoute.md) |  | [optional] 
**SyslogTargets** | Pointer to [**[]ManaV2SyslogCollector**](ManaV2SyslogCollector.md) |  | [optional] 
**TrafficRuleset** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2Vrf

`func NewManaV2Vrf() *ManaV2Vrf`

NewManaV2Vrf instantiates a new ManaV2Vrf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2VrfWithDefaults

`func NewManaV2VrfWithDefaults() *ManaV2Vrf`

NewManaV2VrfWithDefaults instantiates a new ManaV2Vrf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpAggregations

`func (o *ManaV2Vrf) GetBgpAggregations() []ManaV2BgpAggregation`

GetBgpAggregations returns the BgpAggregations field if non-nil, zero value otherwise.

### GetBgpAggregationsOk

`func (o *ManaV2Vrf) GetBgpAggregationsOk() (*[]ManaV2BgpAggregation, bool)`

GetBgpAggregationsOk returns a tuple with the BgpAggregations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpAggregations

`func (o *ManaV2Vrf) SetBgpAggregations(v []ManaV2BgpAggregation)`

SetBgpAggregations sets BgpAggregations field to given value.

### HasBgpAggregations

`func (o *ManaV2Vrf) HasBgpAggregations() bool`

HasBgpAggregations returns a boolean if a field has been set.

### GetBgpMultipath

`func (o *ManaV2Vrf) GetBgpMultipath() ManaV2BgpMultipath`

GetBgpMultipath returns the BgpMultipath field if non-nil, zero value otherwise.

### GetBgpMultipathOk

`func (o *ManaV2Vrf) GetBgpMultipathOk() (*ManaV2BgpMultipath, bool)`

GetBgpMultipathOk returns a tuple with the BgpMultipath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpMultipath

`func (o *ManaV2Vrf) SetBgpMultipath(v ManaV2BgpMultipath)`

SetBgpMultipath sets BgpMultipath field to given value.

### HasBgpMultipath

`func (o *ManaV2Vrf) HasBgpMultipath() bool`

HasBgpMultipath returns a boolean if a field has been set.

### GetBgpNeighbors

`func (o *ManaV2Vrf) GetBgpNeighbors() []ManaV2BgpNeighbor`

GetBgpNeighbors returns the BgpNeighbors field if non-nil, zero value otherwise.

### GetBgpNeighborsOk

`func (o *ManaV2Vrf) GetBgpNeighborsOk() (*[]ManaV2BgpNeighbor, bool)`

GetBgpNeighborsOk returns a tuple with the BgpNeighbors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighbors

`func (o *ManaV2Vrf) SetBgpNeighbors(v []ManaV2BgpNeighbor)`

SetBgpNeighbors sets BgpNeighbors field to given value.

### HasBgpNeighbors

`func (o *ManaV2Vrf) HasBgpNeighbors() bool`

HasBgpNeighbors returns a boolean if a field has been set.

### GetBgpRedistributions

`func (o *ManaV2Vrf) GetBgpRedistributions() ManaV2BgpRedistribute`

GetBgpRedistributions returns the BgpRedistributions field if non-nil, zero value otherwise.

### GetBgpRedistributionsOk

`func (o *ManaV2Vrf) GetBgpRedistributionsOk() (*ManaV2BgpRedistribute, bool)`

GetBgpRedistributionsOk returns a tuple with the BgpRedistributions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpRedistributions

`func (o *ManaV2Vrf) SetBgpRedistributions(v ManaV2BgpRedistribute)`

SetBgpRedistributions sets BgpRedistributions field to given value.

### HasBgpRedistributions

`func (o *ManaV2Vrf) HasBgpRedistributions() bool`

HasBgpRedistributions returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2Vrf) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2Vrf) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2Vrf) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2Vrf) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDhcpSubnets

`func (o *ManaV2Vrf) GetDhcpSubnets() []ManaV2DhcpServerPool`

GetDhcpSubnets returns the DhcpSubnets field if non-nil, zero value otherwise.

### GetDhcpSubnetsOk

`func (o *ManaV2Vrf) GetDhcpSubnetsOk() (*[]ManaV2DhcpServerPool, bool)`

GetDhcpSubnetsOk returns a tuple with the DhcpSubnets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpSubnets

`func (o *ManaV2Vrf) SetDhcpSubnets(v []ManaV2DhcpServerPool)`

SetDhcpSubnets sets DhcpSubnets field to given value.

### HasDhcpSubnets

`func (o *ManaV2Vrf) HasDhcpSubnets() bool`

HasDhcpSubnets returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *ManaV2Vrf) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *ManaV2Vrf) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *ManaV2Vrf) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *ManaV2Vrf) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetFunction

`func (o *ManaV2Vrf) GetFunction() string`

GetFunction returns the Function field if non-nil, zero value otherwise.

### GetFunctionOk

`func (o *ManaV2Vrf) GetFunctionOk() (*string, bool)`

GetFunctionOk returns a tuple with the Function field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunction

`func (o *ManaV2Vrf) SetFunction(v string)`

SetFunction sets Function field to given value.

### HasFunction

`func (o *ManaV2Vrf) HasFunction() bool`

HasFunction returns a boolean if a field has been set.

### GetId

`func (o *ManaV2Vrf) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2Vrf) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2Vrf) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2Vrf) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIpfixExporters

`func (o *ManaV2Vrf) GetIpfixExporters() []ManaV2IpfixExporter`

GetIpfixExporters returns the IpfixExporters field if non-nil, zero value otherwise.

### GetIpfixExportersOk

`func (o *ManaV2Vrf) GetIpfixExportersOk() (*[]ManaV2IpfixExporter, bool)`

GetIpfixExportersOk returns a tuple with the IpfixExporters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpfixExporters

`func (o *ManaV2Vrf) SetIpfixExporters(v []ManaV2IpfixExporter)`

SetIpfixExporters sets IpfixExporters field to given value.

### HasIpfixExporters

`func (o *ManaV2Vrf) HasIpfixExporters() bool`

HasIpfixExporters returns a boolean if a field has been set.

### GetName

`func (o *ManaV2Vrf) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2Vrf) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2Vrf) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2Vrf) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNatRuleset

`func (o *ManaV2Vrf) GetNatRuleset() string`

GetNatRuleset returns the NatRuleset field if non-nil, zero value otherwise.

### GetNatRulesetOk

`func (o *ManaV2Vrf) GetNatRulesetOk() (*string, bool)`

GetNatRulesetOk returns a tuple with the NatRuleset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNatRuleset

`func (o *ManaV2Vrf) SetNatRuleset(v string)`

SetNatRuleset sets NatRuleset field to given value.

### HasNatRuleset

`func (o *ManaV2Vrf) HasNatRuleset() bool`

HasNatRuleset returns a boolean if a field has been set.

### GetNetworks

`func (o *ManaV2Vrf) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *ManaV2Vrf) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *ManaV2Vrf) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *ManaV2Vrf) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetOspfv2Process

`func (o *ManaV2Vrf) GetOspfv2Process() ManaV2OspFv2Process`

GetOspfv2Process returns the Ospfv2Process field if non-nil, zero value otherwise.

### GetOspfv2ProcessOk

`func (o *ManaV2Vrf) GetOspfv2ProcessOk() (*ManaV2OspFv2Process, bool)`

GetOspfv2ProcessOk returns a tuple with the Ospfv2Process field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOspfv2Process

`func (o *ManaV2Vrf) SetOspfv2Process(v ManaV2OspFv2Process)`

SetOspfv2Process sets Ospfv2Process field to given value.

### HasOspfv2Process

`func (o *ManaV2Vrf) HasOspfv2Process() bool`

HasOspfv2Process returns a boolean if a field has been set.

### GetOspfv3Process

`func (o *ManaV2Vrf) GetOspfv3Process() ManaV2OspFv3Process`

GetOspfv3Process returns the Ospfv3Process field if non-nil, zero value otherwise.

### GetOspfv3ProcessOk

`func (o *ManaV2Vrf) GetOspfv3ProcessOk() (*ManaV2OspFv3Process, bool)`

GetOspfv3ProcessOk returns a tuple with the Ospfv3Process field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOspfv3Process

`func (o *ManaV2Vrf) SetOspfv3Process(v ManaV2OspFv3Process)`

SetOspfv3Process sets Ospfv3Process field to given value.

### HasOspfv3Process

`func (o *ManaV2Vrf) HasOspfv3Process() bool`

HasOspfv3Process returns a boolean if a field has been set.

### GetOverlayFilters

`func (o *ManaV2Vrf) GetOverlayFilters() ManaV2OverlayFilters`

GetOverlayFilters returns the OverlayFilters field if non-nil, zero value otherwise.

### GetOverlayFiltersOk

`func (o *ManaV2Vrf) GetOverlayFiltersOk() (*ManaV2OverlayFilters, bool)`

GetOverlayFiltersOk returns a tuple with the OverlayFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlayFilters

`func (o *ManaV2Vrf) SetOverlayFilters(v ManaV2OverlayFilters)`

SetOverlayFilters sets OverlayFilters field to given value.

### HasOverlayFilters

`func (o *ManaV2Vrf) HasOverlayFilters() bool`

HasOverlayFilters returns a boolean if a field has been set.

### GetRoutable

`func (o *ManaV2Vrf) GetRoutable() bool`

GetRoutable returns the Routable field if non-nil, zero value otherwise.

### GetRoutableOk

`func (o *ManaV2Vrf) GetRoutableOk() (*bool, bool)`

GetRoutableOk returns a tuple with the Routable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutable

`func (o *ManaV2Vrf) SetRoutable(v bool)`

SetRoutable sets Routable field to given value.

### HasRoutable

`func (o *ManaV2Vrf) HasRoutable() bool`

HasRoutable returns a boolean if a field has been set.

### GetRouteDistinguisher

`func (o *ManaV2Vrf) GetRouteDistinguisher() string`

GetRouteDistinguisher returns the RouteDistinguisher field if non-nil, zero value otherwise.

### GetRouteDistinguisherOk

`func (o *ManaV2Vrf) GetRouteDistinguisherOk() (*string, bool)`

GetRouteDistinguisherOk returns a tuple with the RouteDistinguisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteDistinguisher

`func (o *ManaV2Vrf) SetRouteDistinguisher(v string)`

SetRouteDistinguisher sets RouteDistinguisher field to given value.

### HasRouteDistinguisher

`func (o *ManaV2Vrf) HasRouteDistinguisher() bool`

HasRouteDistinguisher returns a boolean if a field has been set.

### GetStaticRoutes

`func (o *ManaV2Vrf) GetStaticRoutes() []ManaV2StaticRoute`

GetStaticRoutes returns the StaticRoutes field if non-nil, zero value otherwise.

### GetStaticRoutesOk

`func (o *ManaV2Vrf) GetStaticRoutesOk() (*[]ManaV2StaticRoute, bool)`

GetStaticRoutesOk returns a tuple with the StaticRoutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticRoutes

`func (o *ManaV2Vrf) SetStaticRoutes(v []ManaV2StaticRoute)`

SetStaticRoutes sets StaticRoutes field to given value.

### HasStaticRoutes

`func (o *ManaV2Vrf) HasStaticRoutes() bool`

HasStaticRoutes returns a boolean if a field has been set.

### GetSyslogTargets

`func (o *ManaV2Vrf) GetSyslogTargets() []ManaV2SyslogCollector`

GetSyslogTargets returns the SyslogTargets field if non-nil, zero value otherwise.

### GetSyslogTargetsOk

`func (o *ManaV2Vrf) GetSyslogTargetsOk() (*[]ManaV2SyslogCollector, bool)`

GetSyslogTargetsOk returns a tuple with the SyslogTargets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyslogTargets

`func (o *ManaV2Vrf) SetSyslogTargets(v []ManaV2SyslogCollector)`

SetSyslogTargets sets SyslogTargets field to given value.

### HasSyslogTargets

`func (o *ManaV2Vrf) HasSyslogTargets() bool`

HasSyslogTargets returns a boolean if a field has been set.

### GetTrafficRuleset

`func (o *ManaV2Vrf) GetTrafficRuleset() string`

GetTrafficRuleset returns the TrafficRuleset field if non-nil, zero value otherwise.

### GetTrafficRulesetOk

`func (o *ManaV2Vrf) GetTrafficRulesetOk() (*string, bool)`

GetTrafficRulesetOk returns a tuple with the TrafficRuleset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRuleset

`func (o *ManaV2Vrf) SetTrafficRuleset(v string)`

SetTrafficRuleset sets TrafficRuleset field to given value.

### HasTrafficRuleset

`func (o *ManaV2Vrf) HasTrafficRuleset() bool`

HasTrafficRuleset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



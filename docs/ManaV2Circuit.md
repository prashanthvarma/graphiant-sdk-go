# ManaV2Circuit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpAggregations** | Pointer to [**[]ManaV2BgpAggregation**](ManaV2BgpAggregation.md) |  | [optional] 
**BgpMultipath** | Pointer to [**ManaV2BgpMultipath**](ManaV2BgpMultipath.md) |  | [optional] 
**BgpNeighbors** | Pointer to [**[]ManaV2BgpNeighbor**](ManaV2BgpNeighbor.md) |  | [optional] 
**BgpRedistributions** | Pointer to [**ManaV2BgpRedistribute**](ManaV2BgpRedistribute.md) |  | [optional] 
**Carrier** | Pointer to **string** |  | [optional] 
**CircuitType** | Pointer to **string** |  | [optional] 
**ConnectionType** | Pointer to **string** |  | [optional] 
**CoreLogicalInterfacesV2** | Pointer to [**[]ManaV2CircuitInterface**](ManaV2CircuitInterface.md) |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DiaEnabled** | Pointer to **bool** |  | [optional] 
**DiaSnmpIndex** | Pointer to **int64** |  | [optional] 
**DiscoveredPublicIp** | Pointer to **string** |  | [optional] 
**DropMechanism** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**InterfaceName** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**LastResort** | Pointer to **bool** |  | [optional] 
**LinkDownSpeedMbps** | Pointer to **int32** |  | [optional] 
**LinkUpSpeedMbps** | Pointer to **int32** |  | [optional] 
**Loopback** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PatAddresses** | Pointer to **[]string** |  | [optional] 
**PrivateIp** | Pointer to **string** |  | [optional] 
**Profile** | Pointer to [**ManaV2QoSProfile**](ManaV2QoSProfile.md) |  | [optional] 
**QosProfile** | Pointer to **string** |  | [optional] 
**QosProfileType** | Pointer to **string** |  | [optional] 
**SnmpIndex** | Pointer to **int64** |  | [optional] 
**StaticRoutes** | Pointer to [**[]ManaV2StaticRoute**](ManaV2StaticRoute.md) |  | [optional] 
**WanInterfaceV2** | Pointer to [**ManaV2CircuitInterface**](ManaV2CircuitInterface.md) |  | [optional] 

## Methods

### NewManaV2Circuit

`func NewManaV2Circuit() *ManaV2Circuit`

NewManaV2Circuit instantiates a new ManaV2Circuit object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2CircuitWithDefaults

`func NewManaV2CircuitWithDefaults() *ManaV2Circuit`

NewManaV2CircuitWithDefaults instantiates a new ManaV2Circuit object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpAggregations

`func (o *ManaV2Circuit) GetBgpAggregations() []ManaV2BgpAggregation`

GetBgpAggregations returns the BgpAggregations field if non-nil, zero value otherwise.

### GetBgpAggregationsOk

`func (o *ManaV2Circuit) GetBgpAggregationsOk() (*[]ManaV2BgpAggregation, bool)`

GetBgpAggregationsOk returns a tuple with the BgpAggregations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpAggregations

`func (o *ManaV2Circuit) SetBgpAggregations(v []ManaV2BgpAggregation)`

SetBgpAggregations sets BgpAggregations field to given value.

### HasBgpAggregations

`func (o *ManaV2Circuit) HasBgpAggregations() bool`

HasBgpAggregations returns a boolean if a field has been set.

### GetBgpMultipath

`func (o *ManaV2Circuit) GetBgpMultipath() ManaV2BgpMultipath`

GetBgpMultipath returns the BgpMultipath field if non-nil, zero value otherwise.

### GetBgpMultipathOk

`func (o *ManaV2Circuit) GetBgpMultipathOk() (*ManaV2BgpMultipath, bool)`

GetBgpMultipathOk returns a tuple with the BgpMultipath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpMultipath

`func (o *ManaV2Circuit) SetBgpMultipath(v ManaV2BgpMultipath)`

SetBgpMultipath sets BgpMultipath field to given value.

### HasBgpMultipath

`func (o *ManaV2Circuit) HasBgpMultipath() bool`

HasBgpMultipath returns a boolean if a field has been set.

### GetBgpNeighbors

`func (o *ManaV2Circuit) GetBgpNeighbors() []ManaV2BgpNeighbor`

GetBgpNeighbors returns the BgpNeighbors field if non-nil, zero value otherwise.

### GetBgpNeighborsOk

`func (o *ManaV2Circuit) GetBgpNeighborsOk() (*[]ManaV2BgpNeighbor, bool)`

GetBgpNeighborsOk returns a tuple with the BgpNeighbors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighbors

`func (o *ManaV2Circuit) SetBgpNeighbors(v []ManaV2BgpNeighbor)`

SetBgpNeighbors sets BgpNeighbors field to given value.

### HasBgpNeighbors

`func (o *ManaV2Circuit) HasBgpNeighbors() bool`

HasBgpNeighbors returns a boolean if a field has been set.

### GetBgpRedistributions

`func (o *ManaV2Circuit) GetBgpRedistributions() ManaV2BgpRedistribute`

GetBgpRedistributions returns the BgpRedistributions field if non-nil, zero value otherwise.

### GetBgpRedistributionsOk

`func (o *ManaV2Circuit) GetBgpRedistributionsOk() (*ManaV2BgpRedistribute, bool)`

GetBgpRedistributionsOk returns a tuple with the BgpRedistributions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpRedistributions

`func (o *ManaV2Circuit) SetBgpRedistributions(v ManaV2BgpRedistribute)`

SetBgpRedistributions sets BgpRedistributions field to given value.

### HasBgpRedistributions

`func (o *ManaV2Circuit) HasBgpRedistributions() bool`

HasBgpRedistributions returns a boolean if a field has been set.

### GetCarrier

`func (o *ManaV2Circuit) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ManaV2Circuit) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ManaV2Circuit) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *ManaV2Circuit) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetCircuitType

`func (o *ManaV2Circuit) GetCircuitType() string`

GetCircuitType returns the CircuitType field if non-nil, zero value otherwise.

### GetCircuitTypeOk

`func (o *ManaV2Circuit) GetCircuitTypeOk() (*string, bool)`

GetCircuitTypeOk returns a tuple with the CircuitType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitType

`func (o *ManaV2Circuit) SetCircuitType(v string)`

SetCircuitType sets CircuitType field to given value.

### HasCircuitType

`func (o *ManaV2Circuit) HasCircuitType() bool`

HasCircuitType returns a boolean if a field has been set.

### GetConnectionType

`func (o *ManaV2Circuit) GetConnectionType() string`

GetConnectionType returns the ConnectionType field if non-nil, zero value otherwise.

### GetConnectionTypeOk

`func (o *ManaV2Circuit) GetConnectionTypeOk() (*string, bool)`

GetConnectionTypeOk returns a tuple with the ConnectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionType

`func (o *ManaV2Circuit) SetConnectionType(v string)`

SetConnectionType sets ConnectionType field to given value.

### HasConnectionType

`func (o *ManaV2Circuit) HasConnectionType() bool`

HasConnectionType returns a boolean if a field has been set.

### GetCoreLogicalInterfacesV2

`func (o *ManaV2Circuit) GetCoreLogicalInterfacesV2() []ManaV2CircuitInterface`

GetCoreLogicalInterfacesV2 returns the CoreLogicalInterfacesV2 field if non-nil, zero value otherwise.

### GetCoreLogicalInterfacesV2Ok

`func (o *ManaV2Circuit) GetCoreLogicalInterfacesV2Ok() (*[]ManaV2CircuitInterface, bool)`

GetCoreLogicalInterfacesV2Ok returns a tuple with the CoreLogicalInterfacesV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreLogicalInterfacesV2

`func (o *ManaV2Circuit) SetCoreLogicalInterfacesV2(v []ManaV2CircuitInterface)`

SetCoreLogicalInterfacesV2 sets CoreLogicalInterfacesV2 field to given value.

### HasCoreLogicalInterfacesV2

`func (o *ManaV2Circuit) HasCoreLogicalInterfacesV2() bool`

HasCoreLogicalInterfacesV2 returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2Circuit) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2Circuit) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2Circuit) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2Circuit) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDiaEnabled

`func (o *ManaV2Circuit) GetDiaEnabled() bool`

GetDiaEnabled returns the DiaEnabled field if non-nil, zero value otherwise.

### GetDiaEnabledOk

`func (o *ManaV2Circuit) GetDiaEnabledOk() (*bool, bool)`

GetDiaEnabledOk returns a tuple with the DiaEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiaEnabled

`func (o *ManaV2Circuit) SetDiaEnabled(v bool)`

SetDiaEnabled sets DiaEnabled field to given value.

### HasDiaEnabled

`func (o *ManaV2Circuit) HasDiaEnabled() bool`

HasDiaEnabled returns a boolean if a field has been set.

### GetDiaSnmpIndex

`func (o *ManaV2Circuit) GetDiaSnmpIndex() int64`

GetDiaSnmpIndex returns the DiaSnmpIndex field if non-nil, zero value otherwise.

### GetDiaSnmpIndexOk

`func (o *ManaV2Circuit) GetDiaSnmpIndexOk() (*int64, bool)`

GetDiaSnmpIndexOk returns a tuple with the DiaSnmpIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiaSnmpIndex

`func (o *ManaV2Circuit) SetDiaSnmpIndex(v int64)`

SetDiaSnmpIndex sets DiaSnmpIndex field to given value.

### HasDiaSnmpIndex

`func (o *ManaV2Circuit) HasDiaSnmpIndex() bool`

HasDiaSnmpIndex returns a boolean if a field has been set.

### GetDiscoveredPublicIp

`func (o *ManaV2Circuit) GetDiscoveredPublicIp() string`

GetDiscoveredPublicIp returns the DiscoveredPublicIp field if non-nil, zero value otherwise.

### GetDiscoveredPublicIpOk

`func (o *ManaV2Circuit) GetDiscoveredPublicIpOk() (*string, bool)`

GetDiscoveredPublicIpOk returns a tuple with the DiscoveredPublicIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredPublicIp

`func (o *ManaV2Circuit) SetDiscoveredPublicIp(v string)`

SetDiscoveredPublicIp sets DiscoveredPublicIp field to given value.

### HasDiscoveredPublicIp

`func (o *ManaV2Circuit) HasDiscoveredPublicIp() bool`

HasDiscoveredPublicIp returns a boolean if a field has been set.

### GetDropMechanism

`func (o *ManaV2Circuit) GetDropMechanism() string`

GetDropMechanism returns the DropMechanism field if non-nil, zero value otherwise.

### GetDropMechanismOk

`func (o *ManaV2Circuit) GetDropMechanismOk() (*string, bool)`

GetDropMechanismOk returns a tuple with the DropMechanism field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropMechanism

`func (o *ManaV2Circuit) SetDropMechanism(v string)`

SetDropMechanism sets DropMechanism field to given value.

### HasDropMechanism

`func (o *ManaV2Circuit) HasDropMechanism() bool`

HasDropMechanism returns a boolean if a field has been set.

### GetId

`func (o *ManaV2Circuit) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2Circuit) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2Circuit) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2Circuit) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInterfaceName

`func (o *ManaV2Circuit) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *ManaV2Circuit) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *ManaV2Circuit) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *ManaV2Circuit) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.

### GetLabel

`func (o *ManaV2Circuit) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ManaV2Circuit) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ManaV2Circuit) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ManaV2Circuit) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetLastResort

`func (o *ManaV2Circuit) GetLastResort() bool`

GetLastResort returns the LastResort field if non-nil, zero value otherwise.

### GetLastResortOk

`func (o *ManaV2Circuit) GetLastResortOk() (*bool, bool)`

GetLastResortOk returns a tuple with the LastResort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastResort

`func (o *ManaV2Circuit) SetLastResort(v bool)`

SetLastResort sets LastResort field to given value.

### HasLastResort

`func (o *ManaV2Circuit) HasLastResort() bool`

HasLastResort returns a boolean if a field has been set.

### GetLinkDownSpeedMbps

`func (o *ManaV2Circuit) GetLinkDownSpeedMbps() int32`

GetLinkDownSpeedMbps returns the LinkDownSpeedMbps field if non-nil, zero value otherwise.

### GetLinkDownSpeedMbpsOk

`func (o *ManaV2Circuit) GetLinkDownSpeedMbpsOk() (*int32, bool)`

GetLinkDownSpeedMbpsOk returns a tuple with the LinkDownSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkDownSpeedMbps

`func (o *ManaV2Circuit) SetLinkDownSpeedMbps(v int32)`

SetLinkDownSpeedMbps sets LinkDownSpeedMbps field to given value.

### HasLinkDownSpeedMbps

`func (o *ManaV2Circuit) HasLinkDownSpeedMbps() bool`

HasLinkDownSpeedMbps returns a boolean if a field has been set.

### GetLinkUpSpeedMbps

`func (o *ManaV2Circuit) GetLinkUpSpeedMbps() int32`

GetLinkUpSpeedMbps returns the LinkUpSpeedMbps field if non-nil, zero value otherwise.

### GetLinkUpSpeedMbpsOk

`func (o *ManaV2Circuit) GetLinkUpSpeedMbpsOk() (*int32, bool)`

GetLinkUpSpeedMbpsOk returns a tuple with the LinkUpSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkUpSpeedMbps

`func (o *ManaV2Circuit) SetLinkUpSpeedMbps(v int32)`

SetLinkUpSpeedMbps sets LinkUpSpeedMbps field to given value.

### HasLinkUpSpeedMbps

`func (o *ManaV2Circuit) HasLinkUpSpeedMbps() bool`

HasLinkUpSpeedMbps returns a boolean if a field has been set.

### GetLoopback

`func (o *ManaV2Circuit) GetLoopback() bool`

GetLoopback returns the Loopback field if non-nil, zero value otherwise.

### GetLoopbackOk

`func (o *ManaV2Circuit) GetLoopbackOk() (*bool, bool)`

GetLoopbackOk returns a tuple with the Loopback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoopback

`func (o *ManaV2Circuit) SetLoopback(v bool)`

SetLoopback sets Loopback field to given value.

### HasLoopback

`func (o *ManaV2Circuit) HasLoopback() bool`

HasLoopback returns a boolean if a field has been set.

### GetName

`func (o *ManaV2Circuit) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2Circuit) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2Circuit) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2Circuit) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPatAddresses

`func (o *ManaV2Circuit) GetPatAddresses() []string`

GetPatAddresses returns the PatAddresses field if non-nil, zero value otherwise.

### GetPatAddressesOk

`func (o *ManaV2Circuit) GetPatAddressesOk() (*[]string, bool)`

GetPatAddressesOk returns a tuple with the PatAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatAddresses

`func (o *ManaV2Circuit) SetPatAddresses(v []string)`

SetPatAddresses sets PatAddresses field to given value.

### HasPatAddresses

`func (o *ManaV2Circuit) HasPatAddresses() bool`

HasPatAddresses returns a boolean if a field has been set.

### GetPrivateIp

`func (o *ManaV2Circuit) GetPrivateIp() string`

GetPrivateIp returns the PrivateIp field if non-nil, zero value otherwise.

### GetPrivateIpOk

`func (o *ManaV2Circuit) GetPrivateIpOk() (*string, bool)`

GetPrivateIpOk returns a tuple with the PrivateIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateIp

`func (o *ManaV2Circuit) SetPrivateIp(v string)`

SetPrivateIp sets PrivateIp field to given value.

### HasPrivateIp

`func (o *ManaV2Circuit) HasPrivateIp() bool`

HasPrivateIp returns a boolean if a field has been set.

### GetProfile

`func (o *ManaV2Circuit) GetProfile() ManaV2QoSProfile`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *ManaV2Circuit) GetProfileOk() (*ManaV2QoSProfile, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *ManaV2Circuit) SetProfile(v ManaV2QoSProfile)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *ManaV2Circuit) HasProfile() bool`

HasProfile returns a boolean if a field has been set.

### GetQosProfile

`func (o *ManaV2Circuit) GetQosProfile() string`

GetQosProfile returns the QosProfile field if non-nil, zero value otherwise.

### GetQosProfileOk

`func (o *ManaV2Circuit) GetQosProfileOk() (*string, bool)`

GetQosProfileOk returns a tuple with the QosProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQosProfile

`func (o *ManaV2Circuit) SetQosProfile(v string)`

SetQosProfile sets QosProfile field to given value.

### HasQosProfile

`func (o *ManaV2Circuit) HasQosProfile() bool`

HasQosProfile returns a boolean if a field has been set.

### GetQosProfileType

`func (o *ManaV2Circuit) GetQosProfileType() string`

GetQosProfileType returns the QosProfileType field if non-nil, zero value otherwise.

### GetQosProfileTypeOk

`func (o *ManaV2Circuit) GetQosProfileTypeOk() (*string, bool)`

GetQosProfileTypeOk returns a tuple with the QosProfileType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQosProfileType

`func (o *ManaV2Circuit) SetQosProfileType(v string)`

SetQosProfileType sets QosProfileType field to given value.

### HasQosProfileType

`func (o *ManaV2Circuit) HasQosProfileType() bool`

HasQosProfileType returns a boolean if a field has been set.

### GetSnmpIndex

`func (o *ManaV2Circuit) GetSnmpIndex() int64`

GetSnmpIndex returns the SnmpIndex field if non-nil, zero value otherwise.

### GetSnmpIndexOk

`func (o *ManaV2Circuit) GetSnmpIndexOk() (*int64, bool)`

GetSnmpIndexOk returns a tuple with the SnmpIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnmpIndex

`func (o *ManaV2Circuit) SetSnmpIndex(v int64)`

SetSnmpIndex sets SnmpIndex field to given value.

### HasSnmpIndex

`func (o *ManaV2Circuit) HasSnmpIndex() bool`

HasSnmpIndex returns a boolean if a field has been set.

### GetStaticRoutes

`func (o *ManaV2Circuit) GetStaticRoutes() []ManaV2StaticRoute`

GetStaticRoutes returns the StaticRoutes field if non-nil, zero value otherwise.

### GetStaticRoutesOk

`func (o *ManaV2Circuit) GetStaticRoutesOk() (*[]ManaV2StaticRoute, bool)`

GetStaticRoutesOk returns a tuple with the StaticRoutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticRoutes

`func (o *ManaV2Circuit) SetStaticRoutes(v []ManaV2StaticRoute)`

SetStaticRoutes sets StaticRoutes field to given value.

### HasStaticRoutes

`func (o *ManaV2Circuit) HasStaticRoutes() bool`

HasStaticRoutes returns a boolean if a field has been set.

### GetWanInterfaceV2

`func (o *ManaV2Circuit) GetWanInterfaceV2() ManaV2CircuitInterface`

GetWanInterfaceV2 returns the WanInterfaceV2 field if non-nil, zero value otherwise.

### GetWanInterfaceV2Ok

`func (o *ManaV2Circuit) GetWanInterfaceV2Ok() (*ManaV2CircuitInterface, bool)`

GetWanInterfaceV2Ok returns a tuple with the WanInterfaceV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanInterfaceV2

`func (o *ManaV2Circuit) SetWanInterfaceV2(v ManaV2CircuitInterface)`

SetWanInterfaceV2 sets WanInterfaceV2 field to given value.

### HasWanInterfaceV2

`func (o *ManaV2Circuit) HasWanInterfaceV2() bool`

HasWanInterfaceV2 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



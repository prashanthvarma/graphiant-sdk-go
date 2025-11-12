# ManaV2CircuitConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpAggregations** | Pointer to [**map[string]ManaV2NullableBgpAggregationsConfig**](ManaV2NullableBgpAggregationsConfig.md) |  | [optional] 
**BgpMultipath** | Pointer to [**ManaV2NullableBgpMultipathConfig**](ManaV2NullableBgpMultipathConfig.md) |  | [optional] 
**BgpNeighbors** | Pointer to [**map[string]ManaV2NullableBgpNeighborConfig**](ManaV2NullableBgpNeighborConfig.md) |  | [optional] 
**BgpRedistribution** | Pointer to [**map[string]ManaV2NullableBgpRedistributeProtocolConfig**](ManaV2NullableBgpRedistributeProtocolConfig.md) |  | [optional] 
**Carrier** | Pointer to **string** |  | [optional] 
**CircuitType** | Pointer to **string** |  | [optional] 
**ConnectionType** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DiaEnabled** | Pointer to **bool** |  | [optional] 
**DropMechanism** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**LastResort** | Pointer to **bool** |  | [optional] 
**LinkDownSpeedMbps** | Pointer to **int32** |  | [optional] 
**LinkUpSpeedMbps** | Pointer to **int32** |  | [optional] 
**Loopback** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PatAddresses** | Pointer to [**ManaV2NullableIpList**](ManaV2NullableIpList.md) |  | [optional] 
**QosProfile** | Pointer to **string** |  | [optional] 
**QosProfileType** | Pointer to **string** |  | [optional] 
**StaticRoutes** | Pointer to [**map[string]ManaV2NullableStaticRouteConfig**](ManaV2NullableStaticRouteConfig.md) |  | [optional] 

## Methods

### NewManaV2CircuitConfig

`func NewManaV2CircuitConfig() *ManaV2CircuitConfig`

NewManaV2CircuitConfig instantiates a new ManaV2CircuitConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2CircuitConfigWithDefaults

`func NewManaV2CircuitConfigWithDefaults() *ManaV2CircuitConfig`

NewManaV2CircuitConfigWithDefaults instantiates a new ManaV2CircuitConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpAggregations

`func (o *ManaV2CircuitConfig) GetBgpAggregations() map[string]ManaV2NullableBgpAggregationsConfig`

GetBgpAggregations returns the BgpAggregations field if non-nil, zero value otherwise.

### GetBgpAggregationsOk

`func (o *ManaV2CircuitConfig) GetBgpAggregationsOk() (*map[string]ManaV2NullableBgpAggregationsConfig, bool)`

GetBgpAggregationsOk returns a tuple with the BgpAggregations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpAggregations

`func (o *ManaV2CircuitConfig) SetBgpAggregations(v map[string]ManaV2NullableBgpAggregationsConfig)`

SetBgpAggregations sets BgpAggregations field to given value.

### HasBgpAggregations

`func (o *ManaV2CircuitConfig) HasBgpAggregations() bool`

HasBgpAggregations returns a boolean if a field has been set.

### GetBgpMultipath

`func (o *ManaV2CircuitConfig) GetBgpMultipath() ManaV2NullableBgpMultipathConfig`

GetBgpMultipath returns the BgpMultipath field if non-nil, zero value otherwise.

### GetBgpMultipathOk

`func (o *ManaV2CircuitConfig) GetBgpMultipathOk() (*ManaV2NullableBgpMultipathConfig, bool)`

GetBgpMultipathOk returns a tuple with the BgpMultipath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpMultipath

`func (o *ManaV2CircuitConfig) SetBgpMultipath(v ManaV2NullableBgpMultipathConfig)`

SetBgpMultipath sets BgpMultipath field to given value.

### HasBgpMultipath

`func (o *ManaV2CircuitConfig) HasBgpMultipath() bool`

HasBgpMultipath returns a boolean if a field has been set.

### GetBgpNeighbors

`func (o *ManaV2CircuitConfig) GetBgpNeighbors() map[string]ManaV2NullableBgpNeighborConfig`

GetBgpNeighbors returns the BgpNeighbors field if non-nil, zero value otherwise.

### GetBgpNeighborsOk

`func (o *ManaV2CircuitConfig) GetBgpNeighborsOk() (*map[string]ManaV2NullableBgpNeighborConfig, bool)`

GetBgpNeighborsOk returns a tuple with the BgpNeighbors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighbors

`func (o *ManaV2CircuitConfig) SetBgpNeighbors(v map[string]ManaV2NullableBgpNeighborConfig)`

SetBgpNeighbors sets BgpNeighbors field to given value.

### HasBgpNeighbors

`func (o *ManaV2CircuitConfig) HasBgpNeighbors() bool`

HasBgpNeighbors returns a boolean if a field has been set.

### GetBgpRedistribution

`func (o *ManaV2CircuitConfig) GetBgpRedistribution() map[string]ManaV2NullableBgpRedistributeProtocolConfig`

GetBgpRedistribution returns the BgpRedistribution field if non-nil, zero value otherwise.

### GetBgpRedistributionOk

`func (o *ManaV2CircuitConfig) GetBgpRedistributionOk() (*map[string]ManaV2NullableBgpRedistributeProtocolConfig, bool)`

GetBgpRedistributionOk returns a tuple with the BgpRedistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpRedistribution

`func (o *ManaV2CircuitConfig) SetBgpRedistribution(v map[string]ManaV2NullableBgpRedistributeProtocolConfig)`

SetBgpRedistribution sets BgpRedistribution field to given value.

### HasBgpRedistribution

`func (o *ManaV2CircuitConfig) HasBgpRedistribution() bool`

HasBgpRedistribution returns a boolean if a field has been set.

### GetCarrier

`func (o *ManaV2CircuitConfig) GetCarrier() string`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ManaV2CircuitConfig) GetCarrierOk() (*string, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ManaV2CircuitConfig) SetCarrier(v string)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *ManaV2CircuitConfig) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetCircuitType

`func (o *ManaV2CircuitConfig) GetCircuitType() string`

GetCircuitType returns the CircuitType field if non-nil, zero value otherwise.

### GetCircuitTypeOk

`func (o *ManaV2CircuitConfig) GetCircuitTypeOk() (*string, bool)`

GetCircuitTypeOk returns a tuple with the CircuitType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitType

`func (o *ManaV2CircuitConfig) SetCircuitType(v string)`

SetCircuitType sets CircuitType field to given value.

### HasCircuitType

`func (o *ManaV2CircuitConfig) HasCircuitType() bool`

HasCircuitType returns a boolean if a field has been set.

### GetConnectionType

`func (o *ManaV2CircuitConfig) GetConnectionType() string`

GetConnectionType returns the ConnectionType field if non-nil, zero value otherwise.

### GetConnectionTypeOk

`func (o *ManaV2CircuitConfig) GetConnectionTypeOk() (*string, bool)`

GetConnectionTypeOk returns a tuple with the ConnectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionType

`func (o *ManaV2CircuitConfig) SetConnectionType(v string)`

SetConnectionType sets ConnectionType field to given value.

### HasConnectionType

`func (o *ManaV2CircuitConfig) HasConnectionType() bool`

HasConnectionType returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2CircuitConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2CircuitConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2CircuitConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2CircuitConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDiaEnabled

`func (o *ManaV2CircuitConfig) GetDiaEnabled() bool`

GetDiaEnabled returns the DiaEnabled field if non-nil, zero value otherwise.

### GetDiaEnabledOk

`func (o *ManaV2CircuitConfig) GetDiaEnabledOk() (*bool, bool)`

GetDiaEnabledOk returns a tuple with the DiaEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiaEnabled

`func (o *ManaV2CircuitConfig) SetDiaEnabled(v bool)`

SetDiaEnabled sets DiaEnabled field to given value.

### HasDiaEnabled

`func (o *ManaV2CircuitConfig) HasDiaEnabled() bool`

HasDiaEnabled returns a boolean if a field has been set.

### GetDropMechanism

`func (o *ManaV2CircuitConfig) GetDropMechanism() string`

GetDropMechanism returns the DropMechanism field if non-nil, zero value otherwise.

### GetDropMechanismOk

`func (o *ManaV2CircuitConfig) GetDropMechanismOk() (*string, bool)`

GetDropMechanismOk returns a tuple with the DropMechanism field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDropMechanism

`func (o *ManaV2CircuitConfig) SetDropMechanism(v string)`

SetDropMechanism sets DropMechanism field to given value.

### HasDropMechanism

`func (o *ManaV2CircuitConfig) HasDropMechanism() bool`

HasDropMechanism returns a boolean if a field has been set.

### GetLabel

`func (o *ManaV2CircuitConfig) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ManaV2CircuitConfig) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ManaV2CircuitConfig) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ManaV2CircuitConfig) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetLastResort

`func (o *ManaV2CircuitConfig) GetLastResort() bool`

GetLastResort returns the LastResort field if non-nil, zero value otherwise.

### GetLastResortOk

`func (o *ManaV2CircuitConfig) GetLastResortOk() (*bool, bool)`

GetLastResortOk returns a tuple with the LastResort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastResort

`func (o *ManaV2CircuitConfig) SetLastResort(v bool)`

SetLastResort sets LastResort field to given value.

### HasLastResort

`func (o *ManaV2CircuitConfig) HasLastResort() bool`

HasLastResort returns a boolean if a field has been set.

### GetLinkDownSpeedMbps

`func (o *ManaV2CircuitConfig) GetLinkDownSpeedMbps() int32`

GetLinkDownSpeedMbps returns the LinkDownSpeedMbps field if non-nil, zero value otherwise.

### GetLinkDownSpeedMbpsOk

`func (o *ManaV2CircuitConfig) GetLinkDownSpeedMbpsOk() (*int32, bool)`

GetLinkDownSpeedMbpsOk returns a tuple with the LinkDownSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkDownSpeedMbps

`func (o *ManaV2CircuitConfig) SetLinkDownSpeedMbps(v int32)`

SetLinkDownSpeedMbps sets LinkDownSpeedMbps field to given value.

### HasLinkDownSpeedMbps

`func (o *ManaV2CircuitConfig) HasLinkDownSpeedMbps() bool`

HasLinkDownSpeedMbps returns a boolean if a field has been set.

### GetLinkUpSpeedMbps

`func (o *ManaV2CircuitConfig) GetLinkUpSpeedMbps() int32`

GetLinkUpSpeedMbps returns the LinkUpSpeedMbps field if non-nil, zero value otherwise.

### GetLinkUpSpeedMbpsOk

`func (o *ManaV2CircuitConfig) GetLinkUpSpeedMbpsOk() (*int32, bool)`

GetLinkUpSpeedMbpsOk returns a tuple with the LinkUpSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkUpSpeedMbps

`func (o *ManaV2CircuitConfig) SetLinkUpSpeedMbps(v int32)`

SetLinkUpSpeedMbps sets LinkUpSpeedMbps field to given value.

### HasLinkUpSpeedMbps

`func (o *ManaV2CircuitConfig) HasLinkUpSpeedMbps() bool`

HasLinkUpSpeedMbps returns a boolean if a field has been set.

### GetLoopback

`func (o *ManaV2CircuitConfig) GetLoopback() bool`

GetLoopback returns the Loopback field if non-nil, zero value otherwise.

### GetLoopbackOk

`func (o *ManaV2CircuitConfig) GetLoopbackOk() (*bool, bool)`

GetLoopbackOk returns a tuple with the Loopback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoopback

`func (o *ManaV2CircuitConfig) SetLoopback(v bool)`

SetLoopback sets Loopback field to given value.

### HasLoopback

`func (o *ManaV2CircuitConfig) HasLoopback() bool`

HasLoopback returns a boolean if a field has been set.

### GetName

`func (o *ManaV2CircuitConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2CircuitConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2CircuitConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2CircuitConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPatAddresses

`func (o *ManaV2CircuitConfig) GetPatAddresses() ManaV2NullableIpList`

GetPatAddresses returns the PatAddresses field if non-nil, zero value otherwise.

### GetPatAddressesOk

`func (o *ManaV2CircuitConfig) GetPatAddressesOk() (*ManaV2NullableIpList, bool)`

GetPatAddressesOk returns a tuple with the PatAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatAddresses

`func (o *ManaV2CircuitConfig) SetPatAddresses(v ManaV2NullableIpList)`

SetPatAddresses sets PatAddresses field to given value.

### HasPatAddresses

`func (o *ManaV2CircuitConfig) HasPatAddresses() bool`

HasPatAddresses returns a boolean if a field has been set.

### GetQosProfile

`func (o *ManaV2CircuitConfig) GetQosProfile() string`

GetQosProfile returns the QosProfile field if non-nil, zero value otherwise.

### GetQosProfileOk

`func (o *ManaV2CircuitConfig) GetQosProfileOk() (*string, bool)`

GetQosProfileOk returns a tuple with the QosProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQosProfile

`func (o *ManaV2CircuitConfig) SetQosProfile(v string)`

SetQosProfile sets QosProfile field to given value.

### HasQosProfile

`func (o *ManaV2CircuitConfig) HasQosProfile() bool`

HasQosProfile returns a boolean if a field has been set.

### GetQosProfileType

`func (o *ManaV2CircuitConfig) GetQosProfileType() string`

GetQosProfileType returns the QosProfileType field if non-nil, zero value otherwise.

### GetQosProfileTypeOk

`func (o *ManaV2CircuitConfig) GetQosProfileTypeOk() (*string, bool)`

GetQosProfileTypeOk returns a tuple with the QosProfileType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQosProfileType

`func (o *ManaV2CircuitConfig) SetQosProfileType(v string)`

SetQosProfileType sets QosProfileType field to given value.

### HasQosProfileType

`func (o *ManaV2CircuitConfig) HasQosProfileType() bool`

HasQosProfileType returns a boolean if a field has been set.

### GetStaticRoutes

`func (o *ManaV2CircuitConfig) GetStaticRoutes() map[string]ManaV2NullableStaticRouteConfig`

GetStaticRoutes returns the StaticRoutes field if non-nil, zero value otherwise.

### GetStaticRoutesOk

`func (o *ManaV2CircuitConfig) GetStaticRoutesOk() (*map[string]ManaV2NullableStaticRouteConfig, bool)`

GetStaticRoutesOk returns a tuple with the StaticRoutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticRoutes

`func (o *ManaV2CircuitConfig) SetStaticRoutes(v map[string]ManaV2NullableStaticRouteConfig)`

SetStaticRoutes sets StaticRoutes field to given value.

### HasStaticRoutes

`func (o *ManaV2CircuitConfig) HasStaticRoutes() bool`

HasStaticRoutes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



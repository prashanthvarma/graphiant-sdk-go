# ManaV2CoreVlanInterfaceConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CoreNeighbor** | Pointer to [**ManaV2InterfaceCoreToCorePeerConfig**](ManaV2InterfaceCoreToCorePeerConfig.md) |  | [optional] 
**Default** | Pointer to **map[string]interface{}** |  | [optional] 
**GatewayNeighbor** | Pointer to [**ManaV2InterfaceCoreToGatewayPeerConfig**](ManaV2InterfaceCoreToGatewayPeerConfig.md) |  | [optional] 
**Interface** | Pointer to [**ManaV2CoreInterfaceConfig**](ManaV2CoreInterfaceConfig.md) |  | [optional] 
**InterfaceType** | Pointer to [**ManaV2interfaceConfigType**](ManaV2interfaceConfigType.md) |  | [optional] 
**VlanId** | Pointer to **int32** |  | [optional] 
**Wan** | Pointer to [**ManaV2InterfaceWanConfig**](ManaV2InterfaceWanConfig.md) |  | [optional] 

## Methods

### NewManaV2CoreVlanInterfaceConfig

`func NewManaV2CoreVlanInterfaceConfig() *ManaV2CoreVlanInterfaceConfig`

NewManaV2CoreVlanInterfaceConfig instantiates a new ManaV2CoreVlanInterfaceConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2CoreVlanInterfaceConfigWithDefaults

`func NewManaV2CoreVlanInterfaceConfigWithDefaults() *ManaV2CoreVlanInterfaceConfig`

NewManaV2CoreVlanInterfaceConfigWithDefaults instantiates a new ManaV2CoreVlanInterfaceConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCoreNeighbor

`func (o *ManaV2CoreVlanInterfaceConfig) GetCoreNeighbor() ManaV2InterfaceCoreToCorePeerConfig`

GetCoreNeighbor returns the CoreNeighbor field if non-nil, zero value otherwise.

### GetCoreNeighborOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetCoreNeighborOk() (*ManaV2InterfaceCoreToCorePeerConfig, bool)`

GetCoreNeighborOk returns a tuple with the CoreNeighbor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreNeighbor

`func (o *ManaV2CoreVlanInterfaceConfig) SetCoreNeighbor(v ManaV2InterfaceCoreToCorePeerConfig)`

SetCoreNeighbor sets CoreNeighbor field to given value.

### HasCoreNeighbor

`func (o *ManaV2CoreVlanInterfaceConfig) HasCoreNeighbor() bool`

HasCoreNeighbor returns a boolean if a field has been set.

### GetDefault

`func (o *ManaV2CoreVlanInterfaceConfig) GetDefault() map[string]interface{}`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetDefaultOk() (*map[string]interface{}, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *ManaV2CoreVlanInterfaceConfig) SetDefault(v map[string]interface{})`

SetDefault sets Default field to given value.

### HasDefault

`func (o *ManaV2CoreVlanInterfaceConfig) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetGatewayNeighbor

`func (o *ManaV2CoreVlanInterfaceConfig) GetGatewayNeighbor() ManaV2InterfaceCoreToGatewayPeerConfig`

GetGatewayNeighbor returns the GatewayNeighbor field if non-nil, zero value otherwise.

### GetGatewayNeighborOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetGatewayNeighborOk() (*ManaV2InterfaceCoreToGatewayPeerConfig, bool)`

GetGatewayNeighborOk returns a tuple with the GatewayNeighbor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayNeighbor

`func (o *ManaV2CoreVlanInterfaceConfig) SetGatewayNeighbor(v ManaV2InterfaceCoreToGatewayPeerConfig)`

SetGatewayNeighbor sets GatewayNeighbor field to given value.

### HasGatewayNeighbor

`func (o *ManaV2CoreVlanInterfaceConfig) HasGatewayNeighbor() bool`

HasGatewayNeighbor returns a boolean if a field has been set.

### GetInterface

`func (o *ManaV2CoreVlanInterfaceConfig) GetInterface() ManaV2CoreInterfaceConfig`

GetInterface returns the Interface field if non-nil, zero value otherwise.

### GetInterfaceOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetInterfaceOk() (*ManaV2CoreInterfaceConfig, bool)`

GetInterfaceOk returns a tuple with the Interface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterface

`func (o *ManaV2CoreVlanInterfaceConfig) SetInterface(v ManaV2CoreInterfaceConfig)`

SetInterface sets Interface field to given value.

### HasInterface

`func (o *ManaV2CoreVlanInterfaceConfig) HasInterface() bool`

HasInterface returns a boolean if a field has been set.

### GetInterfaceType

`func (o *ManaV2CoreVlanInterfaceConfig) GetInterfaceType() ManaV2interfaceConfigType`

GetInterfaceType returns the InterfaceType field if non-nil, zero value otherwise.

### GetInterfaceTypeOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetInterfaceTypeOk() (*ManaV2interfaceConfigType, bool)`

GetInterfaceTypeOk returns a tuple with the InterfaceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceType

`func (o *ManaV2CoreVlanInterfaceConfig) SetInterfaceType(v ManaV2interfaceConfigType)`

SetInterfaceType sets InterfaceType field to given value.

### HasInterfaceType

`func (o *ManaV2CoreVlanInterfaceConfig) HasInterfaceType() bool`

HasInterfaceType returns a boolean if a field has been set.

### GetVlanId

`func (o *ManaV2CoreVlanInterfaceConfig) GetVlanId() int32`

GetVlanId returns the VlanId field if non-nil, zero value otherwise.

### GetVlanIdOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetVlanIdOk() (*int32, bool)`

GetVlanIdOk returns a tuple with the VlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanId

`func (o *ManaV2CoreVlanInterfaceConfig) SetVlanId(v int32)`

SetVlanId sets VlanId field to given value.

### HasVlanId

`func (o *ManaV2CoreVlanInterfaceConfig) HasVlanId() bool`

HasVlanId returns a boolean if a field has been set.

### GetWan

`func (o *ManaV2CoreVlanInterfaceConfig) GetWan() ManaV2InterfaceWanConfig`

GetWan returns the Wan field if non-nil, zero value otherwise.

### GetWanOk

`func (o *ManaV2CoreVlanInterfaceConfig) GetWanOk() (*ManaV2InterfaceWanConfig, bool)`

GetWanOk returns a tuple with the Wan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWan

`func (o *ManaV2CoreVlanInterfaceConfig) SetWan(v ManaV2InterfaceWanConfig)`

SetWan sets Wan field to given value.

### HasWan

`func (o *ManaV2CoreVlanInterfaceConfig) HasWan() bool`

HasWan returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



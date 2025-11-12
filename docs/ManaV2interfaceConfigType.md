# ManaV2interfaceConfigType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CoreNeighbor** | Pointer to [**ManaV2InterfaceCoreToCorePeerConfig**](ManaV2InterfaceCoreToCorePeerConfig.md) |  | [optional] 
**CoreToCoreTunnel** | Pointer to **map[string]interface{}** |  | [optional] 
**Default** | Pointer to **map[string]interface{}** |  | [optional] 
**GatewayNeighbor** | Pointer to [**ManaV2InterfaceCoreToGatewayPeerConfig**](ManaV2InterfaceCoreToGatewayPeerConfig.md) |  | [optional] 
**Wan** | Pointer to [**ManaV2InterfaceWanConfig**](ManaV2InterfaceWanConfig.md) |  | [optional] 
**WanManagement** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewManaV2interfaceConfigType

`func NewManaV2interfaceConfigType() *ManaV2interfaceConfigType`

NewManaV2interfaceConfigType instantiates a new ManaV2interfaceConfigType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2interfaceConfigTypeWithDefaults

`func NewManaV2interfaceConfigTypeWithDefaults() *ManaV2interfaceConfigType`

NewManaV2interfaceConfigTypeWithDefaults instantiates a new ManaV2interfaceConfigType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCoreNeighbor

`func (o *ManaV2interfaceConfigType) GetCoreNeighbor() ManaV2InterfaceCoreToCorePeerConfig`

GetCoreNeighbor returns the CoreNeighbor field if non-nil, zero value otherwise.

### GetCoreNeighborOk

`func (o *ManaV2interfaceConfigType) GetCoreNeighborOk() (*ManaV2InterfaceCoreToCorePeerConfig, bool)`

GetCoreNeighborOk returns a tuple with the CoreNeighbor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreNeighbor

`func (o *ManaV2interfaceConfigType) SetCoreNeighbor(v ManaV2InterfaceCoreToCorePeerConfig)`

SetCoreNeighbor sets CoreNeighbor field to given value.

### HasCoreNeighbor

`func (o *ManaV2interfaceConfigType) HasCoreNeighbor() bool`

HasCoreNeighbor returns a boolean if a field has been set.

### GetCoreToCoreTunnel

`func (o *ManaV2interfaceConfigType) GetCoreToCoreTunnel() map[string]interface{}`

GetCoreToCoreTunnel returns the CoreToCoreTunnel field if non-nil, zero value otherwise.

### GetCoreToCoreTunnelOk

`func (o *ManaV2interfaceConfigType) GetCoreToCoreTunnelOk() (*map[string]interface{}, bool)`

GetCoreToCoreTunnelOk returns a tuple with the CoreToCoreTunnel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreToCoreTunnel

`func (o *ManaV2interfaceConfigType) SetCoreToCoreTunnel(v map[string]interface{})`

SetCoreToCoreTunnel sets CoreToCoreTunnel field to given value.

### HasCoreToCoreTunnel

`func (o *ManaV2interfaceConfigType) HasCoreToCoreTunnel() bool`

HasCoreToCoreTunnel returns a boolean if a field has been set.

### GetDefault

`func (o *ManaV2interfaceConfigType) GetDefault() map[string]interface{}`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *ManaV2interfaceConfigType) GetDefaultOk() (*map[string]interface{}, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *ManaV2interfaceConfigType) SetDefault(v map[string]interface{})`

SetDefault sets Default field to given value.

### HasDefault

`func (o *ManaV2interfaceConfigType) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### GetGatewayNeighbor

`func (o *ManaV2interfaceConfigType) GetGatewayNeighbor() ManaV2InterfaceCoreToGatewayPeerConfig`

GetGatewayNeighbor returns the GatewayNeighbor field if non-nil, zero value otherwise.

### GetGatewayNeighborOk

`func (o *ManaV2interfaceConfigType) GetGatewayNeighborOk() (*ManaV2InterfaceCoreToGatewayPeerConfig, bool)`

GetGatewayNeighborOk returns a tuple with the GatewayNeighbor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayNeighbor

`func (o *ManaV2interfaceConfigType) SetGatewayNeighbor(v ManaV2InterfaceCoreToGatewayPeerConfig)`

SetGatewayNeighbor sets GatewayNeighbor field to given value.

### HasGatewayNeighbor

`func (o *ManaV2interfaceConfigType) HasGatewayNeighbor() bool`

HasGatewayNeighbor returns a boolean if a field has been set.

### GetWan

`func (o *ManaV2interfaceConfigType) GetWan() ManaV2InterfaceWanConfig`

GetWan returns the Wan field if non-nil, zero value otherwise.

### GetWanOk

`func (o *ManaV2interfaceConfigType) GetWanOk() (*ManaV2InterfaceWanConfig, bool)`

GetWanOk returns a tuple with the Wan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWan

`func (o *ManaV2interfaceConfigType) SetWan(v ManaV2InterfaceWanConfig)`

SetWan sets Wan field to given value.

### HasWan

`func (o *ManaV2interfaceConfigType) HasWan() bool`

HasWan returns a boolean if a field has been set.

### GetWanManagement

`func (o *ManaV2interfaceConfigType) GetWanManagement() map[string]interface{}`

GetWanManagement returns the WanManagement field if non-nil, zero value otherwise.

### GetWanManagementOk

`func (o *ManaV2interfaceConfigType) GetWanManagementOk() (*map[string]interface{}, bool)`

GetWanManagementOk returns a tuple with the WanManagement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanManagement

`func (o *ManaV2interfaceConfigType) SetWanManagement(v map[string]interface{})`

SetWanManagement sets WanManagement field to given value.

### HasWanManagement

`func (o *ManaV2interfaceConfigType) HasWanManagement() bool`

HasWanManagement returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



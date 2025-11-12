# ManaV2StaticRouteNexthop

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuit** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Metric** | Pointer to **int32** |  | [optional] 
**NextHopAddress** | Pointer to **string** |  | [optional] 
**Nexthop** | Pointer to **string** |  | [optional] 
**OutgoingInterface** | Pointer to **string** |  | [optional] 
**ThirdPartyIpsecTunnel** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2StaticRouteNexthop

`func NewManaV2StaticRouteNexthop() *ManaV2StaticRouteNexthop`

NewManaV2StaticRouteNexthop instantiates a new ManaV2StaticRouteNexthop object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2StaticRouteNexthopWithDefaults

`func NewManaV2StaticRouteNexthopWithDefaults() *ManaV2StaticRouteNexthop`

NewManaV2StaticRouteNexthopWithDefaults instantiates a new ManaV2StaticRouteNexthop object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuit

`func (o *ManaV2StaticRouteNexthop) GetCircuit() string`

GetCircuit returns the Circuit field if non-nil, zero value otherwise.

### GetCircuitOk

`func (o *ManaV2StaticRouteNexthop) GetCircuitOk() (*string, bool)`

GetCircuitOk returns a tuple with the Circuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuit

`func (o *ManaV2StaticRouteNexthop) SetCircuit(v string)`

SetCircuit sets Circuit field to given value.

### HasCircuit

`func (o *ManaV2StaticRouteNexthop) HasCircuit() bool`

HasCircuit returns a boolean if a field has been set.

### GetId

`func (o *ManaV2StaticRouteNexthop) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2StaticRouteNexthop) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2StaticRouteNexthop) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2StaticRouteNexthop) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMetric

`func (o *ManaV2StaticRouteNexthop) GetMetric() int32`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *ManaV2StaticRouteNexthop) GetMetricOk() (*int32, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *ManaV2StaticRouteNexthop) SetMetric(v int32)`

SetMetric sets Metric field to given value.

### HasMetric

`func (o *ManaV2StaticRouteNexthop) HasMetric() bool`

HasMetric returns a boolean if a field has been set.

### GetNextHopAddress

`func (o *ManaV2StaticRouteNexthop) GetNextHopAddress() string`

GetNextHopAddress returns the NextHopAddress field if non-nil, zero value otherwise.

### GetNextHopAddressOk

`func (o *ManaV2StaticRouteNexthop) GetNextHopAddressOk() (*string, bool)`

GetNextHopAddressOk returns a tuple with the NextHopAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHopAddress

`func (o *ManaV2StaticRouteNexthop) SetNextHopAddress(v string)`

SetNextHopAddress sets NextHopAddress field to given value.

### HasNextHopAddress

`func (o *ManaV2StaticRouteNexthop) HasNextHopAddress() bool`

HasNextHopAddress returns a boolean if a field has been set.

### GetNexthop

`func (o *ManaV2StaticRouteNexthop) GetNexthop() string`

GetNexthop returns the Nexthop field if non-nil, zero value otherwise.

### GetNexthopOk

`func (o *ManaV2StaticRouteNexthop) GetNexthopOk() (*string, bool)`

GetNexthopOk returns a tuple with the Nexthop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNexthop

`func (o *ManaV2StaticRouteNexthop) SetNexthop(v string)`

SetNexthop sets Nexthop field to given value.

### HasNexthop

`func (o *ManaV2StaticRouteNexthop) HasNexthop() bool`

HasNexthop returns a boolean if a field has been set.

### GetOutgoingInterface

`func (o *ManaV2StaticRouteNexthop) GetOutgoingInterface() string`

GetOutgoingInterface returns the OutgoingInterface field if non-nil, zero value otherwise.

### GetOutgoingInterfaceOk

`func (o *ManaV2StaticRouteNexthop) GetOutgoingInterfaceOk() (*string, bool)`

GetOutgoingInterfaceOk returns a tuple with the OutgoingInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutgoingInterface

`func (o *ManaV2StaticRouteNexthop) SetOutgoingInterface(v string)`

SetOutgoingInterface sets OutgoingInterface field to given value.

### HasOutgoingInterface

`func (o *ManaV2StaticRouteNexthop) HasOutgoingInterface() bool`

HasOutgoingInterface returns a boolean if a field has been set.

### GetThirdPartyIpsecTunnel

`func (o *ManaV2StaticRouteNexthop) GetThirdPartyIpsecTunnel() string`

GetThirdPartyIpsecTunnel returns the ThirdPartyIpsecTunnel field if non-nil, zero value otherwise.

### GetThirdPartyIpsecTunnelOk

`func (o *ManaV2StaticRouteNexthop) GetThirdPartyIpsecTunnelOk() (*string, bool)`

GetThirdPartyIpsecTunnelOk returns a tuple with the ThirdPartyIpsecTunnel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyIpsecTunnel

`func (o *ManaV2StaticRouteNexthop) SetThirdPartyIpsecTunnel(v string)`

SetThirdPartyIpsecTunnel sets ThirdPartyIpsecTunnel field to given value.

### HasThirdPartyIpsecTunnel

`func (o *ManaV2StaticRouteNexthop) HasThirdPartyIpsecTunnel() bool`

HasThirdPartyIpsecTunnel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



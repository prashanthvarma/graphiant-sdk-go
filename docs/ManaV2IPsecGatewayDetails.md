# ManaV2IPsecGatewayDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationAddress** | Pointer to **string** |  | [optional] 
**IkeInitiator** | Pointer to **bool** |  | [optional] 
**Mtu** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**RemoteIkePeerIdentity** | Pointer to **string** |  | [optional] 
**Routing** | Pointer to [**ManaV2IpsecRoutingConfig**](ManaV2IpsecRoutingConfig.md) |  | [optional] 
**TcpMss** | Pointer to **int32** |  | [optional] 
**Tunnel1** | Pointer to [**ManaV2IPsecGatewayTunnelDetails**](ManaV2IPsecGatewayTunnelDetails.md) |  | [optional] 
**Tunnel2** | Pointer to [**ManaV2IPsecGatewayTunnelDetails**](ManaV2IPsecGatewayTunnelDetails.md) |  | [optional] 
**VpnProfile** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2IPsecGatewayDetails

`func NewManaV2IPsecGatewayDetails() *ManaV2IPsecGatewayDetails`

NewManaV2IPsecGatewayDetails instantiates a new ManaV2IPsecGatewayDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IPsecGatewayDetailsWithDefaults

`func NewManaV2IPsecGatewayDetailsWithDefaults() *ManaV2IPsecGatewayDetails`

NewManaV2IPsecGatewayDetailsWithDefaults instantiates a new ManaV2IPsecGatewayDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationAddress

`func (o *ManaV2IPsecGatewayDetails) GetDestinationAddress() string`

GetDestinationAddress returns the DestinationAddress field if non-nil, zero value otherwise.

### GetDestinationAddressOk

`func (o *ManaV2IPsecGatewayDetails) GetDestinationAddressOk() (*string, bool)`

GetDestinationAddressOk returns a tuple with the DestinationAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationAddress

`func (o *ManaV2IPsecGatewayDetails) SetDestinationAddress(v string)`

SetDestinationAddress sets DestinationAddress field to given value.

### HasDestinationAddress

`func (o *ManaV2IPsecGatewayDetails) HasDestinationAddress() bool`

HasDestinationAddress returns a boolean if a field has been set.

### GetIkeInitiator

`func (o *ManaV2IPsecGatewayDetails) GetIkeInitiator() bool`

GetIkeInitiator returns the IkeInitiator field if non-nil, zero value otherwise.

### GetIkeInitiatorOk

`func (o *ManaV2IPsecGatewayDetails) GetIkeInitiatorOk() (*bool, bool)`

GetIkeInitiatorOk returns a tuple with the IkeInitiator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeInitiator

`func (o *ManaV2IPsecGatewayDetails) SetIkeInitiator(v bool)`

SetIkeInitiator sets IkeInitiator field to given value.

### HasIkeInitiator

`func (o *ManaV2IPsecGatewayDetails) HasIkeInitiator() bool`

HasIkeInitiator returns a boolean if a field has been set.

### GetMtu

`func (o *ManaV2IPsecGatewayDetails) GetMtu() int32`

GetMtu returns the Mtu field if non-nil, zero value otherwise.

### GetMtuOk

`func (o *ManaV2IPsecGatewayDetails) GetMtuOk() (*int32, bool)`

GetMtuOk returns a tuple with the Mtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMtu

`func (o *ManaV2IPsecGatewayDetails) SetMtu(v int32)`

SetMtu sets Mtu field to given value.

### HasMtu

`func (o *ManaV2IPsecGatewayDetails) HasMtu() bool`

HasMtu returns a boolean if a field has been set.

### GetName

`func (o *ManaV2IPsecGatewayDetails) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2IPsecGatewayDetails) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2IPsecGatewayDetails) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2IPsecGatewayDetails) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRemoteIkePeerIdentity

`func (o *ManaV2IPsecGatewayDetails) GetRemoteIkePeerIdentity() string`

GetRemoteIkePeerIdentity returns the RemoteIkePeerIdentity field if non-nil, zero value otherwise.

### GetRemoteIkePeerIdentityOk

`func (o *ManaV2IPsecGatewayDetails) GetRemoteIkePeerIdentityOk() (*string, bool)`

GetRemoteIkePeerIdentityOk returns a tuple with the RemoteIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteIkePeerIdentity

`func (o *ManaV2IPsecGatewayDetails) SetRemoteIkePeerIdentity(v string)`

SetRemoteIkePeerIdentity sets RemoteIkePeerIdentity field to given value.

### HasRemoteIkePeerIdentity

`func (o *ManaV2IPsecGatewayDetails) HasRemoteIkePeerIdentity() bool`

HasRemoteIkePeerIdentity returns a boolean if a field has been set.

### GetRouting

`func (o *ManaV2IPsecGatewayDetails) GetRouting() ManaV2IpsecRoutingConfig`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *ManaV2IPsecGatewayDetails) GetRoutingOk() (*ManaV2IpsecRoutingConfig, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *ManaV2IPsecGatewayDetails) SetRouting(v ManaV2IpsecRoutingConfig)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *ManaV2IPsecGatewayDetails) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### GetTcpMss

`func (o *ManaV2IPsecGatewayDetails) GetTcpMss() int32`

GetTcpMss returns the TcpMss field if non-nil, zero value otherwise.

### GetTcpMssOk

`func (o *ManaV2IPsecGatewayDetails) GetTcpMssOk() (*int32, bool)`

GetTcpMssOk returns a tuple with the TcpMss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpMss

`func (o *ManaV2IPsecGatewayDetails) SetTcpMss(v int32)`

SetTcpMss sets TcpMss field to given value.

### HasTcpMss

`func (o *ManaV2IPsecGatewayDetails) HasTcpMss() bool`

HasTcpMss returns a boolean if a field has been set.

### GetTunnel1

`func (o *ManaV2IPsecGatewayDetails) GetTunnel1() ManaV2IPsecGatewayTunnelDetails`

GetTunnel1 returns the Tunnel1 field if non-nil, zero value otherwise.

### GetTunnel1Ok

`func (o *ManaV2IPsecGatewayDetails) GetTunnel1Ok() (*ManaV2IPsecGatewayTunnelDetails, bool)`

GetTunnel1Ok returns a tuple with the Tunnel1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnel1

`func (o *ManaV2IPsecGatewayDetails) SetTunnel1(v ManaV2IPsecGatewayTunnelDetails)`

SetTunnel1 sets Tunnel1 field to given value.

### HasTunnel1

`func (o *ManaV2IPsecGatewayDetails) HasTunnel1() bool`

HasTunnel1 returns a boolean if a field has been set.

### GetTunnel2

`func (o *ManaV2IPsecGatewayDetails) GetTunnel2() ManaV2IPsecGatewayTunnelDetails`

GetTunnel2 returns the Tunnel2 field if non-nil, zero value otherwise.

### GetTunnel2Ok

`func (o *ManaV2IPsecGatewayDetails) GetTunnel2Ok() (*ManaV2IPsecGatewayTunnelDetails, bool)`

GetTunnel2Ok returns a tuple with the Tunnel2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnel2

`func (o *ManaV2IPsecGatewayDetails) SetTunnel2(v ManaV2IPsecGatewayTunnelDetails)`

SetTunnel2 sets Tunnel2 field to given value.

### HasTunnel2

`func (o *ManaV2IPsecGatewayDetails) HasTunnel2() bool`

HasTunnel2 returns a boolean if a field has been set.

### GetVpnProfile

`func (o *ManaV2IPsecGatewayDetails) GetVpnProfile() string`

GetVpnProfile returns the VpnProfile field if non-nil, zero value otherwise.

### GetVpnProfileOk

`func (o *ManaV2IPsecGatewayDetails) GetVpnProfileOk() (*string, bool)`

GetVpnProfileOk returns a tuple with the VpnProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpnProfile

`func (o *ManaV2IPsecGatewayDetails) SetVpnProfile(v string)`

SetVpnProfile sets VpnProfile field to given value.

### HasVpnProfile

`func (o *ManaV2IPsecGatewayDetails) HasVpnProfile() bool`

HasVpnProfile returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



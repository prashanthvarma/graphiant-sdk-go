# V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationAddress** | Pointer to **string** |  | [optional] 
**IkeInitiator** | Pointer to **bool** |  | [optional] 
**Mtu** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**RemoteIkePeerIdentity** | Pointer to **string** |  | [optional] 
**Routing** | Pointer to [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting.md) |  | [optional] 
**TcpMss** | Pointer to **int32** |  | [optional] 
**Tunnel1** | Pointer to [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1.md) |  | [optional] 
**Tunnel2** | Pointer to [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1.md) |  | [optional] 
**VpnProfile** | Pointer to **string** |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails

`func NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails() *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails`

NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails instantiates a new V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsWithDefaults

`func NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsWithDefaults() *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails`

NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsWithDefaults instantiates a new V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationAddress

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetDestinationAddress() string`

GetDestinationAddress returns the DestinationAddress field if non-nil, zero value otherwise.

### GetDestinationAddressOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetDestinationAddressOk() (*string, bool)`

GetDestinationAddressOk returns a tuple with the DestinationAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationAddress

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetDestinationAddress(v string)`

SetDestinationAddress sets DestinationAddress field to given value.

### HasDestinationAddress

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasDestinationAddress() bool`

HasDestinationAddress returns a boolean if a field has been set.

### GetIkeInitiator

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetIkeInitiator() bool`

GetIkeInitiator returns the IkeInitiator field if non-nil, zero value otherwise.

### GetIkeInitiatorOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetIkeInitiatorOk() (*bool, bool)`

GetIkeInitiatorOk returns a tuple with the IkeInitiator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeInitiator

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetIkeInitiator(v bool)`

SetIkeInitiator sets IkeInitiator field to given value.

### HasIkeInitiator

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasIkeInitiator() bool`

HasIkeInitiator returns a boolean if a field has been set.

### GetMtu

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetMtu() int32`

GetMtu returns the Mtu field if non-nil, zero value otherwise.

### GetMtuOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetMtuOk() (*int32, bool)`

GetMtuOk returns a tuple with the Mtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMtu

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetMtu(v int32)`

SetMtu sets Mtu field to given value.

### HasMtu

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasMtu() bool`

HasMtu returns a boolean if a field has been set.

### GetName

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRemoteIkePeerIdentity

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetRemoteIkePeerIdentity() string`

GetRemoteIkePeerIdentity returns the RemoteIkePeerIdentity field if non-nil, zero value otherwise.

### GetRemoteIkePeerIdentityOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetRemoteIkePeerIdentityOk() (*string, bool)`

GetRemoteIkePeerIdentityOk returns a tuple with the RemoteIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteIkePeerIdentity

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetRemoteIkePeerIdentity(v string)`

SetRemoteIkePeerIdentity sets RemoteIkePeerIdentity field to given value.

### HasRemoteIkePeerIdentity

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasRemoteIkePeerIdentity() bool`

HasRemoteIkePeerIdentity returns a boolean if a field has been set.

### GetRouting

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetRouting() V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetRoutingOk() (*V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetRouting(v V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### GetTcpMss

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetTcpMss() int32`

GetTcpMss returns the TcpMss field if non-nil, zero value otherwise.

### GetTcpMssOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetTcpMssOk() (*int32, bool)`

GetTcpMssOk returns a tuple with the TcpMss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpMss

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetTcpMss(v int32)`

SetTcpMss sets TcpMss field to given value.

### HasTcpMss

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasTcpMss() bool`

HasTcpMss returns a boolean if a field has been set.

### GetTunnel1

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetTunnel1() V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1`

GetTunnel1 returns the Tunnel1 field if non-nil, zero value otherwise.

### GetTunnel1Ok

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetTunnel1Ok() (*V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1, bool)`

GetTunnel1Ok returns a tuple with the Tunnel1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnel1

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetTunnel1(v V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1)`

SetTunnel1 sets Tunnel1 field to given value.

### HasTunnel1

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasTunnel1() bool`

HasTunnel1 returns a boolean if a field has been set.

### GetTunnel2

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetTunnel2() V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1`

GetTunnel2 returns the Tunnel2 field if non-nil, zero value otherwise.

### GetTunnel2Ok

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetTunnel2Ok() (*V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1, bool)`

GetTunnel2Ok returns a tuple with the Tunnel2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnel2

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetTunnel2(v V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1)`

SetTunnel2 sets Tunnel2 field to given value.

### HasTunnel2

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasTunnel2() bool`

HasTunnel2 returns a boolean if a field has been set.

### GetVpnProfile

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetVpnProfile() string`

GetVpnProfile returns the VpnProfile field if non-nil, zero value otherwise.

### GetVpnProfileOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) GetVpnProfileOk() (*string, bool)`

GetVpnProfileOk returns a tuple with the VpnProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpnProfile

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) SetVpnProfile(v string)`

SetVpnProfile sets VpnProfile field to given value.

### HasVpnProfile

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails) HasVpnProfile() bool`

HasVpnProfile returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



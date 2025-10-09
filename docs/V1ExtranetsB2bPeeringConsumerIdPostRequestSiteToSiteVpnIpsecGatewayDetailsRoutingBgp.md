# V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamilies** | Pointer to [**map[string]V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue**](V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue.md) |  | [optional] 
**HoldTimer** | Pointer to **int32** |  | [optional] 
**KeepaliveTimer** | Pointer to **int32** |  | [optional] 
**Md5Password** | Pointer to [**V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password**](V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password.md) |  | [optional] 
**PeerAsn** | Pointer to **int32** |  | [optional] 
**SendCommunity** | Pointer to **bool** |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp

`func NewV1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp() *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp`

NewV1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp instantiates a new V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpWithDefaults

`func NewV1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpWithDefaults() *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp`

NewV1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpWithDefaults instantiates a new V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamilies

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetAddressFamilies() map[string]V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue`

GetAddressFamilies returns the AddressFamilies field if non-nil, zero value otherwise.

### GetAddressFamiliesOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetAddressFamiliesOk() (*map[string]V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue, bool)`

GetAddressFamiliesOk returns a tuple with the AddressFamilies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamilies

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) SetAddressFamilies(v map[string]V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue)`

SetAddressFamilies sets AddressFamilies field to given value.

### HasAddressFamilies

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) HasAddressFamilies() bool`

HasAddressFamilies returns a boolean if a field has been set.

### GetHoldTimer

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetHoldTimer() int32`

GetHoldTimer returns the HoldTimer field if non-nil, zero value otherwise.

### GetHoldTimerOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetHoldTimerOk() (*int32, bool)`

GetHoldTimerOk returns a tuple with the HoldTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoldTimer

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) SetHoldTimer(v int32)`

SetHoldTimer sets HoldTimer field to given value.

### HasHoldTimer

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) HasHoldTimer() bool`

HasHoldTimer returns a boolean if a field has been set.

### GetKeepaliveTimer

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetKeepaliveTimer() int32`

GetKeepaliveTimer returns the KeepaliveTimer field if non-nil, zero value otherwise.

### GetKeepaliveTimerOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetKeepaliveTimerOk() (*int32, bool)`

GetKeepaliveTimerOk returns a tuple with the KeepaliveTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepaliveTimer

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) SetKeepaliveTimer(v int32)`

SetKeepaliveTimer sets KeepaliveTimer field to given value.

### HasKeepaliveTimer

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) HasKeepaliveTimer() bool`

HasKeepaliveTimer returns a boolean if a field has been set.

### GetMd5Password

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetMd5Password() V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password`

GetMd5Password returns the Md5Password field if non-nil, zero value otherwise.

### GetMd5PasswordOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetMd5PasswordOk() (*V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password, bool)`

GetMd5PasswordOk returns a tuple with the Md5Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5Password

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) SetMd5Password(v V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password)`

SetMd5Password sets Md5Password field to given value.

### HasMd5Password

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) HasMd5Password() bool`

HasMd5Password returns a boolean if a field has been set.

### GetPeerAsn

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetPeerAsn() int32`

GetPeerAsn returns the PeerAsn field if non-nil, zero value otherwise.

### GetPeerAsnOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetPeerAsnOk() (*int32, bool)`

GetPeerAsnOk returns a tuple with the PeerAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerAsn

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) SetPeerAsn(v int32)`

SetPeerAsn sets PeerAsn field to given value.

### HasPeerAsn

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) HasPeerAsn() bool`

HasPeerAsn returns a boolean if a field has been set.

### GetSendCommunity

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetSendCommunity() bool`

GetSendCommunity returns the SendCommunity field if non-nil, zero value otherwise.

### GetSendCommunityOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) GetSendCommunityOk() (*bool, bool)`

GetSendCommunityOk returns a tuple with the SendCommunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendCommunity

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) SetSendCommunity(v bool)`

SetSendCommunity sets SendCommunity field to given value.

### HasSendCommunity

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp) HasSendCommunity() bool`

HasSendCommunity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



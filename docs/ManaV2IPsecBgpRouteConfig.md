# ManaV2IPsecBgpRouteConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamilies** | Pointer to [**map[string]ManaV2NullableBgpNeighborAddressFamilyConfig**](ManaV2NullableBgpNeighborAddressFamilyConfig.md) |  | [optional] 
**HoldTimer** | Pointer to **int32** |  | [optional] 
**KeepaliveTimer** | Pointer to **int32** |  | [optional] 
**Md5Password** | Pointer to [**ManaV2NullableMd5Password**](ManaV2NullableMd5Password.md) |  | [optional] 
**PeerAsn** | Pointer to **int32** |  | [optional] 
**SendCommunity** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2IPsecBgpRouteConfig

`func NewManaV2IPsecBgpRouteConfig() *ManaV2IPsecBgpRouteConfig`

NewManaV2IPsecBgpRouteConfig instantiates a new ManaV2IPsecBgpRouteConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IPsecBgpRouteConfigWithDefaults

`func NewManaV2IPsecBgpRouteConfigWithDefaults() *ManaV2IPsecBgpRouteConfig`

NewManaV2IPsecBgpRouteConfigWithDefaults instantiates a new ManaV2IPsecBgpRouteConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamilies

`func (o *ManaV2IPsecBgpRouteConfig) GetAddressFamilies() map[string]ManaV2NullableBgpNeighborAddressFamilyConfig`

GetAddressFamilies returns the AddressFamilies field if non-nil, zero value otherwise.

### GetAddressFamiliesOk

`func (o *ManaV2IPsecBgpRouteConfig) GetAddressFamiliesOk() (*map[string]ManaV2NullableBgpNeighborAddressFamilyConfig, bool)`

GetAddressFamiliesOk returns a tuple with the AddressFamilies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamilies

`func (o *ManaV2IPsecBgpRouteConfig) SetAddressFamilies(v map[string]ManaV2NullableBgpNeighborAddressFamilyConfig)`

SetAddressFamilies sets AddressFamilies field to given value.

### HasAddressFamilies

`func (o *ManaV2IPsecBgpRouteConfig) HasAddressFamilies() bool`

HasAddressFamilies returns a boolean if a field has been set.

### GetHoldTimer

`func (o *ManaV2IPsecBgpRouteConfig) GetHoldTimer() int32`

GetHoldTimer returns the HoldTimer field if non-nil, zero value otherwise.

### GetHoldTimerOk

`func (o *ManaV2IPsecBgpRouteConfig) GetHoldTimerOk() (*int32, bool)`

GetHoldTimerOk returns a tuple with the HoldTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoldTimer

`func (o *ManaV2IPsecBgpRouteConfig) SetHoldTimer(v int32)`

SetHoldTimer sets HoldTimer field to given value.

### HasHoldTimer

`func (o *ManaV2IPsecBgpRouteConfig) HasHoldTimer() bool`

HasHoldTimer returns a boolean if a field has been set.

### GetKeepaliveTimer

`func (o *ManaV2IPsecBgpRouteConfig) GetKeepaliveTimer() int32`

GetKeepaliveTimer returns the KeepaliveTimer field if non-nil, zero value otherwise.

### GetKeepaliveTimerOk

`func (o *ManaV2IPsecBgpRouteConfig) GetKeepaliveTimerOk() (*int32, bool)`

GetKeepaliveTimerOk returns a tuple with the KeepaliveTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepaliveTimer

`func (o *ManaV2IPsecBgpRouteConfig) SetKeepaliveTimer(v int32)`

SetKeepaliveTimer sets KeepaliveTimer field to given value.

### HasKeepaliveTimer

`func (o *ManaV2IPsecBgpRouteConfig) HasKeepaliveTimer() bool`

HasKeepaliveTimer returns a boolean if a field has been set.

### GetMd5Password

`func (o *ManaV2IPsecBgpRouteConfig) GetMd5Password() ManaV2NullableMd5Password`

GetMd5Password returns the Md5Password field if non-nil, zero value otherwise.

### GetMd5PasswordOk

`func (o *ManaV2IPsecBgpRouteConfig) GetMd5PasswordOk() (*ManaV2NullableMd5Password, bool)`

GetMd5PasswordOk returns a tuple with the Md5Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5Password

`func (o *ManaV2IPsecBgpRouteConfig) SetMd5Password(v ManaV2NullableMd5Password)`

SetMd5Password sets Md5Password field to given value.

### HasMd5Password

`func (o *ManaV2IPsecBgpRouteConfig) HasMd5Password() bool`

HasMd5Password returns a boolean if a field has been set.

### GetPeerAsn

`func (o *ManaV2IPsecBgpRouteConfig) GetPeerAsn() int32`

GetPeerAsn returns the PeerAsn field if non-nil, zero value otherwise.

### GetPeerAsnOk

`func (o *ManaV2IPsecBgpRouteConfig) GetPeerAsnOk() (*int32, bool)`

GetPeerAsnOk returns a tuple with the PeerAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerAsn

`func (o *ManaV2IPsecBgpRouteConfig) SetPeerAsn(v int32)`

SetPeerAsn sets PeerAsn field to given value.

### HasPeerAsn

`func (o *ManaV2IPsecBgpRouteConfig) HasPeerAsn() bool`

HasPeerAsn returns a boolean if a field has been set.

### GetSendCommunity

`func (o *ManaV2IPsecBgpRouteConfig) GetSendCommunity() bool`

GetSendCommunity returns the SendCommunity field if non-nil, zero value otherwise.

### GetSendCommunityOk

`func (o *ManaV2IPsecBgpRouteConfig) GetSendCommunityOk() (*bool, bool)`

GetSendCommunityOk returns a tuple with the SendCommunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendCommunity

`func (o *ManaV2IPsecBgpRouteConfig) SetSendCommunity(v bool)`

SetSendCommunity sets SendCommunity field to given value.

### HasSendCommunity

`func (o *ManaV2IPsecBgpRouteConfig) HasSendCommunity() bool`

HasSendCommunity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



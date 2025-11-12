# ManaV2SiteToSiteIPsecIPsecBgpRoutes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamilies** | Pointer to [**[]ManaV2BgpNeighborAddressFamily**](ManaV2BgpNeighborAddressFamily.md) |  | [optional] 
**HoldTimer** | Pointer to **int32** |  | [optional] 
**KeepaliveTimer** | Pointer to **int32** |  | [optional] 
**Md5Password** | Pointer to **string** |  | [optional] 
**PeerAsn** | Pointer to **int32** |  | [optional] 
**SendCommunity** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2SiteToSiteIPsecIPsecBgpRoutes

`func NewManaV2SiteToSiteIPsecIPsecBgpRoutes() *ManaV2SiteToSiteIPsecIPsecBgpRoutes`

NewManaV2SiteToSiteIPsecIPsecBgpRoutes instantiates a new ManaV2SiteToSiteIPsecIPsecBgpRoutes object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SiteToSiteIPsecIPsecBgpRoutesWithDefaults

`func NewManaV2SiteToSiteIPsecIPsecBgpRoutesWithDefaults() *ManaV2SiteToSiteIPsecIPsecBgpRoutes`

NewManaV2SiteToSiteIPsecIPsecBgpRoutesWithDefaults instantiates a new ManaV2SiteToSiteIPsecIPsecBgpRoutes object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamilies

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetAddressFamilies() []ManaV2BgpNeighborAddressFamily`

GetAddressFamilies returns the AddressFamilies field if non-nil, zero value otherwise.

### GetAddressFamiliesOk

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetAddressFamiliesOk() (*[]ManaV2BgpNeighborAddressFamily, bool)`

GetAddressFamiliesOk returns a tuple with the AddressFamilies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamilies

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) SetAddressFamilies(v []ManaV2BgpNeighborAddressFamily)`

SetAddressFamilies sets AddressFamilies field to given value.

### HasAddressFamilies

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) HasAddressFamilies() bool`

HasAddressFamilies returns a boolean if a field has been set.

### GetHoldTimer

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetHoldTimer() int32`

GetHoldTimer returns the HoldTimer field if non-nil, zero value otherwise.

### GetHoldTimerOk

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetHoldTimerOk() (*int32, bool)`

GetHoldTimerOk returns a tuple with the HoldTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoldTimer

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) SetHoldTimer(v int32)`

SetHoldTimer sets HoldTimer field to given value.

### HasHoldTimer

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) HasHoldTimer() bool`

HasHoldTimer returns a boolean if a field has been set.

### GetKeepaliveTimer

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetKeepaliveTimer() int32`

GetKeepaliveTimer returns the KeepaliveTimer field if non-nil, zero value otherwise.

### GetKeepaliveTimerOk

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetKeepaliveTimerOk() (*int32, bool)`

GetKeepaliveTimerOk returns a tuple with the KeepaliveTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepaliveTimer

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) SetKeepaliveTimer(v int32)`

SetKeepaliveTimer sets KeepaliveTimer field to given value.

### HasKeepaliveTimer

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) HasKeepaliveTimer() bool`

HasKeepaliveTimer returns a boolean if a field has been set.

### GetMd5Password

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetMd5Password() string`

GetMd5Password returns the Md5Password field if non-nil, zero value otherwise.

### GetMd5PasswordOk

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetMd5PasswordOk() (*string, bool)`

GetMd5PasswordOk returns a tuple with the Md5Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5Password

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) SetMd5Password(v string)`

SetMd5Password sets Md5Password field to given value.

### HasMd5Password

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) HasMd5Password() bool`

HasMd5Password returns a boolean if a field has been set.

### GetPeerAsn

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetPeerAsn() int32`

GetPeerAsn returns the PeerAsn field if non-nil, zero value otherwise.

### GetPeerAsnOk

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetPeerAsnOk() (*int32, bool)`

GetPeerAsnOk returns a tuple with the PeerAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerAsn

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) SetPeerAsn(v int32)`

SetPeerAsn sets PeerAsn field to given value.

### HasPeerAsn

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) HasPeerAsn() bool`

HasPeerAsn returns a boolean if a field has been set.

### GetSendCommunity

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetSendCommunity() bool`

GetSendCommunity returns the SendCommunity field if non-nil, zero value otherwise.

### GetSendCommunityOk

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) GetSendCommunityOk() (*bool, bool)`

GetSendCommunityOk returns a tuple with the SendCommunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendCommunity

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) SetSendCommunity(v bool)`

SetSendCommunity sets SendCommunity field to given value.

### HasSendCommunity

`func (o *ManaV2SiteToSiteIPsecIPsecBgpRoutes) HasSendCommunity() bool`

HasSendCommunity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



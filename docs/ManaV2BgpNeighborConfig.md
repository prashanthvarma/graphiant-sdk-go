# ManaV2BgpNeighborConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamilies** | Pointer to [**map[string]ManaV2NullableBgpNeighborAddressFamilyConfig**](ManaV2NullableBgpNeighborAddressFamilyConfig.md) |  | [optional] 
**AllowAsIn** | Pointer to [**ManaV2NullableAllowAsIn**](ManaV2NullableAllowAsIn.md) |  | [optional] 
**AsOverride** | Pointer to **bool** |  | [optional] 
**Bfd** | Pointer to [**ManaV2NullableBfdInstanceConfig**](ManaV2NullableBfdInstanceConfig.md) |  | [optional] 
**DefaultOriginate** | Pointer to **string** |  | [optional] 
**EbgpMultihopTtl** | Pointer to [**ManaV2NullableEbgpConfig**](ManaV2NullableEbgpConfig.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**HoldTimer** | Pointer to **int32** |  | [optional] 
**HoldTimerValue** | Pointer to [**ManaV2NullableHoldTimer**](ManaV2NullableHoldTimer.md) |  | [optional] 
**KeepaliveTimer** | Pointer to **int32** |  | [optional] 
**KeepaliveTimerValue** | Pointer to [**ManaV2NullableKeepAliveTimer**](ManaV2NullableKeepAliveTimer.md) |  | [optional] 
**LocalAddress** | Pointer to **string** |  | [optional] 
**LocalInterface** | Pointer to [**ManaV2NullableInterfaceName**](ManaV2NullableInterfaceName.md) |  | [optional] 
**MaxPrefixValue** | Pointer to [**ManaV2NullableMaxPrefix**](ManaV2NullableMaxPrefix.md) |  | [optional] 
**Md5Password** | Pointer to [**ManaV2NullableMd5Password**](ManaV2NullableMd5Password.md) |  | [optional] 
**PeerAsn** | Pointer to **int32** |  | [optional] 
**RemoteAddress** | Pointer to **string** |  | [optional] 
**RemovePrivateAs** | Pointer to **bool** |  | [optional] 
**SendCommunity** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2BgpNeighborConfig

`func NewManaV2BgpNeighborConfig() *ManaV2BgpNeighborConfig`

NewManaV2BgpNeighborConfig instantiates a new ManaV2BgpNeighborConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BgpNeighborConfigWithDefaults

`func NewManaV2BgpNeighborConfigWithDefaults() *ManaV2BgpNeighborConfig`

NewManaV2BgpNeighborConfigWithDefaults instantiates a new ManaV2BgpNeighborConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamilies

`func (o *ManaV2BgpNeighborConfig) GetAddressFamilies() map[string]ManaV2NullableBgpNeighborAddressFamilyConfig`

GetAddressFamilies returns the AddressFamilies field if non-nil, zero value otherwise.

### GetAddressFamiliesOk

`func (o *ManaV2BgpNeighborConfig) GetAddressFamiliesOk() (*map[string]ManaV2NullableBgpNeighborAddressFamilyConfig, bool)`

GetAddressFamiliesOk returns a tuple with the AddressFamilies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamilies

`func (o *ManaV2BgpNeighborConfig) SetAddressFamilies(v map[string]ManaV2NullableBgpNeighborAddressFamilyConfig)`

SetAddressFamilies sets AddressFamilies field to given value.

### HasAddressFamilies

`func (o *ManaV2BgpNeighborConfig) HasAddressFamilies() bool`

HasAddressFamilies returns a boolean if a field has been set.

### GetAllowAsIn

`func (o *ManaV2BgpNeighborConfig) GetAllowAsIn() ManaV2NullableAllowAsIn`

GetAllowAsIn returns the AllowAsIn field if non-nil, zero value otherwise.

### GetAllowAsInOk

`func (o *ManaV2BgpNeighborConfig) GetAllowAsInOk() (*ManaV2NullableAllowAsIn, bool)`

GetAllowAsInOk returns a tuple with the AllowAsIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowAsIn

`func (o *ManaV2BgpNeighborConfig) SetAllowAsIn(v ManaV2NullableAllowAsIn)`

SetAllowAsIn sets AllowAsIn field to given value.

### HasAllowAsIn

`func (o *ManaV2BgpNeighborConfig) HasAllowAsIn() bool`

HasAllowAsIn returns a boolean if a field has been set.

### GetAsOverride

`func (o *ManaV2BgpNeighborConfig) GetAsOverride() bool`

GetAsOverride returns the AsOverride field if non-nil, zero value otherwise.

### GetAsOverrideOk

`func (o *ManaV2BgpNeighborConfig) GetAsOverrideOk() (*bool, bool)`

GetAsOverrideOk returns a tuple with the AsOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsOverride

`func (o *ManaV2BgpNeighborConfig) SetAsOverride(v bool)`

SetAsOverride sets AsOverride field to given value.

### HasAsOverride

`func (o *ManaV2BgpNeighborConfig) HasAsOverride() bool`

HasAsOverride returns a boolean if a field has been set.

### GetBfd

`func (o *ManaV2BgpNeighborConfig) GetBfd() ManaV2NullableBfdInstanceConfig`

GetBfd returns the Bfd field if non-nil, zero value otherwise.

### GetBfdOk

`func (o *ManaV2BgpNeighborConfig) GetBfdOk() (*ManaV2NullableBfdInstanceConfig, bool)`

GetBfdOk returns a tuple with the Bfd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBfd

`func (o *ManaV2BgpNeighborConfig) SetBfd(v ManaV2NullableBfdInstanceConfig)`

SetBfd sets Bfd field to given value.

### HasBfd

`func (o *ManaV2BgpNeighborConfig) HasBfd() bool`

HasBfd returns a boolean if a field has been set.

### GetDefaultOriginate

`func (o *ManaV2BgpNeighborConfig) GetDefaultOriginate() string`

GetDefaultOriginate returns the DefaultOriginate field if non-nil, zero value otherwise.

### GetDefaultOriginateOk

`func (o *ManaV2BgpNeighborConfig) GetDefaultOriginateOk() (*string, bool)`

GetDefaultOriginateOk returns a tuple with the DefaultOriginate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultOriginate

`func (o *ManaV2BgpNeighborConfig) SetDefaultOriginate(v string)`

SetDefaultOriginate sets DefaultOriginate field to given value.

### HasDefaultOriginate

`func (o *ManaV2BgpNeighborConfig) HasDefaultOriginate() bool`

HasDefaultOriginate returns a boolean if a field has been set.

### GetEbgpMultihopTtl

`func (o *ManaV2BgpNeighborConfig) GetEbgpMultihopTtl() ManaV2NullableEbgpConfig`

GetEbgpMultihopTtl returns the EbgpMultihopTtl field if non-nil, zero value otherwise.

### GetEbgpMultihopTtlOk

`func (o *ManaV2BgpNeighborConfig) GetEbgpMultihopTtlOk() (*ManaV2NullableEbgpConfig, bool)`

GetEbgpMultihopTtlOk returns a tuple with the EbgpMultihopTtl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEbgpMultihopTtl

`func (o *ManaV2BgpNeighborConfig) SetEbgpMultihopTtl(v ManaV2NullableEbgpConfig)`

SetEbgpMultihopTtl sets EbgpMultihopTtl field to given value.

### HasEbgpMultihopTtl

`func (o *ManaV2BgpNeighborConfig) HasEbgpMultihopTtl() bool`

HasEbgpMultihopTtl returns a boolean if a field has been set.

### GetEnabled

`func (o *ManaV2BgpNeighborConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManaV2BgpNeighborConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManaV2BgpNeighborConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManaV2BgpNeighborConfig) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetHoldTimer

`func (o *ManaV2BgpNeighborConfig) GetHoldTimer() int32`

GetHoldTimer returns the HoldTimer field if non-nil, zero value otherwise.

### GetHoldTimerOk

`func (o *ManaV2BgpNeighborConfig) GetHoldTimerOk() (*int32, bool)`

GetHoldTimerOk returns a tuple with the HoldTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoldTimer

`func (o *ManaV2BgpNeighborConfig) SetHoldTimer(v int32)`

SetHoldTimer sets HoldTimer field to given value.

### HasHoldTimer

`func (o *ManaV2BgpNeighborConfig) HasHoldTimer() bool`

HasHoldTimer returns a boolean if a field has been set.

### GetHoldTimerValue

`func (o *ManaV2BgpNeighborConfig) GetHoldTimerValue() ManaV2NullableHoldTimer`

GetHoldTimerValue returns the HoldTimerValue field if non-nil, zero value otherwise.

### GetHoldTimerValueOk

`func (o *ManaV2BgpNeighborConfig) GetHoldTimerValueOk() (*ManaV2NullableHoldTimer, bool)`

GetHoldTimerValueOk returns a tuple with the HoldTimerValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoldTimerValue

`func (o *ManaV2BgpNeighborConfig) SetHoldTimerValue(v ManaV2NullableHoldTimer)`

SetHoldTimerValue sets HoldTimerValue field to given value.

### HasHoldTimerValue

`func (o *ManaV2BgpNeighborConfig) HasHoldTimerValue() bool`

HasHoldTimerValue returns a boolean if a field has been set.

### GetKeepaliveTimer

`func (o *ManaV2BgpNeighborConfig) GetKeepaliveTimer() int32`

GetKeepaliveTimer returns the KeepaliveTimer field if non-nil, zero value otherwise.

### GetKeepaliveTimerOk

`func (o *ManaV2BgpNeighborConfig) GetKeepaliveTimerOk() (*int32, bool)`

GetKeepaliveTimerOk returns a tuple with the KeepaliveTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepaliveTimer

`func (o *ManaV2BgpNeighborConfig) SetKeepaliveTimer(v int32)`

SetKeepaliveTimer sets KeepaliveTimer field to given value.

### HasKeepaliveTimer

`func (o *ManaV2BgpNeighborConfig) HasKeepaliveTimer() bool`

HasKeepaliveTimer returns a boolean if a field has been set.

### GetKeepaliveTimerValue

`func (o *ManaV2BgpNeighborConfig) GetKeepaliveTimerValue() ManaV2NullableKeepAliveTimer`

GetKeepaliveTimerValue returns the KeepaliveTimerValue field if non-nil, zero value otherwise.

### GetKeepaliveTimerValueOk

`func (o *ManaV2BgpNeighborConfig) GetKeepaliveTimerValueOk() (*ManaV2NullableKeepAliveTimer, bool)`

GetKeepaliveTimerValueOk returns a tuple with the KeepaliveTimerValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepaliveTimerValue

`func (o *ManaV2BgpNeighborConfig) SetKeepaliveTimerValue(v ManaV2NullableKeepAliveTimer)`

SetKeepaliveTimerValue sets KeepaliveTimerValue field to given value.

### HasKeepaliveTimerValue

`func (o *ManaV2BgpNeighborConfig) HasKeepaliveTimerValue() bool`

HasKeepaliveTimerValue returns a boolean if a field has been set.

### GetLocalAddress

`func (o *ManaV2BgpNeighborConfig) GetLocalAddress() string`

GetLocalAddress returns the LocalAddress field if non-nil, zero value otherwise.

### GetLocalAddressOk

`func (o *ManaV2BgpNeighborConfig) GetLocalAddressOk() (*string, bool)`

GetLocalAddressOk returns a tuple with the LocalAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAddress

`func (o *ManaV2BgpNeighborConfig) SetLocalAddress(v string)`

SetLocalAddress sets LocalAddress field to given value.

### HasLocalAddress

`func (o *ManaV2BgpNeighborConfig) HasLocalAddress() bool`

HasLocalAddress returns a boolean if a field has been set.

### GetLocalInterface

`func (o *ManaV2BgpNeighborConfig) GetLocalInterface() ManaV2NullableInterfaceName`

GetLocalInterface returns the LocalInterface field if non-nil, zero value otherwise.

### GetLocalInterfaceOk

`func (o *ManaV2BgpNeighborConfig) GetLocalInterfaceOk() (*ManaV2NullableInterfaceName, bool)`

GetLocalInterfaceOk returns a tuple with the LocalInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalInterface

`func (o *ManaV2BgpNeighborConfig) SetLocalInterface(v ManaV2NullableInterfaceName)`

SetLocalInterface sets LocalInterface field to given value.

### HasLocalInterface

`func (o *ManaV2BgpNeighborConfig) HasLocalInterface() bool`

HasLocalInterface returns a boolean if a field has been set.

### GetMaxPrefixValue

`func (o *ManaV2BgpNeighborConfig) GetMaxPrefixValue() ManaV2NullableMaxPrefix`

GetMaxPrefixValue returns the MaxPrefixValue field if non-nil, zero value otherwise.

### GetMaxPrefixValueOk

`func (o *ManaV2BgpNeighborConfig) GetMaxPrefixValueOk() (*ManaV2NullableMaxPrefix, bool)`

GetMaxPrefixValueOk returns a tuple with the MaxPrefixValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPrefixValue

`func (o *ManaV2BgpNeighborConfig) SetMaxPrefixValue(v ManaV2NullableMaxPrefix)`

SetMaxPrefixValue sets MaxPrefixValue field to given value.

### HasMaxPrefixValue

`func (o *ManaV2BgpNeighborConfig) HasMaxPrefixValue() bool`

HasMaxPrefixValue returns a boolean if a field has been set.

### GetMd5Password

`func (o *ManaV2BgpNeighborConfig) GetMd5Password() ManaV2NullableMd5Password`

GetMd5Password returns the Md5Password field if non-nil, zero value otherwise.

### GetMd5PasswordOk

`func (o *ManaV2BgpNeighborConfig) GetMd5PasswordOk() (*ManaV2NullableMd5Password, bool)`

GetMd5PasswordOk returns a tuple with the Md5Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5Password

`func (o *ManaV2BgpNeighborConfig) SetMd5Password(v ManaV2NullableMd5Password)`

SetMd5Password sets Md5Password field to given value.

### HasMd5Password

`func (o *ManaV2BgpNeighborConfig) HasMd5Password() bool`

HasMd5Password returns a boolean if a field has been set.

### GetPeerAsn

`func (o *ManaV2BgpNeighborConfig) GetPeerAsn() int32`

GetPeerAsn returns the PeerAsn field if non-nil, zero value otherwise.

### GetPeerAsnOk

`func (o *ManaV2BgpNeighborConfig) GetPeerAsnOk() (*int32, bool)`

GetPeerAsnOk returns a tuple with the PeerAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerAsn

`func (o *ManaV2BgpNeighborConfig) SetPeerAsn(v int32)`

SetPeerAsn sets PeerAsn field to given value.

### HasPeerAsn

`func (o *ManaV2BgpNeighborConfig) HasPeerAsn() bool`

HasPeerAsn returns a boolean if a field has been set.

### GetRemoteAddress

`func (o *ManaV2BgpNeighborConfig) GetRemoteAddress() string`

GetRemoteAddress returns the RemoteAddress field if non-nil, zero value otherwise.

### GetRemoteAddressOk

`func (o *ManaV2BgpNeighborConfig) GetRemoteAddressOk() (*string, bool)`

GetRemoteAddressOk returns a tuple with the RemoteAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteAddress

`func (o *ManaV2BgpNeighborConfig) SetRemoteAddress(v string)`

SetRemoteAddress sets RemoteAddress field to given value.

### HasRemoteAddress

`func (o *ManaV2BgpNeighborConfig) HasRemoteAddress() bool`

HasRemoteAddress returns a boolean if a field has been set.

### GetRemovePrivateAs

`func (o *ManaV2BgpNeighborConfig) GetRemovePrivateAs() bool`

GetRemovePrivateAs returns the RemovePrivateAs field if non-nil, zero value otherwise.

### GetRemovePrivateAsOk

`func (o *ManaV2BgpNeighborConfig) GetRemovePrivateAsOk() (*bool, bool)`

GetRemovePrivateAsOk returns a tuple with the RemovePrivateAs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovePrivateAs

`func (o *ManaV2BgpNeighborConfig) SetRemovePrivateAs(v bool)`

SetRemovePrivateAs sets RemovePrivateAs field to given value.

### HasRemovePrivateAs

`func (o *ManaV2BgpNeighborConfig) HasRemovePrivateAs() bool`

HasRemovePrivateAs returns a boolean if a field has been set.

### GetSendCommunity

`func (o *ManaV2BgpNeighborConfig) GetSendCommunity() bool`

GetSendCommunity returns the SendCommunity field if non-nil, zero value otherwise.

### GetSendCommunityOk

`func (o *ManaV2BgpNeighborConfig) GetSendCommunityOk() (*bool, bool)`

GetSendCommunityOk returns a tuple with the SendCommunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendCommunity

`func (o *ManaV2BgpNeighborConfig) SetSendCommunity(v bool)`

SetSendCommunity sets SendCommunity field to given value.

### HasSendCommunity

`func (o *ManaV2BgpNeighborConfig) HasSendCommunity() bool`

HasSendCommunity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



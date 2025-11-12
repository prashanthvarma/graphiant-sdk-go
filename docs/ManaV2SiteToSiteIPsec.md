# ManaV2SiteToSiteIPsec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bgp** | Pointer to [**ManaV2SiteToSiteIPsecIPsecBgpRoutes**](ManaV2SiteToSiteIPsecIPsecBgpRoutes.md) |  | [optional] 
**DestinationAddress** | Pointer to **string** |  | [optional] 
**IkeInitiator** | Pointer to **bool** |  | [optional] 
**IpsecLabel** | Pointer to **string** |  | [optional] 
**Lan** | Pointer to **string** |  | [optional] 
**LocalAddressV4** | Pointer to **string** |  | [optional] 
**LocalAddressV6** | Pointer to **string** |  | [optional] 
**LocalCircuit** | Pointer to **string** |  | [optional] 
**LocalIkePeerIdentity** | Pointer to **string** |  | [optional] 
**Mtu** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PresharedKey** | Pointer to **string** |  | [optional] 
**RemoteAddressV4** | Pointer to **string** |  | [optional] 
**RemoteAddressV6** | Pointer to **string** |  | [optional] 
**RemoteIkePeerIdentity** | Pointer to **string** |  | [optional] 
**Static** | Pointer to [**ManaV2SiteToSiteIPsecIPsecStaticRoutes**](ManaV2SiteToSiteIPsecIPsecStaticRoutes.md) |  | [optional] 
**TcpMss** | Pointer to **int32** |  | [optional] 
**VpnProfile** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SiteToSiteIPsec

`func NewManaV2SiteToSiteIPsec() *ManaV2SiteToSiteIPsec`

NewManaV2SiteToSiteIPsec instantiates a new ManaV2SiteToSiteIPsec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SiteToSiteIPsecWithDefaults

`func NewManaV2SiteToSiteIPsecWithDefaults() *ManaV2SiteToSiteIPsec`

NewManaV2SiteToSiteIPsecWithDefaults instantiates a new ManaV2SiteToSiteIPsec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgp

`func (o *ManaV2SiteToSiteIPsec) GetBgp() ManaV2SiteToSiteIPsecIPsecBgpRoutes`

GetBgp returns the Bgp field if non-nil, zero value otherwise.

### GetBgpOk

`func (o *ManaV2SiteToSiteIPsec) GetBgpOk() (*ManaV2SiteToSiteIPsecIPsecBgpRoutes, bool)`

GetBgpOk returns a tuple with the Bgp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgp

`func (o *ManaV2SiteToSiteIPsec) SetBgp(v ManaV2SiteToSiteIPsecIPsecBgpRoutes)`

SetBgp sets Bgp field to given value.

### HasBgp

`func (o *ManaV2SiteToSiteIPsec) HasBgp() bool`

HasBgp returns a boolean if a field has been set.

### GetDestinationAddress

`func (o *ManaV2SiteToSiteIPsec) GetDestinationAddress() string`

GetDestinationAddress returns the DestinationAddress field if non-nil, zero value otherwise.

### GetDestinationAddressOk

`func (o *ManaV2SiteToSiteIPsec) GetDestinationAddressOk() (*string, bool)`

GetDestinationAddressOk returns a tuple with the DestinationAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationAddress

`func (o *ManaV2SiteToSiteIPsec) SetDestinationAddress(v string)`

SetDestinationAddress sets DestinationAddress field to given value.

### HasDestinationAddress

`func (o *ManaV2SiteToSiteIPsec) HasDestinationAddress() bool`

HasDestinationAddress returns a boolean if a field has been set.

### GetIkeInitiator

`func (o *ManaV2SiteToSiteIPsec) GetIkeInitiator() bool`

GetIkeInitiator returns the IkeInitiator field if non-nil, zero value otherwise.

### GetIkeInitiatorOk

`func (o *ManaV2SiteToSiteIPsec) GetIkeInitiatorOk() (*bool, bool)`

GetIkeInitiatorOk returns a tuple with the IkeInitiator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeInitiator

`func (o *ManaV2SiteToSiteIPsec) SetIkeInitiator(v bool)`

SetIkeInitiator sets IkeInitiator field to given value.

### HasIkeInitiator

`func (o *ManaV2SiteToSiteIPsec) HasIkeInitiator() bool`

HasIkeInitiator returns a boolean if a field has been set.

### GetIpsecLabel

`func (o *ManaV2SiteToSiteIPsec) GetIpsecLabel() string`

GetIpsecLabel returns the IpsecLabel field if non-nil, zero value otherwise.

### GetIpsecLabelOk

`func (o *ManaV2SiteToSiteIPsec) GetIpsecLabelOk() (*string, bool)`

GetIpsecLabelOk returns a tuple with the IpsecLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecLabel

`func (o *ManaV2SiteToSiteIPsec) SetIpsecLabel(v string)`

SetIpsecLabel sets IpsecLabel field to given value.

### HasIpsecLabel

`func (o *ManaV2SiteToSiteIPsec) HasIpsecLabel() bool`

HasIpsecLabel returns a boolean if a field has been set.

### GetLan

`func (o *ManaV2SiteToSiteIPsec) GetLan() string`

GetLan returns the Lan field if non-nil, zero value otherwise.

### GetLanOk

`func (o *ManaV2SiteToSiteIPsec) GetLanOk() (*string, bool)`

GetLanOk returns a tuple with the Lan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLan

`func (o *ManaV2SiteToSiteIPsec) SetLan(v string)`

SetLan sets Lan field to given value.

### HasLan

`func (o *ManaV2SiteToSiteIPsec) HasLan() bool`

HasLan returns a boolean if a field has been set.

### GetLocalAddressV4

`func (o *ManaV2SiteToSiteIPsec) GetLocalAddressV4() string`

GetLocalAddressV4 returns the LocalAddressV4 field if non-nil, zero value otherwise.

### GetLocalAddressV4Ok

`func (o *ManaV2SiteToSiteIPsec) GetLocalAddressV4Ok() (*string, bool)`

GetLocalAddressV4Ok returns a tuple with the LocalAddressV4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAddressV4

`func (o *ManaV2SiteToSiteIPsec) SetLocalAddressV4(v string)`

SetLocalAddressV4 sets LocalAddressV4 field to given value.

### HasLocalAddressV4

`func (o *ManaV2SiteToSiteIPsec) HasLocalAddressV4() bool`

HasLocalAddressV4 returns a boolean if a field has been set.

### GetLocalAddressV6

`func (o *ManaV2SiteToSiteIPsec) GetLocalAddressV6() string`

GetLocalAddressV6 returns the LocalAddressV6 field if non-nil, zero value otherwise.

### GetLocalAddressV6Ok

`func (o *ManaV2SiteToSiteIPsec) GetLocalAddressV6Ok() (*string, bool)`

GetLocalAddressV6Ok returns a tuple with the LocalAddressV6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAddressV6

`func (o *ManaV2SiteToSiteIPsec) SetLocalAddressV6(v string)`

SetLocalAddressV6 sets LocalAddressV6 field to given value.

### HasLocalAddressV6

`func (o *ManaV2SiteToSiteIPsec) HasLocalAddressV6() bool`

HasLocalAddressV6 returns a boolean if a field has been set.

### GetLocalCircuit

`func (o *ManaV2SiteToSiteIPsec) GetLocalCircuit() string`

GetLocalCircuit returns the LocalCircuit field if non-nil, zero value otherwise.

### GetLocalCircuitOk

`func (o *ManaV2SiteToSiteIPsec) GetLocalCircuitOk() (*string, bool)`

GetLocalCircuitOk returns a tuple with the LocalCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalCircuit

`func (o *ManaV2SiteToSiteIPsec) SetLocalCircuit(v string)`

SetLocalCircuit sets LocalCircuit field to given value.

### HasLocalCircuit

`func (o *ManaV2SiteToSiteIPsec) HasLocalCircuit() bool`

HasLocalCircuit returns a boolean if a field has been set.

### GetLocalIkePeerIdentity

`func (o *ManaV2SiteToSiteIPsec) GetLocalIkePeerIdentity() string`

GetLocalIkePeerIdentity returns the LocalIkePeerIdentity field if non-nil, zero value otherwise.

### GetLocalIkePeerIdentityOk

`func (o *ManaV2SiteToSiteIPsec) GetLocalIkePeerIdentityOk() (*string, bool)`

GetLocalIkePeerIdentityOk returns a tuple with the LocalIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIkePeerIdentity

`func (o *ManaV2SiteToSiteIPsec) SetLocalIkePeerIdentity(v string)`

SetLocalIkePeerIdentity sets LocalIkePeerIdentity field to given value.

### HasLocalIkePeerIdentity

`func (o *ManaV2SiteToSiteIPsec) HasLocalIkePeerIdentity() bool`

HasLocalIkePeerIdentity returns a boolean if a field has been set.

### GetMtu

`func (o *ManaV2SiteToSiteIPsec) GetMtu() int32`

GetMtu returns the Mtu field if non-nil, zero value otherwise.

### GetMtuOk

`func (o *ManaV2SiteToSiteIPsec) GetMtuOk() (*int32, bool)`

GetMtuOk returns a tuple with the Mtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMtu

`func (o *ManaV2SiteToSiteIPsec) SetMtu(v int32)`

SetMtu sets Mtu field to given value.

### HasMtu

`func (o *ManaV2SiteToSiteIPsec) HasMtu() bool`

HasMtu returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SiteToSiteIPsec) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SiteToSiteIPsec) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SiteToSiteIPsec) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SiteToSiteIPsec) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPresharedKey

`func (o *ManaV2SiteToSiteIPsec) GetPresharedKey() string`

GetPresharedKey returns the PresharedKey field if non-nil, zero value otherwise.

### GetPresharedKeyOk

`func (o *ManaV2SiteToSiteIPsec) GetPresharedKeyOk() (*string, bool)`

GetPresharedKeyOk returns a tuple with the PresharedKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresharedKey

`func (o *ManaV2SiteToSiteIPsec) SetPresharedKey(v string)`

SetPresharedKey sets PresharedKey field to given value.

### HasPresharedKey

`func (o *ManaV2SiteToSiteIPsec) HasPresharedKey() bool`

HasPresharedKey returns a boolean if a field has been set.

### GetRemoteAddressV4

`func (o *ManaV2SiteToSiteIPsec) GetRemoteAddressV4() string`

GetRemoteAddressV4 returns the RemoteAddressV4 field if non-nil, zero value otherwise.

### GetRemoteAddressV4Ok

`func (o *ManaV2SiteToSiteIPsec) GetRemoteAddressV4Ok() (*string, bool)`

GetRemoteAddressV4Ok returns a tuple with the RemoteAddressV4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteAddressV4

`func (o *ManaV2SiteToSiteIPsec) SetRemoteAddressV4(v string)`

SetRemoteAddressV4 sets RemoteAddressV4 field to given value.

### HasRemoteAddressV4

`func (o *ManaV2SiteToSiteIPsec) HasRemoteAddressV4() bool`

HasRemoteAddressV4 returns a boolean if a field has been set.

### GetRemoteAddressV6

`func (o *ManaV2SiteToSiteIPsec) GetRemoteAddressV6() string`

GetRemoteAddressV6 returns the RemoteAddressV6 field if non-nil, zero value otherwise.

### GetRemoteAddressV6Ok

`func (o *ManaV2SiteToSiteIPsec) GetRemoteAddressV6Ok() (*string, bool)`

GetRemoteAddressV6Ok returns a tuple with the RemoteAddressV6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteAddressV6

`func (o *ManaV2SiteToSiteIPsec) SetRemoteAddressV6(v string)`

SetRemoteAddressV6 sets RemoteAddressV6 field to given value.

### HasRemoteAddressV6

`func (o *ManaV2SiteToSiteIPsec) HasRemoteAddressV6() bool`

HasRemoteAddressV6 returns a boolean if a field has been set.

### GetRemoteIkePeerIdentity

`func (o *ManaV2SiteToSiteIPsec) GetRemoteIkePeerIdentity() string`

GetRemoteIkePeerIdentity returns the RemoteIkePeerIdentity field if non-nil, zero value otherwise.

### GetRemoteIkePeerIdentityOk

`func (o *ManaV2SiteToSiteIPsec) GetRemoteIkePeerIdentityOk() (*string, bool)`

GetRemoteIkePeerIdentityOk returns a tuple with the RemoteIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteIkePeerIdentity

`func (o *ManaV2SiteToSiteIPsec) SetRemoteIkePeerIdentity(v string)`

SetRemoteIkePeerIdentity sets RemoteIkePeerIdentity field to given value.

### HasRemoteIkePeerIdentity

`func (o *ManaV2SiteToSiteIPsec) HasRemoteIkePeerIdentity() bool`

HasRemoteIkePeerIdentity returns a boolean if a field has been set.

### GetStatic

`func (o *ManaV2SiteToSiteIPsec) GetStatic() ManaV2SiteToSiteIPsecIPsecStaticRoutes`

GetStatic returns the Static field if non-nil, zero value otherwise.

### GetStaticOk

`func (o *ManaV2SiteToSiteIPsec) GetStaticOk() (*ManaV2SiteToSiteIPsecIPsecStaticRoutes, bool)`

GetStaticOk returns a tuple with the Static field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatic

`func (o *ManaV2SiteToSiteIPsec) SetStatic(v ManaV2SiteToSiteIPsecIPsecStaticRoutes)`

SetStatic sets Static field to given value.

### HasStatic

`func (o *ManaV2SiteToSiteIPsec) HasStatic() bool`

HasStatic returns a boolean if a field has been set.

### GetTcpMss

`func (o *ManaV2SiteToSiteIPsec) GetTcpMss() int32`

GetTcpMss returns the TcpMss field if non-nil, zero value otherwise.

### GetTcpMssOk

`func (o *ManaV2SiteToSiteIPsec) GetTcpMssOk() (*int32, bool)`

GetTcpMssOk returns a tuple with the TcpMss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpMss

`func (o *ManaV2SiteToSiteIPsec) SetTcpMss(v int32)`

SetTcpMss sets TcpMss field to given value.

### HasTcpMss

`func (o *ManaV2SiteToSiteIPsec) HasTcpMss() bool`

HasTcpMss returns a boolean if a field has been set.

### GetVpnProfile

`func (o *ManaV2SiteToSiteIPsec) GetVpnProfile() string`

GetVpnProfile returns the VpnProfile field if non-nil, zero value otherwise.

### GetVpnProfileOk

`func (o *ManaV2SiteToSiteIPsec) GetVpnProfileOk() (*string, bool)`

GetVpnProfileOk returns a tuple with the VpnProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpnProfile

`func (o *ManaV2SiteToSiteIPsec) SetVpnProfile(v string)`

SetVpnProfile sets VpnProfile field to given value.

### HasVpnProfile

`func (o *ManaV2SiteToSiteIPsec) HasVpnProfile() bool`

HasVpnProfile returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



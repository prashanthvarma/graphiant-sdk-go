# ManaV2InterfaceIPsecConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AntiReplayWindowSize** | Pointer to **int32** |  | [optional] 
**DhGroup** | Pointer to **string** |  | [optional] 
**DpdInterval** | Pointer to **int32** |  | [optional] 
**EncryptionAlg** | Pointer to **string** |  | [optional] 
**Esn** | Pointer to **bool** |  | [optional] 
**IkeIntegrity** | Pointer to **string** |  | [optional] 
**Initiator** | Pointer to **bool** |  | [optional] 
**IpsecEncryptionAlg** | Pointer to **string** |  | [optional] 
**IpsecIntegrity** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**LocalAddress** | Pointer to **string** |  | [optional] 
**LocalCircuit** | Pointer to **string** |  | [optional] 
**LocalIkePeerIdentity** | Pointer to **string** |  | [optional] 
**PerfectForwardSecrecy** | Pointer to **string** |  | [optional] 
**PresharedKey** | Pointer to **string** |  | [optional] 
**ReauthInterval** | Pointer to **int32** |  | [optional] 
**RekeyInterval** | Pointer to **int32** |  | [optional] 
**RemoteAddress** | Pointer to **string** |  | [optional] 
**RemoteIkePeerIdentity** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2InterfaceIPsecConfig

`func NewManaV2InterfaceIPsecConfig() *ManaV2InterfaceIPsecConfig`

NewManaV2InterfaceIPsecConfig instantiates a new ManaV2InterfaceIPsecConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2InterfaceIPsecConfigWithDefaults

`func NewManaV2InterfaceIPsecConfigWithDefaults() *ManaV2InterfaceIPsecConfig`

NewManaV2InterfaceIPsecConfigWithDefaults instantiates a new ManaV2InterfaceIPsecConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAntiReplayWindowSize

`func (o *ManaV2InterfaceIPsecConfig) GetAntiReplayWindowSize() int32`

GetAntiReplayWindowSize returns the AntiReplayWindowSize field if non-nil, zero value otherwise.

### GetAntiReplayWindowSizeOk

`func (o *ManaV2InterfaceIPsecConfig) GetAntiReplayWindowSizeOk() (*int32, bool)`

GetAntiReplayWindowSizeOk returns a tuple with the AntiReplayWindowSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAntiReplayWindowSize

`func (o *ManaV2InterfaceIPsecConfig) SetAntiReplayWindowSize(v int32)`

SetAntiReplayWindowSize sets AntiReplayWindowSize field to given value.

### HasAntiReplayWindowSize

`func (o *ManaV2InterfaceIPsecConfig) HasAntiReplayWindowSize() bool`

HasAntiReplayWindowSize returns a boolean if a field has been set.

### GetDhGroup

`func (o *ManaV2InterfaceIPsecConfig) GetDhGroup() string`

GetDhGroup returns the DhGroup field if non-nil, zero value otherwise.

### GetDhGroupOk

`func (o *ManaV2InterfaceIPsecConfig) GetDhGroupOk() (*string, bool)`

GetDhGroupOk returns a tuple with the DhGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhGroup

`func (o *ManaV2InterfaceIPsecConfig) SetDhGroup(v string)`

SetDhGroup sets DhGroup field to given value.

### HasDhGroup

`func (o *ManaV2InterfaceIPsecConfig) HasDhGroup() bool`

HasDhGroup returns a boolean if a field has been set.

### GetDpdInterval

`func (o *ManaV2InterfaceIPsecConfig) GetDpdInterval() int32`

GetDpdInterval returns the DpdInterval field if non-nil, zero value otherwise.

### GetDpdIntervalOk

`func (o *ManaV2InterfaceIPsecConfig) GetDpdIntervalOk() (*int32, bool)`

GetDpdIntervalOk returns a tuple with the DpdInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpdInterval

`func (o *ManaV2InterfaceIPsecConfig) SetDpdInterval(v int32)`

SetDpdInterval sets DpdInterval field to given value.

### HasDpdInterval

`func (o *ManaV2InterfaceIPsecConfig) HasDpdInterval() bool`

HasDpdInterval returns a boolean if a field has been set.

### GetEncryptionAlg

`func (o *ManaV2InterfaceIPsecConfig) GetEncryptionAlg() string`

GetEncryptionAlg returns the EncryptionAlg field if non-nil, zero value otherwise.

### GetEncryptionAlgOk

`func (o *ManaV2InterfaceIPsecConfig) GetEncryptionAlgOk() (*string, bool)`

GetEncryptionAlgOk returns a tuple with the EncryptionAlg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptionAlg

`func (o *ManaV2InterfaceIPsecConfig) SetEncryptionAlg(v string)`

SetEncryptionAlg sets EncryptionAlg field to given value.

### HasEncryptionAlg

`func (o *ManaV2InterfaceIPsecConfig) HasEncryptionAlg() bool`

HasEncryptionAlg returns a boolean if a field has been set.

### GetEsn

`func (o *ManaV2InterfaceIPsecConfig) GetEsn() bool`

GetEsn returns the Esn field if non-nil, zero value otherwise.

### GetEsnOk

`func (o *ManaV2InterfaceIPsecConfig) GetEsnOk() (*bool, bool)`

GetEsnOk returns a tuple with the Esn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEsn

`func (o *ManaV2InterfaceIPsecConfig) SetEsn(v bool)`

SetEsn sets Esn field to given value.

### HasEsn

`func (o *ManaV2InterfaceIPsecConfig) HasEsn() bool`

HasEsn returns a boolean if a field has been set.

### GetIkeIntegrity

`func (o *ManaV2InterfaceIPsecConfig) GetIkeIntegrity() string`

GetIkeIntegrity returns the IkeIntegrity field if non-nil, zero value otherwise.

### GetIkeIntegrityOk

`func (o *ManaV2InterfaceIPsecConfig) GetIkeIntegrityOk() (*string, bool)`

GetIkeIntegrityOk returns a tuple with the IkeIntegrity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeIntegrity

`func (o *ManaV2InterfaceIPsecConfig) SetIkeIntegrity(v string)`

SetIkeIntegrity sets IkeIntegrity field to given value.

### HasIkeIntegrity

`func (o *ManaV2InterfaceIPsecConfig) HasIkeIntegrity() bool`

HasIkeIntegrity returns a boolean if a field has been set.

### GetInitiator

`func (o *ManaV2InterfaceIPsecConfig) GetInitiator() bool`

GetInitiator returns the Initiator field if non-nil, zero value otherwise.

### GetInitiatorOk

`func (o *ManaV2InterfaceIPsecConfig) GetInitiatorOk() (*bool, bool)`

GetInitiatorOk returns a tuple with the Initiator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitiator

`func (o *ManaV2InterfaceIPsecConfig) SetInitiator(v bool)`

SetInitiator sets Initiator field to given value.

### HasInitiator

`func (o *ManaV2InterfaceIPsecConfig) HasInitiator() bool`

HasInitiator returns a boolean if a field has been set.

### GetIpsecEncryptionAlg

`func (o *ManaV2InterfaceIPsecConfig) GetIpsecEncryptionAlg() string`

GetIpsecEncryptionAlg returns the IpsecEncryptionAlg field if non-nil, zero value otherwise.

### GetIpsecEncryptionAlgOk

`func (o *ManaV2InterfaceIPsecConfig) GetIpsecEncryptionAlgOk() (*string, bool)`

GetIpsecEncryptionAlgOk returns a tuple with the IpsecEncryptionAlg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecEncryptionAlg

`func (o *ManaV2InterfaceIPsecConfig) SetIpsecEncryptionAlg(v string)`

SetIpsecEncryptionAlg sets IpsecEncryptionAlg field to given value.

### HasIpsecEncryptionAlg

`func (o *ManaV2InterfaceIPsecConfig) HasIpsecEncryptionAlg() bool`

HasIpsecEncryptionAlg returns a boolean if a field has been set.

### GetIpsecIntegrity

`func (o *ManaV2InterfaceIPsecConfig) GetIpsecIntegrity() string`

GetIpsecIntegrity returns the IpsecIntegrity field if non-nil, zero value otherwise.

### GetIpsecIntegrityOk

`func (o *ManaV2InterfaceIPsecConfig) GetIpsecIntegrityOk() (*string, bool)`

GetIpsecIntegrityOk returns a tuple with the IpsecIntegrity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecIntegrity

`func (o *ManaV2InterfaceIPsecConfig) SetIpsecIntegrity(v string)`

SetIpsecIntegrity sets IpsecIntegrity field to given value.

### HasIpsecIntegrity

`func (o *ManaV2InterfaceIPsecConfig) HasIpsecIntegrity() bool`

HasIpsecIntegrity returns a boolean if a field has been set.

### GetLabel

`func (o *ManaV2InterfaceIPsecConfig) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ManaV2InterfaceIPsecConfig) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ManaV2InterfaceIPsecConfig) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ManaV2InterfaceIPsecConfig) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetLocalAddress

`func (o *ManaV2InterfaceIPsecConfig) GetLocalAddress() string`

GetLocalAddress returns the LocalAddress field if non-nil, zero value otherwise.

### GetLocalAddressOk

`func (o *ManaV2InterfaceIPsecConfig) GetLocalAddressOk() (*string, bool)`

GetLocalAddressOk returns a tuple with the LocalAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAddress

`func (o *ManaV2InterfaceIPsecConfig) SetLocalAddress(v string)`

SetLocalAddress sets LocalAddress field to given value.

### HasLocalAddress

`func (o *ManaV2InterfaceIPsecConfig) HasLocalAddress() bool`

HasLocalAddress returns a boolean if a field has been set.

### GetLocalCircuit

`func (o *ManaV2InterfaceIPsecConfig) GetLocalCircuit() string`

GetLocalCircuit returns the LocalCircuit field if non-nil, zero value otherwise.

### GetLocalCircuitOk

`func (o *ManaV2InterfaceIPsecConfig) GetLocalCircuitOk() (*string, bool)`

GetLocalCircuitOk returns a tuple with the LocalCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalCircuit

`func (o *ManaV2InterfaceIPsecConfig) SetLocalCircuit(v string)`

SetLocalCircuit sets LocalCircuit field to given value.

### HasLocalCircuit

`func (o *ManaV2InterfaceIPsecConfig) HasLocalCircuit() bool`

HasLocalCircuit returns a boolean if a field has been set.

### GetLocalIkePeerIdentity

`func (o *ManaV2InterfaceIPsecConfig) GetLocalIkePeerIdentity() string`

GetLocalIkePeerIdentity returns the LocalIkePeerIdentity field if non-nil, zero value otherwise.

### GetLocalIkePeerIdentityOk

`func (o *ManaV2InterfaceIPsecConfig) GetLocalIkePeerIdentityOk() (*string, bool)`

GetLocalIkePeerIdentityOk returns a tuple with the LocalIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIkePeerIdentity

`func (o *ManaV2InterfaceIPsecConfig) SetLocalIkePeerIdentity(v string)`

SetLocalIkePeerIdentity sets LocalIkePeerIdentity field to given value.

### HasLocalIkePeerIdentity

`func (o *ManaV2InterfaceIPsecConfig) HasLocalIkePeerIdentity() bool`

HasLocalIkePeerIdentity returns a boolean if a field has been set.

### GetPerfectForwardSecrecy

`func (o *ManaV2InterfaceIPsecConfig) GetPerfectForwardSecrecy() string`

GetPerfectForwardSecrecy returns the PerfectForwardSecrecy field if non-nil, zero value otherwise.

### GetPerfectForwardSecrecyOk

`func (o *ManaV2InterfaceIPsecConfig) GetPerfectForwardSecrecyOk() (*string, bool)`

GetPerfectForwardSecrecyOk returns a tuple with the PerfectForwardSecrecy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerfectForwardSecrecy

`func (o *ManaV2InterfaceIPsecConfig) SetPerfectForwardSecrecy(v string)`

SetPerfectForwardSecrecy sets PerfectForwardSecrecy field to given value.

### HasPerfectForwardSecrecy

`func (o *ManaV2InterfaceIPsecConfig) HasPerfectForwardSecrecy() bool`

HasPerfectForwardSecrecy returns a boolean if a field has been set.

### GetPresharedKey

`func (o *ManaV2InterfaceIPsecConfig) GetPresharedKey() string`

GetPresharedKey returns the PresharedKey field if non-nil, zero value otherwise.

### GetPresharedKeyOk

`func (o *ManaV2InterfaceIPsecConfig) GetPresharedKeyOk() (*string, bool)`

GetPresharedKeyOk returns a tuple with the PresharedKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresharedKey

`func (o *ManaV2InterfaceIPsecConfig) SetPresharedKey(v string)`

SetPresharedKey sets PresharedKey field to given value.

### HasPresharedKey

`func (o *ManaV2InterfaceIPsecConfig) HasPresharedKey() bool`

HasPresharedKey returns a boolean if a field has been set.

### GetReauthInterval

`func (o *ManaV2InterfaceIPsecConfig) GetReauthInterval() int32`

GetReauthInterval returns the ReauthInterval field if non-nil, zero value otherwise.

### GetReauthIntervalOk

`func (o *ManaV2InterfaceIPsecConfig) GetReauthIntervalOk() (*int32, bool)`

GetReauthIntervalOk returns a tuple with the ReauthInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReauthInterval

`func (o *ManaV2InterfaceIPsecConfig) SetReauthInterval(v int32)`

SetReauthInterval sets ReauthInterval field to given value.

### HasReauthInterval

`func (o *ManaV2InterfaceIPsecConfig) HasReauthInterval() bool`

HasReauthInterval returns a boolean if a field has been set.

### GetRekeyInterval

`func (o *ManaV2InterfaceIPsecConfig) GetRekeyInterval() int32`

GetRekeyInterval returns the RekeyInterval field if non-nil, zero value otherwise.

### GetRekeyIntervalOk

`func (o *ManaV2InterfaceIPsecConfig) GetRekeyIntervalOk() (*int32, bool)`

GetRekeyIntervalOk returns a tuple with the RekeyInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRekeyInterval

`func (o *ManaV2InterfaceIPsecConfig) SetRekeyInterval(v int32)`

SetRekeyInterval sets RekeyInterval field to given value.

### HasRekeyInterval

`func (o *ManaV2InterfaceIPsecConfig) HasRekeyInterval() bool`

HasRekeyInterval returns a boolean if a field has been set.

### GetRemoteAddress

`func (o *ManaV2InterfaceIPsecConfig) GetRemoteAddress() string`

GetRemoteAddress returns the RemoteAddress field if non-nil, zero value otherwise.

### GetRemoteAddressOk

`func (o *ManaV2InterfaceIPsecConfig) GetRemoteAddressOk() (*string, bool)`

GetRemoteAddressOk returns a tuple with the RemoteAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteAddress

`func (o *ManaV2InterfaceIPsecConfig) SetRemoteAddress(v string)`

SetRemoteAddress sets RemoteAddress field to given value.

### HasRemoteAddress

`func (o *ManaV2InterfaceIPsecConfig) HasRemoteAddress() bool`

HasRemoteAddress returns a boolean if a field has been set.

### GetRemoteIkePeerIdentity

`func (o *ManaV2InterfaceIPsecConfig) GetRemoteIkePeerIdentity() string`

GetRemoteIkePeerIdentity returns the RemoteIkePeerIdentity field if non-nil, zero value otherwise.

### GetRemoteIkePeerIdentityOk

`func (o *ManaV2InterfaceIPsecConfig) GetRemoteIkePeerIdentityOk() (*string, bool)`

GetRemoteIkePeerIdentityOk returns a tuple with the RemoteIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteIkePeerIdentity

`func (o *ManaV2InterfaceIPsecConfig) SetRemoteIkePeerIdentity(v string)`

SetRemoteIkePeerIdentity sets RemoteIkePeerIdentity field to given value.

### HasRemoteIkePeerIdentity

`func (o *ManaV2InterfaceIPsecConfig) HasRemoteIkePeerIdentity() bool`

HasRemoteIkePeerIdentity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



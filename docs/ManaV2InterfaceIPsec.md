# ManaV2InterfaceIPsec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AntiReplayWindowSize** | Pointer to **int32** |  | [optional] 
**DhGroup** | Pointer to **string** |  | [optional] 
**DpdInterval** | Pointer to **int32** |  | [optional] 
**EncryptionAlg** | Pointer to **string** |  | [optional] 
**Esn** | Pointer to **bool** |  | [optional] 
**EstablishedTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**IkeIntegrity** | Pointer to **string** |  | [optional] 
**IpsecEncryptionAlg** | Pointer to **string** |  | [optional] 
**IpsecIntegrity** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**LocalAddress** | Pointer to **string** |  | [optional] 
**LocalCircuit** | Pointer to **string** |  | [optional] 
**LocalIkePeerIdentity** | Pointer to **string** |  | [optional] 
**LocalIkesaSpi** | Pointer to **int64** |  | [optional] 
**LocalPort** | Pointer to **int32** |  | [optional] 
**NegotiatedAlgo** | Pointer to **string** |  | [optional] 
**OperState** | Pointer to **bool** |  | [optional] 
**PerfectForwardSecrecy** | Pointer to **string** |  | [optional] 
**PresharedKey** | Pointer to **string** |  | [optional] 
**Protocol** | Pointer to **string** |  | [optional] 
**ReauthInterval** | Pointer to **int64** |  | [optional] 
**RekeyInterval** | Pointer to **int64** |  | [optional] 
**RemoteAddress** | Pointer to **string** |  | [optional] 
**RemoteIkePeerIdentity** | Pointer to **string** |  | [optional] 
**RemoteIkesaSpi** | Pointer to **int64** |  | [optional] 
**RemotePort** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2InterfaceIPsec

`func NewManaV2InterfaceIPsec() *ManaV2InterfaceIPsec`

NewManaV2InterfaceIPsec instantiates a new ManaV2InterfaceIPsec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2InterfaceIPsecWithDefaults

`func NewManaV2InterfaceIPsecWithDefaults() *ManaV2InterfaceIPsec`

NewManaV2InterfaceIPsecWithDefaults instantiates a new ManaV2InterfaceIPsec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAntiReplayWindowSize

`func (o *ManaV2InterfaceIPsec) GetAntiReplayWindowSize() int32`

GetAntiReplayWindowSize returns the AntiReplayWindowSize field if non-nil, zero value otherwise.

### GetAntiReplayWindowSizeOk

`func (o *ManaV2InterfaceIPsec) GetAntiReplayWindowSizeOk() (*int32, bool)`

GetAntiReplayWindowSizeOk returns a tuple with the AntiReplayWindowSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAntiReplayWindowSize

`func (o *ManaV2InterfaceIPsec) SetAntiReplayWindowSize(v int32)`

SetAntiReplayWindowSize sets AntiReplayWindowSize field to given value.

### HasAntiReplayWindowSize

`func (o *ManaV2InterfaceIPsec) HasAntiReplayWindowSize() bool`

HasAntiReplayWindowSize returns a boolean if a field has been set.

### GetDhGroup

`func (o *ManaV2InterfaceIPsec) GetDhGroup() string`

GetDhGroup returns the DhGroup field if non-nil, zero value otherwise.

### GetDhGroupOk

`func (o *ManaV2InterfaceIPsec) GetDhGroupOk() (*string, bool)`

GetDhGroupOk returns a tuple with the DhGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhGroup

`func (o *ManaV2InterfaceIPsec) SetDhGroup(v string)`

SetDhGroup sets DhGroup field to given value.

### HasDhGroup

`func (o *ManaV2InterfaceIPsec) HasDhGroup() bool`

HasDhGroup returns a boolean if a field has been set.

### GetDpdInterval

`func (o *ManaV2InterfaceIPsec) GetDpdInterval() int32`

GetDpdInterval returns the DpdInterval field if non-nil, zero value otherwise.

### GetDpdIntervalOk

`func (o *ManaV2InterfaceIPsec) GetDpdIntervalOk() (*int32, bool)`

GetDpdIntervalOk returns a tuple with the DpdInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpdInterval

`func (o *ManaV2InterfaceIPsec) SetDpdInterval(v int32)`

SetDpdInterval sets DpdInterval field to given value.

### HasDpdInterval

`func (o *ManaV2InterfaceIPsec) HasDpdInterval() bool`

HasDpdInterval returns a boolean if a field has been set.

### GetEncryptionAlg

`func (o *ManaV2InterfaceIPsec) GetEncryptionAlg() string`

GetEncryptionAlg returns the EncryptionAlg field if non-nil, zero value otherwise.

### GetEncryptionAlgOk

`func (o *ManaV2InterfaceIPsec) GetEncryptionAlgOk() (*string, bool)`

GetEncryptionAlgOk returns a tuple with the EncryptionAlg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptionAlg

`func (o *ManaV2InterfaceIPsec) SetEncryptionAlg(v string)`

SetEncryptionAlg sets EncryptionAlg field to given value.

### HasEncryptionAlg

`func (o *ManaV2InterfaceIPsec) HasEncryptionAlg() bool`

HasEncryptionAlg returns a boolean if a field has been set.

### GetEsn

`func (o *ManaV2InterfaceIPsec) GetEsn() bool`

GetEsn returns the Esn field if non-nil, zero value otherwise.

### GetEsnOk

`func (o *ManaV2InterfaceIPsec) GetEsnOk() (*bool, bool)`

GetEsnOk returns a tuple with the Esn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEsn

`func (o *ManaV2InterfaceIPsec) SetEsn(v bool)`

SetEsn sets Esn field to given value.

### HasEsn

`func (o *ManaV2InterfaceIPsec) HasEsn() bool`

HasEsn returns a boolean if a field has been set.

### GetEstablishedTime

`func (o *ManaV2InterfaceIPsec) GetEstablishedTime() GoogleProtobufTimestamp`

GetEstablishedTime returns the EstablishedTime field if non-nil, zero value otherwise.

### GetEstablishedTimeOk

`func (o *ManaV2InterfaceIPsec) GetEstablishedTimeOk() (*GoogleProtobufTimestamp, bool)`

GetEstablishedTimeOk returns a tuple with the EstablishedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstablishedTime

`func (o *ManaV2InterfaceIPsec) SetEstablishedTime(v GoogleProtobufTimestamp)`

SetEstablishedTime sets EstablishedTime field to given value.

### HasEstablishedTime

`func (o *ManaV2InterfaceIPsec) HasEstablishedTime() bool`

HasEstablishedTime returns a boolean if a field has been set.

### GetIkeIntegrity

`func (o *ManaV2InterfaceIPsec) GetIkeIntegrity() string`

GetIkeIntegrity returns the IkeIntegrity field if non-nil, zero value otherwise.

### GetIkeIntegrityOk

`func (o *ManaV2InterfaceIPsec) GetIkeIntegrityOk() (*string, bool)`

GetIkeIntegrityOk returns a tuple with the IkeIntegrity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeIntegrity

`func (o *ManaV2InterfaceIPsec) SetIkeIntegrity(v string)`

SetIkeIntegrity sets IkeIntegrity field to given value.

### HasIkeIntegrity

`func (o *ManaV2InterfaceIPsec) HasIkeIntegrity() bool`

HasIkeIntegrity returns a boolean if a field has been set.

### GetIpsecEncryptionAlg

`func (o *ManaV2InterfaceIPsec) GetIpsecEncryptionAlg() string`

GetIpsecEncryptionAlg returns the IpsecEncryptionAlg field if non-nil, zero value otherwise.

### GetIpsecEncryptionAlgOk

`func (o *ManaV2InterfaceIPsec) GetIpsecEncryptionAlgOk() (*string, bool)`

GetIpsecEncryptionAlgOk returns a tuple with the IpsecEncryptionAlg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecEncryptionAlg

`func (o *ManaV2InterfaceIPsec) SetIpsecEncryptionAlg(v string)`

SetIpsecEncryptionAlg sets IpsecEncryptionAlg field to given value.

### HasIpsecEncryptionAlg

`func (o *ManaV2InterfaceIPsec) HasIpsecEncryptionAlg() bool`

HasIpsecEncryptionAlg returns a boolean if a field has been set.

### GetIpsecIntegrity

`func (o *ManaV2InterfaceIPsec) GetIpsecIntegrity() string`

GetIpsecIntegrity returns the IpsecIntegrity field if non-nil, zero value otherwise.

### GetIpsecIntegrityOk

`func (o *ManaV2InterfaceIPsec) GetIpsecIntegrityOk() (*string, bool)`

GetIpsecIntegrityOk returns a tuple with the IpsecIntegrity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecIntegrity

`func (o *ManaV2InterfaceIPsec) SetIpsecIntegrity(v string)`

SetIpsecIntegrity sets IpsecIntegrity field to given value.

### HasIpsecIntegrity

`func (o *ManaV2InterfaceIPsec) HasIpsecIntegrity() bool`

HasIpsecIntegrity returns a boolean if a field has been set.

### GetLabel

`func (o *ManaV2InterfaceIPsec) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ManaV2InterfaceIPsec) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ManaV2InterfaceIPsec) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *ManaV2InterfaceIPsec) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetLocalAddress

`func (o *ManaV2InterfaceIPsec) GetLocalAddress() string`

GetLocalAddress returns the LocalAddress field if non-nil, zero value otherwise.

### GetLocalAddressOk

`func (o *ManaV2InterfaceIPsec) GetLocalAddressOk() (*string, bool)`

GetLocalAddressOk returns a tuple with the LocalAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAddress

`func (o *ManaV2InterfaceIPsec) SetLocalAddress(v string)`

SetLocalAddress sets LocalAddress field to given value.

### HasLocalAddress

`func (o *ManaV2InterfaceIPsec) HasLocalAddress() bool`

HasLocalAddress returns a boolean if a field has been set.

### GetLocalCircuit

`func (o *ManaV2InterfaceIPsec) GetLocalCircuit() string`

GetLocalCircuit returns the LocalCircuit field if non-nil, zero value otherwise.

### GetLocalCircuitOk

`func (o *ManaV2InterfaceIPsec) GetLocalCircuitOk() (*string, bool)`

GetLocalCircuitOk returns a tuple with the LocalCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalCircuit

`func (o *ManaV2InterfaceIPsec) SetLocalCircuit(v string)`

SetLocalCircuit sets LocalCircuit field to given value.

### HasLocalCircuit

`func (o *ManaV2InterfaceIPsec) HasLocalCircuit() bool`

HasLocalCircuit returns a boolean if a field has been set.

### GetLocalIkePeerIdentity

`func (o *ManaV2InterfaceIPsec) GetLocalIkePeerIdentity() string`

GetLocalIkePeerIdentity returns the LocalIkePeerIdentity field if non-nil, zero value otherwise.

### GetLocalIkePeerIdentityOk

`func (o *ManaV2InterfaceIPsec) GetLocalIkePeerIdentityOk() (*string, bool)`

GetLocalIkePeerIdentityOk returns a tuple with the LocalIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIkePeerIdentity

`func (o *ManaV2InterfaceIPsec) SetLocalIkePeerIdentity(v string)`

SetLocalIkePeerIdentity sets LocalIkePeerIdentity field to given value.

### HasLocalIkePeerIdentity

`func (o *ManaV2InterfaceIPsec) HasLocalIkePeerIdentity() bool`

HasLocalIkePeerIdentity returns a boolean if a field has been set.

### GetLocalIkesaSpi

`func (o *ManaV2InterfaceIPsec) GetLocalIkesaSpi() int64`

GetLocalIkesaSpi returns the LocalIkesaSpi field if non-nil, zero value otherwise.

### GetLocalIkesaSpiOk

`func (o *ManaV2InterfaceIPsec) GetLocalIkesaSpiOk() (*int64, bool)`

GetLocalIkesaSpiOk returns a tuple with the LocalIkesaSpi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIkesaSpi

`func (o *ManaV2InterfaceIPsec) SetLocalIkesaSpi(v int64)`

SetLocalIkesaSpi sets LocalIkesaSpi field to given value.

### HasLocalIkesaSpi

`func (o *ManaV2InterfaceIPsec) HasLocalIkesaSpi() bool`

HasLocalIkesaSpi returns a boolean if a field has been set.

### GetLocalPort

`func (o *ManaV2InterfaceIPsec) GetLocalPort() int32`

GetLocalPort returns the LocalPort field if non-nil, zero value otherwise.

### GetLocalPortOk

`func (o *ManaV2InterfaceIPsec) GetLocalPortOk() (*int32, bool)`

GetLocalPortOk returns a tuple with the LocalPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalPort

`func (o *ManaV2InterfaceIPsec) SetLocalPort(v int32)`

SetLocalPort sets LocalPort field to given value.

### HasLocalPort

`func (o *ManaV2InterfaceIPsec) HasLocalPort() bool`

HasLocalPort returns a boolean if a field has been set.

### GetNegotiatedAlgo

`func (o *ManaV2InterfaceIPsec) GetNegotiatedAlgo() string`

GetNegotiatedAlgo returns the NegotiatedAlgo field if non-nil, zero value otherwise.

### GetNegotiatedAlgoOk

`func (o *ManaV2InterfaceIPsec) GetNegotiatedAlgoOk() (*string, bool)`

GetNegotiatedAlgoOk returns a tuple with the NegotiatedAlgo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegotiatedAlgo

`func (o *ManaV2InterfaceIPsec) SetNegotiatedAlgo(v string)`

SetNegotiatedAlgo sets NegotiatedAlgo field to given value.

### HasNegotiatedAlgo

`func (o *ManaV2InterfaceIPsec) HasNegotiatedAlgo() bool`

HasNegotiatedAlgo returns a boolean if a field has been set.

### GetOperState

`func (o *ManaV2InterfaceIPsec) GetOperState() bool`

GetOperState returns the OperState field if non-nil, zero value otherwise.

### GetOperStateOk

`func (o *ManaV2InterfaceIPsec) GetOperStateOk() (*bool, bool)`

GetOperStateOk returns a tuple with the OperState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperState

`func (o *ManaV2InterfaceIPsec) SetOperState(v bool)`

SetOperState sets OperState field to given value.

### HasOperState

`func (o *ManaV2InterfaceIPsec) HasOperState() bool`

HasOperState returns a boolean if a field has been set.

### GetPerfectForwardSecrecy

`func (o *ManaV2InterfaceIPsec) GetPerfectForwardSecrecy() string`

GetPerfectForwardSecrecy returns the PerfectForwardSecrecy field if non-nil, zero value otherwise.

### GetPerfectForwardSecrecyOk

`func (o *ManaV2InterfaceIPsec) GetPerfectForwardSecrecyOk() (*string, bool)`

GetPerfectForwardSecrecyOk returns a tuple with the PerfectForwardSecrecy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerfectForwardSecrecy

`func (o *ManaV2InterfaceIPsec) SetPerfectForwardSecrecy(v string)`

SetPerfectForwardSecrecy sets PerfectForwardSecrecy field to given value.

### HasPerfectForwardSecrecy

`func (o *ManaV2InterfaceIPsec) HasPerfectForwardSecrecy() bool`

HasPerfectForwardSecrecy returns a boolean if a field has been set.

### GetPresharedKey

`func (o *ManaV2InterfaceIPsec) GetPresharedKey() string`

GetPresharedKey returns the PresharedKey field if non-nil, zero value otherwise.

### GetPresharedKeyOk

`func (o *ManaV2InterfaceIPsec) GetPresharedKeyOk() (*string, bool)`

GetPresharedKeyOk returns a tuple with the PresharedKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresharedKey

`func (o *ManaV2InterfaceIPsec) SetPresharedKey(v string)`

SetPresharedKey sets PresharedKey field to given value.

### HasPresharedKey

`func (o *ManaV2InterfaceIPsec) HasPresharedKey() bool`

HasPresharedKey returns a boolean if a field has been set.

### GetProtocol

`func (o *ManaV2InterfaceIPsec) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *ManaV2InterfaceIPsec) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *ManaV2InterfaceIPsec) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *ManaV2InterfaceIPsec) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetReauthInterval

`func (o *ManaV2InterfaceIPsec) GetReauthInterval() int64`

GetReauthInterval returns the ReauthInterval field if non-nil, zero value otherwise.

### GetReauthIntervalOk

`func (o *ManaV2InterfaceIPsec) GetReauthIntervalOk() (*int64, bool)`

GetReauthIntervalOk returns a tuple with the ReauthInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReauthInterval

`func (o *ManaV2InterfaceIPsec) SetReauthInterval(v int64)`

SetReauthInterval sets ReauthInterval field to given value.

### HasReauthInterval

`func (o *ManaV2InterfaceIPsec) HasReauthInterval() bool`

HasReauthInterval returns a boolean if a field has been set.

### GetRekeyInterval

`func (o *ManaV2InterfaceIPsec) GetRekeyInterval() int64`

GetRekeyInterval returns the RekeyInterval field if non-nil, zero value otherwise.

### GetRekeyIntervalOk

`func (o *ManaV2InterfaceIPsec) GetRekeyIntervalOk() (*int64, bool)`

GetRekeyIntervalOk returns a tuple with the RekeyInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRekeyInterval

`func (o *ManaV2InterfaceIPsec) SetRekeyInterval(v int64)`

SetRekeyInterval sets RekeyInterval field to given value.

### HasRekeyInterval

`func (o *ManaV2InterfaceIPsec) HasRekeyInterval() bool`

HasRekeyInterval returns a boolean if a field has been set.

### GetRemoteAddress

`func (o *ManaV2InterfaceIPsec) GetRemoteAddress() string`

GetRemoteAddress returns the RemoteAddress field if non-nil, zero value otherwise.

### GetRemoteAddressOk

`func (o *ManaV2InterfaceIPsec) GetRemoteAddressOk() (*string, bool)`

GetRemoteAddressOk returns a tuple with the RemoteAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteAddress

`func (o *ManaV2InterfaceIPsec) SetRemoteAddress(v string)`

SetRemoteAddress sets RemoteAddress field to given value.

### HasRemoteAddress

`func (o *ManaV2InterfaceIPsec) HasRemoteAddress() bool`

HasRemoteAddress returns a boolean if a field has been set.

### GetRemoteIkePeerIdentity

`func (o *ManaV2InterfaceIPsec) GetRemoteIkePeerIdentity() string`

GetRemoteIkePeerIdentity returns the RemoteIkePeerIdentity field if non-nil, zero value otherwise.

### GetRemoteIkePeerIdentityOk

`func (o *ManaV2InterfaceIPsec) GetRemoteIkePeerIdentityOk() (*string, bool)`

GetRemoteIkePeerIdentityOk returns a tuple with the RemoteIkePeerIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteIkePeerIdentity

`func (o *ManaV2InterfaceIPsec) SetRemoteIkePeerIdentity(v string)`

SetRemoteIkePeerIdentity sets RemoteIkePeerIdentity field to given value.

### HasRemoteIkePeerIdentity

`func (o *ManaV2InterfaceIPsec) HasRemoteIkePeerIdentity() bool`

HasRemoteIkePeerIdentity returns a boolean if a field has been set.

### GetRemoteIkesaSpi

`func (o *ManaV2InterfaceIPsec) GetRemoteIkesaSpi() int64`

GetRemoteIkesaSpi returns the RemoteIkesaSpi field if non-nil, zero value otherwise.

### GetRemoteIkesaSpiOk

`func (o *ManaV2InterfaceIPsec) GetRemoteIkesaSpiOk() (*int64, bool)`

GetRemoteIkesaSpiOk returns a tuple with the RemoteIkesaSpi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteIkesaSpi

`func (o *ManaV2InterfaceIPsec) SetRemoteIkesaSpi(v int64)`

SetRemoteIkesaSpi sets RemoteIkesaSpi field to given value.

### HasRemoteIkesaSpi

`func (o *ManaV2InterfaceIPsec) HasRemoteIkesaSpi() bool`

HasRemoteIkesaSpi returns a boolean if a field has been set.

### GetRemotePort

`func (o *ManaV2InterfaceIPsec) GetRemotePort() int32`

GetRemotePort returns the RemotePort field if non-nil, zero value otherwise.

### GetRemotePortOk

`func (o *ManaV2InterfaceIPsec) GetRemotePortOk() (*int32, bool)`

GetRemotePortOk returns a tuple with the RemotePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemotePort

`func (o *ManaV2InterfaceIPsec) SetRemotePort(v int32)`

SetRemotePort sets RemotePort field to given value.

### HasRemotePort

`func (o *ManaV2InterfaceIPsec) HasRemotePort() bool`

HasRemotePort returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



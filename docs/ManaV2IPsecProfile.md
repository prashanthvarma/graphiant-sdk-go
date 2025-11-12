# ManaV2IPsecProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AntiReplayWindowSize** | Pointer to **int32** |  | [optional] 
**DpdInterval** | Pointer to **int32** |  | [optional] 
**Esn** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**IkeDhGroup** | Pointer to **string** |  | [optional] 
**IkeEncryptionAlg** | Pointer to **string** |  | [optional] 
**IkeIntegrity** | Pointer to **string** |  | [optional] 
**IpsecEncryptionAlg** | Pointer to **string** |  | [optional] 
**IpsecIntegrity** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PerfectForwardSecrecy** | Pointer to **string** |  | [optional] 
**ReauthInterval** | Pointer to **int32** |  | [optional] 
**RekeyInterval** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2IPsecProfile

`func NewManaV2IPsecProfile() *ManaV2IPsecProfile`

NewManaV2IPsecProfile instantiates a new ManaV2IPsecProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IPsecProfileWithDefaults

`func NewManaV2IPsecProfileWithDefaults() *ManaV2IPsecProfile`

NewManaV2IPsecProfileWithDefaults instantiates a new ManaV2IPsecProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAntiReplayWindowSize

`func (o *ManaV2IPsecProfile) GetAntiReplayWindowSize() int32`

GetAntiReplayWindowSize returns the AntiReplayWindowSize field if non-nil, zero value otherwise.

### GetAntiReplayWindowSizeOk

`func (o *ManaV2IPsecProfile) GetAntiReplayWindowSizeOk() (*int32, bool)`

GetAntiReplayWindowSizeOk returns a tuple with the AntiReplayWindowSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAntiReplayWindowSize

`func (o *ManaV2IPsecProfile) SetAntiReplayWindowSize(v int32)`

SetAntiReplayWindowSize sets AntiReplayWindowSize field to given value.

### HasAntiReplayWindowSize

`func (o *ManaV2IPsecProfile) HasAntiReplayWindowSize() bool`

HasAntiReplayWindowSize returns a boolean if a field has been set.

### GetDpdInterval

`func (o *ManaV2IPsecProfile) GetDpdInterval() int32`

GetDpdInterval returns the DpdInterval field if non-nil, zero value otherwise.

### GetDpdIntervalOk

`func (o *ManaV2IPsecProfile) GetDpdIntervalOk() (*int32, bool)`

GetDpdIntervalOk returns a tuple with the DpdInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpdInterval

`func (o *ManaV2IPsecProfile) SetDpdInterval(v int32)`

SetDpdInterval sets DpdInterval field to given value.

### HasDpdInterval

`func (o *ManaV2IPsecProfile) HasDpdInterval() bool`

HasDpdInterval returns a boolean if a field has been set.

### GetEsn

`func (o *ManaV2IPsecProfile) GetEsn() bool`

GetEsn returns the Esn field if non-nil, zero value otherwise.

### GetEsnOk

`func (o *ManaV2IPsecProfile) GetEsnOk() (*bool, bool)`

GetEsnOk returns a tuple with the Esn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEsn

`func (o *ManaV2IPsecProfile) SetEsn(v bool)`

SetEsn sets Esn field to given value.

### HasEsn

`func (o *ManaV2IPsecProfile) HasEsn() bool`

HasEsn returns a boolean if a field has been set.

### GetId

`func (o *ManaV2IPsecProfile) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2IPsecProfile) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2IPsecProfile) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2IPsecProfile) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIkeDhGroup

`func (o *ManaV2IPsecProfile) GetIkeDhGroup() string`

GetIkeDhGroup returns the IkeDhGroup field if non-nil, zero value otherwise.

### GetIkeDhGroupOk

`func (o *ManaV2IPsecProfile) GetIkeDhGroupOk() (*string, bool)`

GetIkeDhGroupOk returns a tuple with the IkeDhGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeDhGroup

`func (o *ManaV2IPsecProfile) SetIkeDhGroup(v string)`

SetIkeDhGroup sets IkeDhGroup field to given value.

### HasIkeDhGroup

`func (o *ManaV2IPsecProfile) HasIkeDhGroup() bool`

HasIkeDhGroup returns a boolean if a field has been set.

### GetIkeEncryptionAlg

`func (o *ManaV2IPsecProfile) GetIkeEncryptionAlg() string`

GetIkeEncryptionAlg returns the IkeEncryptionAlg field if non-nil, zero value otherwise.

### GetIkeEncryptionAlgOk

`func (o *ManaV2IPsecProfile) GetIkeEncryptionAlgOk() (*string, bool)`

GetIkeEncryptionAlgOk returns a tuple with the IkeEncryptionAlg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeEncryptionAlg

`func (o *ManaV2IPsecProfile) SetIkeEncryptionAlg(v string)`

SetIkeEncryptionAlg sets IkeEncryptionAlg field to given value.

### HasIkeEncryptionAlg

`func (o *ManaV2IPsecProfile) HasIkeEncryptionAlg() bool`

HasIkeEncryptionAlg returns a boolean if a field has been set.

### GetIkeIntegrity

`func (o *ManaV2IPsecProfile) GetIkeIntegrity() string`

GetIkeIntegrity returns the IkeIntegrity field if non-nil, zero value otherwise.

### GetIkeIntegrityOk

`func (o *ManaV2IPsecProfile) GetIkeIntegrityOk() (*string, bool)`

GetIkeIntegrityOk returns a tuple with the IkeIntegrity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeIntegrity

`func (o *ManaV2IPsecProfile) SetIkeIntegrity(v string)`

SetIkeIntegrity sets IkeIntegrity field to given value.

### HasIkeIntegrity

`func (o *ManaV2IPsecProfile) HasIkeIntegrity() bool`

HasIkeIntegrity returns a boolean if a field has been set.

### GetIpsecEncryptionAlg

`func (o *ManaV2IPsecProfile) GetIpsecEncryptionAlg() string`

GetIpsecEncryptionAlg returns the IpsecEncryptionAlg field if non-nil, zero value otherwise.

### GetIpsecEncryptionAlgOk

`func (o *ManaV2IPsecProfile) GetIpsecEncryptionAlgOk() (*string, bool)`

GetIpsecEncryptionAlgOk returns a tuple with the IpsecEncryptionAlg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecEncryptionAlg

`func (o *ManaV2IPsecProfile) SetIpsecEncryptionAlg(v string)`

SetIpsecEncryptionAlg sets IpsecEncryptionAlg field to given value.

### HasIpsecEncryptionAlg

`func (o *ManaV2IPsecProfile) HasIpsecEncryptionAlg() bool`

HasIpsecEncryptionAlg returns a boolean if a field has been set.

### GetIpsecIntegrity

`func (o *ManaV2IPsecProfile) GetIpsecIntegrity() string`

GetIpsecIntegrity returns the IpsecIntegrity field if non-nil, zero value otherwise.

### GetIpsecIntegrityOk

`func (o *ManaV2IPsecProfile) GetIpsecIntegrityOk() (*string, bool)`

GetIpsecIntegrityOk returns a tuple with the IpsecIntegrity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecIntegrity

`func (o *ManaV2IPsecProfile) SetIpsecIntegrity(v string)`

SetIpsecIntegrity sets IpsecIntegrity field to given value.

### HasIpsecIntegrity

`func (o *ManaV2IPsecProfile) HasIpsecIntegrity() bool`

HasIpsecIntegrity returns a boolean if a field has been set.

### GetName

`func (o *ManaV2IPsecProfile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2IPsecProfile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2IPsecProfile) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2IPsecProfile) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPerfectForwardSecrecy

`func (o *ManaV2IPsecProfile) GetPerfectForwardSecrecy() string`

GetPerfectForwardSecrecy returns the PerfectForwardSecrecy field if non-nil, zero value otherwise.

### GetPerfectForwardSecrecyOk

`func (o *ManaV2IPsecProfile) GetPerfectForwardSecrecyOk() (*string, bool)`

GetPerfectForwardSecrecyOk returns a tuple with the PerfectForwardSecrecy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerfectForwardSecrecy

`func (o *ManaV2IPsecProfile) SetPerfectForwardSecrecy(v string)`

SetPerfectForwardSecrecy sets PerfectForwardSecrecy field to given value.

### HasPerfectForwardSecrecy

`func (o *ManaV2IPsecProfile) HasPerfectForwardSecrecy() bool`

HasPerfectForwardSecrecy returns a boolean if a field has been set.

### GetReauthInterval

`func (o *ManaV2IPsecProfile) GetReauthInterval() int32`

GetReauthInterval returns the ReauthInterval field if non-nil, zero value otherwise.

### GetReauthIntervalOk

`func (o *ManaV2IPsecProfile) GetReauthIntervalOk() (*int32, bool)`

GetReauthIntervalOk returns a tuple with the ReauthInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReauthInterval

`func (o *ManaV2IPsecProfile) SetReauthInterval(v int32)`

SetReauthInterval sets ReauthInterval field to given value.

### HasReauthInterval

`func (o *ManaV2IPsecProfile) HasReauthInterval() bool`

HasReauthInterval returns a boolean if a field has been set.

### GetRekeyInterval

`func (o *ManaV2IPsecProfile) GetRekeyInterval() int32`

GetRekeyInterval returns the RekeyInterval field if non-nil, zero value otherwise.

### GetRekeyIntervalOk

`func (o *ManaV2IPsecProfile) GetRekeyIntervalOk() (*int32, bool)`

GetRekeyIntervalOk returns a tuple with the RekeyInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRekeyInterval

`func (o *ManaV2IPsecProfile) SetRekeyInterval(v int32)`

SetRekeyInterval sets RekeyInterval field to given value.

### HasRekeyInterval

`func (o *ManaV2IPsecProfile) HasRekeyInterval() bool`

HasRekeyInterval returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



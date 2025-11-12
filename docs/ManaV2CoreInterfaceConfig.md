# ManaV2CoreInterfaceConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminStatus** | Pointer to **bool** |  | [optional] 
**Alias** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Duplex** | Pointer to **string** |  | [optional] 
**Ipv4** | Pointer to [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**Ipv6** | Pointer to [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**MaxTransmissionUnit** | Pointer to **int32** |  | [optional] 
**MplsEnabled** | Pointer to **bool** |  | [optional] 
**TcpMssV4** | Pointer to **int32** |  | [optional] 
**TcpMssV6** | Pointer to **int32** |  | [optional] 
**XTalkFilter** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2CoreInterfaceConfig

`func NewManaV2CoreInterfaceConfig() *ManaV2CoreInterfaceConfig`

NewManaV2CoreInterfaceConfig instantiates a new ManaV2CoreInterfaceConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2CoreInterfaceConfigWithDefaults

`func NewManaV2CoreInterfaceConfigWithDefaults() *ManaV2CoreInterfaceConfig`

NewManaV2CoreInterfaceConfigWithDefaults instantiates a new ManaV2CoreInterfaceConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminStatus

`func (o *ManaV2CoreInterfaceConfig) GetAdminStatus() bool`

GetAdminStatus returns the AdminStatus field if non-nil, zero value otherwise.

### GetAdminStatusOk

`func (o *ManaV2CoreInterfaceConfig) GetAdminStatusOk() (*bool, bool)`

GetAdminStatusOk returns a tuple with the AdminStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminStatus

`func (o *ManaV2CoreInterfaceConfig) SetAdminStatus(v bool)`

SetAdminStatus sets AdminStatus field to given value.

### HasAdminStatus

`func (o *ManaV2CoreInterfaceConfig) HasAdminStatus() bool`

HasAdminStatus returns a boolean if a field has been set.

### GetAlias

`func (o *ManaV2CoreInterfaceConfig) GetAlias() string`

GetAlias returns the Alias field if non-nil, zero value otherwise.

### GetAliasOk

`func (o *ManaV2CoreInterfaceConfig) GetAliasOk() (*string, bool)`

GetAliasOk returns a tuple with the Alias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlias

`func (o *ManaV2CoreInterfaceConfig) SetAlias(v string)`

SetAlias sets Alias field to given value.

### HasAlias

`func (o *ManaV2CoreInterfaceConfig) HasAlias() bool`

HasAlias returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2CoreInterfaceConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2CoreInterfaceConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2CoreInterfaceConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2CoreInterfaceConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDuplex

`func (o *ManaV2CoreInterfaceConfig) GetDuplex() string`

GetDuplex returns the Duplex field if non-nil, zero value otherwise.

### GetDuplexOk

`func (o *ManaV2CoreInterfaceConfig) GetDuplexOk() (*string, bool)`

GetDuplexOk returns a tuple with the Duplex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplex

`func (o *ManaV2CoreInterfaceConfig) SetDuplex(v string)`

SetDuplex sets Duplex field to given value.

### HasDuplex

`func (o *ManaV2CoreInterfaceConfig) HasDuplex() bool`

HasDuplex returns a boolean if a field has been set.

### GetIpv4

`func (o *ManaV2CoreInterfaceConfig) GetIpv4() ManaV2InterfaceIpConfig`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *ManaV2CoreInterfaceConfig) GetIpv4Ok() (*ManaV2InterfaceIpConfig, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *ManaV2CoreInterfaceConfig) SetIpv4(v ManaV2InterfaceIpConfig)`

SetIpv4 sets Ipv4 field to given value.

### HasIpv4

`func (o *ManaV2CoreInterfaceConfig) HasIpv4() bool`

HasIpv4 returns a boolean if a field has been set.

### GetIpv6

`func (o *ManaV2CoreInterfaceConfig) GetIpv6() ManaV2InterfaceIpConfig`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *ManaV2CoreInterfaceConfig) GetIpv6Ok() (*ManaV2InterfaceIpConfig, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *ManaV2CoreInterfaceConfig) SetIpv6(v ManaV2InterfaceIpConfig)`

SetIpv6 sets Ipv6 field to given value.

### HasIpv6

`func (o *ManaV2CoreInterfaceConfig) HasIpv6() bool`

HasIpv6 returns a boolean if a field has been set.

### GetMaxTransmissionUnit

`func (o *ManaV2CoreInterfaceConfig) GetMaxTransmissionUnit() int32`

GetMaxTransmissionUnit returns the MaxTransmissionUnit field if non-nil, zero value otherwise.

### GetMaxTransmissionUnitOk

`func (o *ManaV2CoreInterfaceConfig) GetMaxTransmissionUnitOk() (*int32, bool)`

GetMaxTransmissionUnitOk returns a tuple with the MaxTransmissionUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTransmissionUnit

`func (o *ManaV2CoreInterfaceConfig) SetMaxTransmissionUnit(v int32)`

SetMaxTransmissionUnit sets MaxTransmissionUnit field to given value.

### HasMaxTransmissionUnit

`func (o *ManaV2CoreInterfaceConfig) HasMaxTransmissionUnit() bool`

HasMaxTransmissionUnit returns a boolean if a field has been set.

### GetMplsEnabled

`func (o *ManaV2CoreInterfaceConfig) GetMplsEnabled() bool`

GetMplsEnabled returns the MplsEnabled field if non-nil, zero value otherwise.

### GetMplsEnabledOk

`func (o *ManaV2CoreInterfaceConfig) GetMplsEnabledOk() (*bool, bool)`

GetMplsEnabledOk returns a tuple with the MplsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMplsEnabled

`func (o *ManaV2CoreInterfaceConfig) SetMplsEnabled(v bool)`

SetMplsEnabled sets MplsEnabled field to given value.

### HasMplsEnabled

`func (o *ManaV2CoreInterfaceConfig) HasMplsEnabled() bool`

HasMplsEnabled returns a boolean if a field has been set.

### GetTcpMssV4

`func (o *ManaV2CoreInterfaceConfig) GetTcpMssV4() int32`

GetTcpMssV4 returns the TcpMssV4 field if non-nil, zero value otherwise.

### GetTcpMssV4Ok

`func (o *ManaV2CoreInterfaceConfig) GetTcpMssV4Ok() (*int32, bool)`

GetTcpMssV4Ok returns a tuple with the TcpMssV4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpMssV4

`func (o *ManaV2CoreInterfaceConfig) SetTcpMssV4(v int32)`

SetTcpMssV4 sets TcpMssV4 field to given value.

### HasTcpMssV4

`func (o *ManaV2CoreInterfaceConfig) HasTcpMssV4() bool`

HasTcpMssV4 returns a boolean if a field has been set.

### GetTcpMssV6

`func (o *ManaV2CoreInterfaceConfig) GetTcpMssV6() int32`

GetTcpMssV6 returns the TcpMssV6 field if non-nil, zero value otherwise.

### GetTcpMssV6Ok

`func (o *ManaV2CoreInterfaceConfig) GetTcpMssV6Ok() (*int32, bool)`

GetTcpMssV6Ok returns a tuple with the TcpMssV6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpMssV6

`func (o *ManaV2CoreInterfaceConfig) SetTcpMssV6(v int32)`

SetTcpMssV6 sets TcpMssV6 field to given value.

### HasTcpMssV6

`func (o *ManaV2CoreInterfaceConfig) HasTcpMssV6() bool`

HasTcpMssV6 returns a boolean if a field has been set.

### GetXTalkFilter

`func (o *ManaV2CoreInterfaceConfig) GetXTalkFilter() bool`

GetXTalkFilter returns the XTalkFilter field if non-nil, zero value otherwise.

### GetXTalkFilterOk

`func (o *ManaV2CoreInterfaceConfig) GetXTalkFilterOk() (*bool, bool)`

GetXTalkFilterOk returns a tuple with the XTalkFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetXTalkFilter

`func (o *ManaV2CoreInterfaceConfig) SetXTalkFilter(v bool)`

SetXTalkFilter sets XTalkFilter field to given value.

### HasXTalkFilter

`func (o *ManaV2CoreInterfaceConfig) HasXTalkFilter() bool`

HasXTalkFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



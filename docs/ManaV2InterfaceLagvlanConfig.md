# ManaV2InterfaceLagvlanConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminStatus** | Pointer to **bool** |  | [optional] 
**Alias** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Ipv4** | Pointer to [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**Ipv6** | Pointer to [**ManaV2InterfaceIpConfig**](ManaV2InterfaceIpConfig.md) |  | [optional] 
**Segment** | Pointer to **string** |  | [optional] 
**Vlan** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2InterfaceLagvlanConfig

`func NewManaV2InterfaceLagvlanConfig() *ManaV2InterfaceLagvlanConfig`

NewManaV2InterfaceLagvlanConfig instantiates a new ManaV2InterfaceLagvlanConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2InterfaceLagvlanConfigWithDefaults

`func NewManaV2InterfaceLagvlanConfigWithDefaults() *ManaV2InterfaceLagvlanConfig`

NewManaV2InterfaceLagvlanConfigWithDefaults instantiates a new ManaV2InterfaceLagvlanConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminStatus

`func (o *ManaV2InterfaceLagvlanConfig) GetAdminStatus() bool`

GetAdminStatus returns the AdminStatus field if non-nil, zero value otherwise.

### GetAdminStatusOk

`func (o *ManaV2InterfaceLagvlanConfig) GetAdminStatusOk() (*bool, bool)`

GetAdminStatusOk returns a tuple with the AdminStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminStatus

`func (o *ManaV2InterfaceLagvlanConfig) SetAdminStatus(v bool)`

SetAdminStatus sets AdminStatus field to given value.

### HasAdminStatus

`func (o *ManaV2InterfaceLagvlanConfig) HasAdminStatus() bool`

HasAdminStatus returns a boolean if a field has been set.

### GetAlias

`func (o *ManaV2InterfaceLagvlanConfig) GetAlias() string`

GetAlias returns the Alias field if non-nil, zero value otherwise.

### GetAliasOk

`func (o *ManaV2InterfaceLagvlanConfig) GetAliasOk() (*string, bool)`

GetAliasOk returns a tuple with the Alias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlias

`func (o *ManaV2InterfaceLagvlanConfig) SetAlias(v string)`

SetAlias sets Alias field to given value.

### HasAlias

`func (o *ManaV2InterfaceLagvlanConfig) HasAlias() bool`

HasAlias returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2InterfaceLagvlanConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2InterfaceLagvlanConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2InterfaceLagvlanConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2InterfaceLagvlanConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIpv4

`func (o *ManaV2InterfaceLagvlanConfig) GetIpv4() ManaV2InterfaceIpConfig`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *ManaV2InterfaceLagvlanConfig) GetIpv4Ok() (*ManaV2InterfaceIpConfig, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *ManaV2InterfaceLagvlanConfig) SetIpv4(v ManaV2InterfaceIpConfig)`

SetIpv4 sets Ipv4 field to given value.

### HasIpv4

`func (o *ManaV2InterfaceLagvlanConfig) HasIpv4() bool`

HasIpv4 returns a boolean if a field has been set.

### GetIpv6

`func (o *ManaV2InterfaceLagvlanConfig) GetIpv6() ManaV2InterfaceIpConfig`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *ManaV2InterfaceLagvlanConfig) GetIpv6Ok() (*ManaV2InterfaceIpConfig, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *ManaV2InterfaceLagvlanConfig) SetIpv6(v ManaV2InterfaceIpConfig)`

SetIpv6 sets Ipv6 field to given value.

### HasIpv6

`func (o *ManaV2InterfaceLagvlanConfig) HasIpv6() bool`

HasIpv6 returns a boolean if a field has been set.

### GetSegment

`func (o *ManaV2InterfaceLagvlanConfig) GetSegment() string`

GetSegment returns the Segment field if non-nil, zero value otherwise.

### GetSegmentOk

`func (o *ManaV2InterfaceLagvlanConfig) GetSegmentOk() (*string, bool)`

GetSegmentOk returns a tuple with the Segment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegment

`func (o *ManaV2InterfaceLagvlanConfig) SetSegment(v string)`

SetSegment sets Segment field to given value.

### HasSegment

`func (o *ManaV2InterfaceLagvlanConfig) HasSegment() bool`

HasSegment returns a boolean if a field has been set.

### GetVlan

`func (o *ManaV2InterfaceLagvlanConfig) GetVlan() int32`

GetVlan returns the Vlan field if non-nil, zero value otherwise.

### GetVlanOk

`func (o *ManaV2InterfaceLagvlanConfig) GetVlanOk() (*int32, bool)`

GetVlanOk returns a tuple with the Vlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlan

`func (o *ManaV2InterfaceLagvlanConfig) SetVlan(v int32)`

SetVlan sets Vlan field to given value.

### HasVlan

`func (o *ManaV2InterfaceLagvlanConfig) HasVlan() bool`

HasVlan returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2DhcpSubnetConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DefaultLeaseTimeSecs** | Pointer to **int32** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DomainName** | Pointer to **string** |  | [optional] 
**DomainNameServer** | Pointer to [**ManaV2DhcpServerDnsParametersConfig**](ManaV2DhcpServerDnsParametersConfig.md) |  | [optional] 
**Interface** | Pointer to **string** |  | [optional] 
**IpGateway** | Pointer to **string** |  | [optional] 
**IpPrefix** | Pointer to **string** |  | [optional] 
**IpRanges** | Pointer to [**[]ManaV2DhcpipRangeConfig**](ManaV2DhcpipRangeConfig.md) |  | [optional] 
**IpRangesV2** | Pointer to [**ManaV2NullableDhcpipRangeList**](ManaV2NullableDhcpipRangeList.md) |  | [optional] 
**MaxLeaseTimeSecs** | Pointer to **int32** |  | [optional] 
**MinLeaseTimeSecs** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**StaticLeases** | Pointer to [**map[string]ManaV2NullableDhcpSubnetStaticLeaseConfig**](ManaV2NullableDhcpSubnetStaticLeaseConfig.md) |  | [optional] 

## Methods

### NewManaV2DhcpSubnetConfig

`func NewManaV2DhcpSubnetConfig() *ManaV2DhcpSubnetConfig`

NewManaV2DhcpSubnetConfig instantiates a new ManaV2DhcpSubnetConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DhcpSubnetConfigWithDefaults

`func NewManaV2DhcpSubnetConfigWithDefaults() *ManaV2DhcpSubnetConfig`

NewManaV2DhcpSubnetConfigWithDefaults instantiates a new ManaV2DhcpSubnetConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefaultLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) GetDefaultLeaseTimeSecs() int32`

GetDefaultLeaseTimeSecs returns the DefaultLeaseTimeSecs field if non-nil, zero value otherwise.

### GetDefaultLeaseTimeSecsOk

`func (o *ManaV2DhcpSubnetConfig) GetDefaultLeaseTimeSecsOk() (*int32, bool)`

GetDefaultLeaseTimeSecsOk returns a tuple with the DefaultLeaseTimeSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) SetDefaultLeaseTimeSecs(v int32)`

SetDefaultLeaseTimeSecs sets DefaultLeaseTimeSecs field to given value.

### HasDefaultLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) HasDefaultLeaseTimeSecs() bool`

HasDefaultLeaseTimeSecs returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2DhcpSubnetConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2DhcpSubnetConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2DhcpSubnetConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2DhcpSubnetConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDomainName

`func (o *ManaV2DhcpSubnetConfig) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *ManaV2DhcpSubnetConfig) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *ManaV2DhcpSubnetConfig) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.

### HasDomainName

`func (o *ManaV2DhcpSubnetConfig) HasDomainName() bool`

HasDomainName returns a boolean if a field has been set.

### GetDomainNameServer

`func (o *ManaV2DhcpSubnetConfig) GetDomainNameServer() ManaV2DhcpServerDnsParametersConfig`

GetDomainNameServer returns the DomainNameServer field if non-nil, zero value otherwise.

### GetDomainNameServerOk

`func (o *ManaV2DhcpSubnetConfig) GetDomainNameServerOk() (*ManaV2DhcpServerDnsParametersConfig, bool)`

GetDomainNameServerOk returns a tuple with the DomainNameServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNameServer

`func (o *ManaV2DhcpSubnetConfig) SetDomainNameServer(v ManaV2DhcpServerDnsParametersConfig)`

SetDomainNameServer sets DomainNameServer field to given value.

### HasDomainNameServer

`func (o *ManaV2DhcpSubnetConfig) HasDomainNameServer() bool`

HasDomainNameServer returns a boolean if a field has been set.

### GetInterface

`func (o *ManaV2DhcpSubnetConfig) GetInterface() string`

GetInterface returns the Interface field if non-nil, zero value otherwise.

### GetInterfaceOk

`func (o *ManaV2DhcpSubnetConfig) GetInterfaceOk() (*string, bool)`

GetInterfaceOk returns a tuple with the Interface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterface

`func (o *ManaV2DhcpSubnetConfig) SetInterface(v string)`

SetInterface sets Interface field to given value.

### HasInterface

`func (o *ManaV2DhcpSubnetConfig) HasInterface() bool`

HasInterface returns a boolean if a field has been set.

### GetIpGateway

`func (o *ManaV2DhcpSubnetConfig) GetIpGateway() string`

GetIpGateway returns the IpGateway field if non-nil, zero value otherwise.

### GetIpGatewayOk

`func (o *ManaV2DhcpSubnetConfig) GetIpGatewayOk() (*string, bool)`

GetIpGatewayOk returns a tuple with the IpGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpGateway

`func (o *ManaV2DhcpSubnetConfig) SetIpGateway(v string)`

SetIpGateway sets IpGateway field to given value.

### HasIpGateway

`func (o *ManaV2DhcpSubnetConfig) HasIpGateway() bool`

HasIpGateway returns a boolean if a field has been set.

### GetIpPrefix

`func (o *ManaV2DhcpSubnetConfig) GetIpPrefix() string`

GetIpPrefix returns the IpPrefix field if non-nil, zero value otherwise.

### GetIpPrefixOk

`func (o *ManaV2DhcpSubnetConfig) GetIpPrefixOk() (*string, bool)`

GetIpPrefixOk returns a tuple with the IpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpPrefix

`func (o *ManaV2DhcpSubnetConfig) SetIpPrefix(v string)`

SetIpPrefix sets IpPrefix field to given value.

### HasIpPrefix

`func (o *ManaV2DhcpSubnetConfig) HasIpPrefix() bool`

HasIpPrefix returns a boolean if a field has been set.

### GetIpRanges

`func (o *ManaV2DhcpSubnetConfig) GetIpRanges() []ManaV2DhcpipRangeConfig`

GetIpRanges returns the IpRanges field if non-nil, zero value otherwise.

### GetIpRangesOk

`func (o *ManaV2DhcpSubnetConfig) GetIpRangesOk() (*[]ManaV2DhcpipRangeConfig, bool)`

GetIpRangesOk returns a tuple with the IpRanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpRanges

`func (o *ManaV2DhcpSubnetConfig) SetIpRanges(v []ManaV2DhcpipRangeConfig)`

SetIpRanges sets IpRanges field to given value.

### HasIpRanges

`func (o *ManaV2DhcpSubnetConfig) HasIpRanges() bool`

HasIpRanges returns a boolean if a field has been set.

### GetIpRangesV2

`func (o *ManaV2DhcpSubnetConfig) GetIpRangesV2() ManaV2NullableDhcpipRangeList`

GetIpRangesV2 returns the IpRangesV2 field if non-nil, zero value otherwise.

### GetIpRangesV2Ok

`func (o *ManaV2DhcpSubnetConfig) GetIpRangesV2Ok() (*ManaV2NullableDhcpipRangeList, bool)`

GetIpRangesV2Ok returns a tuple with the IpRangesV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpRangesV2

`func (o *ManaV2DhcpSubnetConfig) SetIpRangesV2(v ManaV2NullableDhcpipRangeList)`

SetIpRangesV2 sets IpRangesV2 field to given value.

### HasIpRangesV2

`func (o *ManaV2DhcpSubnetConfig) HasIpRangesV2() bool`

HasIpRangesV2 returns a boolean if a field has been set.

### GetMaxLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) GetMaxLeaseTimeSecs() int32`

GetMaxLeaseTimeSecs returns the MaxLeaseTimeSecs field if non-nil, zero value otherwise.

### GetMaxLeaseTimeSecsOk

`func (o *ManaV2DhcpSubnetConfig) GetMaxLeaseTimeSecsOk() (*int32, bool)`

GetMaxLeaseTimeSecsOk returns a tuple with the MaxLeaseTimeSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) SetMaxLeaseTimeSecs(v int32)`

SetMaxLeaseTimeSecs sets MaxLeaseTimeSecs field to given value.

### HasMaxLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) HasMaxLeaseTimeSecs() bool`

HasMaxLeaseTimeSecs returns a boolean if a field has been set.

### GetMinLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) GetMinLeaseTimeSecs() int32`

GetMinLeaseTimeSecs returns the MinLeaseTimeSecs field if non-nil, zero value otherwise.

### GetMinLeaseTimeSecsOk

`func (o *ManaV2DhcpSubnetConfig) GetMinLeaseTimeSecsOk() (*int32, bool)`

GetMinLeaseTimeSecsOk returns a tuple with the MinLeaseTimeSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) SetMinLeaseTimeSecs(v int32)`

SetMinLeaseTimeSecs sets MinLeaseTimeSecs field to given value.

### HasMinLeaseTimeSecs

`func (o *ManaV2DhcpSubnetConfig) HasMinLeaseTimeSecs() bool`

HasMinLeaseTimeSecs returns a boolean if a field has been set.

### GetName

`func (o *ManaV2DhcpSubnetConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2DhcpSubnetConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2DhcpSubnetConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2DhcpSubnetConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStaticLeases

`func (o *ManaV2DhcpSubnetConfig) GetStaticLeases() map[string]ManaV2NullableDhcpSubnetStaticLeaseConfig`

GetStaticLeases returns the StaticLeases field if non-nil, zero value otherwise.

### GetStaticLeasesOk

`func (o *ManaV2DhcpSubnetConfig) GetStaticLeasesOk() (*map[string]ManaV2NullableDhcpSubnetStaticLeaseConfig, bool)`

GetStaticLeasesOk returns a tuple with the StaticLeases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticLeases

`func (o *ManaV2DhcpSubnetConfig) SetStaticLeases(v map[string]ManaV2NullableDhcpSubnetStaticLeaseConfig)`

SetStaticLeases sets StaticLeases field to given value.

### HasStaticLeases

`func (o *ManaV2DhcpSubnetConfig) HasStaticLeases() bool`

HasStaticLeases returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



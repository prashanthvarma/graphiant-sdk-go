# ManaV2DhcpServerPool

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DefaultLeaseTimeSecs** | Pointer to **int32** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DomainName** | Pointer to **string** |  | [optional] 
**Gateway** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Interface** | Pointer to **string** |  | [optional] 
**IpPrefix** | Pointer to **string** |  | [optional] 
**IpVersion** | Pointer to **int32** |  | [optional] 
**Leases** | Pointer to [**[]ManaV2DhcpLease**](ManaV2DhcpLease.md) |  | [optional] 
**MaxLeaseTimeSecs** | Pointer to **int32** |  | [optional] 
**MinLeaseTimeSecs** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Nameservers** | Pointer to [**ManaV2DnsServers**](ManaV2DnsServers.md) |  | [optional] 
**Ranges** | Pointer to [**[]ManaV2DhcpServerIpRange**](ManaV2DhcpServerIpRange.md) |  | [optional] 
**StaticLeases** | Pointer to [**[]ManaV2DhcpStaticLease**](ManaV2DhcpStaticLease.md) |  | [optional] 
**TotalAddresses** | Pointer to **int64** |  | [optional] 
**Utilization** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2DhcpServerPool

`func NewManaV2DhcpServerPool() *ManaV2DhcpServerPool`

NewManaV2DhcpServerPool instantiates a new ManaV2DhcpServerPool object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DhcpServerPoolWithDefaults

`func NewManaV2DhcpServerPoolWithDefaults() *ManaV2DhcpServerPool`

NewManaV2DhcpServerPoolWithDefaults instantiates a new ManaV2DhcpServerPool object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefaultLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) GetDefaultLeaseTimeSecs() int32`

GetDefaultLeaseTimeSecs returns the DefaultLeaseTimeSecs field if non-nil, zero value otherwise.

### GetDefaultLeaseTimeSecsOk

`func (o *ManaV2DhcpServerPool) GetDefaultLeaseTimeSecsOk() (*int32, bool)`

GetDefaultLeaseTimeSecsOk returns a tuple with the DefaultLeaseTimeSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) SetDefaultLeaseTimeSecs(v int32)`

SetDefaultLeaseTimeSecs sets DefaultLeaseTimeSecs field to given value.

### HasDefaultLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) HasDefaultLeaseTimeSecs() bool`

HasDefaultLeaseTimeSecs returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2DhcpServerPool) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2DhcpServerPool) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2DhcpServerPool) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2DhcpServerPool) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDomainName

`func (o *ManaV2DhcpServerPool) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *ManaV2DhcpServerPool) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *ManaV2DhcpServerPool) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.

### HasDomainName

`func (o *ManaV2DhcpServerPool) HasDomainName() bool`

HasDomainName returns a boolean if a field has been set.

### GetGateway

`func (o *ManaV2DhcpServerPool) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *ManaV2DhcpServerPool) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *ManaV2DhcpServerPool) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *ManaV2DhcpServerPool) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetId

`func (o *ManaV2DhcpServerPool) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2DhcpServerPool) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2DhcpServerPool) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2DhcpServerPool) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInterface

`func (o *ManaV2DhcpServerPool) GetInterface() string`

GetInterface returns the Interface field if non-nil, zero value otherwise.

### GetInterfaceOk

`func (o *ManaV2DhcpServerPool) GetInterfaceOk() (*string, bool)`

GetInterfaceOk returns a tuple with the Interface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterface

`func (o *ManaV2DhcpServerPool) SetInterface(v string)`

SetInterface sets Interface field to given value.

### HasInterface

`func (o *ManaV2DhcpServerPool) HasInterface() bool`

HasInterface returns a boolean if a field has been set.

### GetIpPrefix

`func (o *ManaV2DhcpServerPool) GetIpPrefix() string`

GetIpPrefix returns the IpPrefix field if non-nil, zero value otherwise.

### GetIpPrefixOk

`func (o *ManaV2DhcpServerPool) GetIpPrefixOk() (*string, bool)`

GetIpPrefixOk returns a tuple with the IpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpPrefix

`func (o *ManaV2DhcpServerPool) SetIpPrefix(v string)`

SetIpPrefix sets IpPrefix field to given value.

### HasIpPrefix

`func (o *ManaV2DhcpServerPool) HasIpPrefix() bool`

HasIpPrefix returns a boolean if a field has been set.

### GetIpVersion

`func (o *ManaV2DhcpServerPool) GetIpVersion() int32`

GetIpVersion returns the IpVersion field if non-nil, zero value otherwise.

### GetIpVersionOk

`func (o *ManaV2DhcpServerPool) GetIpVersionOk() (*int32, bool)`

GetIpVersionOk returns a tuple with the IpVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpVersion

`func (o *ManaV2DhcpServerPool) SetIpVersion(v int32)`

SetIpVersion sets IpVersion field to given value.

### HasIpVersion

`func (o *ManaV2DhcpServerPool) HasIpVersion() bool`

HasIpVersion returns a boolean if a field has been set.

### GetLeases

`func (o *ManaV2DhcpServerPool) GetLeases() []ManaV2DhcpLease`

GetLeases returns the Leases field if non-nil, zero value otherwise.

### GetLeasesOk

`func (o *ManaV2DhcpServerPool) GetLeasesOk() (*[]ManaV2DhcpLease, bool)`

GetLeasesOk returns a tuple with the Leases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeases

`func (o *ManaV2DhcpServerPool) SetLeases(v []ManaV2DhcpLease)`

SetLeases sets Leases field to given value.

### HasLeases

`func (o *ManaV2DhcpServerPool) HasLeases() bool`

HasLeases returns a boolean if a field has been set.

### GetMaxLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) GetMaxLeaseTimeSecs() int32`

GetMaxLeaseTimeSecs returns the MaxLeaseTimeSecs field if non-nil, zero value otherwise.

### GetMaxLeaseTimeSecsOk

`func (o *ManaV2DhcpServerPool) GetMaxLeaseTimeSecsOk() (*int32, bool)`

GetMaxLeaseTimeSecsOk returns a tuple with the MaxLeaseTimeSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) SetMaxLeaseTimeSecs(v int32)`

SetMaxLeaseTimeSecs sets MaxLeaseTimeSecs field to given value.

### HasMaxLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) HasMaxLeaseTimeSecs() bool`

HasMaxLeaseTimeSecs returns a boolean if a field has been set.

### GetMinLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) GetMinLeaseTimeSecs() int32`

GetMinLeaseTimeSecs returns the MinLeaseTimeSecs field if non-nil, zero value otherwise.

### GetMinLeaseTimeSecsOk

`func (o *ManaV2DhcpServerPool) GetMinLeaseTimeSecsOk() (*int32, bool)`

GetMinLeaseTimeSecsOk returns a tuple with the MinLeaseTimeSecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) SetMinLeaseTimeSecs(v int32)`

SetMinLeaseTimeSecs sets MinLeaseTimeSecs field to given value.

### HasMinLeaseTimeSecs

`func (o *ManaV2DhcpServerPool) HasMinLeaseTimeSecs() bool`

HasMinLeaseTimeSecs returns a boolean if a field has been set.

### GetName

`func (o *ManaV2DhcpServerPool) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2DhcpServerPool) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2DhcpServerPool) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2DhcpServerPool) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNameservers

`func (o *ManaV2DhcpServerPool) GetNameservers() ManaV2DnsServers`

GetNameservers returns the Nameservers field if non-nil, zero value otherwise.

### GetNameserversOk

`func (o *ManaV2DhcpServerPool) GetNameserversOk() (*ManaV2DnsServers, bool)`

GetNameserversOk returns a tuple with the Nameservers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameservers

`func (o *ManaV2DhcpServerPool) SetNameservers(v ManaV2DnsServers)`

SetNameservers sets Nameservers field to given value.

### HasNameservers

`func (o *ManaV2DhcpServerPool) HasNameservers() bool`

HasNameservers returns a boolean if a field has been set.

### GetRanges

`func (o *ManaV2DhcpServerPool) GetRanges() []ManaV2DhcpServerIpRange`

GetRanges returns the Ranges field if non-nil, zero value otherwise.

### GetRangesOk

`func (o *ManaV2DhcpServerPool) GetRangesOk() (*[]ManaV2DhcpServerIpRange, bool)`

GetRangesOk returns a tuple with the Ranges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRanges

`func (o *ManaV2DhcpServerPool) SetRanges(v []ManaV2DhcpServerIpRange)`

SetRanges sets Ranges field to given value.

### HasRanges

`func (o *ManaV2DhcpServerPool) HasRanges() bool`

HasRanges returns a boolean if a field has been set.

### GetStaticLeases

`func (o *ManaV2DhcpServerPool) GetStaticLeases() []ManaV2DhcpStaticLease`

GetStaticLeases returns the StaticLeases field if non-nil, zero value otherwise.

### GetStaticLeasesOk

`func (o *ManaV2DhcpServerPool) GetStaticLeasesOk() (*[]ManaV2DhcpStaticLease, bool)`

GetStaticLeasesOk returns a tuple with the StaticLeases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticLeases

`func (o *ManaV2DhcpServerPool) SetStaticLeases(v []ManaV2DhcpStaticLease)`

SetStaticLeases sets StaticLeases field to given value.

### HasStaticLeases

`func (o *ManaV2DhcpServerPool) HasStaticLeases() bool`

HasStaticLeases returns a boolean if a field has been set.

### GetTotalAddresses

`func (o *ManaV2DhcpServerPool) GetTotalAddresses() int64`

GetTotalAddresses returns the TotalAddresses field if non-nil, zero value otherwise.

### GetTotalAddressesOk

`func (o *ManaV2DhcpServerPool) GetTotalAddressesOk() (*int64, bool)`

GetTotalAddressesOk returns a tuple with the TotalAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAddresses

`func (o *ManaV2DhcpServerPool) SetTotalAddresses(v int64)`

SetTotalAddresses sets TotalAddresses field to given value.

### HasTotalAddresses

`func (o *ManaV2DhcpServerPool) HasTotalAddresses() bool`

HasTotalAddresses returns a boolean if a field has been set.

### GetUtilization

`func (o *ManaV2DhcpServerPool) GetUtilization() int32`

GetUtilization returns the Utilization field if non-nil, zero value otherwise.

### GetUtilizationOk

`func (o *ManaV2DhcpServerPool) GetUtilizationOk() (*int32, bool)`

GetUtilizationOk returns a tuple with the Utilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtilization

`func (o *ManaV2DhcpServerPool) SetUtilization(v int32)`

SetUtilization sets Utilization field to given value.

### HasUtilization

`func (o *ManaV2DhcpServerPool) HasUtilization() bool`

HasUtilization returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



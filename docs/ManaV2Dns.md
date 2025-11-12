# ManaV2Dns

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CloudflareServers** | Pointer to [**[]ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 
**DynamicServers** | Pointer to [**[]ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 
**DynamicServersV2** | Pointer to [**ManaV2DynamicDnsServers**](ManaV2DynamicDnsServers.md) |  | [optional] 
**Mode** | Pointer to **string** |  | [optional] 
**StaticServers** | Pointer to [**[]ManaV2DnsipAddress**](ManaV2DnsipAddress.md) |  | [optional] 
**StaticServersV2** | Pointer to [**ManaV2StaticDnsServers**](ManaV2StaticDnsServers.md) |  | [optional] 

## Methods

### NewManaV2Dns

`func NewManaV2Dns() *ManaV2Dns`

NewManaV2Dns instantiates a new ManaV2Dns object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DnsWithDefaults

`func NewManaV2DnsWithDefaults() *ManaV2Dns`

NewManaV2DnsWithDefaults instantiates a new ManaV2Dns object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCloudflareServers

`func (o *ManaV2Dns) GetCloudflareServers() []ManaV2DnsipAddress`

GetCloudflareServers returns the CloudflareServers field if non-nil, zero value otherwise.

### GetCloudflareServersOk

`func (o *ManaV2Dns) GetCloudflareServersOk() (*[]ManaV2DnsipAddress, bool)`

GetCloudflareServersOk returns a tuple with the CloudflareServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudflareServers

`func (o *ManaV2Dns) SetCloudflareServers(v []ManaV2DnsipAddress)`

SetCloudflareServers sets CloudflareServers field to given value.

### HasCloudflareServers

`func (o *ManaV2Dns) HasCloudflareServers() bool`

HasCloudflareServers returns a boolean if a field has been set.

### GetDynamicServers

`func (o *ManaV2Dns) GetDynamicServers() []ManaV2DnsipAddress`

GetDynamicServers returns the DynamicServers field if non-nil, zero value otherwise.

### GetDynamicServersOk

`func (o *ManaV2Dns) GetDynamicServersOk() (*[]ManaV2DnsipAddress, bool)`

GetDynamicServersOk returns a tuple with the DynamicServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDynamicServers

`func (o *ManaV2Dns) SetDynamicServers(v []ManaV2DnsipAddress)`

SetDynamicServers sets DynamicServers field to given value.

### HasDynamicServers

`func (o *ManaV2Dns) HasDynamicServers() bool`

HasDynamicServers returns a boolean if a field has been set.

### GetDynamicServersV2

`func (o *ManaV2Dns) GetDynamicServersV2() ManaV2DynamicDnsServers`

GetDynamicServersV2 returns the DynamicServersV2 field if non-nil, zero value otherwise.

### GetDynamicServersV2Ok

`func (o *ManaV2Dns) GetDynamicServersV2Ok() (*ManaV2DynamicDnsServers, bool)`

GetDynamicServersV2Ok returns a tuple with the DynamicServersV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDynamicServersV2

`func (o *ManaV2Dns) SetDynamicServersV2(v ManaV2DynamicDnsServers)`

SetDynamicServersV2 sets DynamicServersV2 field to given value.

### HasDynamicServersV2

`func (o *ManaV2Dns) HasDynamicServersV2() bool`

HasDynamicServersV2 returns a boolean if a field has been set.

### GetMode

`func (o *ManaV2Dns) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ManaV2Dns) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ManaV2Dns) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *ManaV2Dns) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetStaticServers

`func (o *ManaV2Dns) GetStaticServers() []ManaV2DnsipAddress`

GetStaticServers returns the StaticServers field if non-nil, zero value otherwise.

### GetStaticServersOk

`func (o *ManaV2Dns) GetStaticServersOk() (*[]ManaV2DnsipAddress, bool)`

GetStaticServersOk returns a tuple with the StaticServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticServers

`func (o *ManaV2Dns) SetStaticServers(v []ManaV2DnsipAddress)`

SetStaticServers sets StaticServers field to given value.

### HasStaticServers

`func (o *ManaV2Dns) HasStaticServers() bool`

HasStaticServers returns a boolean if a field has been set.

### GetStaticServersV2

`func (o *ManaV2Dns) GetStaticServersV2() ManaV2StaticDnsServers`

GetStaticServersV2 returns the StaticServersV2 field if non-nil, zero value otherwise.

### GetStaticServersV2Ok

`func (o *ManaV2Dns) GetStaticServersV2Ok() (*ManaV2StaticDnsServers, bool)`

GetStaticServersV2Ok returns a tuple with the StaticServersV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticServersV2

`func (o *ManaV2Dns) SetStaticServersV2(v ManaV2StaticDnsServers)`

SetStaticServersV2 sets StaticServersV2 field to given value.

### HasStaticServersV2

`func (o *ManaV2Dns) HasStaticServersV2() bool`

HasStaticServersV2 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



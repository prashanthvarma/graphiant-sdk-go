# ManaV2DnsConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cloudflare** | Pointer to **map[string]interface{}** |  | [optional] 
**Dynamic** | Pointer to [**ManaV2DNSConfigDynamic**](ManaV2DNSConfigDynamic.md) |  | [optional] 
**Static** | Pointer to [**ManaV2DNSConfigStatic**](ManaV2DNSConfigStatic.md) |  | [optional] 

## Methods

### NewManaV2DnsConfig

`func NewManaV2DnsConfig() *ManaV2DnsConfig`

NewManaV2DnsConfig instantiates a new ManaV2DnsConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DnsConfigWithDefaults

`func NewManaV2DnsConfigWithDefaults() *ManaV2DnsConfig`

NewManaV2DnsConfigWithDefaults instantiates a new ManaV2DnsConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCloudflare

`func (o *ManaV2DnsConfig) GetCloudflare() map[string]interface{}`

GetCloudflare returns the Cloudflare field if non-nil, zero value otherwise.

### GetCloudflareOk

`func (o *ManaV2DnsConfig) GetCloudflareOk() (*map[string]interface{}, bool)`

GetCloudflareOk returns a tuple with the Cloudflare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudflare

`func (o *ManaV2DnsConfig) SetCloudflare(v map[string]interface{})`

SetCloudflare sets Cloudflare field to given value.

### HasCloudflare

`func (o *ManaV2DnsConfig) HasCloudflare() bool`

HasCloudflare returns a boolean if a field has been set.

### GetDynamic

`func (o *ManaV2DnsConfig) GetDynamic() ManaV2DNSConfigDynamic`

GetDynamic returns the Dynamic field if non-nil, zero value otherwise.

### GetDynamicOk

`func (o *ManaV2DnsConfig) GetDynamicOk() (*ManaV2DNSConfigDynamic, bool)`

GetDynamicOk returns a tuple with the Dynamic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDynamic

`func (o *ManaV2DnsConfig) SetDynamic(v ManaV2DNSConfigDynamic)`

SetDynamic sets Dynamic field to given value.

### HasDynamic

`func (o *ManaV2DnsConfig) HasDynamic() bool`

HasDynamic returns a boolean if a field has been set.

### GetStatic

`func (o *ManaV2DnsConfig) GetStatic() ManaV2DNSConfigStatic`

GetStatic returns the Static field if non-nil, zero value otherwise.

### GetStaticOk

`func (o *ManaV2DnsConfig) GetStaticOk() (*ManaV2DNSConfigStatic, bool)`

GetStaticOk returns a tuple with the Static field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatic

`func (o *ManaV2DnsConfig) SetStatic(v ManaV2DNSConfigStatic)`

SetStatic sets Static field to given value.

### HasStatic

`func (o *ManaV2DnsConfig) HasStatic() bool`

HasStatic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



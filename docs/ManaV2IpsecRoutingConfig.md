# ManaV2IpsecRoutingConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bgp** | Pointer to [**ManaV2IPsecBgpRouteConfig**](ManaV2IPsecBgpRouteConfig.md) |  | [optional] 
**Static** | Pointer to [**ManaV2IPsecStaticRouteConfig**](ManaV2IPsecStaticRouteConfig.md) |  | [optional] 

## Methods

### NewManaV2IpsecRoutingConfig

`func NewManaV2IpsecRoutingConfig() *ManaV2IpsecRoutingConfig`

NewManaV2IpsecRoutingConfig instantiates a new ManaV2IpsecRoutingConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IpsecRoutingConfigWithDefaults

`func NewManaV2IpsecRoutingConfigWithDefaults() *ManaV2IpsecRoutingConfig`

NewManaV2IpsecRoutingConfigWithDefaults instantiates a new ManaV2IpsecRoutingConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgp

`func (o *ManaV2IpsecRoutingConfig) GetBgp() ManaV2IPsecBgpRouteConfig`

GetBgp returns the Bgp field if non-nil, zero value otherwise.

### GetBgpOk

`func (o *ManaV2IpsecRoutingConfig) GetBgpOk() (*ManaV2IPsecBgpRouteConfig, bool)`

GetBgpOk returns a tuple with the Bgp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgp

`func (o *ManaV2IpsecRoutingConfig) SetBgp(v ManaV2IPsecBgpRouteConfig)`

SetBgp sets Bgp field to given value.

### HasBgp

`func (o *ManaV2IpsecRoutingConfig) HasBgp() bool`

HasBgp returns a boolean if a field has been set.

### GetStatic

`func (o *ManaV2IpsecRoutingConfig) GetStatic() ManaV2IPsecStaticRouteConfig`

GetStatic returns the Static field if non-nil, zero value otherwise.

### GetStaticOk

`func (o *ManaV2IpsecRoutingConfig) GetStaticOk() (*ManaV2IPsecStaticRouteConfig, bool)`

GetStaticOk returns a tuple with the Static field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatic

`func (o *ManaV2IpsecRoutingConfig) SetStatic(v ManaV2IPsecStaticRouteConfig)`

SetStatic sets Static field to given value.

### HasStatic

`func (o *ManaV2IpsecRoutingConfig) HasStatic() bool`

HasStatic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



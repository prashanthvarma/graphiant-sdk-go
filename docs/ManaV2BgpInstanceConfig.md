# ManaV2BgpInstanceConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamilies** | Pointer to **[]string** |  | [optional] 
**Asn** | Pointer to **int32** |  | [optional] 
**RouteServer** | Pointer to **bool** |  | [optional] 
**RouterId** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2BgpInstanceConfig

`func NewManaV2BgpInstanceConfig() *ManaV2BgpInstanceConfig`

NewManaV2BgpInstanceConfig instantiates a new ManaV2BgpInstanceConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BgpInstanceConfigWithDefaults

`func NewManaV2BgpInstanceConfigWithDefaults() *ManaV2BgpInstanceConfig`

NewManaV2BgpInstanceConfigWithDefaults instantiates a new ManaV2BgpInstanceConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamilies

`func (o *ManaV2BgpInstanceConfig) GetAddressFamilies() []string`

GetAddressFamilies returns the AddressFamilies field if non-nil, zero value otherwise.

### GetAddressFamiliesOk

`func (o *ManaV2BgpInstanceConfig) GetAddressFamiliesOk() (*[]string, bool)`

GetAddressFamiliesOk returns a tuple with the AddressFamilies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamilies

`func (o *ManaV2BgpInstanceConfig) SetAddressFamilies(v []string)`

SetAddressFamilies sets AddressFamilies field to given value.

### HasAddressFamilies

`func (o *ManaV2BgpInstanceConfig) HasAddressFamilies() bool`

HasAddressFamilies returns a boolean if a field has been set.

### GetAsn

`func (o *ManaV2BgpInstanceConfig) GetAsn() int32`

GetAsn returns the Asn field if non-nil, zero value otherwise.

### GetAsnOk

`func (o *ManaV2BgpInstanceConfig) GetAsnOk() (*int32, bool)`

GetAsnOk returns a tuple with the Asn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsn

`func (o *ManaV2BgpInstanceConfig) SetAsn(v int32)`

SetAsn sets Asn field to given value.

### HasAsn

`func (o *ManaV2BgpInstanceConfig) HasAsn() bool`

HasAsn returns a boolean if a field has been set.

### GetRouteServer

`func (o *ManaV2BgpInstanceConfig) GetRouteServer() bool`

GetRouteServer returns the RouteServer field if non-nil, zero value otherwise.

### GetRouteServerOk

`func (o *ManaV2BgpInstanceConfig) GetRouteServerOk() (*bool, bool)`

GetRouteServerOk returns a tuple with the RouteServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteServer

`func (o *ManaV2BgpInstanceConfig) SetRouteServer(v bool)`

SetRouteServer sets RouteServer field to given value.

### HasRouteServer

`func (o *ManaV2BgpInstanceConfig) HasRouteServer() bool`

HasRouteServer returns a boolean if a field has been set.

### GetRouterId

`func (o *ManaV2BgpInstanceConfig) GetRouterId() string`

GetRouterId returns the RouterId field if non-nil, zero value otherwise.

### GetRouterIdOk

`func (o *ManaV2BgpInstanceConfig) GetRouterIdOk() (*string, bool)`

GetRouterIdOk returns a tuple with the RouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterId

`func (o *ManaV2BgpInstanceConfig) SetRouterId(v string)`

SetRouterId sets RouterId field to given value.

### HasRouterId

`func (o *ManaV2BgpInstanceConfig) HasRouterId() bool`

HasRouterId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



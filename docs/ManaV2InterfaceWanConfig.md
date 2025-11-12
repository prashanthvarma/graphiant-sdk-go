# ManaV2InterfaceWanConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Gw** | Pointer to [**ManaV2NullableInterfaceIpConfig**](ManaV2NullableInterfaceIpConfig.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**VrfName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2InterfaceWanConfig

`func NewManaV2InterfaceWanConfig() *ManaV2InterfaceWanConfig`

NewManaV2InterfaceWanConfig instantiates a new ManaV2InterfaceWanConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2InterfaceWanConfigWithDefaults

`func NewManaV2InterfaceWanConfigWithDefaults() *ManaV2InterfaceWanConfig`

NewManaV2InterfaceWanConfigWithDefaults instantiates a new ManaV2InterfaceWanConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGw

`func (o *ManaV2InterfaceWanConfig) GetGw() ManaV2NullableInterfaceIpConfig`

GetGw returns the Gw field if non-nil, zero value otherwise.

### GetGwOk

`func (o *ManaV2InterfaceWanConfig) GetGwOk() (*ManaV2NullableInterfaceIpConfig, bool)`

GetGwOk returns a tuple with the Gw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGw

`func (o *ManaV2InterfaceWanConfig) SetGw(v ManaV2NullableInterfaceIpConfig)`

SetGw sets Gw field to given value.

### HasGw

`func (o *ManaV2InterfaceWanConfig) HasGw() bool`

HasGw returns a boolean if a field has been set.

### GetType

`func (o *ManaV2InterfaceWanConfig) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2InterfaceWanConfig) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2InterfaceWanConfig) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2InterfaceWanConfig) HasType() bool`

HasType returns a boolean if a field has been set.

### GetVrfName

`func (o *ManaV2InterfaceWanConfig) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *ManaV2InterfaceWanConfig) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *ManaV2InterfaceWanConfig) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *ManaV2InterfaceWanConfig) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



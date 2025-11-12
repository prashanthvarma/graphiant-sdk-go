# ManaV2OspfAreaConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AreaId** | Pointer to **string** |  | [optional] 
**Interfaces** | Pointer to [**map[string]ManaV2NullableOspfInterfaceConfig**](ManaV2NullableOspfInterfaceConfig.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2OspfAreaConfig

`func NewManaV2OspfAreaConfig() *ManaV2OspfAreaConfig`

NewManaV2OspfAreaConfig instantiates a new ManaV2OspfAreaConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2OspfAreaConfigWithDefaults

`func NewManaV2OspfAreaConfigWithDefaults() *ManaV2OspfAreaConfig`

NewManaV2OspfAreaConfigWithDefaults instantiates a new ManaV2OspfAreaConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAreaId

`func (o *ManaV2OspfAreaConfig) GetAreaId() string`

GetAreaId returns the AreaId field if non-nil, zero value otherwise.

### GetAreaIdOk

`func (o *ManaV2OspfAreaConfig) GetAreaIdOk() (*string, bool)`

GetAreaIdOk returns a tuple with the AreaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaId

`func (o *ManaV2OspfAreaConfig) SetAreaId(v string)`

SetAreaId sets AreaId field to given value.

### HasAreaId

`func (o *ManaV2OspfAreaConfig) HasAreaId() bool`

HasAreaId returns a boolean if a field has been set.

### GetInterfaces

`func (o *ManaV2OspfAreaConfig) GetInterfaces() map[string]ManaV2NullableOspfInterfaceConfig`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *ManaV2OspfAreaConfig) GetInterfacesOk() (*map[string]ManaV2NullableOspfInterfaceConfig, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *ManaV2OspfAreaConfig) SetInterfaces(v map[string]ManaV2NullableOspfInterfaceConfig)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *ManaV2OspfAreaConfig) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetName

`func (o *ManaV2OspfAreaConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2OspfAreaConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2OspfAreaConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2OspfAreaConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ManaV2OspfAreaConfig) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2OspfAreaConfig) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2OspfAreaConfig) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2OspfAreaConfig) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



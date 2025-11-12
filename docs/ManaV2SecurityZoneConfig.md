# ManaV2SecurityZoneConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Inside** | Pointer to **string** |  | [optional] 
**Pairs** | Pointer to [**map[string]ManaV2NullableSecurityZonePairConfig**](ManaV2NullableSecurityZonePairConfig.md) |  | [optional] 

## Methods

### NewManaV2SecurityZoneConfig

`func NewManaV2SecurityZoneConfig() *ManaV2SecurityZoneConfig`

NewManaV2SecurityZoneConfig instantiates a new ManaV2SecurityZoneConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SecurityZoneConfigWithDefaults

`func NewManaV2SecurityZoneConfigWithDefaults() *ManaV2SecurityZoneConfig`

NewManaV2SecurityZoneConfigWithDefaults instantiates a new ManaV2SecurityZoneConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInside

`func (o *ManaV2SecurityZoneConfig) GetInside() string`

GetInside returns the Inside field if non-nil, zero value otherwise.

### GetInsideOk

`func (o *ManaV2SecurityZoneConfig) GetInsideOk() (*string, bool)`

GetInsideOk returns a tuple with the Inside field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInside

`func (o *ManaV2SecurityZoneConfig) SetInside(v string)`

SetInside sets Inside field to given value.

### HasInside

`func (o *ManaV2SecurityZoneConfig) HasInside() bool`

HasInside returns a boolean if a field has been set.

### GetPairs

`func (o *ManaV2SecurityZoneConfig) GetPairs() map[string]ManaV2NullableSecurityZonePairConfig`

GetPairs returns the Pairs field if non-nil, zero value otherwise.

### GetPairsOk

`func (o *ManaV2SecurityZoneConfig) GetPairsOk() (*map[string]ManaV2NullableSecurityZonePairConfig, bool)`

GetPairsOk returns a tuple with the Pairs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPairs

`func (o *ManaV2SecurityZoneConfig) SetPairs(v map[string]ManaV2NullableSecurityZonePairConfig)`

SetPairs sets Pairs field to given value.

### HasPairs

`func (o *ManaV2SecurityZoneConfig) HasPairs() bool`

HasPairs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



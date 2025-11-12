# ManaV2OspfProcessConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamilies** | Pointer to **[]string** |  | [optional] 
**AdminDistance** | Pointer to [**ManaV2NullableOspfAdminDistanceValue**](ManaV2NullableOspfAdminDistanceValue.md) |  | [optional] 
**Areas** | Pointer to [**map[string]ManaV2NullableOspfAreaConfig**](ManaV2NullableOspfAreaConfig.md) |  | [optional] 
**Auto** | Pointer to **bool** |  | [optional] 
**DefaultOriginate** | Pointer to **string** |  | [optional] 
**Manual** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Redistribution** | Pointer to [**map[string]ManaV2NullableOspfRedistributeProtocolConfig**](ManaV2NullableOspfRedistributeProtocolConfig.md) |  | [optional] 

## Methods

### NewManaV2OspfProcessConfig

`func NewManaV2OspfProcessConfig() *ManaV2OspfProcessConfig`

NewManaV2OspfProcessConfig instantiates a new ManaV2OspfProcessConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2OspfProcessConfigWithDefaults

`func NewManaV2OspfProcessConfigWithDefaults() *ManaV2OspfProcessConfig`

NewManaV2OspfProcessConfigWithDefaults instantiates a new ManaV2OspfProcessConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamilies

`func (o *ManaV2OspfProcessConfig) GetAddressFamilies() []string`

GetAddressFamilies returns the AddressFamilies field if non-nil, zero value otherwise.

### GetAddressFamiliesOk

`func (o *ManaV2OspfProcessConfig) GetAddressFamiliesOk() (*[]string, bool)`

GetAddressFamiliesOk returns a tuple with the AddressFamilies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamilies

`func (o *ManaV2OspfProcessConfig) SetAddressFamilies(v []string)`

SetAddressFamilies sets AddressFamilies field to given value.

### HasAddressFamilies

`func (o *ManaV2OspfProcessConfig) HasAddressFamilies() bool`

HasAddressFamilies returns a boolean if a field has been set.

### GetAdminDistance

`func (o *ManaV2OspfProcessConfig) GetAdminDistance() ManaV2NullableOspfAdminDistanceValue`

GetAdminDistance returns the AdminDistance field if non-nil, zero value otherwise.

### GetAdminDistanceOk

`func (o *ManaV2OspfProcessConfig) GetAdminDistanceOk() (*ManaV2NullableOspfAdminDistanceValue, bool)`

GetAdminDistanceOk returns a tuple with the AdminDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminDistance

`func (o *ManaV2OspfProcessConfig) SetAdminDistance(v ManaV2NullableOspfAdminDistanceValue)`

SetAdminDistance sets AdminDistance field to given value.

### HasAdminDistance

`func (o *ManaV2OspfProcessConfig) HasAdminDistance() bool`

HasAdminDistance returns a boolean if a field has been set.

### GetAreas

`func (o *ManaV2OspfProcessConfig) GetAreas() map[string]ManaV2NullableOspfAreaConfig`

GetAreas returns the Areas field if non-nil, zero value otherwise.

### GetAreasOk

`func (o *ManaV2OspfProcessConfig) GetAreasOk() (*map[string]ManaV2NullableOspfAreaConfig, bool)`

GetAreasOk returns a tuple with the Areas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreas

`func (o *ManaV2OspfProcessConfig) SetAreas(v map[string]ManaV2NullableOspfAreaConfig)`

SetAreas sets Areas field to given value.

### HasAreas

`func (o *ManaV2OspfProcessConfig) HasAreas() bool`

HasAreas returns a boolean if a field has been set.

### GetAuto

`func (o *ManaV2OspfProcessConfig) GetAuto() bool`

GetAuto returns the Auto field if non-nil, zero value otherwise.

### GetAutoOk

`func (o *ManaV2OspfProcessConfig) GetAutoOk() (*bool, bool)`

GetAutoOk returns a tuple with the Auto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuto

`func (o *ManaV2OspfProcessConfig) SetAuto(v bool)`

SetAuto sets Auto field to given value.

### HasAuto

`func (o *ManaV2OspfProcessConfig) HasAuto() bool`

HasAuto returns a boolean if a field has been set.

### GetDefaultOriginate

`func (o *ManaV2OspfProcessConfig) GetDefaultOriginate() string`

GetDefaultOriginate returns the DefaultOriginate field if non-nil, zero value otherwise.

### GetDefaultOriginateOk

`func (o *ManaV2OspfProcessConfig) GetDefaultOriginateOk() (*string, bool)`

GetDefaultOriginateOk returns a tuple with the DefaultOriginate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultOriginate

`func (o *ManaV2OspfProcessConfig) SetDefaultOriginate(v string)`

SetDefaultOriginate sets DefaultOriginate field to given value.

### HasDefaultOriginate

`func (o *ManaV2OspfProcessConfig) HasDefaultOriginate() bool`

HasDefaultOriginate returns a boolean if a field has been set.

### GetManual

`func (o *ManaV2OspfProcessConfig) GetManual() string`

GetManual returns the Manual field if non-nil, zero value otherwise.

### GetManualOk

`func (o *ManaV2OspfProcessConfig) GetManualOk() (*string, bool)`

GetManualOk returns a tuple with the Manual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManual

`func (o *ManaV2OspfProcessConfig) SetManual(v string)`

SetManual sets Manual field to given value.

### HasManual

`func (o *ManaV2OspfProcessConfig) HasManual() bool`

HasManual returns a boolean if a field has been set.

### GetName

`func (o *ManaV2OspfProcessConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2OspfProcessConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2OspfProcessConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2OspfProcessConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRedistribution

`func (o *ManaV2OspfProcessConfig) GetRedistribution() map[string]ManaV2NullableOspfRedistributeProtocolConfig`

GetRedistribution returns the Redistribution field if non-nil, zero value otherwise.

### GetRedistributionOk

`func (o *ManaV2OspfProcessConfig) GetRedistributionOk() (*map[string]ManaV2NullableOspfRedistributeProtocolConfig, bool)`

GetRedistributionOk returns a tuple with the Redistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedistribution

`func (o *ManaV2OspfProcessConfig) SetRedistribution(v map[string]ManaV2NullableOspfRedistributeProtocolConfig)`

SetRedistribution sets Redistribution field to given value.

### HasRedistribution

`func (o *ManaV2OspfProcessConfig) HasRedistribution() bool`

HasRedistribution returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



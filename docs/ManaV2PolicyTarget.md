# ManaV2PolicyTarget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExcludedDevices** | Pointer to [**[]ManaV2Device**](ManaV2Device.md) |  | [optional] 
**PrefixSet** | Pointer to [**ManaV2EnterprisePrefixSet**](ManaV2EnterprisePrefixSet.md) |  | [optional] 
**Sites** | Pointer to [**[]ManaV2Site**](ManaV2Site.md) |  | [optional] 

## Methods

### NewManaV2PolicyTarget

`func NewManaV2PolicyTarget() *ManaV2PolicyTarget`

NewManaV2PolicyTarget instantiates a new ManaV2PolicyTarget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2PolicyTargetWithDefaults

`func NewManaV2PolicyTargetWithDefaults() *ManaV2PolicyTarget`

NewManaV2PolicyTargetWithDefaults instantiates a new ManaV2PolicyTarget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExcludedDevices

`func (o *ManaV2PolicyTarget) GetExcludedDevices() []ManaV2Device`

GetExcludedDevices returns the ExcludedDevices field if non-nil, zero value otherwise.

### GetExcludedDevicesOk

`func (o *ManaV2PolicyTarget) GetExcludedDevicesOk() (*[]ManaV2Device, bool)`

GetExcludedDevicesOk returns a tuple with the ExcludedDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedDevices

`func (o *ManaV2PolicyTarget) SetExcludedDevices(v []ManaV2Device)`

SetExcludedDevices sets ExcludedDevices field to given value.

### HasExcludedDevices

`func (o *ManaV2PolicyTarget) HasExcludedDevices() bool`

HasExcludedDevices returns a boolean if a field has been set.

### GetPrefixSet

`func (o *ManaV2PolicyTarget) GetPrefixSet() ManaV2EnterprisePrefixSet`

GetPrefixSet returns the PrefixSet field if non-nil, zero value otherwise.

### GetPrefixSetOk

`func (o *ManaV2PolicyTarget) GetPrefixSetOk() (*ManaV2EnterprisePrefixSet, bool)`

GetPrefixSetOk returns a tuple with the PrefixSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixSet

`func (o *ManaV2PolicyTarget) SetPrefixSet(v ManaV2EnterprisePrefixSet)`

SetPrefixSet sets PrefixSet field to given value.

### HasPrefixSet

`func (o *ManaV2PolicyTarget) HasPrefixSet() bool`

HasPrefixSet returns a boolean if a field has been set.

### GetSites

`func (o *ManaV2PolicyTarget) GetSites() []ManaV2Site`

GetSites returns the Sites field if non-nil, zero value otherwise.

### GetSitesOk

`func (o *ManaV2PolicyTarget) GetSitesOk() (*[]ManaV2Site, bool)`

GetSitesOk returns a tuple with the Sites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSites

`func (o *ManaV2PolicyTarget) SetSites(v []ManaV2Site)`

SetSites sets Sites field to given value.

### HasSites

`func (o *ManaV2PolicyTarget) HasSites() bool`

HasSites returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



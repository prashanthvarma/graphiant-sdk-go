# ManaV2PolicyTargetInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExcludedDevices** | Pointer to **[]int64** |  | [optional] 
**PrefixSet** | Pointer to [**ManaV2EnterprisePrefixSetInput**](ManaV2EnterprisePrefixSetInput.md) |  | [optional] 
**Sites** | Pointer to **[]int64** |  | [optional] 

## Methods

### NewManaV2PolicyTargetInput

`func NewManaV2PolicyTargetInput() *ManaV2PolicyTargetInput`

NewManaV2PolicyTargetInput instantiates a new ManaV2PolicyTargetInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2PolicyTargetInputWithDefaults

`func NewManaV2PolicyTargetInputWithDefaults() *ManaV2PolicyTargetInput`

NewManaV2PolicyTargetInputWithDefaults instantiates a new ManaV2PolicyTargetInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExcludedDevices

`func (o *ManaV2PolicyTargetInput) GetExcludedDevices() []int64`

GetExcludedDevices returns the ExcludedDevices field if non-nil, zero value otherwise.

### GetExcludedDevicesOk

`func (o *ManaV2PolicyTargetInput) GetExcludedDevicesOk() (*[]int64, bool)`

GetExcludedDevicesOk returns a tuple with the ExcludedDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedDevices

`func (o *ManaV2PolicyTargetInput) SetExcludedDevices(v []int64)`

SetExcludedDevices sets ExcludedDevices field to given value.

### HasExcludedDevices

`func (o *ManaV2PolicyTargetInput) HasExcludedDevices() bool`

HasExcludedDevices returns a boolean if a field has been set.

### GetPrefixSet

`func (o *ManaV2PolicyTargetInput) GetPrefixSet() ManaV2EnterprisePrefixSetInput`

GetPrefixSet returns the PrefixSet field if non-nil, zero value otherwise.

### GetPrefixSetOk

`func (o *ManaV2PolicyTargetInput) GetPrefixSetOk() (*ManaV2EnterprisePrefixSetInput, bool)`

GetPrefixSetOk returns a tuple with the PrefixSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixSet

`func (o *ManaV2PolicyTargetInput) SetPrefixSet(v ManaV2EnterprisePrefixSetInput)`

SetPrefixSet sets PrefixSet field to given value.

### HasPrefixSet

`func (o *ManaV2PolicyTargetInput) HasPrefixSet() bool`

HasPrefixSet returns a boolean if a field has been set.

### GetSites

`func (o *ManaV2PolicyTargetInput) GetSites() []int64`

GetSites returns the Sites field if non-nil, zero value otherwise.

### GetSitesOk

`func (o *ManaV2PolicyTargetInput) GetSitesOk() (*[]int64, bool)`

GetSitesOk returns a tuple with the Sites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSites

`func (o *ManaV2PolicyTargetInput) SetSites(v []int64)`

SetSites sets Sites field to given value.

### HasSites

`func (o *ManaV2PolicyTargetInput) HasSites() bool`

HasSites returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



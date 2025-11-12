# ManaV2AppListConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Apps** | Pointer to [**[]ManaV2AppIdentifier**](ManaV2AppIdentifier.md) |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2AppListConfig

`func NewManaV2AppListConfig() *ManaV2AppListConfig`

NewManaV2AppListConfig instantiates a new ManaV2AppListConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AppListConfigWithDefaults

`func NewManaV2AppListConfigWithDefaults() *ManaV2AppListConfig`

NewManaV2AppListConfigWithDefaults instantiates a new ManaV2AppListConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApps

`func (o *ManaV2AppListConfig) GetApps() []ManaV2AppIdentifier`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *ManaV2AppListConfig) GetAppsOk() (*[]ManaV2AppIdentifier, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *ManaV2AppListConfig) SetApps(v []ManaV2AppIdentifier)`

SetApps sets Apps field to given value.

### HasApps

`func (o *ManaV2AppListConfig) HasApps() bool`

HasApps returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2AppListConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2AppListConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2AppListConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2AppListConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetName

`func (o *ManaV2AppListConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2AppListConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2AppListConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2AppListConfig) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



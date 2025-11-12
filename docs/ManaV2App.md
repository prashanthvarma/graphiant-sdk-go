# ManaV2App

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Identifier** | Pointer to [**ManaV2AppIdentifier**](ManaV2AppIdentifier.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2App

`func NewManaV2App() *ManaV2App`

NewManaV2App instantiates a new ManaV2App object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AppWithDefaults

`func NewManaV2AppWithDefaults() *ManaV2App`

NewManaV2AppWithDefaults instantiates a new ManaV2App object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2App) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2App) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2App) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2App) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIdentifier

`func (o *ManaV2App) GetIdentifier() ManaV2AppIdentifier`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ManaV2App) GetIdentifierOk() (*ManaV2AppIdentifier, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ManaV2App) SetIdentifier(v ManaV2AppIdentifier)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ManaV2App) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetName

`func (o *ManaV2App) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2App) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2App) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2App) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2PrefixSet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Entries** | Pointer to [**[]ManaV2PrefixSetEntry**](ManaV2PrefixSetEntry.md) |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Mode** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Policies** | Pointer to [**[]ManaV2PrefixSetPolicy**](ManaV2PrefixSetPolicy.md) |  | [optional] 
**PolicyCount** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2PrefixSet

`func NewManaV2PrefixSet() *ManaV2PrefixSet`

NewManaV2PrefixSet instantiates a new ManaV2PrefixSet object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2PrefixSetWithDefaults

`func NewManaV2PrefixSetWithDefaults() *ManaV2PrefixSet`

NewManaV2PrefixSetWithDefaults instantiates a new ManaV2PrefixSet object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2PrefixSet) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2PrefixSet) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2PrefixSet) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2PrefixSet) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEntries

`func (o *ManaV2PrefixSet) GetEntries() []ManaV2PrefixSetEntry`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *ManaV2PrefixSet) GetEntriesOk() (*[]ManaV2PrefixSetEntry, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *ManaV2PrefixSet) SetEntries(v []ManaV2PrefixSetEntry)`

SetEntries sets Entries field to given value.

### HasEntries

`func (o *ManaV2PrefixSet) HasEntries() bool`

HasEntries returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ManaV2PrefixSet) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ManaV2PrefixSet) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ManaV2PrefixSet) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ManaV2PrefixSet) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2PrefixSet) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2PrefixSet) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2PrefixSet) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2PrefixSet) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetId

`func (o *ManaV2PrefixSet) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2PrefixSet) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2PrefixSet) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2PrefixSet) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMode

`func (o *ManaV2PrefixSet) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ManaV2PrefixSet) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ManaV2PrefixSet) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *ManaV2PrefixSet) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetName

`func (o *ManaV2PrefixSet) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2PrefixSet) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2PrefixSet) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2PrefixSet) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPolicies

`func (o *ManaV2PrefixSet) GetPolicies() []ManaV2PrefixSetPolicy`

GetPolicies returns the Policies field if non-nil, zero value otherwise.

### GetPoliciesOk

`func (o *ManaV2PrefixSet) GetPoliciesOk() (*[]ManaV2PrefixSetPolicy, bool)`

GetPoliciesOk returns a tuple with the Policies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicies

`func (o *ManaV2PrefixSet) SetPolicies(v []ManaV2PrefixSetPolicy)`

SetPolicies sets Policies field to given value.

### HasPolicies

`func (o *ManaV2PrefixSet) HasPolicies() bool`

HasPolicies returns a boolean if a field has been set.

### GetPolicyCount

`func (o *ManaV2PrefixSet) GetPolicyCount() int32`

GetPolicyCount returns the PolicyCount field if non-nil, zero value otherwise.

### GetPolicyCountOk

`func (o *ManaV2PrefixSet) GetPolicyCountOk() (*int32, bool)`

GetPolicyCountOk returns a tuple with the PolicyCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyCount

`func (o *ManaV2PrefixSet) SetPolicyCount(v int32)`

SetPolicyCount sets PolicyCount field to given value.

### HasPolicyCount

`func (o *ManaV2PrefixSet) HasPolicyCount() bool`

HasPolicyCount returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2PrefixSet) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2PrefixSet) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2PrefixSet) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2PrefixSet) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



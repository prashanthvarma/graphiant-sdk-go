# ManaV2NatPolicyRulesetConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Rules** | Pointer to [**map[string]ManaV2NATPolicyRulesetConfigNullableRule**](ManaV2NATPolicyRulesetConfigNullableRule.md) |  | [optional] 

## Methods

### NewManaV2NatPolicyRulesetConfig

`func NewManaV2NatPolicyRulesetConfig() *ManaV2NatPolicyRulesetConfig`

NewManaV2NatPolicyRulesetConfig instantiates a new ManaV2NatPolicyRulesetConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2NatPolicyRulesetConfigWithDefaults

`func NewManaV2NatPolicyRulesetConfigWithDefaults() *ManaV2NatPolicyRulesetConfig`

NewManaV2NatPolicyRulesetConfigWithDefaults instantiates a new ManaV2NatPolicyRulesetConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2NatPolicyRulesetConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2NatPolicyRulesetConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2NatPolicyRulesetConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2NatPolicyRulesetConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetName

`func (o *ManaV2NatPolicyRulesetConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2NatPolicyRulesetConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2NatPolicyRulesetConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2NatPolicyRulesetConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRules

`func (o *ManaV2NatPolicyRulesetConfig) GetRules() map[string]ManaV2NATPolicyRulesetConfigNullableRule`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *ManaV2NatPolicyRulesetConfig) GetRulesOk() (*map[string]ManaV2NATPolicyRulesetConfigNullableRule, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *ManaV2NatPolicyRulesetConfig) SetRules(v map[string]ManaV2NATPolicyRulesetConfigNullableRule)`

SetRules sets Rules field to given value.

### HasRules

`func (o *ManaV2NatPolicyRulesetConfig) HasRules() bool`

HasRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



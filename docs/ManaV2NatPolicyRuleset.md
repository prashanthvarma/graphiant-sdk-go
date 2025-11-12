# ManaV2NatPolicyRuleset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Rules** | Pointer to [**[]ManaV2NATPolicyRulesetRule**](ManaV2NATPolicyRulesetRule.md) |  | [optional] 

## Methods

### NewManaV2NatPolicyRuleset

`func NewManaV2NatPolicyRuleset() *ManaV2NatPolicyRuleset`

NewManaV2NatPolicyRuleset instantiates a new ManaV2NatPolicyRuleset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2NatPolicyRulesetWithDefaults

`func NewManaV2NatPolicyRulesetWithDefaults() *ManaV2NatPolicyRuleset`

NewManaV2NatPolicyRulesetWithDefaults instantiates a new ManaV2NatPolicyRuleset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2NatPolicyRuleset) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2NatPolicyRuleset) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2NatPolicyRuleset) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2NatPolicyRuleset) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *ManaV2NatPolicyRuleset) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2NatPolicyRuleset) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2NatPolicyRuleset) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2NatPolicyRuleset) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2NatPolicyRuleset) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2NatPolicyRuleset) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2NatPolicyRuleset) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2NatPolicyRuleset) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRules

`func (o *ManaV2NatPolicyRuleset) GetRules() []ManaV2NATPolicyRulesetRule`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *ManaV2NatPolicyRuleset) GetRulesOk() (*[]ManaV2NATPolicyRulesetRule, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *ManaV2NatPolicyRuleset) SetRules(v []ManaV2NATPolicyRulesetRule)`

SetRules sets Rules field to given value.

### HasRules

`func (o *ManaV2NatPolicyRuleset) HasRules() bool`

HasRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2TrafficPolicyRuleset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Index** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Rules** | Pointer to [**[]ManaV2TrafficPolicyRulesetRule**](ManaV2TrafficPolicyRulesetRule.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2TrafficPolicyRuleset

`func NewManaV2TrafficPolicyRuleset() *ManaV2TrafficPolicyRuleset`

NewManaV2TrafficPolicyRuleset instantiates a new ManaV2TrafficPolicyRuleset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2TrafficPolicyRulesetWithDefaults

`func NewManaV2TrafficPolicyRulesetWithDefaults() *ManaV2TrafficPolicyRuleset`

NewManaV2TrafficPolicyRulesetWithDefaults instantiates a new ManaV2TrafficPolicyRuleset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2TrafficPolicyRuleset) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2TrafficPolicyRuleset) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2TrafficPolicyRuleset) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2TrafficPolicyRuleset) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ManaV2TrafficPolicyRuleset) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ManaV2TrafficPolicyRuleset) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ManaV2TrafficPolicyRuleset) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ManaV2TrafficPolicyRuleset) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2TrafficPolicyRuleset) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2TrafficPolicyRuleset) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2TrafficPolicyRuleset) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2TrafficPolicyRuleset) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetId

`func (o *ManaV2TrafficPolicyRuleset) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2TrafficPolicyRuleset) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2TrafficPolicyRuleset) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2TrafficPolicyRuleset) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIndex

`func (o *ManaV2TrafficPolicyRuleset) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *ManaV2TrafficPolicyRuleset) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *ManaV2TrafficPolicyRuleset) SetIndex(v int32)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *ManaV2TrafficPolicyRuleset) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### GetName

`func (o *ManaV2TrafficPolicyRuleset) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2TrafficPolicyRuleset) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2TrafficPolicyRuleset) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2TrafficPolicyRuleset) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRules

`func (o *ManaV2TrafficPolicyRuleset) GetRules() []ManaV2TrafficPolicyRulesetRule`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *ManaV2TrafficPolicyRuleset) GetRulesOk() (*[]ManaV2TrafficPolicyRulesetRule, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *ManaV2TrafficPolicyRuleset) SetRules(v []ManaV2TrafficPolicyRulesetRule)`

SetRules sets Rules field to given value.

### HasRules

`func (o *ManaV2TrafficPolicyRuleset) HasRules() bool`

HasRules returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2TrafficPolicyRuleset) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2TrafficPolicyRuleset) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2TrafficPolicyRuleset) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2TrafficPolicyRuleset) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



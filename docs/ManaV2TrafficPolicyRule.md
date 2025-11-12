# ManaV2TrafficPolicyRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to [**ManaV2TrafficPolicyAction**](ManaV2TrafficPolicyAction.md) |  | [optional] 
**Match** | Pointer to [**ManaV2PolicyMatch**](ManaV2PolicyMatch.md) |  | [optional] 
**PolicyRuleIndex** | Pointer to **int64** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2TrafficPolicyRule

`func NewManaV2TrafficPolicyRule() *ManaV2TrafficPolicyRule`

NewManaV2TrafficPolicyRule instantiates a new ManaV2TrafficPolicyRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2TrafficPolicyRuleWithDefaults

`func NewManaV2TrafficPolicyRuleWithDefaults() *ManaV2TrafficPolicyRule`

NewManaV2TrafficPolicyRuleWithDefaults instantiates a new ManaV2TrafficPolicyRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *ManaV2TrafficPolicyRule) GetAction() ManaV2TrafficPolicyAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ManaV2TrafficPolicyRule) GetActionOk() (*ManaV2TrafficPolicyAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ManaV2TrafficPolicyRule) SetAction(v ManaV2TrafficPolicyAction)`

SetAction sets Action field to given value.

### HasAction

`func (o *ManaV2TrafficPolicyRule) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetMatch

`func (o *ManaV2TrafficPolicyRule) GetMatch() ManaV2PolicyMatch`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *ManaV2TrafficPolicyRule) GetMatchOk() (*ManaV2PolicyMatch, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *ManaV2TrafficPolicyRule) SetMatch(v ManaV2PolicyMatch)`

SetMatch sets Match field to given value.

### HasMatch

`func (o *ManaV2TrafficPolicyRule) HasMatch() bool`

HasMatch returns a boolean if a field has been set.

### GetPolicyRuleIndex

`func (o *ManaV2TrafficPolicyRule) GetPolicyRuleIndex() int64`

GetPolicyRuleIndex returns the PolicyRuleIndex field if non-nil, zero value otherwise.

### GetPolicyRuleIndexOk

`func (o *ManaV2TrafficPolicyRule) GetPolicyRuleIndexOk() (*int64, bool)`

GetPolicyRuleIndexOk returns a tuple with the PolicyRuleIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyRuleIndex

`func (o *ManaV2TrafficPolicyRule) SetPolicyRuleIndex(v int64)`

SetPolicyRuleIndex sets PolicyRuleIndex field to given value.

### HasPolicyRuleIndex

`func (o *ManaV2TrafficPolicyRule) HasPolicyRuleIndex() bool`

HasPolicyRuleIndex returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2TrafficPolicyRule) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2TrafficPolicyRule) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2TrafficPolicyRule) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2TrafficPolicyRule) HasSeq() bool`

HasSeq returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



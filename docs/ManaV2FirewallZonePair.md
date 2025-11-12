# ManaV2FirewallZonePair

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Inside** | Pointer to **string** |  | [optional] 
**Outside** | Pointer to **string** |  | [optional] 
**SecurityRulesets** | Pointer to [**[]ManaV2SecurityPolicyRuleset**](ManaV2SecurityPolicyRuleset.md) |  | [optional] 

## Methods

### NewManaV2FirewallZonePair

`func NewManaV2FirewallZonePair() *ManaV2FirewallZonePair`

NewManaV2FirewallZonePair instantiates a new ManaV2FirewallZonePair object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2FirewallZonePairWithDefaults

`func NewManaV2FirewallZonePairWithDefaults() *ManaV2FirewallZonePair`

NewManaV2FirewallZonePairWithDefaults instantiates a new ManaV2FirewallZonePair object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInside

`func (o *ManaV2FirewallZonePair) GetInside() string`

GetInside returns the Inside field if non-nil, zero value otherwise.

### GetInsideOk

`func (o *ManaV2FirewallZonePair) GetInsideOk() (*string, bool)`

GetInsideOk returns a tuple with the Inside field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInside

`func (o *ManaV2FirewallZonePair) SetInside(v string)`

SetInside sets Inside field to given value.

### HasInside

`func (o *ManaV2FirewallZonePair) HasInside() bool`

HasInside returns a boolean if a field has been set.

### GetOutside

`func (o *ManaV2FirewallZonePair) GetOutside() string`

GetOutside returns the Outside field if non-nil, zero value otherwise.

### GetOutsideOk

`func (o *ManaV2FirewallZonePair) GetOutsideOk() (*string, bool)`

GetOutsideOk returns a tuple with the Outside field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutside

`func (o *ManaV2FirewallZonePair) SetOutside(v string)`

SetOutside sets Outside field to given value.

### HasOutside

`func (o *ManaV2FirewallZonePair) HasOutside() bool`

HasOutside returns a boolean if a field has been set.

### GetSecurityRulesets

`func (o *ManaV2FirewallZonePair) GetSecurityRulesets() []ManaV2SecurityPolicyRuleset`

GetSecurityRulesets returns the SecurityRulesets field if non-nil, zero value otherwise.

### GetSecurityRulesetsOk

`func (o *ManaV2FirewallZonePair) GetSecurityRulesetsOk() (*[]ManaV2SecurityPolicyRuleset, bool)`

GetSecurityRulesetsOk returns a tuple with the SecurityRulesets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityRulesets

`func (o *ManaV2FirewallZonePair) SetSecurityRulesets(v []ManaV2SecurityPolicyRuleset)`

SetSecurityRulesets sets SecurityRulesets field to given value.

### HasSecurityRulesets

`func (o *ManaV2FirewallZonePair) HasSecurityRulesets() bool`

HasSecurityRulesets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



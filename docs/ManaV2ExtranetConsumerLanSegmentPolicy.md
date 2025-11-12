# ManaV2ExtranetConsumerLanSegmentPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerLanSegment** | Pointer to **int64** |  | [optional] 
**RestrictedPrefixes** | Pointer to **[]string** |  | [optional] 
**Rules** | Pointer to [**[]ManaV2ExtranetConsumerNatRule**](ManaV2ExtranetConsumerNatRule.md) |  | [optional] 

## Methods

### NewManaV2ExtranetConsumerLanSegmentPolicy

`func NewManaV2ExtranetConsumerLanSegmentPolicy() *ManaV2ExtranetConsumerLanSegmentPolicy`

NewManaV2ExtranetConsumerLanSegmentPolicy instantiates a new ManaV2ExtranetConsumerLanSegmentPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ExtranetConsumerLanSegmentPolicyWithDefaults

`func NewManaV2ExtranetConsumerLanSegmentPolicyWithDefaults() *ManaV2ExtranetConsumerLanSegmentPolicy`

NewManaV2ExtranetConsumerLanSegmentPolicyWithDefaults instantiates a new ManaV2ExtranetConsumerLanSegmentPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerLanSegment

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) GetConsumerLanSegment() int64`

GetConsumerLanSegment returns the ConsumerLanSegment field if non-nil, zero value otherwise.

### GetConsumerLanSegmentOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) GetConsumerLanSegmentOk() (*int64, bool)`

GetConsumerLanSegmentOk returns a tuple with the ConsumerLanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerLanSegment

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) SetConsumerLanSegment(v int64)`

SetConsumerLanSegment sets ConsumerLanSegment field to given value.

### HasConsumerLanSegment

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) HasConsumerLanSegment() bool`

HasConsumerLanSegment returns a boolean if a field has been set.

### GetRestrictedPrefixes

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) GetRestrictedPrefixes() []string`

GetRestrictedPrefixes returns the RestrictedPrefixes field if non-nil, zero value otherwise.

### GetRestrictedPrefixesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) GetRestrictedPrefixesOk() (*[]string, bool)`

GetRestrictedPrefixesOk returns a tuple with the RestrictedPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedPrefixes

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) SetRestrictedPrefixes(v []string)`

SetRestrictedPrefixes sets RestrictedPrefixes field to given value.

### HasRestrictedPrefixes

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) HasRestrictedPrefixes() bool`

HasRestrictedPrefixes returns a boolean if a field has been set.

### GetRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) GetRules() []ManaV2ExtranetConsumerNatRule`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) GetRulesOk() (*[]ManaV2ExtranetConsumerNatRule, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) SetRules(v []ManaV2ExtranetConsumerNatRule)`

SetRules sets Rules field to given value.

### HasRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicy) HasRules() bool`

HasRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



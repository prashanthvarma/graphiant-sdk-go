# ManaV2ExtranetConsumerLanSegmentPolicyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerLanSegment** | Pointer to **int64** |  | [optional] 
**InboundSecurityRules** | Pointer to [**[]ManaV2SecurityPolicyRule**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**OutboundSecurityRules** | Pointer to [**[]ManaV2SecurityPolicyRule**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**RestrictedPrefixes** | Pointer to **[]string** |  | [optional] 
**Rules** | Pointer to [**[]ManaV2ExtranetConsumerNatRule**](ManaV2ExtranetConsumerNatRule.md) |  | [optional] 
**TrafficRules** | Pointer to [**[]ManaV2TrafficPolicyRule**](ManaV2TrafficPolicyRule.md) |  | [optional] 

## Methods

### NewManaV2ExtranetConsumerLanSegmentPolicyResponse

`func NewManaV2ExtranetConsumerLanSegmentPolicyResponse() *ManaV2ExtranetConsumerLanSegmentPolicyResponse`

NewManaV2ExtranetConsumerLanSegmentPolicyResponse instantiates a new ManaV2ExtranetConsumerLanSegmentPolicyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ExtranetConsumerLanSegmentPolicyResponseWithDefaults

`func NewManaV2ExtranetConsumerLanSegmentPolicyResponseWithDefaults() *ManaV2ExtranetConsumerLanSegmentPolicyResponse`

NewManaV2ExtranetConsumerLanSegmentPolicyResponseWithDefaults instantiates a new ManaV2ExtranetConsumerLanSegmentPolicyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerLanSegment

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetConsumerLanSegment() int64`

GetConsumerLanSegment returns the ConsumerLanSegment field if non-nil, zero value otherwise.

### GetConsumerLanSegmentOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetConsumerLanSegmentOk() (*int64, bool)`

GetConsumerLanSegmentOk returns a tuple with the ConsumerLanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerLanSegment

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) SetConsumerLanSegment(v int64)`

SetConsumerLanSegment sets ConsumerLanSegment field to given value.

### HasConsumerLanSegment

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) HasConsumerLanSegment() bool`

HasConsumerLanSegment returns a boolean if a field has been set.

### GetInboundSecurityRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetInboundSecurityRules() []ManaV2SecurityPolicyRule`

GetInboundSecurityRules returns the InboundSecurityRules field if non-nil, zero value otherwise.

### GetInboundSecurityRulesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetInboundSecurityRulesOk() (*[]ManaV2SecurityPolicyRule, bool)`

GetInboundSecurityRulesOk returns a tuple with the InboundSecurityRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundSecurityRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) SetInboundSecurityRules(v []ManaV2SecurityPolicyRule)`

SetInboundSecurityRules sets InboundSecurityRules field to given value.

### HasInboundSecurityRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) HasInboundSecurityRules() bool`

HasInboundSecurityRules returns a boolean if a field has been set.

### GetOutboundSecurityRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetOutboundSecurityRules() []ManaV2SecurityPolicyRule`

GetOutboundSecurityRules returns the OutboundSecurityRules field if non-nil, zero value otherwise.

### GetOutboundSecurityRulesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetOutboundSecurityRulesOk() (*[]ManaV2SecurityPolicyRule, bool)`

GetOutboundSecurityRulesOk returns a tuple with the OutboundSecurityRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundSecurityRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) SetOutboundSecurityRules(v []ManaV2SecurityPolicyRule)`

SetOutboundSecurityRules sets OutboundSecurityRules field to given value.

### HasOutboundSecurityRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) HasOutboundSecurityRules() bool`

HasOutboundSecurityRules returns a boolean if a field has been set.

### GetRestrictedPrefixes

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetRestrictedPrefixes() []string`

GetRestrictedPrefixes returns the RestrictedPrefixes field if non-nil, zero value otherwise.

### GetRestrictedPrefixesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetRestrictedPrefixesOk() (*[]string, bool)`

GetRestrictedPrefixesOk returns a tuple with the RestrictedPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedPrefixes

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) SetRestrictedPrefixes(v []string)`

SetRestrictedPrefixes sets RestrictedPrefixes field to given value.

### HasRestrictedPrefixes

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) HasRestrictedPrefixes() bool`

HasRestrictedPrefixes returns a boolean if a field has been set.

### GetRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetRules() []ManaV2ExtranetConsumerNatRule`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetRulesOk() (*[]ManaV2ExtranetConsumerNatRule, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) SetRules(v []ManaV2ExtranetConsumerNatRule)`

SetRules sets Rules field to given value.

### HasRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) HasRules() bool`

HasRules returns a boolean if a field has been set.

### GetTrafficRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetTrafficRules() []ManaV2TrafficPolicyRule`

GetTrafficRules returns the TrafficRules field if non-nil, zero value otherwise.

### GetTrafficRulesOk

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) GetTrafficRulesOk() (*[]ManaV2TrafficPolicyRule, bool)`

GetTrafficRulesOk returns a tuple with the TrafficRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) SetTrafficRules(v []ManaV2TrafficPolicyRule)`

SetTrafficRules sets TrafficRules field to given value.

### HasTrafficRules

`func (o *ManaV2ExtranetConsumerLanSegmentPolicyResponse) HasTrafficRules() bool`

HasTrafficRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



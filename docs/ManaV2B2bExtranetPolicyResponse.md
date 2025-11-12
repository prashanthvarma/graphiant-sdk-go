# ManaV2B2bExtranetPolicyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DnsName** | Pointer to **string** |  | [optional] 
**InboundSecurityRules** | Pointer to [**[]ManaV2SecurityPolicyRule**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**Policy** | Pointer to [**ManaV2B2bExtranetProducerPolicy**](ManaV2B2bExtranetProducerPolicy.md) |  | [optional] 
**ServiceName** | Pointer to **string** |  | [optional] 
**TrafficRules** | Pointer to [**[]ManaV2TrafficPolicyRule**](ManaV2TrafficPolicyRule.md) |  | [optional] 

## Methods

### NewManaV2B2bExtranetPolicyResponse

`func NewManaV2B2bExtranetPolicyResponse() *ManaV2B2bExtranetPolicyResponse`

NewManaV2B2bExtranetPolicyResponse instantiates a new ManaV2B2bExtranetPolicyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2B2bExtranetPolicyResponseWithDefaults

`func NewManaV2B2bExtranetPolicyResponseWithDefaults() *ManaV2B2bExtranetPolicyResponse`

NewManaV2B2bExtranetPolicyResponseWithDefaults instantiates a new ManaV2B2bExtranetPolicyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDnsName

`func (o *ManaV2B2bExtranetPolicyResponse) GetDnsName() string`

GetDnsName returns the DnsName field if non-nil, zero value otherwise.

### GetDnsNameOk

`func (o *ManaV2B2bExtranetPolicyResponse) GetDnsNameOk() (*string, bool)`

GetDnsNameOk returns a tuple with the DnsName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsName

`func (o *ManaV2B2bExtranetPolicyResponse) SetDnsName(v string)`

SetDnsName sets DnsName field to given value.

### HasDnsName

`func (o *ManaV2B2bExtranetPolicyResponse) HasDnsName() bool`

HasDnsName returns a boolean if a field has been set.

### GetInboundSecurityRules

`func (o *ManaV2B2bExtranetPolicyResponse) GetInboundSecurityRules() []ManaV2SecurityPolicyRule`

GetInboundSecurityRules returns the InboundSecurityRules field if non-nil, zero value otherwise.

### GetInboundSecurityRulesOk

`func (o *ManaV2B2bExtranetPolicyResponse) GetInboundSecurityRulesOk() (*[]ManaV2SecurityPolicyRule, bool)`

GetInboundSecurityRulesOk returns a tuple with the InboundSecurityRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundSecurityRules

`func (o *ManaV2B2bExtranetPolicyResponse) SetInboundSecurityRules(v []ManaV2SecurityPolicyRule)`

SetInboundSecurityRules sets InboundSecurityRules field to given value.

### HasInboundSecurityRules

`func (o *ManaV2B2bExtranetPolicyResponse) HasInboundSecurityRules() bool`

HasInboundSecurityRules returns a boolean if a field has been set.

### GetPolicy

`func (o *ManaV2B2bExtranetPolicyResponse) GetPolicy() ManaV2B2bExtranetProducerPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *ManaV2B2bExtranetPolicyResponse) GetPolicyOk() (*ManaV2B2bExtranetProducerPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *ManaV2B2bExtranetPolicyResponse) SetPolicy(v ManaV2B2bExtranetProducerPolicy)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *ManaV2B2bExtranetPolicyResponse) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### GetServiceName

`func (o *ManaV2B2bExtranetPolicyResponse) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ManaV2B2bExtranetPolicyResponse) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ManaV2B2bExtranetPolicyResponse) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *ManaV2B2bExtranetPolicyResponse) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetTrafficRules

`func (o *ManaV2B2bExtranetPolicyResponse) GetTrafficRules() []ManaV2TrafficPolicyRule`

GetTrafficRules returns the TrafficRules field if non-nil, zero value otherwise.

### GetTrafficRulesOk

`func (o *ManaV2B2bExtranetPolicyResponse) GetTrafficRulesOk() (*[]ManaV2TrafficPolicyRule, bool)`

GetTrafficRulesOk returns a tuple with the TrafficRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRules

`func (o *ManaV2B2bExtranetPolicyResponse) SetTrafficRules(v []ManaV2TrafficPolicyRule)`

SetTrafficRules sets TrafficRules field to given value.

### HasTrafficRules

`func (o *ManaV2B2bExtranetPolicyResponse) HasTrafficRules() bool`

HasTrafficRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



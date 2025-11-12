# V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SecurityRules** | Pointer to [**[]ManaV2SecurityPolicyRuleRow**](ManaV2SecurityPolicyRuleRow.md) |  | [optional] 
**TrafficRules** | Pointer to [**[]ManaV2TrafficPolicyRuleRow**](ManaV2TrafficPolicyRuleRow.md) |  | [optional] 

## Methods

### NewV1ExtranetsMonitoringTrafficSecurityPolicyPostResponse

`func NewV1ExtranetsMonitoringTrafficSecurityPolicyPostResponse() *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse`

NewV1ExtranetsMonitoringTrafficSecurityPolicyPostResponse instantiates a new V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsMonitoringTrafficSecurityPolicyPostResponseWithDefaults

`func NewV1ExtranetsMonitoringTrafficSecurityPolicyPostResponseWithDefaults() *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse`

NewV1ExtranetsMonitoringTrafficSecurityPolicyPostResponseWithDefaults instantiates a new V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSecurityRules

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) GetSecurityRules() []ManaV2SecurityPolicyRuleRow`

GetSecurityRules returns the SecurityRules field if non-nil, zero value otherwise.

### GetSecurityRulesOk

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) GetSecurityRulesOk() (*[]ManaV2SecurityPolicyRuleRow, bool)`

GetSecurityRulesOk returns a tuple with the SecurityRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityRules

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) SetSecurityRules(v []ManaV2SecurityPolicyRuleRow)`

SetSecurityRules sets SecurityRules field to given value.

### HasSecurityRules

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) HasSecurityRules() bool`

HasSecurityRules returns a boolean if a field has been set.

### GetTrafficRules

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) GetTrafficRules() []ManaV2TrafficPolicyRuleRow`

GetTrafficRules returns the TrafficRules field if non-nil, zero value otherwise.

### GetTrafficRulesOk

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) GetTrafficRulesOk() (*[]ManaV2TrafficPolicyRuleRow, bool)`

GetTrafficRulesOk returns a tuple with the TrafficRules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRules

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) SetTrafficRules(v []ManaV2TrafficPolicyRuleRow)`

SetTrafficRules sets TrafficRules field to given value.

### HasTrafficRules

`func (o *V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse) HasTrafficRules() bool`

HasTrafficRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



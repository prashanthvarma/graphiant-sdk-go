# ManaV2PrometheusRuleGroupConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**IntervalSeconds** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Rules** | Pointer to [**map[string]ManaV2NullablePrometheusRuleConfig**](ManaV2NullablePrometheusRuleConfig.md) |  | [optional] 

## Methods

### NewManaV2PrometheusRuleGroupConfig

`func NewManaV2PrometheusRuleGroupConfig() *ManaV2PrometheusRuleGroupConfig`

NewManaV2PrometheusRuleGroupConfig instantiates a new ManaV2PrometheusRuleGroupConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2PrometheusRuleGroupConfigWithDefaults

`func NewManaV2PrometheusRuleGroupConfigWithDefaults() *ManaV2PrometheusRuleGroupConfig`

NewManaV2PrometheusRuleGroupConfigWithDefaults instantiates a new ManaV2PrometheusRuleGroupConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2PrometheusRuleGroupConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2PrometheusRuleGroupConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2PrometheusRuleGroupConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2PrometheusRuleGroupConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIntervalSeconds

`func (o *ManaV2PrometheusRuleGroupConfig) GetIntervalSeconds() int32`

GetIntervalSeconds returns the IntervalSeconds field if non-nil, zero value otherwise.

### GetIntervalSecondsOk

`func (o *ManaV2PrometheusRuleGroupConfig) GetIntervalSecondsOk() (*int32, bool)`

GetIntervalSecondsOk returns a tuple with the IntervalSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntervalSeconds

`func (o *ManaV2PrometheusRuleGroupConfig) SetIntervalSeconds(v int32)`

SetIntervalSeconds sets IntervalSeconds field to given value.

### HasIntervalSeconds

`func (o *ManaV2PrometheusRuleGroupConfig) HasIntervalSeconds() bool`

HasIntervalSeconds returns a boolean if a field has been set.

### GetName

`func (o *ManaV2PrometheusRuleGroupConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2PrometheusRuleGroupConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2PrometheusRuleGroupConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2PrometheusRuleGroupConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRules

`func (o *ManaV2PrometheusRuleGroupConfig) GetRules() map[string]ManaV2NullablePrometheusRuleConfig`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *ManaV2PrometheusRuleGroupConfig) GetRulesOk() (*map[string]ManaV2NullablePrometheusRuleConfig, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *ManaV2PrometheusRuleGroupConfig) SetRules(v map[string]ManaV2NullablePrometheusRuleConfig)`

SetRules sets Rules field to given value.

### HasRules

`func (o *ManaV2PrometheusRuleGroupConfig) HasRules() bool`

HasRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



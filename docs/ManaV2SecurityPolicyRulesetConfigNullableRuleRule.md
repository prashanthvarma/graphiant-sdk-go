# ManaV2SecurityPolicyRulesetConfigNullableRuleRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DownlinkBurstRate** | Pointer to [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 
**DownlinkPolicerRate** | Pointer to [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 
**Logging** | Pointer to **bool** |  | [optional] 
**Match** | Pointer to [**ManaV2ForwardingPolicyMatchConfig**](ManaV2ForwardingPolicyMatchConfig.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**UplinkBurstRate** | Pointer to [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 
**UplinkPolicerRate** | Pointer to [**ManaV2NullableMeterRates**](ManaV2NullableMeterRates.md) |  | [optional] 

## Methods

### NewManaV2SecurityPolicyRulesetConfigNullableRuleRule

`func NewManaV2SecurityPolicyRulesetConfigNullableRuleRule() *ManaV2SecurityPolicyRulesetConfigNullableRuleRule`

NewManaV2SecurityPolicyRulesetConfigNullableRuleRule instantiates a new ManaV2SecurityPolicyRulesetConfigNullableRuleRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SecurityPolicyRulesetConfigNullableRuleRuleWithDefaults

`func NewManaV2SecurityPolicyRulesetConfigNullableRuleRuleWithDefaults() *ManaV2SecurityPolicyRulesetConfigNullableRuleRule`

NewManaV2SecurityPolicyRulesetConfigNullableRuleRuleWithDefaults instantiates a new ManaV2SecurityPolicyRulesetConfigNullableRuleRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDownlinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetDownlinkBurstRate() ManaV2NullableMeterRates`

GetDownlinkBurstRate returns the DownlinkBurstRate field if non-nil, zero value otherwise.

### GetDownlinkBurstRateOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetDownlinkBurstRateOk() (*ManaV2NullableMeterRates, bool)`

GetDownlinkBurstRateOk returns a tuple with the DownlinkBurstRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownlinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetDownlinkBurstRate(v ManaV2NullableMeterRates)`

SetDownlinkBurstRate sets DownlinkBurstRate field to given value.

### HasDownlinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasDownlinkBurstRate() bool`

HasDownlinkBurstRate returns a boolean if a field has been set.

### GetDownlinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetDownlinkPolicerRate() ManaV2NullableMeterRates`

GetDownlinkPolicerRate returns the DownlinkPolicerRate field if non-nil, zero value otherwise.

### GetDownlinkPolicerRateOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetDownlinkPolicerRateOk() (*ManaV2NullableMeterRates, bool)`

GetDownlinkPolicerRateOk returns a tuple with the DownlinkPolicerRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownlinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetDownlinkPolicerRate(v ManaV2NullableMeterRates)`

SetDownlinkPolicerRate sets DownlinkPolicerRate field to given value.

### HasDownlinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasDownlinkPolicerRate() bool`

HasDownlinkPolicerRate returns a boolean if a field has been set.

### GetLogging

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetLogging() bool`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetLoggingOk() (*bool, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetLogging(v bool)`

SetLogging sets Logging field to given value.

### HasLogging

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasLogging() bool`

HasLogging returns a boolean if a field has been set.

### GetMatch

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetMatch() ManaV2ForwardingPolicyMatchConfig`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetMatchOk() (*ManaV2ForwardingPolicyMatchConfig, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetMatch(v ManaV2ForwardingPolicyMatchConfig)`

SetMatch sets Match field to given value.

### HasMatch

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasMatch() bool`

HasMatch returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

### GetUplinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetUplinkBurstRate() ManaV2NullableMeterRates`

GetUplinkBurstRate returns the UplinkBurstRate field if non-nil, zero value otherwise.

### GetUplinkBurstRateOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetUplinkBurstRateOk() (*ManaV2NullableMeterRates, bool)`

GetUplinkBurstRateOk returns a tuple with the UplinkBurstRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUplinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetUplinkBurstRate(v ManaV2NullableMeterRates)`

SetUplinkBurstRate sets UplinkBurstRate field to given value.

### HasUplinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasUplinkBurstRate() bool`

HasUplinkBurstRate returns a boolean if a field has been set.

### GetUplinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetUplinkPolicerRate() ManaV2NullableMeterRates`

GetUplinkPolicerRate returns the UplinkPolicerRate field if non-nil, zero value otherwise.

### GetUplinkPolicerRateOk

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) GetUplinkPolicerRateOk() (*ManaV2NullableMeterRates, bool)`

GetUplinkPolicerRateOk returns a tuple with the UplinkPolicerRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUplinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) SetUplinkPolicerRate(v ManaV2NullableMeterRates)`

SetUplinkPolicerRate sets UplinkPolicerRate field to given value.

### HasUplinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetConfigNullableRuleRule) HasUplinkPolicerRate() bool`

HasUplinkPolicerRate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



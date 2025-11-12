# ManaV2SecurityPolicyRulesetRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DownlinkBurstRate** | Pointer to **int32** |  | [optional] 
**DownlinkPolicerRate** | Pointer to **int32** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Index** | Pointer to **int32** |  | [optional] 
**Logging** | Pointer to **bool** |  | [optional] 
**Match** | Pointer to [**ManaV2ForwardingPolicyMatch**](ManaV2ForwardingPolicyMatch.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**UplinkBurstRate** | Pointer to **int32** |  | [optional] 
**UplinkPolicerRate** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2SecurityPolicyRulesetRule

`func NewManaV2SecurityPolicyRulesetRule() *ManaV2SecurityPolicyRulesetRule`

NewManaV2SecurityPolicyRulesetRule instantiates a new ManaV2SecurityPolicyRulesetRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SecurityPolicyRulesetRuleWithDefaults

`func NewManaV2SecurityPolicyRulesetRuleWithDefaults() *ManaV2SecurityPolicyRulesetRule`

NewManaV2SecurityPolicyRulesetRuleWithDefaults instantiates a new ManaV2SecurityPolicyRulesetRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *ManaV2SecurityPolicyRulesetRule) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ManaV2SecurityPolicyRulesetRule) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *ManaV2SecurityPolicyRulesetRule) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2SecurityPolicyRulesetRule) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2SecurityPolicyRulesetRule) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2SecurityPolicyRulesetRule) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDownlinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetRule) GetDownlinkBurstRate() int32`

GetDownlinkBurstRate returns the DownlinkBurstRate field if non-nil, zero value otherwise.

### GetDownlinkBurstRateOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetDownlinkBurstRateOk() (*int32, bool)`

GetDownlinkBurstRateOk returns a tuple with the DownlinkBurstRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownlinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetRule) SetDownlinkBurstRate(v int32)`

SetDownlinkBurstRate sets DownlinkBurstRate field to given value.

### HasDownlinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetRule) HasDownlinkBurstRate() bool`

HasDownlinkBurstRate returns a boolean if a field has been set.

### GetDownlinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetRule) GetDownlinkPolicerRate() int32`

GetDownlinkPolicerRate returns the DownlinkPolicerRate field if non-nil, zero value otherwise.

### GetDownlinkPolicerRateOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetDownlinkPolicerRateOk() (*int32, bool)`

GetDownlinkPolicerRateOk returns a tuple with the DownlinkPolicerRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownlinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetRule) SetDownlinkPolicerRate(v int32)`

SetDownlinkPolicerRate sets DownlinkPolicerRate field to given value.

### HasDownlinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetRule) HasDownlinkPolicerRate() bool`

HasDownlinkPolicerRate returns a boolean if a field has been set.

### GetId

`func (o *ManaV2SecurityPolicyRulesetRule) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2SecurityPolicyRulesetRule) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2SecurityPolicyRulesetRule) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIndex

`func (o *ManaV2SecurityPolicyRulesetRule) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *ManaV2SecurityPolicyRulesetRule) SetIndex(v int32)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *ManaV2SecurityPolicyRulesetRule) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### GetLogging

`func (o *ManaV2SecurityPolicyRulesetRule) GetLogging() bool`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetLoggingOk() (*bool, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *ManaV2SecurityPolicyRulesetRule) SetLogging(v bool)`

SetLogging sets Logging field to given value.

### HasLogging

`func (o *ManaV2SecurityPolicyRulesetRule) HasLogging() bool`

HasLogging returns a boolean if a field has been set.

### GetMatch

`func (o *ManaV2SecurityPolicyRulesetRule) GetMatch() ManaV2ForwardingPolicyMatch`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetMatchOk() (*ManaV2ForwardingPolicyMatch, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *ManaV2SecurityPolicyRulesetRule) SetMatch(v ManaV2ForwardingPolicyMatch)`

SetMatch sets Match field to given value.

### HasMatch

`func (o *ManaV2SecurityPolicyRulesetRule) HasMatch() bool`

HasMatch returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SecurityPolicyRulesetRule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SecurityPolicyRulesetRule) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SecurityPolicyRulesetRule) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2SecurityPolicyRulesetRule) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2SecurityPolicyRulesetRule) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2SecurityPolicyRulesetRule) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

### GetUplinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetRule) GetUplinkBurstRate() int32`

GetUplinkBurstRate returns the UplinkBurstRate field if non-nil, zero value otherwise.

### GetUplinkBurstRateOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetUplinkBurstRateOk() (*int32, bool)`

GetUplinkBurstRateOk returns a tuple with the UplinkBurstRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUplinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetRule) SetUplinkBurstRate(v int32)`

SetUplinkBurstRate sets UplinkBurstRate field to given value.

### HasUplinkBurstRate

`func (o *ManaV2SecurityPolicyRulesetRule) HasUplinkBurstRate() bool`

HasUplinkBurstRate returns a boolean if a field has been set.

### GetUplinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetRule) GetUplinkPolicerRate() int32`

GetUplinkPolicerRate returns the UplinkPolicerRate field if non-nil, zero value otherwise.

### GetUplinkPolicerRateOk

`func (o *ManaV2SecurityPolicyRulesetRule) GetUplinkPolicerRateOk() (*int32, bool)`

GetUplinkPolicerRateOk returns a tuple with the UplinkPolicerRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUplinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetRule) SetUplinkPolicerRate(v int32)`

SetUplinkPolicerRate sets UplinkPolicerRate field to given value.

### HasUplinkPolicerRate

`func (o *ManaV2SecurityPolicyRulesetRule) HasUplinkPolicerRate() bool`

HasUplinkPolicerRate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



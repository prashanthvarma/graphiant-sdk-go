# ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BackupCircuit** | Pointer to [**ManaV2NullableSetCircuitConfig**](ManaV2NullableSetCircuitConfig.md) |  | [optional] 
**BackupCircuitLabel** | Pointer to [**ManaV2NullableSetCircuitLabelConfig**](ManaV2NullableSetCircuitLabelConfig.md) |  | [optional] 
**Egress** | Pointer to **string** |  | [optional] 
**Logging** | Pointer to **bool** |  | [optional] 
**PrimaryCircuit** | Pointer to [**ManaV2NullableSetCircuitConfig**](ManaV2NullableSetCircuitConfig.md) |  | [optional] 
**PrimaryCircuitLabel** | Pointer to [**ManaV2NullableSetCircuitLabelConfig**](ManaV2NullableSetCircuitLabelConfig.md) |  | [optional] 
**Remark** | Pointer to [**ManaV2NullableSetDscpConfig**](ManaV2NullableSetDscpConfig.md) |  | [optional] 
**SetSlaClass** | Pointer to [**ManaV2NullableSetSlaClassConfig**](ManaV2NullableSetSlaClassConfig.md) |  | [optional] 

## Methods

### NewManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction

`func NewManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction() *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction`

NewManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction instantiates a new ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2TrafficPolicyRulesetConfigNullableRuleRuleActionWithDefaults

`func NewManaV2TrafficPolicyRulesetConfigNullableRuleRuleActionWithDefaults() *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction`

NewManaV2TrafficPolicyRulesetConfigNullableRuleRuleActionWithDefaults instantiates a new ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackupCircuit

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetBackupCircuit() ManaV2NullableSetCircuitConfig`

GetBackupCircuit returns the BackupCircuit field if non-nil, zero value otherwise.

### GetBackupCircuitOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetBackupCircuitOk() (*ManaV2NullableSetCircuitConfig, bool)`

GetBackupCircuitOk returns a tuple with the BackupCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCircuit

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetBackupCircuit(v ManaV2NullableSetCircuitConfig)`

SetBackupCircuit sets BackupCircuit field to given value.

### HasBackupCircuit

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasBackupCircuit() bool`

HasBackupCircuit returns a boolean if a field has been set.

### GetBackupCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetBackupCircuitLabel() ManaV2NullableSetCircuitLabelConfig`

GetBackupCircuitLabel returns the BackupCircuitLabel field if non-nil, zero value otherwise.

### GetBackupCircuitLabelOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetBackupCircuitLabelOk() (*ManaV2NullableSetCircuitLabelConfig, bool)`

GetBackupCircuitLabelOk returns a tuple with the BackupCircuitLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetBackupCircuitLabel(v ManaV2NullableSetCircuitLabelConfig)`

SetBackupCircuitLabel sets BackupCircuitLabel field to given value.

### HasBackupCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasBackupCircuitLabel() bool`

HasBackupCircuitLabel returns a boolean if a field has been set.

### GetEgress

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetEgress() string`

GetEgress returns the Egress field if non-nil, zero value otherwise.

### GetEgressOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetEgressOk() (*string, bool)`

GetEgressOk returns a tuple with the Egress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEgress

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetEgress(v string)`

SetEgress sets Egress field to given value.

### HasEgress

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasEgress() bool`

HasEgress returns a boolean if a field has been set.

### GetLogging

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetLogging() bool`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetLoggingOk() (*bool, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetLogging(v bool)`

SetLogging sets Logging field to given value.

### HasLogging

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasLogging() bool`

HasLogging returns a boolean if a field has been set.

### GetPrimaryCircuit

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetPrimaryCircuit() ManaV2NullableSetCircuitConfig`

GetPrimaryCircuit returns the PrimaryCircuit field if non-nil, zero value otherwise.

### GetPrimaryCircuitOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetPrimaryCircuitOk() (*ManaV2NullableSetCircuitConfig, bool)`

GetPrimaryCircuitOk returns a tuple with the PrimaryCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryCircuit

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetPrimaryCircuit(v ManaV2NullableSetCircuitConfig)`

SetPrimaryCircuit sets PrimaryCircuit field to given value.

### HasPrimaryCircuit

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasPrimaryCircuit() bool`

HasPrimaryCircuit returns a boolean if a field has been set.

### GetPrimaryCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetPrimaryCircuitLabel() ManaV2NullableSetCircuitLabelConfig`

GetPrimaryCircuitLabel returns the PrimaryCircuitLabel field if non-nil, zero value otherwise.

### GetPrimaryCircuitLabelOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetPrimaryCircuitLabelOk() (*ManaV2NullableSetCircuitLabelConfig, bool)`

GetPrimaryCircuitLabelOk returns a tuple with the PrimaryCircuitLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetPrimaryCircuitLabel(v ManaV2NullableSetCircuitLabelConfig)`

SetPrimaryCircuitLabel sets PrimaryCircuitLabel field to given value.

### HasPrimaryCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasPrimaryCircuitLabel() bool`

HasPrimaryCircuitLabel returns a boolean if a field has been set.

### GetRemark

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetRemark() ManaV2NullableSetDscpConfig`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetRemarkOk() (*ManaV2NullableSetDscpConfig, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetRemark(v ManaV2NullableSetDscpConfig)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### GetSetSlaClass

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetSetSlaClass() ManaV2NullableSetSlaClassConfig`

GetSetSlaClass returns the SetSlaClass field if non-nil, zero value otherwise.

### GetSetSlaClassOk

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) GetSetSlaClassOk() (*ManaV2NullableSetSlaClassConfig, bool)`

GetSetSlaClassOk returns a tuple with the SetSlaClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetSlaClass

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) SetSetSlaClass(v ManaV2NullableSetSlaClassConfig)`

SetSetSlaClass sets SetSlaClass field to given value.

### HasSetSlaClass

`func (o *ManaV2TrafficPolicyRulesetConfigNullableRuleRuleAction) HasSetSlaClass() bool`

HasSetSlaClass returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



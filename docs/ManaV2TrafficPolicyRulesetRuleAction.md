# ManaV2TrafficPolicyRulesetRuleAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BackupCircuit** | Pointer to **string** |  | [optional] 
**BackupCircuitLabel** | Pointer to **string** |  | [optional] 
**Egress** | Pointer to **string** |  | [optional] 
**Logging** | Pointer to **bool** |  | [optional] 
**PrimaryCircuit** | Pointer to **string** |  | [optional] 
**PrimaryCircuitLabel** | Pointer to **string** |  | [optional] 
**Remark** | Pointer to [**ManaV2Dscp**](ManaV2Dscp.md) |  | [optional] 
**SlaClass** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2TrafficPolicyRulesetRuleAction

`func NewManaV2TrafficPolicyRulesetRuleAction() *ManaV2TrafficPolicyRulesetRuleAction`

NewManaV2TrafficPolicyRulesetRuleAction instantiates a new ManaV2TrafficPolicyRulesetRuleAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2TrafficPolicyRulesetRuleActionWithDefaults

`func NewManaV2TrafficPolicyRulesetRuleActionWithDefaults() *ManaV2TrafficPolicyRulesetRuleAction`

NewManaV2TrafficPolicyRulesetRuleActionWithDefaults instantiates a new ManaV2TrafficPolicyRulesetRuleAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackupCircuit

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetBackupCircuit() string`

GetBackupCircuit returns the BackupCircuit field if non-nil, zero value otherwise.

### GetBackupCircuitOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetBackupCircuitOk() (*string, bool)`

GetBackupCircuitOk returns a tuple with the BackupCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCircuit

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetBackupCircuit(v string)`

SetBackupCircuit sets BackupCircuit field to given value.

### HasBackupCircuit

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasBackupCircuit() bool`

HasBackupCircuit returns a boolean if a field has been set.

### GetBackupCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetBackupCircuitLabel() string`

GetBackupCircuitLabel returns the BackupCircuitLabel field if non-nil, zero value otherwise.

### GetBackupCircuitLabelOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetBackupCircuitLabelOk() (*string, bool)`

GetBackupCircuitLabelOk returns a tuple with the BackupCircuitLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetBackupCircuitLabel(v string)`

SetBackupCircuitLabel sets BackupCircuitLabel field to given value.

### HasBackupCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasBackupCircuitLabel() bool`

HasBackupCircuitLabel returns a boolean if a field has been set.

### GetEgress

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetEgress() string`

GetEgress returns the Egress field if non-nil, zero value otherwise.

### GetEgressOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetEgressOk() (*string, bool)`

GetEgressOk returns a tuple with the Egress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEgress

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetEgress(v string)`

SetEgress sets Egress field to given value.

### HasEgress

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasEgress() bool`

HasEgress returns a boolean if a field has been set.

### GetLogging

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetLogging() bool`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetLoggingOk() (*bool, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetLogging(v bool)`

SetLogging sets Logging field to given value.

### HasLogging

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasLogging() bool`

HasLogging returns a boolean if a field has been set.

### GetPrimaryCircuit

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetPrimaryCircuit() string`

GetPrimaryCircuit returns the PrimaryCircuit field if non-nil, zero value otherwise.

### GetPrimaryCircuitOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetPrimaryCircuitOk() (*string, bool)`

GetPrimaryCircuitOk returns a tuple with the PrimaryCircuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryCircuit

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetPrimaryCircuit(v string)`

SetPrimaryCircuit sets PrimaryCircuit field to given value.

### HasPrimaryCircuit

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasPrimaryCircuit() bool`

HasPrimaryCircuit returns a boolean if a field has been set.

### GetPrimaryCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetPrimaryCircuitLabel() string`

GetPrimaryCircuitLabel returns the PrimaryCircuitLabel field if non-nil, zero value otherwise.

### GetPrimaryCircuitLabelOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetPrimaryCircuitLabelOk() (*string, bool)`

GetPrimaryCircuitLabelOk returns a tuple with the PrimaryCircuitLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetPrimaryCircuitLabel(v string)`

SetPrimaryCircuitLabel sets PrimaryCircuitLabel field to given value.

### HasPrimaryCircuitLabel

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasPrimaryCircuitLabel() bool`

HasPrimaryCircuitLabel returns a boolean if a field has been set.

### GetRemark

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetRemark() ManaV2Dscp`

GetRemark returns the Remark field if non-nil, zero value otherwise.

### GetRemarkOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetRemarkOk() (*ManaV2Dscp, bool)`

GetRemarkOk returns a tuple with the Remark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemark

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetRemark(v ManaV2Dscp)`

SetRemark sets Remark field to given value.

### HasRemark

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasRemark() bool`

HasRemark returns a boolean if a field has been set.

### GetSlaClass

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetSlaClass() string`

GetSlaClass returns the SlaClass field if non-nil, zero value otherwise.

### GetSlaClassOk

`func (o *ManaV2TrafficPolicyRulesetRuleAction) GetSlaClassOk() (*string, bool)`

GetSlaClassOk returns a tuple with the SlaClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlaClass

`func (o *ManaV2TrafficPolicyRulesetRuleAction) SetSlaClass(v string)`

SetSlaClass sets SlaClass field to given value.

### HasSlaClass

`func (o *ManaV2TrafficPolicyRulesetRuleAction) HasSlaClass() bool`

HasSlaClass returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



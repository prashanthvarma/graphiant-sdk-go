# ManaV2PrometheusConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RuleGroups** | Pointer to [**map[string]ManaV2NullablePrometheusRuleGroupConfig**](ManaV2NullablePrometheusRuleGroupConfig.md) |  | [optional] 
**Sink** | Pointer to [**ManaV2NullablePrometheusRemoteWriteSinkConfig**](ManaV2NullablePrometheusRemoteWriteSinkConfig.md) |  | [optional] 
**SysdbMonitors** | Pointer to [**map[string]ManaV2NullablePrometheusSysDbMonitorConfig**](ManaV2NullablePrometheusSysDbMonitorConfig.md) |  | [optional] 

## Methods

### NewManaV2PrometheusConfig

`func NewManaV2PrometheusConfig() *ManaV2PrometheusConfig`

NewManaV2PrometheusConfig instantiates a new ManaV2PrometheusConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2PrometheusConfigWithDefaults

`func NewManaV2PrometheusConfigWithDefaults() *ManaV2PrometheusConfig`

NewManaV2PrometheusConfigWithDefaults instantiates a new ManaV2PrometheusConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRuleGroups

`func (o *ManaV2PrometheusConfig) GetRuleGroups() map[string]ManaV2NullablePrometheusRuleGroupConfig`

GetRuleGroups returns the RuleGroups field if non-nil, zero value otherwise.

### GetRuleGroupsOk

`func (o *ManaV2PrometheusConfig) GetRuleGroupsOk() (*map[string]ManaV2NullablePrometheusRuleGroupConfig, bool)`

GetRuleGroupsOk returns a tuple with the RuleGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleGroups

`func (o *ManaV2PrometheusConfig) SetRuleGroups(v map[string]ManaV2NullablePrometheusRuleGroupConfig)`

SetRuleGroups sets RuleGroups field to given value.

### HasRuleGroups

`func (o *ManaV2PrometheusConfig) HasRuleGroups() bool`

HasRuleGroups returns a boolean if a field has been set.

### GetSink

`func (o *ManaV2PrometheusConfig) GetSink() ManaV2NullablePrometheusRemoteWriteSinkConfig`

GetSink returns the Sink field if non-nil, zero value otherwise.

### GetSinkOk

`func (o *ManaV2PrometheusConfig) GetSinkOk() (*ManaV2NullablePrometheusRemoteWriteSinkConfig, bool)`

GetSinkOk returns a tuple with the Sink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSink

`func (o *ManaV2PrometheusConfig) SetSink(v ManaV2NullablePrometheusRemoteWriteSinkConfig)`

SetSink sets Sink field to given value.

### HasSink

`func (o *ManaV2PrometheusConfig) HasSink() bool`

HasSink returns a boolean if a field has been set.

### GetSysdbMonitors

`func (o *ManaV2PrometheusConfig) GetSysdbMonitors() map[string]ManaV2NullablePrometheusSysDbMonitorConfig`

GetSysdbMonitors returns the SysdbMonitors field if non-nil, zero value otherwise.

### GetSysdbMonitorsOk

`func (o *ManaV2PrometheusConfig) GetSysdbMonitorsOk() (*map[string]ManaV2NullablePrometheusSysDbMonitorConfig, bool)`

GetSysdbMonitorsOk returns a tuple with the SysdbMonitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSysdbMonitors

`func (o *ManaV2PrometheusConfig) SetSysdbMonitors(v map[string]ManaV2NullablePrometheusSysDbMonitorConfig)`

SetSysdbMonitors sets SysdbMonitors field to given value.

### HasSysdbMonitors

`func (o *ManaV2PrometheusConfig) HasSysdbMonitors() bool`

HasSysdbMonitors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



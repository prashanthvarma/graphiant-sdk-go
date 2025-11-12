# StatsmonV2CircuitSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AverageDelay** | Pointer to **float32** | Average delay for this circuit in this time duration | [optional] 
**AverageJitter** | Pointer to **float32** | Average jitter for this circuit in this time duration | [optional] 
**AverageLinkDownSpeedKbps** | Pointer to **float32** |  | [optional] 
**AverageLinkUpSpeedKbps** | Pointer to **float32** |  | [optional] 
**AverageLoss** | Pointer to **float32** | Average loss for this circuit in this time duration | [optional] 
**AvgMos** | Pointer to **float32** | Graphiant avg score/QoE based on mos for the time duration | [optional] 
**CircuitName** | Pointer to **string** |  | [optional] 
**ConfigLinkDownSpeedMbps** | Pointer to **int32** |  | [optional] 
**ConfigLinkUpSpeedMbps** | Pointer to **int32** |  | [optional] 
**ConnectionStatus** | Pointer to **string** |  | [optional] 
**CurrentLinkDownSpeedKbps** | Pointer to **float32** |  | [optional] 
**CurrentLinkUpSpeedKbps** | Pointer to **float32** |  | [optional] 
**Delay** | Pointer to **int64** | Delay in nano seconds | [optional] 
**Jitter** | Pointer to **int64** | Jitter in nano seconds | [optional] 
**LastResort** | Pointer to **bool** |  | [optional] 
**Loss** | Pointer to **float32** | Loss in percentage | [optional] 
**MaxDelay** | Pointer to **float32** | Max delay for this circuit in this time duration | [optional] 
**MaxJitter** | Pointer to **float32** | Max jitter for this circuit in this time duration | [optional] 
**MaxLoss** | Pointer to **float32** | Max loss for this circuit in this time duration | [optional] 
**MaxMos** | Pointer to **float32** | Graphiant max score/QoE based on mos for the time duration | [optional] 
**MinDelay** | Pointer to **float32** | Min delay for this circuit in this time duration | [optional] 
**MinJitter** | Pointer to **float32** | Min jitter for this circuit in this time duration | [optional] 
**MinLoss** | Pointer to **float32** | Min loss for this circuit in this time duration | [optional] 
**MinMos** | Pointer to **float32** | Graphiant min score/QoE based on mos for the time duration | [optional] 
**Mos** | Pointer to **float32** | Graphiant score/QoE based on mos | [optional] 

## Methods

### NewStatsmonV2CircuitSummary

`func NewStatsmonV2CircuitSummary() *StatsmonV2CircuitSummary`

NewStatsmonV2CircuitSummary instantiates a new StatsmonV2CircuitSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2CircuitSummaryWithDefaults

`func NewStatsmonV2CircuitSummaryWithDefaults() *StatsmonV2CircuitSummary`

NewStatsmonV2CircuitSummaryWithDefaults instantiates a new StatsmonV2CircuitSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAverageDelay

`func (o *StatsmonV2CircuitSummary) GetAverageDelay() float32`

GetAverageDelay returns the AverageDelay field if non-nil, zero value otherwise.

### GetAverageDelayOk

`func (o *StatsmonV2CircuitSummary) GetAverageDelayOk() (*float32, bool)`

GetAverageDelayOk returns a tuple with the AverageDelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageDelay

`func (o *StatsmonV2CircuitSummary) SetAverageDelay(v float32)`

SetAverageDelay sets AverageDelay field to given value.

### HasAverageDelay

`func (o *StatsmonV2CircuitSummary) HasAverageDelay() bool`

HasAverageDelay returns a boolean if a field has been set.

### GetAverageJitter

`func (o *StatsmonV2CircuitSummary) GetAverageJitter() float32`

GetAverageJitter returns the AverageJitter field if non-nil, zero value otherwise.

### GetAverageJitterOk

`func (o *StatsmonV2CircuitSummary) GetAverageJitterOk() (*float32, bool)`

GetAverageJitterOk returns a tuple with the AverageJitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageJitter

`func (o *StatsmonV2CircuitSummary) SetAverageJitter(v float32)`

SetAverageJitter sets AverageJitter field to given value.

### HasAverageJitter

`func (o *StatsmonV2CircuitSummary) HasAverageJitter() bool`

HasAverageJitter returns a boolean if a field has been set.

### GetAverageLinkDownSpeedKbps

`func (o *StatsmonV2CircuitSummary) GetAverageLinkDownSpeedKbps() float32`

GetAverageLinkDownSpeedKbps returns the AverageLinkDownSpeedKbps field if non-nil, zero value otherwise.

### GetAverageLinkDownSpeedKbpsOk

`func (o *StatsmonV2CircuitSummary) GetAverageLinkDownSpeedKbpsOk() (*float32, bool)`

GetAverageLinkDownSpeedKbpsOk returns a tuple with the AverageLinkDownSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageLinkDownSpeedKbps

`func (o *StatsmonV2CircuitSummary) SetAverageLinkDownSpeedKbps(v float32)`

SetAverageLinkDownSpeedKbps sets AverageLinkDownSpeedKbps field to given value.

### HasAverageLinkDownSpeedKbps

`func (o *StatsmonV2CircuitSummary) HasAverageLinkDownSpeedKbps() bool`

HasAverageLinkDownSpeedKbps returns a boolean if a field has been set.

### GetAverageLinkUpSpeedKbps

`func (o *StatsmonV2CircuitSummary) GetAverageLinkUpSpeedKbps() float32`

GetAverageLinkUpSpeedKbps returns the AverageLinkUpSpeedKbps field if non-nil, zero value otherwise.

### GetAverageLinkUpSpeedKbpsOk

`func (o *StatsmonV2CircuitSummary) GetAverageLinkUpSpeedKbpsOk() (*float32, bool)`

GetAverageLinkUpSpeedKbpsOk returns a tuple with the AverageLinkUpSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageLinkUpSpeedKbps

`func (o *StatsmonV2CircuitSummary) SetAverageLinkUpSpeedKbps(v float32)`

SetAverageLinkUpSpeedKbps sets AverageLinkUpSpeedKbps field to given value.

### HasAverageLinkUpSpeedKbps

`func (o *StatsmonV2CircuitSummary) HasAverageLinkUpSpeedKbps() bool`

HasAverageLinkUpSpeedKbps returns a boolean if a field has been set.

### GetAverageLoss

`func (o *StatsmonV2CircuitSummary) GetAverageLoss() float32`

GetAverageLoss returns the AverageLoss field if non-nil, zero value otherwise.

### GetAverageLossOk

`func (o *StatsmonV2CircuitSummary) GetAverageLossOk() (*float32, bool)`

GetAverageLossOk returns a tuple with the AverageLoss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageLoss

`func (o *StatsmonV2CircuitSummary) SetAverageLoss(v float32)`

SetAverageLoss sets AverageLoss field to given value.

### HasAverageLoss

`func (o *StatsmonV2CircuitSummary) HasAverageLoss() bool`

HasAverageLoss returns a boolean if a field has been set.

### GetAvgMos

`func (o *StatsmonV2CircuitSummary) GetAvgMos() float32`

GetAvgMos returns the AvgMos field if non-nil, zero value otherwise.

### GetAvgMosOk

`func (o *StatsmonV2CircuitSummary) GetAvgMosOk() (*float32, bool)`

GetAvgMosOk returns a tuple with the AvgMos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgMos

`func (o *StatsmonV2CircuitSummary) SetAvgMos(v float32)`

SetAvgMos sets AvgMos field to given value.

### HasAvgMos

`func (o *StatsmonV2CircuitSummary) HasAvgMos() bool`

HasAvgMos returns a boolean if a field has been set.

### GetCircuitName

`func (o *StatsmonV2CircuitSummary) GetCircuitName() string`

GetCircuitName returns the CircuitName field if non-nil, zero value otherwise.

### GetCircuitNameOk

`func (o *StatsmonV2CircuitSummary) GetCircuitNameOk() (*string, bool)`

GetCircuitNameOk returns a tuple with the CircuitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitName

`func (o *StatsmonV2CircuitSummary) SetCircuitName(v string)`

SetCircuitName sets CircuitName field to given value.

### HasCircuitName

`func (o *StatsmonV2CircuitSummary) HasCircuitName() bool`

HasCircuitName returns a boolean if a field has been set.

### GetConfigLinkDownSpeedMbps

`func (o *StatsmonV2CircuitSummary) GetConfigLinkDownSpeedMbps() int32`

GetConfigLinkDownSpeedMbps returns the ConfigLinkDownSpeedMbps field if non-nil, zero value otherwise.

### GetConfigLinkDownSpeedMbpsOk

`func (o *StatsmonV2CircuitSummary) GetConfigLinkDownSpeedMbpsOk() (*int32, bool)`

GetConfigLinkDownSpeedMbpsOk returns a tuple with the ConfigLinkDownSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigLinkDownSpeedMbps

`func (o *StatsmonV2CircuitSummary) SetConfigLinkDownSpeedMbps(v int32)`

SetConfigLinkDownSpeedMbps sets ConfigLinkDownSpeedMbps field to given value.

### HasConfigLinkDownSpeedMbps

`func (o *StatsmonV2CircuitSummary) HasConfigLinkDownSpeedMbps() bool`

HasConfigLinkDownSpeedMbps returns a boolean if a field has been set.

### GetConfigLinkUpSpeedMbps

`func (o *StatsmonV2CircuitSummary) GetConfigLinkUpSpeedMbps() int32`

GetConfigLinkUpSpeedMbps returns the ConfigLinkUpSpeedMbps field if non-nil, zero value otherwise.

### GetConfigLinkUpSpeedMbpsOk

`func (o *StatsmonV2CircuitSummary) GetConfigLinkUpSpeedMbpsOk() (*int32, bool)`

GetConfigLinkUpSpeedMbpsOk returns a tuple with the ConfigLinkUpSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigLinkUpSpeedMbps

`func (o *StatsmonV2CircuitSummary) SetConfigLinkUpSpeedMbps(v int32)`

SetConfigLinkUpSpeedMbps sets ConfigLinkUpSpeedMbps field to given value.

### HasConfigLinkUpSpeedMbps

`func (o *StatsmonV2CircuitSummary) HasConfigLinkUpSpeedMbps() bool`

HasConfigLinkUpSpeedMbps returns a boolean if a field has been set.

### GetConnectionStatus

`func (o *StatsmonV2CircuitSummary) GetConnectionStatus() string`

GetConnectionStatus returns the ConnectionStatus field if non-nil, zero value otherwise.

### GetConnectionStatusOk

`func (o *StatsmonV2CircuitSummary) GetConnectionStatusOk() (*string, bool)`

GetConnectionStatusOk returns a tuple with the ConnectionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionStatus

`func (o *StatsmonV2CircuitSummary) SetConnectionStatus(v string)`

SetConnectionStatus sets ConnectionStatus field to given value.

### HasConnectionStatus

`func (o *StatsmonV2CircuitSummary) HasConnectionStatus() bool`

HasConnectionStatus returns a boolean if a field has been set.

### GetCurrentLinkDownSpeedKbps

`func (o *StatsmonV2CircuitSummary) GetCurrentLinkDownSpeedKbps() float32`

GetCurrentLinkDownSpeedKbps returns the CurrentLinkDownSpeedKbps field if non-nil, zero value otherwise.

### GetCurrentLinkDownSpeedKbpsOk

`func (o *StatsmonV2CircuitSummary) GetCurrentLinkDownSpeedKbpsOk() (*float32, bool)`

GetCurrentLinkDownSpeedKbpsOk returns a tuple with the CurrentLinkDownSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentLinkDownSpeedKbps

`func (o *StatsmonV2CircuitSummary) SetCurrentLinkDownSpeedKbps(v float32)`

SetCurrentLinkDownSpeedKbps sets CurrentLinkDownSpeedKbps field to given value.

### HasCurrentLinkDownSpeedKbps

`func (o *StatsmonV2CircuitSummary) HasCurrentLinkDownSpeedKbps() bool`

HasCurrentLinkDownSpeedKbps returns a boolean if a field has been set.

### GetCurrentLinkUpSpeedKbps

`func (o *StatsmonV2CircuitSummary) GetCurrentLinkUpSpeedKbps() float32`

GetCurrentLinkUpSpeedKbps returns the CurrentLinkUpSpeedKbps field if non-nil, zero value otherwise.

### GetCurrentLinkUpSpeedKbpsOk

`func (o *StatsmonV2CircuitSummary) GetCurrentLinkUpSpeedKbpsOk() (*float32, bool)`

GetCurrentLinkUpSpeedKbpsOk returns a tuple with the CurrentLinkUpSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentLinkUpSpeedKbps

`func (o *StatsmonV2CircuitSummary) SetCurrentLinkUpSpeedKbps(v float32)`

SetCurrentLinkUpSpeedKbps sets CurrentLinkUpSpeedKbps field to given value.

### HasCurrentLinkUpSpeedKbps

`func (o *StatsmonV2CircuitSummary) HasCurrentLinkUpSpeedKbps() bool`

HasCurrentLinkUpSpeedKbps returns a boolean if a field has been set.

### GetDelay

`func (o *StatsmonV2CircuitSummary) GetDelay() int64`

GetDelay returns the Delay field if non-nil, zero value otherwise.

### GetDelayOk

`func (o *StatsmonV2CircuitSummary) GetDelayOk() (*int64, bool)`

GetDelayOk returns a tuple with the Delay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelay

`func (o *StatsmonV2CircuitSummary) SetDelay(v int64)`

SetDelay sets Delay field to given value.

### HasDelay

`func (o *StatsmonV2CircuitSummary) HasDelay() bool`

HasDelay returns a boolean if a field has been set.

### GetJitter

`func (o *StatsmonV2CircuitSummary) GetJitter() int64`

GetJitter returns the Jitter field if non-nil, zero value otherwise.

### GetJitterOk

`func (o *StatsmonV2CircuitSummary) GetJitterOk() (*int64, bool)`

GetJitterOk returns a tuple with the Jitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitter

`func (o *StatsmonV2CircuitSummary) SetJitter(v int64)`

SetJitter sets Jitter field to given value.

### HasJitter

`func (o *StatsmonV2CircuitSummary) HasJitter() bool`

HasJitter returns a boolean if a field has been set.

### GetLastResort

`func (o *StatsmonV2CircuitSummary) GetLastResort() bool`

GetLastResort returns the LastResort field if non-nil, zero value otherwise.

### GetLastResortOk

`func (o *StatsmonV2CircuitSummary) GetLastResortOk() (*bool, bool)`

GetLastResortOk returns a tuple with the LastResort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastResort

`func (o *StatsmonV2CircuitSummary) SetLastResort(v bool)`

SetLastResort sets LastResort field to given value.

### HasLastResort

`func (o *StatsmonV2CircuitSummary) HasLastResort() bool`

HasLastResort returns a boolean if a field has been set.

### GetLoss

`func (o *StatsmonV2CircuitSummary) GetLoss() float32`

GetLoss returns the Loss field if non-nil, zero value otherwise.

### GetLossOk

`func (o *StatsmonV2CircuitSummary) GetLossOk() (*float32, bool)`

GetLossOk returns a tuple with the Loss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoss

`func (o *StatsmonV2CircuitSummary) SetLoss(v float32)`

SetLoss sets Loss field to given value.

### HasLoss

`func (o *StatsmonV2CircuitSummary) HasLoss() bool`

HasLoss returns a boolean if a field has been set.

### GetMaxDelay

`func (o *StatsmonV2CircuitSummary) GetMaxDelay() float32`

GetMaxDelay returns the MaxDelay field if non-nil, zero value otherwise.

### GetMaxDelayOk

`func (o *StatsmonV2CircuitSummary) GetMaxDelayOk() (*float32, bool)`

GetMaxDelayOk returns a tuple with the MaxDelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDelay

`func (o *StatsmonV2CircuitSummary) SetMaxDelay(v float32)`

SetMaxDelay sets MaxDelay field to given value.

### HasMaxDelay

`func (o *StatsmonV2CircuitSummary) HasMaxDelay() bool`

HasMaxDelay returns a boolean if a field has been set.

### GetMaxJitter

`func (o *StatsmonV2CircuitSummary) GetMaxJitter() float32`

GetMaxJitter returns the MaxJitter field if non-nil, zero value otherwise.

### GetMaxJitterOk

`func (o *StatsmonV2CircuitSummary) GetMaxJitterOk() (*float32, bool)`

GetMaxJitterOk returns a tuple with the MaxJitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxJitter

`func (o *StatsmonV2CircuitSummary) SetMaxJitter(v float32)`

SetMaxJitter sets MaxJitter field to given value.

### HasMaxJitter

`func (o *StatsmonV2CircuitSummary) HasMaxJitter() bool`

HasMaxJitter returns a boolean if a field has been set.

### GetMaxLoss

`func (o *StatsmonV2CircuitSummary) GetMaxLoss() float32`

GetMaxLoss returns the MaxLoss field if non-nil, zero value otherwise.

### GetMaxLossOk

`func (o *StatsmonV2CircuitSummary) GetMaxLossOk() (*float32, bool)`

GetMaxLossOk returns a tuple with the MaxLoss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLoss

`func (o *StatsmonV2CircuitSummary) SetMaxLoss(v float32)`

SetMaxLoss sets MaxLoss field to given value.

### HasMaxLoss

`func (o *StatsmonV2CircuitSummary) HasMaxLoss() bool`

HasMaxLoss returns a boolean if a field has been set.

### GetMaxMos

`func (o *StatsmonV2CircuitSummary) GetMaxMos() float32`

GetMaxMos returns the MaxMos field if non-nil, zero value otherwise.

### GetMaxMosOk

`func (o *StatsmonV2CircuitSummary) GetMaxMosOk() (*float32, bool)`

GetMaxMosOk returns a tuple with the MaxMos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxMos

`func (o *StatsmonV2CircuitSummary) SetMaxMos(v float32)`

SetMaxMos sets MaxMos field to given value.

### HasMaxMos

`func (o *StatsmonV2CircuitSummary) HasMaxMos() bool`

HasMaxMos returns a boolean if a field has been set.

### GetMinDelay

`func (o *StatsmonV2CircuitSummary) GetMinDelay() float32`

GetMinDelay returns the MinDelay field if non-nil, zero value otherwise.

### GetMinDelayOk

`func (o *StatsmonV2CircuitSummary) GetMinDelayOk() (*float32, bool)`

GetMinDelayOk returns a tuple with the MinDelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinDelay

`func (o *StatsmonV2CircuitSummary) SetMinDelay(v float32)`

SetMinDelay sets MinDelay field to given value.

### HasMinDelay

`func (o *StatsmonV2CircuitSummary) HasMinDelay() bool`

HasMinDelay returns a boolean if a field has been set.

### GetMinJitter

`func (o *StatsmonV2CircuitSummary) GetMinJitter() float32`

GetMinJitter returns the MinJitter field if non-nil, zero value otherwise.

### GetMinJitterOk

`func (o *StatsmonV2CircuitSummary) GetMinJitterOk() (*float32, bool)`

GetMinJitterOk returns a tuple with the MinJitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinJitter

`func (o *StatsmonV2CircuitSummary) SetMinJitter(v float32)`

SetMinJitter sets MinJitter field to given value.

### HasMinJitter

`func (o *StatsmonV2CircuitSummary) HasMinJitter() bool`

HasMinJitter returns a boolean if a field has been set.

### GetMinLoss

`func (o *StatsmonV2CircuitSummary) GetMinLoss() float32`

GetMinLoss returns the MinLoss field if non-nil, zero value otherwise.

### GetMinLossOk

`func (o *StatsmonV2CircuitSummary) GetMinLossOk() (*float32, bool)`

GetMinLossOk returns a tuple with the MinLoss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLoss

`func (o *StatsmonV2CircuitSummary) SetMinLoss(v float32)`

SetMinLoss sets MinLoss field to given value.

### HasMinLoss

`func (o *StatsmonV2CircuitSummary) HasMinLoss() bool`

HasMinLoss returns a boolean if a field has been set.

### GetMinMos

`func (o *StatsmonV2CircuitSummary) GetMinMos() float32`

GetMinMos returns the MinMos field if non-nil, zero value otherwise.

### GetMinMosOk

`func (o *StatsmonV2CircuitSummary) GetMinMosOk() (*float32, bool)`

GetMinMosOk returns a tuple with the MinMos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinMos

`func (o *StatsmonV2CircuitSummary) SetMinMos(v float32)`

SetMinMos sets MinMos field to given value.

### HasMinMos

`func (o *StatsmonV2CircuitSummary) HasMinMos() bool`

HasMinMos returns a boolean if a field has been set.

### GetMos

`func (o *StatsmonV2CircuitSummary) GetMos() float32`

GetMos returns the Mos field if non-nil, zero value otherwise.

### GetMosOk

`func (o *StatsmonV2CircuitSummary) GetMosOk() (*float32, bool)`

GetMosOk returns a tuple with the Mos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMos

`func (o *StatsmonV2CircuitSummary) SetMos(v float32)`

SetMos sets Mos field to given value.

### HasMos

`func (o *StatsmonV2CircuitSummary) HasMos() bool`

HasMos returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



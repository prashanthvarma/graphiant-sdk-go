# StatsmonCircuitSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminStatus** | Pointer to **bool** |  | [optional] 
**AverageLinkDownSpeedKbps** | Pointer to **float32** |  | [optional] 
**AverageLinkUpSpeedKbps** | Pointer to **float32** |  | [optional] 
**AvgMos** | Pointer to **float32** | Graphiant avg score/QoE based on mos for the time duration | [optional] 
**ConfigLinkDownSpeedMbps** | Pointer to **int32** |  | [optional] 
**ConfigLinkUpSpeedMbps** | Pointer to **int32** |  | [optional] 
**ConnectionStatus** | Pointer to **string** |  | [optional] 
**CurrentLinkDownSpeedKbps** | Pointer to **float32** |  | [optional] 
**CurrentLinkUpSpeedKbps** | Pointer to **float32** |  | [optional] 
**Delay** | Pointer to **int64** | Delay in nano seconds | [optional] 
**Jitter** | Pointer to **int64** | Jitter in nano seconds | [optional] 
**Loss** | Pointer to **float32** | Loss in percentage | [optional] 
**Mos** | Pointer to **float32** | Graphiant score/QoE based on mos | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonCircuitSummary

`func NewStatsmonCircuitSummary() *StatsmonCircuitSummary`

NewStatsmonCircuitSummary instantiates a new StatsmonCircuitSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonCircuitSummaryWithDefaults

`func NewStatsmonCircuitSummaryWithDefaults() *StatsmonCircuitSummary`

NewStatsmonCircuitSummaryWithDefaults instantiates a new StatsmonCircuitSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminStatus

`func (o *StatsmonCircuitSummary) GetAdminStatus() bool`

GetAdminStatus returns the AdminStatus field if non-nil, zero value otherwise.

### GetAdminStatusOk

`func (o *StatsmonCircuitSummary) GetAdminStatusOk() (*bool, bool)`

GetAdminStatusOk returns a tuple with the AdminStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminStatus

`func (o *StatsmonCircuitSummary) SetAdminStatus(v bool)`

SetAdminStatus sets AdminStatus field to given value.

### HasAdminStatus

`func (o *StatsmonCircuitSummary) HasAdminStatus() bool`

HasAdminStatus returns a boolean if a field has been set.

### GetAverageLinkDownSpeedKbps

`func (o *StatsmonCircuitSummary) GetAverageLinkDownSpeedKbps() float32`

GetAverageLinkDownSpeedKbps returns the AverageLinkDownSpeedKbps field if non-nil, zero value otherwise.

### GetAverageLinkDownSpeedKbpsOk

`func (o *StatsmonCircuitSummary) GetAverageLinkDownSpeedKbpsOk() (*float32, bool)`

GetAverageLinkDownSpeedKbpsOk returns a tuple with the AverageLinkDownSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageLinkDownSpeedKbps

`func (o *StatsmonCircuitSummary) SetAverageLinkDownSpeedKbps(v float32)`

SetAverageLinkDownSpeedKbps sets AverageLinkDownSpeedKbps field to given value.

### HasAverageLinkDownSpeedKbps

`func (o *StatsmonCircuitSummary) HasAverageLinkDownSpeedKbps() bool`

HasAverageLinkDownSpeedKbps returns a boolean if a field has been set.

### GetAverageLinkUpSpeedKbps

`func (o *StatsmonCircuitSummary) GetAverageLinkUpSpeedKbps() float32`

GetAverageLinkUpSpeedKbps returns the AverageLinkUpSpeedKbps field if non-nil, zero value otherwise.

### GetAverageLinkUpSpeedKbpsOk

`func (o *StatsmonCircuitSummary) GetAverageLinkUpSpeedKbpsOk() (*float32, bool)`

GetAverageLinkUpSpeedKbpsOk returns a tuple with the AverageLinkUpSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageLinkUpSpeedKbps

`func (o *StatsmonCircuitSummary) SetAverageLinkUpSpeedKbps(v float32)`

SetAverageLinkUpSpeedKbps sets AverageLinkUpSpeedKbps field to given value.

### HasAverageLinkUpSpeedKbps

`func (o *StatsmonCircuitSummary) HasAverageLinkUpSpeedKbps() bool`

HasAverageLinkUpSpeedKbps returns a boolean if a field has been set.

### GetAvgMos

`func (o *StatsmonCircuitSummary) GetAvgMos() float32`

GetAvgMos returns the AvgMos field if non-nil, zero value otherwise.

### GetAvgMosOk

`func (o *StatsmonCircuitSummary) GetAvgMosOk() (*float32, bool)`

GetAvgMosOk returns a tuple with the AvgMos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgMos

`func (o *StatsmonCircuitSummary) SetAvgMos(v float32)`

SetAvgMos sets AvgMos field to given value.

### HasAvgMos

`func (o *StatsmonCircuitSummary) HasAvgMos() bool`

HasAvgMos returns a boolean if a field has been set.

### GetConfigLinkDownSpeedMbps

`func (o *StatsmonCircuitSummary) GetConfigLinkDownSpeedMbps() int32`

GetConfigLinkDownSpeedMbps returns the ConfigLinkDownSpeedMbps field if non-nil, zero value otherwise.

### GetConfigLinkDownSpeedMbpsOk

`func (o *StatsmonCircuitSummary) GetConfigLinkDownSpeedMbpsOk() (*int32, bool)`

GetConfigLinkDownSpeedMbpsOk returns a tuple with the ConfigLinkDownSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigLinkDownSpeedMbps

`func (o *StatsmonCircuitSummary) SetConfigLinkDownSpeedMbps(v int32)`

SetConfigLinkDownSpeedMbps sets ConfigLinkDownSpeedMbps field to given value.

### HasConfigLinkDownSpeedMbps

`func (o *StatsmonCircuitSummary) HasConfigLinkDownSpeedMbps() bool`

HasConfigLinkDownSpeedMbps returns a boolean if a field has been set.

### GetConfigLinkUpSpeedMbps

`func (o *StatsmonCircuitSummary) GetConfigLinkUpSpeedMbps() int32`

GetConfigLinkUpSpeedMbps returns the ConfigLinkUpSpeedMbps field if non-nil, zero value otherwise.

### GetConfigLinkUpSpeedMbpsOk

`func (o *StatsmonCircuitSummary) GetConfigLinkUpSpeedMbpsOk() (*int32, bool)`

GetConfigLinkUpSpeedMbpsOk returns a tuple with the ConfigLinkUpSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigLinkUpSpeedMbps

`func (o *StatsmonCircuitSummary) SetConfigLinkUpSpeedMbps(v int32)`

SetConfigLinkUpSpeedMbps sets ConfigLinkUpSpeedMbps field to given value.

### HasConfigLinkUpSpeedMbps

`func (o *StatsmonCircuitSummary) HasConfigLinkUpSpeedMbps() bool`

HasConfigLinkUpSpeedMbps returns a boolean if a field has been set.

### GetConnectionStatus

`func (o *StatsmonCircuitSummary) GetConnectionStatus() string`

GetConnectionStatus returns the ConnectionStatus field if non-nil, zero value otherwise.

### GetConnectionStatusOk

`func (o *StatsmonCircuitSummary) GetConnectionStatusOk() (*string, bool)`

GetConnectionStatusOk returns a tuple with the ConnectionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionStatus

`func (o *StatsmonCircuitSummary) SetConnectionStatus(v string)`

SetConnectionStatus sets ConnectionStatus field to given value.

### HasConnectionStatus

`func (o *StatsmonCircuitSummary) HasConnectionStatus() bool`

HasConnectionStatus returns a boolean if a field has been set.

### GetCurrentLinkDownSpeedKbps

`func (o *StatsmonCircuitSummary) GetCurrentLinkDownSpeedKbps() float32`

GetCurrentLinkDownSpeedKbps returns the CurrentLinkDownSpeedKbps field if non-nil, zero value otherwise.

### GetCurrentLinkDownSpeedKbpsOk

`func (o *StatsmonCircuitSummary) GetCurrentLinkDownSpeedKbpsOk() (*float32, bool)`

GetCurrentLinkDownSpeedKbpsOk returns a tuple with the CurrentLinkDownSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentLinkDownSpeedKbps

`func (o *StatsmonCircuitSummary) SetCurrentLinkDownSpeedKbps(v float32)`

SetCurrentLinkDownSpeedKbps sets CurrentLinkDownSpeedKbps field to given value.

### HasCurrentLinkDownSpeedKbps

`func (o *StatsmonCircuitSummary) HasCurrentLinkDownSpeedKbps() bool`

HasCurrentLinkDownSpeedKbps returns a boolean if a field has been set.

### GetCurrentLinkUpSpeedKbps

`func (o *StatsmonCircuitSummary) GetCurrentLinkUpSpeedKbps() float32`

GetCurrentLinkUpSpeedKbps returns the CurrentLinkUpSpeedKbps field if non-nil, zero value otherwise.

### GetCurrentLinkUpSpeedKbpsOk

`func (o *StatsmonCircuitSummary) GetCurrentLinkUpSpeedKbpsOk() (*float32, bool)`

GetCurrentLinkUpSpeedKbpsOk returns a tuple with the CurrentLinkUpSpeedKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentLinkUpSpeedKbps

`func (o *StatsmonCircuitSummary) SetCurrentLinkUpSpeedKbps(v float32)`

SetCurrentLinkUpSpeedKbps sets CurrentLinkUpSpeedKbps field to given value.

### HasCurrentLinkUpSpeedKbps

`func (o *StatsmonCircuitSummary) HasCurrentLinkUpSpeedKbps() bool`

HasCurrentLinkUpSpeedKbps returns a boolean if a field has been set.

### GetDelay

`func (o *StatsmonCircuitSummary) GetDelay() int64`

GetDelay returns the Delay field if non-nil, zero value otherwise.

### GetDelayOk

`func (o *StatsmonCircuitSummary) GetDelayOk() (*int64, bool)`

GetDelayOk returns a tuple with the Delay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelay

`func (o *StatsmonCircuitSummary) SetDelay(v int64)`

SetDelay sets Delay field to given value.

### HasDelay

`func (o *StatsmonCircuitSummary) HasDelay() bool`

HasDelay returns a boolean if a field has been set.

### GetJitter

`func (o *StatsmonCircuitSummary) GetJitter() int64`

GetJitter returns the Jitter field if non-nil, zero value otherwise.

### GetJitterOk

`func (o *StatsmonCircuitSummary) GetJitterOk() (*int64, bool)`

GetJitterOk returns a tuple with the Jitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitter

`func (o *StatsmonCircuitSummary) SetJitter(v int64)`

SetJitter sets Jitter field to given value.

### HasJitter

`func (o *StatsmonCircuitSummary) HasJitter() bool`

HasJitter returns a boolean if a field has been set.

### GetLoss

`func (o *StatsmonCircuitSummary) GetLoss() float32`

GetLoss returns the Loss field if non-nil, zero value otherwise.

### GetLossOk

`func (o *StatsmonCircuitSummary) GetLossOk() (*float32, bool)`

GetLossOk returns a tuple with the Loss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoss

`func (o *StatsmonCircuitSummary) SetLoss(v float32)`

SetLoss sets Loss field to given value.

### HasLoss

`func (o *StatsmonCircuitSummary) HasLoss() bool`

HasLoss returns a boolean if a field has been set.

### GetMos

`func (o *StatsmonCircuitSummary) GetMos() float32`

GetMos returns the Mos field if non-nil, zero value otherwise.

### GetMosOk

`func (o *StatsmonCircuitSummary) GetMosOk() (*float32, bool)`

GetMosOk returns a tuple with the Mos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMos

`func (o *StatsmonCircuitSummary) SetMos(v float32)`

SetMos sets Mos field to given value.

### HasMos

`func (o *StatsmonCircuitSummary) HasMos() bool`

HasMos returns a boolean if a field has been set.

### GetName

`func (o *StatsmonCircuitSummary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StatsmonCircuitSummary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StatsmonCircuitSummary) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *StatsmonCircuitSummary) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



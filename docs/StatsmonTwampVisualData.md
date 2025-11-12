# StatsmonTwampVisualData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CircuitName** | Pointer to **string** |  | [optional] 
**CoreLocation** | Pointer to **string** |  | [optional] 
**EgressLatency** | Pointer to **float32** |  | [optional] 
**IngressLatency** | Pointer to **float32** |  | [optional] 
**LossPercent** | Pointer to **float32** |  | [optional] 
**ProbesRx** | Pointer to **int64** |  | [optional] 
**ProbesTx** | Pointer to **int64** |  | [optional] 
**RoundTripLatency** | Pointer to **float32** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewStatsmonTwampVisualData

`func NewStatsmonTwampVisualData() *StatsmonTwampVisualData`

NewStatsmonTwampVisualData instantiates a new StatsmonTwampVisualData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonTwampVisualDataWithDefaults

`func NewStatsmonTwampVisualDataWithDefaults() *StatsmonTwampVisualData`

NewStatsmonTwampVisualDataWithDefaults instantiates a new StatsmonTwampVisualData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuitName

`func (o *StatsmonTwampVisualData) GetCircuitName() string`

GetCircuitName returns the CircuitName field if non-nil, zero value otherwise.

### GetCircuitNameOk

`func (o *StatsmonTwampVisualData) GetCircuitNameOk() (*string, bool)`

GetCircuitNameOk returns a tuple with the CircuitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitName

`func (o *StatsmonTwampVisualData) SetCircuitName(v string)`

SetCircuitName sets CircuitName field to given value.

### HasCircuitName

`func (o *StatsmonTwampVisualData) HasCircuitName() bool`

HasCircuitName returns a boolean if a field has been set.

### GetCoreLocation

`func (o *StatsmonTwampVisualData) GetCoreLocation() string`

GetCoreLocation returns the CoreLocation field if non-nil, zero value otherwise.

### GetCoreLocationOk

`func (o *StatsmonTwampVisualData) GetCoreLocationOk() (*string, bool)`

GetCoreLocationOk returns a tuple with the CoreLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreLocation

`func (o *StatsmonTwampVisualData) SetCoreLocation(v string)`

SetCoreLocation sets CoreLocation field to given value.

### HasCoreLocation

`func (o *StatsmonTwampVisualData) HasCoreLocation() bool`

HasCoreLocation returns a boolean if a field has been set.

### GetEgressLatency

`func (o *StatsmonTwampVisualData) GetEgressLatency() float32`

GetEgressLatency returns the EgressLatency field if non-nil, zero value otherwise.

### GetEgressLatencyOk

`func (o *StatsmonTwampVisualData) GetEgressLatencyOk() (*float32, bool)`

GetEgressLatencyOk returns a tuple with the EgressLatency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEgressLatency

`func (o *StatsmonTwampVisualData) SetEgressLatency(v float32)`

SetEgressLatency sets EgressLatency field to given value.

### HasEgressLatency

`func (o *StatsmonTwampVisualData) HasEgressLatency() bool`

HasEgressLatency returns a boolean if a field has been set.

### GetIngressLatency

`func (o *StatsmonTwampVisualData) GetIngressLatency() float32`

GetIngressLatency returns the IngressLatency field if non-nil, zero value otherwise.

### GetIngressLatencyOk

`func (o *StatsmonTwampVisualData) GetIngressLatencyOk() (*float32, bool)`

GetIngressLatencyOk returns a tuple with the IngressLatency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIngressLatency

`func (o *StatsmonTwampVisualData) SetIngressLatency(v float32)`

SetIngressLatency sets IngressLatency field to given value.

### HasIngressLatency

`func (o *StatsmonTwampVisualData) HasIngressLatency() bool`

HasIngressLatency returns a boolean if a field has been set.

### GetLossPercent

`func (o *StatsmonTwampVisualData) GetLossPercent() float32`

GetLossPercent returns the LossPercent field if non-nil, zero value otherwise.

### GetLossPercentOk

`func (o *StatsmonTwampVisualData) GetLossPercentOk() (*float32, bool)`

GetLossPercentOk returns a tuple with the LossPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLossPercent

`func (o *StatsmonTwampVisualData) SetLossPercent(v float32)`

SetLossPercent sets LossPercent field to given value.

### HasLossPercent

`func (o *StatsmonTwampVisualData) HasLossPercent() bool`

HasLossPercent returns a boolean if a field has been set.

### GetProbesRx

`func (o *StatsmonTwampVisualData) GetProbesRx() int64`

GetProbesRx returns the ProbesRx field if non-nil, zero value otherwise.

### GetProbesRxOk

`func (o *StatsmonTwampVisualData) GetProbesRxOk() (*int64, bool)`

GetProbesRxOk returns a tuple with the ProbesRx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProbesRx

`func (o *StatsmonTwampVisualData) SetProbesRx(v int64)`

SetProbesRx sets ProbesRx field to given value.

### HasProbesRx

`func (o *StatsmonTwampVisualData) HasProbesRx() bool`

HasProbesRx returns a boolean if a field has been set.

### GetProbesTx

`func (o *StatsmonTwampVisualData) GetProbesTx() int64`

GetProbesTx returns the ProbesTx field if non-nil, zero value otherwise.

### GetProbesTxOk

`func (o *StatsmonTwampVisualData) GetProbesTxOk() (*int64, bool)`

GetProbesTxOk returns a tuple with the ProbesTx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProbesTx

`func (o *StatsmonTwampVisualData) SetProbesTx(v int64)`

SetProbesTx sets ProbesTx field to given value.

### HasProbesTx

`func (o *StatsmonTwampVisualData) HasProbesTx() bool`

HasProbesTx returns a boolean if a field has been set.

### GetRoundTripLatency

`func (o *StatsmonTwampVisualData) GetRoundTripLatency() float32`

GetRoundTripLatency returns the RoundTripLatency field if non-nil, zero value otherwise.

### GetRoundTripLatencyOk

`func (o *StatsmonTwampVisualData) GetRoundTripLatencyOk() (*float32, bool)`

GetRoundTripLatencyOk returns a tuple with the RoundTripLatency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoundTripLatency

`func (o *StatsmonTwampVisualData) SetRoundTripLatency(v float32)`

SetRoundTripLatency sets RoundTripLatency field to given value.

### HasRoundTripLatency

`func (o *StatsmonTwampVisualData) HasRoundTripLatency() bool`

HasRoundTripLatency returns a boolean if a field has been set.

### GetTs

`func (o *StatsmonTwampVisualData) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *StatsmonTwampVisualData) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *StatsmonTwampVisualData) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *StatsmonTwampVisualData) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



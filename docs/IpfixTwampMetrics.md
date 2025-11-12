# IpfixTwampMetrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HealthAvg** | Pointer to **string** | calculated health average (over time window)  | [optional] 
**Jitter** | Pointer to **float64** | Jitter in ms | [optional] 
**Latency** | Pointer to **float64** | Latency in  ms | [optional] 
**Loss** | Pointer to **float32** | Loss in percentage | [optional] 
**Mos** | Pointer to **float32** |  | [optional] 
**Status** | Pointer to **string** | calculated status (last measured value) | [optional] 

## Methods

### NewIpfixTwampMetrics

`func NewIpfixTwampMetrics() *IpfixTwampMetrics`

NewIpfixTwampMetrics instantiates a new IpfixTwampMetrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixTwampMetricsWithDefaults

`func NewIpfixTwampMetricsWithDefaults() *IpfixTwampMetrics`

NewIpfixTwampMetricsWithDefaults instantiates a new IpfixTwampMetrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHealthAvg

`func (o *IpfixTwampMetrics) GetHealthAvg() string`

GetHealthAvg returns the HealthAvg field if non-nil, zero value otherwise.

### GetHealthAvgOk

`func (o *IpfixTwampMetrics) GetHealthAvgOk() (*string, bool)`

GetHealthAvgOk returns a tuple with the HealthAvg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthAvg

`func (o *IpfixTwampMetrics) SetHealthAvg(v string)`

SetHealthAvg sets HealthAvg field to given value.

### HasHealthAvg

`func (o *IpfixTwampMetrics) HasHealthAvg() bool`

HasHealthAvg returns a boolean if a field has been set.

### GetJitter

`func (o *IpfixTwampMetrics) GetJitter() float64`

GetJitter returns the Jitter field if non-nil, zero value otherwise.

### GetJitterOk

`func (o *IpfixTwampMetrics) GetJitterOk() (*float64, bool)`

GetJitterOk returns a tuple with the Jitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitter

`func (o *IpfixTwampMetrics) SetJitter(v float64)`

SetJitter sets Jitter field to given value.

### HasJitter

`func (o *IpfixTwampMetrics) HasJitter() bool`

HasJitter returns a boolean if a field has been set.

### GetLatency

`func (o *IpfixTwampMetrics) GetLatency() float64`

GetLatency returns the Latency field if non-nil, zero value otherwise.

### GetLatencyOk

`func (o *IpfixTwampMetrics) GetLatencyOk() (*float64, bool)`

GetLatencyOk returns a tuple with the Latency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatency

`func (o *IpfixTwampMetrics) SetLatency(v float64)`

SetLatency sets Latency field to given value.

### HasLatency

`func (o *IpfixTwampMetrics) HasLatency() bool`

HasLatency returns a boolean if a field has been set.

### GetLoss

`func (o *IpfixTwampMetrics) GetLoss() float32`

GetLoss returns the Loss field if non-nil, zero value otherwise.

### GetLossOk

`func (o *IpfixTwampMetrics) GetLossOk() (*float32, bool)`

GetLossOk returns a tuple with the Loss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoss

`func (o *IpfixTwampMetrics) SetLoss(v float32)`

SetLoss sets Loss field to given value.

### HasLoss

`func (o *IpfixTwampMetrics) HasLoss() bool`

HasLoss returns a boolean if a field has been set.

### GetMos

`func (o *IpfixTwampMetrics) GetMos() float32`

GetMos returns the Mos field if non-nil, zero value otherwise.

### GetMosOk

`func (o *IpfixTwampMetrics) GetMosOk() (*float32, bool)`

GetMosOk returns a tuple with the Mos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMos

`func (o *IpfixTwampMetrics) SetMos(v float32)`

SetMos sets Mos field to given value.

### HasMos

`func (o *IpfixTwampMetrics) HasMos() bool`

HasMos returns a boolean if a field has been set.

### GetStatus

`func (o *IpfixTwampMetrics) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *IpfixTwampMetrics) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *IpfixTwampMetrics) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *IpfixTwampMetrics) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



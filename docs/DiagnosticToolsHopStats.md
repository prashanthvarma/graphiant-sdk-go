# DiagnosticToolsHopStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvgTime** | Pointer to **float64** | Time in milli seconds (required) | [optional] 
**MaxTime** | Pointer to **float64** | Time in milli seconds (required) | [optional] 
**MinTime** | Pointer to **float64** | Time in milli seconds (required) | [optional] 
**RxPackets** | Pointer to **int32** | Received packet count (required) | [optional] 
**StdDevTime** | Pointer to **float64** | Standard deviation of the round-trip time in milli seconds (required) | [optional] 
**TxPackets** | Pointer to **int32** | Transmitted packet count (required) | [optional] 

## Methods

### NewDiagnosticToolsHopStats

`func NewDiagnosticToolsHopStats() *DiagnosticToolsHopStats`

NewDiagnosticToolsHopStats instantiates a new DiagnosticToolsHopStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsHopStatsWithDefaults

`func NewDiagnosticToolsHopStatsWithDefaults() *DiagnosticToolsHopStats`

NewDiagnosticToolsHopStatsWithDefaults instantiates a new DiagnosticToolsHopStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvgTime

`func (o *DiagnosticToolsHopStats) GetAvgTime() float64`

GetAvgTime returns the AvgTime field if non-nil, zero value otherwise.

### GetAvgTimeOk

`func (o *DiagnosticToolsHopStats) GetAvgTimeOk() (*float64, bool)`

GetAvgTimeOk returns a tuple with the AvgTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgTime

`func (o *DiagnosticToolsHopStats) SetAvgTime(v float64)`

SetAvgTime sets AvgTime field to given value.

### HasAvgTime

`func (o *DiagnosticToolsHopStats) HasAvgTime() bool`

HasAvgTime returns a boolean if a field has been set.

### GetMaxTime

`func (o *DiagnosticToolsHopStats) GetMaxTime() float64`

GetMaxTime returns the MaxTime field if non-nil, zero value otherwise.

### GetMaxTimeOk

`func (o *DiagnosticToolsHopStats) GetMaxTimeOk() (*float64, bool)`

GetMaxTimeOk returns a tuple with the MaxTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTime

`func (o *DiagnosticToolsHopStats) SetMaxTime(v float64)`

SetMaxTime sets MaxTime field to given value.

### HasMaxTime

`func (o *DiagnosticToolsHopStats) HasMaxTime() bool`

HasMaxTime returns a boolean if a field has been set.

### GetMinTime

`func (o *DiagnosticToolsHopStats) GetMinTime() float64`

GetMinTime returns the MinTime field if non-nil, zero value otherwise.

### GetMinTimeOk

`func (o *DiagnosticToolsHopStats) GetMinTimeOk() (*float64, bool)`

GetMinTimeOk returns a tuple with the MinTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinTime

`func (o *DiagnosticToolsHopStats) SetMinTime(v float64)`

SetMinTime sets MinTime field to given value.

### HasMinTime

`func (o *DiagnosticToolsHopStats) HasMinTime() bool`

HasMinTime returns a boolean if a field has been set.

### GetRxPackets

`func (o *DiagnosticToolsHopStats) GetRxPackets() int32`

GetRxPackets returns the RxPackets field if non-nil, zero value otherwise.

### GetRxPacketsOk

`func (o *DiagnosticToolsHopStats) GetRxPacketsOk() (*int32, bool)`

GetRxPacketsOk returns a tuple with the RxPackets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRxPackets

`func (o *DiagnosticToolsHopStats) SetRxPackets(v int32)`

SetRxPackets sets RxPackets field to given value.

### HasRxPackets

`func (o *DiagnosticToolsHopStats) HasRxPackets() bool`

HasRxPackets returns a boolean if a field has been set.

### GetStdDevTime

`func (o *DiagnosticToolsHopStats) GetStdDevTime() float64`

GetStdDevTime returns the StdDevTime field if non-nil, zero value otherwise.

### GetStdDevTimeOk

`func (o *DiagnosticToolsHopStats) GetStdDevTimeOk() (*float64, bool)`

GetStdDevTimeOk returns a tuple with the StdDevTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStdDevTime

`func (o *DiagnosticToolsHopStats) SetStdDevTime(v float64)`

SetStdDevTime sets StdDevTime field to given value.

### HasStdDevTime

`func (o *DiagnosticToolsHopStats) HasStdDevTime() bool`

HasStdDevTime returns a boolean if a field has been set.

### GetTxPackets

`func (o *DiagnosticToolsHopStats) GetTxPackets() int32`

GetTxPackets returns the TxPackets field if non-nil, zero value otherwise.

### GetTxPacketsOk

`func (o *DiagnosticToolsHopStats) GetTxPacketsOk() (*int32, bool)`

GetTxPacketsOk returns a tuple with the TxPackets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTxPackets

`func (o *DiagnosticToolsHopStats) SetTxPackets(v int32)`

SetTxPackets sets TxPackets field to given value.

### HasTxPackets

`func (o *DiagnosticToolsHopStats) HasTxPackets() bool`

HasTxPackets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



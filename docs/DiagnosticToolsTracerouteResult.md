# DiagnosticToolsTracerouteResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hops** | Pointer to [**[]DiagnosticToolsHopInfo**](DiagnosticToolsHopInfo.md) |  | [optional] 
**MaxLatency** | Pointer to **float64** | time in milliseconds (required) | [optional] 
**MaxLatencyHost** | Pointer to **string** | IPv4 or IPv6 address (required) | [optional] 
**MaxPathMtu** | Pointer to **int32** | Path MTU (required) | [optional] 
**MinPathMtu** | Pointer to **int32** | Path MTU (required) | [optional] 
**Result** | Pointer to **string** | Success or Failed (required) | [optional] 
**StoppedTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewDiagnosticToolsTracerouteResult

`func NewDiagnosticToolsTracerouteResult() *DiagnosticToolsTracerouteResult`

NewDiagnosticToolsTracerouteResult instantiates a new DiagnosticToolsTracerouteResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsTracerouteResultWithDefaults

`func NewDiagnosticToolsTracerouteResultWithDefaults() *DiagnosticToolsTracerouteResult`

NewDiagnosticToolsTracerouteResultWithDefaults instantiates a new DiagnosticToolsTracerouteResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHops

`func (o *DiagnosticToolsTracerouteResult) GetHops() []DiagnosticToolsHopInfo`

GetHops returns the Hops field if non-nil, zero value otherwise.

### GetHopsOk

`func (o *DiagnosticToolsTracerouteResult) GetHopsOk() (*[]DiagnosticToolsHopInfo, bool)`

GetHopsOk returns a tuple with the Hops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHops

`func (o *DiagnosticToolsTracerouteResult) SetHops(v []DiagnosticToolsHopInfo)`

SetHops sets Hops field to given value.

### HasHops

`func (o *DiagnosticToolsTracerouteResult) HasHops() bool`

HasHops returns a boolean if a field has been set.

### GetMaxLatency

`func (o *DiagnosticToolsTracerouteResult) GetMaxLatency() float64`

GetMaxLatency returns the MaxLatency field if non-nil, zero value otherwise.

### GetMaxLatencyOk

`func (o *DiagnosticToolsTracerouteResult) GetMaxLatencyOk() (*float64, bool)`

GetMaxLatencyOk returns a tuple with the MaxLatency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLatency

`func (o *DiagnosticToolsTracerouteResult) SetMaxLatency(v float64)`

SetMaxLatency sets MaxLatency field to given value.

### HasMaxLatency

`func (o *DiagnosticToolsTracerouteResult) HasMaxLatency() bool`

HasMaxLatency returns a boolean if a field has been set.

### GetMaxLatencyHost

`func (o *DiagnosticToolsTracerouteResult) GetMaxLatencyHost() string`

GetMaxLatencyHost returns the MaxLatencyHost field if non-nil, zero value otherwise.

### GetMaxLatencyHostOk

`func (o *DiagnosticToolsTracerouteResult) GetMaxLatencyHostOk() (*string, bool)`

GetMaxLatencyHostOk returns a tuple with the MaxLatencyHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLatencyHost

`func (o *DiagnosticToolsTracerouteResult) SetMaxLatencyHost(v string)`

SetMaxLatencyHost sets MaxLatencyHost field to given value.

### HasMaxLatencyHost

`func (o *DiagnosticToolsTracerouteResult) HasMaxLatencyHost() bool`

HasMaxLatencyHost returns a boolean if a field has been set.

### GetMaxPathMtu

`func (o *DiagnosticToolsTracerouteResult) GetMaxPathMtu() int32`

GetMaxPathMtu returns the MaxPathMtu field if non-nil, zero value otherwise.

### GetMaxPathMtuOk

`func (o *DiagnosticToolsTracerouteResult) GetMaxPathMtuOk() (*int32, bool)`

GetMaxPathMtuOk returns a tuple with the MaxPathMtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPathMtu

`func (o *DiagnosticToolsTracerouteResult) SetMaxPathMtu(v int32)`

SetMaxPathMtu sets MaxPathMtu field to given value.

### HasMaxPathMtu

`func (o *DiagnosticToolsTracerouteResult) HasMaxPathMtu() bool`

HasMaxPathMtu returns a boolean if a field has been set.

### GetMinPathMtu

`func (o *DiagnosticToolsTracerouteResult) GetMinPathMtu() int32`

GetMinPathMtu returns the MinPathMtu field if non-nil, zero value otherwise.

### GetMinPathMtuOk

`func (o *DiagnosticToolsTracerouteResult) GetMinPathMtuOk() (*int32, bool)`

GetMinPathMtuOk returns a tuple with the MinPathMtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinPathMtu

`func (o *DiagnosticToolsTracerouteResult) SetMinPathMtu(v int32)`

SetMinPathMtu sets MinPathMtu field to given value.

### HasMinPathMtu

`func (o *DiagnosticToolsTracerouteResult) HasMinPathMtu() bool`

HasMinPathMtu returns a boolean if a field has been set.

### GetResult

`func (o *DiagnosticToolsTracerouteResult) GetResult() string`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *DiagnosticToolsTracerouteResult) GetResultOk() (*string, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *DiagnosticToolsTracerouteResult) SetResult(v string)`

SetResult sets Result field to given value.

### HasResult

`func (o *DiagnosticToolsTracerouteResult) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetStoppedTime

`func (o *DiagnosticToolsTracerouteResult) GetStoppedTime() GoogleProtobufTimestamp`

GetStoppedTime returns the StoppedTime field if non-nil, zero value otherwise.

### GetStoppedTimeOk

`func (o *DiagnosticToolsTracerouteResult) GetStoppedTimeOk() (*GoogleProtobufTimestamp, bool)`

GetStoppedTimeOk returns a tuple with the StoppedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoppedTime

`func (o *DiagnosticToolsTracerouteResult) SetStoppedTime(v GoogleProtobufTimestamp)`

SetStoppedTime sets StoppedTime field to given value.

### HasStoppedTime

`func (o *DiagnosticToolsTracerouteResult) HasStoppedTime() bool`

HasStoppedTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# DiagnosticToolsPingResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvgLoss** | Pointer to **float32** | % loss (required) | [optional] 
**AvgTime** | Pointer to **float64** | Time in milli seconds (required) | [optional] 
**CompletedTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**MaxTime** | Pointer to **float64** | Time in milli seconds (required) | [optional] 
**MinTime** | Pointer to **float64** | Time in milli seconds (required) | [optional] 
**Result** | Pointer to **string** | Success or Failed (required) | [optional] 

## Methods

### NewDiagnosticToolsPingResult

`func NewDiagnosticToolsPingResult() *DiagnosticToolsPingResult`

NewDiagnosticToolsPingResult instantiates a new DiagnosticToolsPingResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsPingResultWithDefaults

`func NewDiagnosticToolsPingResultWithDefaults() *DiagnosticToolsPingResult`

NewDiagnosticToolsPingResultWithDefaults instantiates a new DiagnosticToolsPingResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvgLoss

`func (o *DiagnosticToolsPingResult) GetAvgLoss() float32`

GetAvgLoss returns the AvgLoss field if non-nil, zero value otherwise.

### GetAvgLossOk

`func (o *DiagnosticToolsPingResult) GetAvgLossOk() (*float32, bool)`

GetAvgLossOk returns a tuple with the AvgLoss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgLoss

`func (o *DiagnosticToolsPingResult) SetAvgLoss(v float32)`

SetAvgLoss sets AvgLoss field to given value.

### HasAvgLoss

`func (o *DiagnosticToolsPingResult) HasAvgLoss() bool`

HasAvgLoss returns a boolean if a field has been set.

### GetAvgTime

`func (o *DiagnosticToolsPingResult) GetAvgTime() float64`

GetAvgTime returns the AvgTime field if non-nil, zero value otherwise.

### GetAvgTimeOk

`func (o *DiagnosticToolsPingResult) GetAvgTimeOk() (*float64, bool)`

GetAvgTimeOk returns a tuple with the AvgTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgTime

`func (o *DiagnosticToolsPingResult) SetAvgTime(v float64)`

SetAvgTime sets AvgTime field to given value.

### HasAvgTime

`func (o *DiagnosticToolsPingResult) HasAvgTime() bool`

HasAvgTime returns a boolean if a field has been set.

### GetCompletedTime

`func (o *DiagnosticToolsPingResult) GetCompletedTime() GoogleProtobufTimestamp`

GetCompletedTime returns the CompletedTime field if non-nil, zero value otherwise.

### GetCompletedTimeOk

`func (o *DiagnosticToolsPingResult) GetCompletedTimeOk() (*GoogleProtobufTimestamp, bool)`

GetCompletedTimeOk returns a tuple with the CompletedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedTime

`func (o *DiagnosticToolsPingResult) SetCompletedTime(v GoogleProtobufTimestamp)`

SetCompletedTime sets CompletedTime field to given value.

### HasCompletedTime

`func (o *DiagnosticToolsPingResult) HasCompletedTime() bool`

HasCompletedTime returns a boolean if a field has been set.

### GetMaxTime

`func (o *DiagnosticToolsPingResult) GetMaxTime() float64`

GetMaxTime returns the MaxTime field if non-nil, zero value otherwise.

### GetMaxTimeOk

`func (o *DiagnosticToolsPingResult) GetMaxTimeOk() (*float64, bool)`

GetMaxTimeOk returns a tuple with the MaxTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTime

`func (o *DiagnosticToolsPingResult) SetMaxTime(v float64)`

SetMaxTime sets MaxTime field to given value.

### HasMaxTime

`func (o *DiagnosticToolsPingResult) HasMaxTime() bool`

HasMaxTime returns a boolean if a field has been set.

### GetMinTime

`func (o *DiagnosticToolsPingResult) GetMinTime() float64`

GetMinTime returns the MinTime field if non-nil, zero value otherwise.

### GetMinTimeOk

`func (o *DiagnosticToolsPingResult) GetMinTimeOk() (*float64, bool)`

GetMinTimeOk returns a tuple with the MinTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinTime

`func (o *DiagnosticToolsPingResult) SetMinTime(v float64)`

SetMinTime sets MinTime field to given value.

### HasMinTime

`func (o *DiagnosticToolsPingResult) HasMinTime() bool`

HasMinTime returns a boolean if a field has been set.

### GetResult

`func (o *DiagnosticToolsPingResult) GetResult() string`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *DiagnosticToolsPingResult) GetResultOk() (*string, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *DiagnosticToolsPingResult) SetResult(v string)`

SetResult sets Result field to given value.

### HasResult

`func (o *DiagnosticToolsPingResult) HasResult() bool`

HasResult returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



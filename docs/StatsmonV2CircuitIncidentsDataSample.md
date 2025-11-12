# StatsmonV2CircuitIncidentsDataSample

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DlIncidents** | Pointer to [**StatsmonV2CircuitIncidentsDataSampleIncidents**](StatsmonV2CircuitIncidentsDataSampleIncidents.md) |  | [optional] 
**OverallStatus** | Pointer to **string** | Overall circuit status based on num of poor/fair incidents. | [optional] 
**TotalIncidents** | Pointer to [**StatsmonV2CircuitIncidentsDataSampleIncidents**](StatsmonV2CircuitIncidentsDataSampleIncidents.md) |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**UlIncidents** | Pointer to [**StatsmonV2CircuitIncidentsDataSampleIncidents**](StatsmonV2CircuitIncidentsDataSampleIncidents.md) |  | [optional] 

## Methods

### NewStatsmonV2CircuitIncidentsDataSample

`func NewStatsmonV2CircuitIncidentsDataSample() *StatsmonV2CircuitIncidentsDataSample`

NewStatsmonV2CircuitIncidentsDataSample instantiates a new StatsmonV2CircuitIncidentsDataSample object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2CircuitIncidentsDataSampleWithDefaults

`func NewStatsmonV2CircuitIncidentsDataSampleWithDefaults() *StatsmonV2CircuitIncidentsDataSample`

NewStatsmonV2CircuitIncidentsDataSampleWithDefaults instantiates a new StatsmonV2CircuitIncidentsDataSample object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDlIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) GetDlIncidents() StatsmonV2CircuitIncidentsDataSampleIncidents`

GetDlIncidents returns the DlIncidents field if non-nil, zero value otherwise.

### GetDlIncidentsOk

`func (o *StatsmonV2CircuitIncidentsDataSample) GetDlIncidentsOk() (*StatsmonV2CircuitIncidentsDataSampleIncidents, bool)`

GetDlIncidentsOk returns a tuple with the DlIncidents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDlIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) SetDlIncidents(v StatsmonV2CircuitIncidentsDataSampleIncidents)`

SetDlIncidents sets DlIncidents field to given value.

### HasDlIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) HasDlIncidents() bool`

HasDlIncidents returns a boolean if a field has been set.

### GetOverallStatus

`func (o *StatsmonV2CircuitIncidentsDataSample) GetOverallStatus() string`

GetOverallStatus returns the OverallStatus field if non-nil, zero value otherwise.

### GetOverallStatusOk

`func (o *StatsmonV2CircuitIncidentsDataSample) GetOverallStatusOk() (*string, bool)`

GetOverallStatusOk returns a tuple with the OverallStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverallStatus

`func (o *StatsmonV2CircuitIncidentsDataSample) SetOverallStatus(v string)`

SetOverallStatus sets OverallStatus field to given value.

### HasOverallStatus

`func (o *StatsmonV2CircuitIncidentsDataSample) HasOverallStatus() bool`

HasOverallStatus returns a boolean if a field has been set.

### GetTotalIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) GetTotalIncidents() StatsmonV2CircuitIncidentsDataSampleIncidents`

GetTotalIncidents returns the TotalIncidents field if non-nil, zero value otherwise.

### GetTotalIncidentsOk

`func (o *StatsmonV2CircuitIncidentsDataSample) GetTotalIncidentsOk() (*StatsmonV2CircuitIncidentsDataSampleIncidents, bool)`

GetTotalIncidentsOk returns a tuple with the TotalIncidents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) SetTotalIncidents(v StatsmonV2CircuitIncidentsDataSampleIncidents)`

SetTotalIncidents sets TotalIncidents field to given value.

### HasTotalIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) HasTotalIncidents() bool`

HasTotalIncidents returns a boolean if a field has been set.

### GetTs

`func (o *StatsmonV2CircuitIncidentsDataSample) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *StatsmonV2CircuitIncidentsDataSample) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *StatsmonV2CircuitIncidentsDataSample) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *StatsmonV2CircuitIncidentsDataSample) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetUlIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) GetUlIncidents() StatsmonV2CircuitIncidentsDataSampleIncidents`

GetUlIncidents returns the UlIncidents field if non-nil, zero value otherwise.

### GetUlIncidentsOk

`func (o *StatsmonV2CircuitIncidentsDataSample) GetUlIncidentsOk() (*StatsmonV2CircuitIncidentsDataSampleIncidents, bool)`

GetUlIncidentsOk returns a tuple with the UlIncidents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUlIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) SetUlIncidents(v StatsmonV2CircuitIncidentsDataSampleIncidents)`

SetUlIncidents sets UlIncidents field to given value.

### HasUlIncidents

`func (o *StatsmonV2CircuitIncidentsDataSample) HasUlIncidents() bool`

HasUlIncidents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



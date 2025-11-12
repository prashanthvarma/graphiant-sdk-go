# StatsmonV2StatsSample

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Value** | Pointer to **float64** |  | [optional] 

## Methods

### NewStatsmonV2StatsSample

`func NewStatsmonV2StatsSample() *StatsmonV2StatsSample`

NewStatsmonV2StatsSample instantiates a new StatsmonV2StatsSample object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2StatsSampleWithDefaults

`func NewStatsmonV2StatsSampleWithDefaults() *StatsmonV2StatsSample`

NewStatsmonV2StatsSampleWithDefaults instantiates a new StatsmonV2StatsSample object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *StatsmonV2StatsSample) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonV2StatsSample) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonV2StatsSample) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonV2StatsSample) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTs

`func (o *StatsmonV2StatsSample) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *StatsmonV2StatsSample) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *StatsmonV2StatsSample) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *StatsmonV2StatsSample) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetValue

`func (o *StatsmonV2StatsSample) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *StatsmonV2StatsSample) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *StatsmonV2StatsSample) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *StatsmonV2StatsSample) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



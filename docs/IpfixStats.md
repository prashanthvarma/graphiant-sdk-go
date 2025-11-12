# IpfixStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvgUsage** | Pointer to **float64** | Average service usage in kbps | [optional] 
**PeakUsage** | Pointer to **float64** | Peak service usage in kbps | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewIpfixStats

`func NewIpfixStats() *IpfixStats`

NewIpfixStats instantiates a new IpfixStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixStatsWithDefaults

`func NewIpfixStatsWithDefaults() *IpfixStats`

NewIpfixStatsWithDefaults instantiates a new IpfixStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvgUsage

`func (o *IpfixStats) GetAvgUsage() float64`

GetAvgUsage returns the AvgUsage field if non-nil, zero value otherwise.

### GetAvgUsageOk

`func (o *IpfixStats) GetAvgUsageOk() (*float64, bool)`

GetAvgUsageOk returns a tuple with the AvgUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgUsage

`func (o *IpfixStats) SetAvgUsage(v float64)`

SetAvgUsage sets AvgUsage field to given value.

### HasAvgUsage

`func (o *IpfixStats) HasAvgUsage() bool`

HasAvgUsage returns a boolean if a field has been set.

### GetPeakUsage

`func (o *IpfixStats) GetPeakUsage() float64`

GetPeakUsage returns the PeakUsage field if non-nil, zero value otherwise.

### GetPeakUsageOk

`func (o *IpfixStats) GetPeakUsageOk() (*float64, bool)`

GetPeakUsageOk returns a tuple with the PeakUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeakUsage

`func (o *IpfixStats) SetPeakUsage(v float64)`

SetPeakUsage sets PeakUsage field to given value.

### HasPeakUsage

`func (o *IpfixStats) HasPeakUsage() bool`

HasPeakUsage returns a boolean if a field has been set.

### GetTs

`func (o *IpfixStats) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *IpfixStats) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *IpfixStats) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *IpfixStats) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



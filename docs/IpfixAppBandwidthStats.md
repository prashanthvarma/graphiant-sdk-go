# IpfixAppBandwidthStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DlBw** | Pointer to **float64** | Bandwidth in kilo bits per second | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**UlBw** | Pointer to **float64** | Bandwidth in kilo bits per second | [optional] 

## Methods

### NewIpfixAppBandwidthStats

`func NewIpfixAppBandwidthStats() *IpfixAppBandwidthStats`

NewIpfixAppBandwidthStats instantiates a new IpfixAppBandwidthStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppBandwidthStatsWithDefaults

`func NewIpfixAppBandwidthStatsWithDefaults() *IpfixAppBandwidthStats`

NewIpfixAppBandwidthStatsWithDefaults instantiates a new IpfixAppBandwidthStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDlBw

`func (o *IpfixAppBandwidthStats) GetDlBw() float64`

GetDlBw returns the DlBw field if non-nil, zero value otherwise.

### GetDlBwOk

`func (o *IpfixAppBandwidthStats) GetDlBwOk() (*float64, bool)`

GetDlBwOk returns a tuple with the DlBw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDlBw

`func (o *IpfixAppBandwidthStats) SetDlBw(v float64)`

SetDlBw sets DlBw field to given value.

### HasDlBw

`func (o *IpfixAppBandwidthStats) HasDlBw() bool`

HasDlBw returns a boolean if a field has been set.

### GetTs

`func (o *IpfixAppBandwidthStats) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *IpfixAppBandwidthStats) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *IpfixAppBandwidthStats) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *IpfixAppBandwidthStats) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetUlBw

`func (o *IpfixAppBandwidthStats) GetUlBw() float64`

GetUlBw returns the UlBw field if non-nil, zero value otherwise.

### GetUlBwOk

`func (o *IpfixAppBandwidthStats) GetUlBwOk() (*float64, bool)`

GetUlBwOk returns a tuple with the UlBw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUlBw

`func (o *IpfixAppBandwidthStats) SetUlBw(v float64)`

SetUlBw sets UlBw field to given value.

### HasUlBw

`func (o *IpfixAppBandwidthStats) HasUlBw() bool`

HasUlBw returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



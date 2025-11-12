# IpfixCircuitMetrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | circuit name | [optional] 
**SlaClass** | Pointer to **string** |  | [optional] 
**Stats** | Pointer to [**IpfixTwampMetrics**](IpfixTwampMetrics.md) |  | [optional] 
**Usage** | Pointer to **float64** | usage of the circuit by the application in kilo bytes | [optional] 
**UsagePct** | Pointer to **float32** |  | [optional] 

## Methods

### NewIpfixCircuitMetrics

`func NewIpfixCircuitMetrics() *IpfixCircuitMetrics`

NewIpfixCircuitMetrics instantiates a new IpfixCircuitMetrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixCircuitMetricsWithDefaults

`func NewIpfixCircuitMetricsWithDefaults() *IpfixCircuitMetrics`

NewIpfixCircuitMetricsWithDefaults instantiates a new IpfixCircuitMetrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *IpfixCircuitMetrics) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *IpfixCircuitMetrics) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *IpfixCircuitMetrics) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *IpfixCircuitMetrics) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSlaClass

`func (o *IpfixCircuitMetrics) GetSlaClass() string`

GetSlaClass returns the SlaClass field if non-nil, zero value otherwise.

### GetSlaClassOk

`func (o *IpfixCircuitMetrics) GetSlaClassOk() (*string, bool)`

GetSlaClassOk returns a tuple with the SlaClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlaClass

`func (o *IpfixCircuitMetrics) SetSlaClass(v string)`

SetSlaClass sets SlaClass field to given value.

### HasSlaClass

`func (o *IpfixCircuitMetrics) HasSlaClass() bool`

HasSlaClass returns a boolean if a field has been set.

### GetStats

`func (o *IpfixCircuitMetrics) GetStats() IpfixTwampMetrics`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *IpfixCircuitMetrics) GetStatsOk() (*IpfixTwampMetrics, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *IpfixCircuitMetrics) SetStats(v IpfixTwampMetrics)`

SetStats sets Stats field to given value.

### HasStats

`func (o *IpfixCircuitMetrics) HasStats() bool`

HasStats returns a boolean if a field has been set.

### GetUsage

`func (o *IpfixCircuitMetrics) GetUsage() float64`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *IpfixCircuitMetrics) GetUsageOk() (*float64, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *IpfixCircuitMetrics) SetUsage(v float64)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *IpfixCircuitMetrics) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetUsagePct

`func (o *IpfixCircuitMetrics) GetUsagePct() float32`

GetUsagePct returns the UsagePct field if non-nil, zero value otherwise.

### GetUsagePctOk

`func (o *IpfixCircuitMetrics) GetUsagePctOk() (*float32, bool)`

GetUsagePctOk returns a tuple with the UsagePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsagePct

`func (o *IpfixCircuitMetrics) SetUsagePct(v float32)`

SetUsagePct sets UsagePct field to given value.

### HasUsagePct

`func (o *IpfixCircuitMetrics) HasUsagePct() bool`

HasUsagePct returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



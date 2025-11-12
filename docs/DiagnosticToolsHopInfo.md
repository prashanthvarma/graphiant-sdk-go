# DiagnosticToolsHopInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HostAddress** | Pointer to **string** | IPv4 or IPv6 address (required) | [optional] 
**PathMtu** | Pointer to **int32** | Path MTU for this host_address (required) | [optional] 
**RoundTripTime** | Pointer to **float64** | time in milli seconds (required) | [optional] 
**Stats** | Pointer to [**DiagnosticToolsHopStats**](DiagnosticToolsHopStats.md) |  | [optional] 

## Methods

### NewDiagnosticToolsHopInfo

`func NewDiagnosticToolsHopInfo() *DiagnosticToolsHopInfo`

NewDiagnosticToolsHopInfo instantiates a new DiagnosticToolsHopInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsHopInfoWithDefaults

`func NewDiagnosticToolsHopInfoWithDefaults() *DiagnosticToolsHopInfo`

NewDiagnosticToolsHopInfoWithDefaults instantiates a new DiagnosticToolsHopInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHostAddress

`func (o *DiagnosticToolsHopInfo) GetHostAddress() string`

GetHostAddress returns the HostAddress field if non-nil, zero value otherwise.

### GetHostAddressOk

`func (o *DiagnosticToolsHopInfo) GetHostAddressOk() (*string, bool)`

GetHostAddressOk returns a tuple with the HostAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostAddress

`func (o *DiagnosticToolsHopInfo) SetHostAddress(v string)`

SetHostAddress sets HostAddress field to given value.

### HasHostAddress

`func (o *DiagnosticToolsHopInfo) HasHostAddress() bool`

HasHostAddress returns a boolean if a field has been set.

### GetPathMtu

`func (o *DiagnosticToolsHopInfo) GetPathMtu() int32`

GetPathMtu returns the PathMtu field if non-nil, zero value otherwise.

### GetPathMtuOk

`func (o *DiagnosticToolsHopInfo) GetPathMtuOk() (*int32, bool)`

GetPathMtuOk returns a tuple with the PathMtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPathMtu

`func (o *DiagnosticToolsHopInfo) SetPathMtu(v int32)`

SetPathMtu sets PathMtu field to given value.

### HasPathMtu

`func (o *DiagnosticToolsHopInfo) HasPathMtu() bool`

HasPathMtu returns a boolean if a field has been set.

### GetRoundTripTime

`func (o *DiagnosticToolsHopInfo) GetRoundTripTime() float64`

GetRoundTripTime returns the RoundTripTime field if non-nil, zero value otherwise.

### GetRoundTripTimeOk

`func (o *DiagnosticToolsHopInfo) GetRoundTripTimeOk() (*float64, bool)`

GetRoundTripTimeOk returns a tuple with the RoundTripTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoundTripTime

`func (o *DiagnosticToolsHopInfo) SetRoundTripTime(v float64)`

SetRoundTripTime sets RoundTripTime field to given value.

### HasRoundTripTime

`func (o *DiagnosticToolsHopInfo) HasRoundTripTime() bool`

HasRoundTripTime returns a boolean if a field has been set.

### GetStats

`func (o *DiagnosticToolsHopInfo) GetStats() DiagnosticToolsHopStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *DiagnosticToolsHopInfo) GetStatsOk() (*DiagnosticToolsHopStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *DiagnosticToolsHopInfo) SetStats(v DiagnosticToolsHopStats)`

SetStats sets Stats field to given value.

### HasStats

`func (o *DiagnosticToolsHopInfo) HasStats() bool`

HasStats returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



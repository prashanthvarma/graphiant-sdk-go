# StatsmonV2Connection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | Pointer to **bool** |  | [optional] 
**CircuitCarrier** | Pointer to **string** |  | [optional] 
**CircuitName** | Pointer to **string** |  | [optional] 
**DestinationIp** | Pointer to **string** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**LastEstablishedTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**LastResort** | Pointer to **bool** |  | [optional] 
**Quality** | Pointer to **string** |  | [optional] 
**SourceIp** | Pointer to **string** |  | [optional] 
**SourcePublicIp** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonV2Connection

`func NewStatsmonV2Connection() *StatsmonV2Connection`

NewStatsmonV2Connection instantiates a new StatsmonV2Connection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2ConnectionWithDefaults

`func NewStatsmonV2ConnectionWithDefaults() *StatsmonV2Connection`

NewStatsmonV2ConnectionWithDefaults instantiates a new StatsmonV2Connection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *StatsmonV2Connection) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *StatsmonV2Connection) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *StatsmonV2Connection) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *StatsmonV2Connection) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCircuitCarrier

`func (o *StatsmonV2Connection) GetCircuitCarrier() string`

GetCircuitCarrier returns the CircuitCarrier field if non-nil, zero value otherwise.

### GetCircuitCarrierOk

`func (o *StatsmonV2Connection) GetCircuitCarrierOk() (*string, bool)`

GetCircuitCarrierOk returns a tuple with the CircuitCarrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitCarrier

`func (o *StatsmonV2Connection) SetCircuitCarrier(v string)`

SetCircuitCarrier sets CircuitCarrier field to given value.

### HasCircuitCarrier

`func (o *StatsmonV2Connection) HasCircuitCarrier() bool`

HasCircuitCarrier returns a boolean if a field has been set.

### GetCircuitName

`func (o *StatsmonV2Connection) GetCircuitName() string`

GetCircuitName returns the CircuitName field if non-nil, zero value otherwise.

### GetCircuitNameOk

`func (o *StatsmonV2Connection) GetCircuitNameOk() (*string, bool)`

GetCircuitNameOk returns a tuple with the CircuitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitName

`func (o *StatsmonV2Connection) SetCircuitName(v string)`

SetCircuitName sets CircuitName field to given value.

### HasCircuitName

`func (o *StatsmonV2Connection) HasCircuitName() bool`

HasCircuitName returns a boolean if a field has been set.

### GetDestinationIp

`func (o *StatsmonV2Connection) GetDestinationIp() string`

GetDestinationIp returns the DestinationIp field if non-nil, zero value otherwise.

### GetDestinationIpOk

`func (o *StatsmonV2Connection) GetDestinationIpOk() (*string, bool)`

GetDestinationIpOk returns a tuple with the DestinationIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationIp

`func (o *StatsmonV2Connection) SetDestinationIp(v string)`

SetDestinationIp sets DestinationIp field to given value.

### HasDestinationIp

`func (o *StatsmonV2Connection) HasDestinationIp() bool`

HasDestinationIp returns a boolean if a field has been set.

### GetHostname

`func (o *StatsmonV2Connection) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *StatsmonV2Connection) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *StatsmonV2Connection) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *StatsmonV2Connection) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetLastEstablishedTime

`func (o *StatsmonV2Connection) GetLastEstablishedTime() GoogleProtobufTimestamp`

GetLastEstablishedTime returns the LastEstablishedTime field if non-nil, zero value otherwise.

### GetLastEstablishedTimeOk

`func (o *StatsmonV2Connection) GetLastEstablishedTimeOk() (*GoogleProtobufTimestamp, bool)`

GetLastEstablishedTimeOk returns a tuple with the LastEstablishedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEstablishedTime

`func (o *StatsmonV2Connection) SetLastEstablishedTime(v GoogleProtobufTimestamp)`

SetLastEstablishedTime sets LastEstablishedTime field to given value.

### HasLastEstablishedTime

`func (o *StatsmonV2Connection) HasLastEstablishedTime() bool`

HasLastEstablishedTime returns a boolean if a field has been set.

### GetLastResort

`func (o *StatsmonV2Connection) GetLastResort() bool`

GetLastResort returns the LastResort field if non-nil, zero value otherwise.

### GetLastResortOk

`func (o *StatsmonV2Connection) GetLastResortOk() (*bool, bool)`

GetLastResortOk returns a tuple with the LastResort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastResort

`func (o *StatsmonV2Connection) SetLastResort(v bool)`

SetLastResort sets LastResort field to given value.

### HasLastResort

`func (o *StatsmonV2Connection) HasLastResort() bool`

HasLastResort returns a boolean if a field has been set.

### GetQuality

`func (o *StatsmonV2Connection) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *StatsmonV2Connection) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *StatsmonV2Connection) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *StatsmonV2Connection) HasQuality() bool`

HasQuality returns a boolean if a field has been set.

### GetSourceIp

`func (o *StatsmonV2Connection) GetSourceIp() string`

GetSourceIp returns the SourceIp field if non-nil, zero value otherwise.

### GetSourceIpOk

`func (o *StatsmonV2Connection) GetSourceIpOk() (*string, bool)`

GetSourceIpOk returns a tuple with the SourceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceIp

`func (o *StatsmonV2Connection) SetSourceIp(v string)`

SetSourceIp sets SourceIp field to given value.

### HasSourceIp

`func (o *StatsmonV2Connection) HasSourceIp() bool`

HasSourceIp returns a boolean if a field has been set.

### GetSourcePublicIp

`func (o *StatsmonV2Connection) GetSourcePublicIp() string`

GetSourcePublicIp returns the SourcePublicIp field if non-nil, zero value otherwise.

### GetSourcePublicIpOk

`func (o *StatsmonV2Connection) GetSourcePublicIpOk() (*string, bool)`

GetSourcePublicIpOk returns a tuple with the SourcePublicIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePublicIp

`func (o *StatsmonV2Connection) SetSourcePublicIp(v string)`

SetSourcePublicIp sets SourcePublicIp field to given value.

### HasSourcePublicIp

`func (o *StatsmonV2Connection) HasSourcePublicIp() bool`

HasSourcePublicIp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



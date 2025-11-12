# StatsmonV2NodeConnection

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

### NewStatsmonV2NodeConnection

`func NewStatsmonV2NodeConnection() *StatsmonV2NodeConnection`

NewStatsmonV2NodeConnection instantiates a new StatsmonV2NodeConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2NodeConnectionWithDefaults

`func NewStatsmonV2NodeConnectionWithDefaults() *StatsmonV2NodeConnection`

NewStatsmonV2NodeConnectionWithDefaults instantiates a new StatsmonV2NodeConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *StatsmonV2NodeConnection) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *StatsmonV2NodeConnection) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *StatsmonV2NodeConnection) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *StatsmonV2NodeConnection) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCircuitCarrier

`func (o *StatsmonV2NodeConnection) GetCircuitCarrier() string`

GetCircuitCarrier returns the CircuitCarrier field if non-nil, zero value otherwise.

### GetCircuitCarrierOk

`func (o *StatsmonV2NodeConnection) GetCircuitCarrierOk() (*string, bool)`

GetCircuitCarrierOk returns a tuple with the CircuitCarrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitCarrier

`func (o *StatsmonV2NodeConnection) SetCircuitCarrier(v string)`

SetCircuitCarrier sets CircuitCarrier field to given value.

### HasCircuitCarrier

`func (o *StatsmonV2NodeConnection) HasCircuitCarrier() bool`

HasCircuitCarrier returns a boolean if a field has been set.

### GetCircuitName

`func (o *StatsmonV2NodeConnection) GetCircuitName() string`

GetCircuitName returns the CircuitName field if non-nil, zero value otherwise.

### GetCircuitNameOk

`func (o *StatsmonV2NodeConnection) GetCircuitNameOk() (*string, bool)`

GetCircuitNameOk returns a tuple with the CircuitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitName

`func (o *StatsmonV2NodeConnection) SetCircuitName(v string)`

SetCircuitName sets CircuitName field to given value.

### HasCircuitName

`func (o *StatsmonV2NodeConnection) HasCircuitName() bool`

HasCircuitName returns a boolean if a field has been set.

### GetDestinationIp

`func (o *StatsmonV2NodeConnection) GetDestinationIp() string`

GetDestinationIp returns the DestinationIp field if non-nil, zero value otherwise.

### GetDestinationIpOk

`func (o *StatsmonV2NodeConnection) GetDestinationIpOk() (*string, bool)`

GetDestinationIpOk returns a tuple with the DestinationIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationIp

`func (o *StatsmonV2NodeConnection) SetDestinationIp(v string)`

SetDestinationIp sets DestinationIp field to given value.

### HasDestinationIp

`func (o *StatsmonV2NodeConnection) HasDestinationIp() bool`

HasDestinationIp returns a boolean if a field has been set.

### GetHostname

`func (o *StatsmonV2NodeConnection) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *StatsmonV2NodeConnection) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *StatsmonV2NodeConnection) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *StatsmonV2NodeConnection) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetLastEstablishedTime

`func (o *StatsmonV2NodeConnection) GetLastEstablishedTime() GoogleProtobufTimestamp`

GetLastEstablishedTime returns the LastEstablishedTime field if non-nil, zero value otherwise.

### GetLastEstablishedTimeOk

`func (o *StatsmonV2NodeConnection) GetLastEstablishedTimeOk() (*GoogleProtobufTimestamp, bool)`

GetLastEstablishedTimeOk returns a tuple with the LastEstablishedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEstablishedTime

`func (o *StatsmonV2NodeConnection) SetLastEstablishedTime(v GoogleProtobufTimestamp)`

SetLastEstablishedTime sets LastEstablishedTime field to given value.

### HasLastEstablishedTime

`func (o *StatsmonV2NodeConnection) HasLastEstablishedTime() bool`

HasLastEstablishedTime returns a boolean if a field has been set.

### GetLastResort

`func (o *StatsmonV2NodeConnection) GetLastResort() bool`

GetLastResort returns the LastResort field if non-nil, zero value otherwise.

### GetLastResortOk

`func (o *StatsmonV2NodeConnection) GetLastResortOk() (*bool, bool)`

GetLastResortOk returns a tuple with the LastResort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastResort

`func (o *StatsmonV2NodeConnection) SetLastResort(v bool)`

SetLastResort sets LastResort field to given value.

### HasLastResort

`func (o *StatsmonV2NodeConnection) HasLastResort() bool`

HasLastResort returns a boolean if a field has been set.

### GetQuality

`func (o *StatsmonV2NodeConnection) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *StatsmonV2NodeConnection) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *StatsmonV2NodeConnection) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *StatsmonV2NodeConnection) HasQuality() bool`

HasQuality returns a boolean if a field has been set.

### GetSourceIp

`func (o *StatsmonV2NodeConnection) GetSourceIp() string`

GetSourceIp returns the SourceIp field if non-nil, zero value otherwise.

### GetSourceIpOk

`func (o *StatsmonV2NodeConnection) GetSourceIpOk() (*string, bool)`

GetSourceIpOk returns a tuple with the SourceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceIp

`func (o *StatsmonV2NodeConnection) SetSourceIp(v string)`

SetSourceIp sets SourceIp field to given value.

### HasSourceIp

`func (o *StatsmonV2NodeConnection) HasSourceIp() bool`

HasSourceIp returns a boolean if a field has been set.

### GetSourcePublicIp

`func (o *StatsmonV2NodeConnection) GetSourcePublicIp() string`

GetSourcePublicIp returns the SourcePublicIp field if non-nil, zero value otherwise.

### GetSourcePublicIpOk

`func (o *StatsmonV2NodeConnection) GetSourcePublicIpOk() (*string, bool)`

GetSourcePublicIpOk returns a tuple with the SourcePublicIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePublicIp

`func (o *StatsmonV2NodeConnection) SetSourcePublicIp(v string)`

SetSourcePublicIp sets SourcePublicIp field to given value.

### HasSourcePublicIp

`func (o *StatsmonV2NodeConnection) HasSourcePublicIp() bool`

HasSourcePublicIp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



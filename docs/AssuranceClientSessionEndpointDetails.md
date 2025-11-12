# AssuranceClientSessionEndpointDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuits** | Pointer to **[]string** |  | [optional] 
**Edges** | Pointer to [**[]AssuranceEdge**](AssuranceEdge.md) |  | [optional] 
**IsGateway** | Pointer to **bool** |  | [optional] 
**Jitter** | Pointer to [**AssuranceClientSessionEndpointDetailsStatistics**](AssuranceClientSessionEndpointDetailsStatistics.md) |  | [optional] 
**Latency** | Pointer to [**AssuranceClientSessionEndpointDetailsStatistics**](AssuranceClientSessionEndpointDetailsStatistics.md) |  | [optional] 
**Loss** | Pointer to [**AssuranceClientSessionEndpointDetailsStatistics**](AssuranceClientSessionEndpointDetailsStatistics.md) |  | [optional] 
**Site** | Pointer to [**AssuranceSite**](AssuranceSite.md) |  | [optional] 
**TotalDownlinkUsage** | Pointer to **int64** |  | [optional] 
**TotalUplinkUsage** | Pointer to **int64** |  | [optional] 

## Methods

### NewAssuranceClientSessionEndpointDetails

`func NewAssuranceClientSessionEndpointDetails() *AssuranceClientSessionEndpointDetails`

NewAssuranceClientSessionEndpointDetails instantiates a new AssuranceClientSessionEndpointDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceClientSessionEndpointDetailsWithDefaults

`func NewAssuranceClientSessionEndpointDetailsWithDefaults() *AssuranceClientSessionEndpointDetails`

NewAssuranceClientSessionEndpointDetailsWithDefaults instantiates a new AssuranceClientSessionEndpointDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuits

`func (o *AssuranceClientSessionEndpointDetails) GetCircuits() []string`

GetCircuits returns the Circuits field if non-nil, zero value otherwise.

### GetCircuitsOk

`func (o *AssuranceClientSessionEndpointDetails) GetCircuitsOk() (*[]string, bool)`

GetCircuitsOk returns a tuple with the Circuits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuits

`func (o *AssuranceClientSessionEndpointDetails) SetCircuits(v []string)`

SetCircuits sets Circuits field to given value.

### HasCircuits

`func (o *AssuranceClientSessionEndpointDetails) HasCircuits() bool`

HasCircuits returns a boolean if a field has been set.

### GetEdges

`func (o *AssuranceClientSessionEndpointDetails) GetEdges() []AssuranceEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *AssuranceClientSessionEndpointDetails) GetEdgesOk() (*[]AssuranceEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *AssuranceClientSessionEndpointDetails) SetEdges(v []AssuranceEdge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *AssuranceClientSessionEndpointDetails) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetIsGateway

`func (o *AssuranceClientSessionEndpointDetails) GetIsGateway() bool`

GetIsGateway returns the IsGateway field if non-nil, zero value otherwise.

### GetIsGatewayOk

`func (o *AssuranceClientSessionEndpointDetails) GetIsGatewayOk() (*bool, bool)`

GetIsGatewayOk returns a tuple with the IsGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGateway

`func (o *AssuranceClientSessionEndpointDetails) SetIsGateway(v bool)`

SetIsGateway sets IsGateway field to given value.

### HasIsGateway

`func (o *AssuranceClientSessionEndpointDetails) HasIsGateway() bool`

HasIsGateway returns a boolean if a field has been set.

### GetJitter

`func (o *AssuranceClientSessionEndpointDetails) GetJitter() AssuranceClientSessionEndpointDetailsStatistics`

GetJitter returns the Jitter field if non-nil, zero value otherwise.

### GetJitterOk

`func (o *AssuranceClientSessionEndpointDetails) GetJitterOk() (*AssuranceClientSessionEndpointDetailsStatistics, bool)`

GetJitterOk returns a tuple with the Jitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitter

`func (o *AssuranceClientSessionEndpointDetails) SetJitter(v AssuranceClientSessionEndpointDetailsStatistics)`

SetJitter sets Jitter field to given value.

### HasJitter

`func (o *AssuranceClientSessionEndpointDetails) HasJitter() bool`

HasJitter returns a boolean if a field has been set.

### GetLatency

`func (o *AssuranceClientSessionEndpointDetails) GetLatency() AssuranceClientSessionEndpointDetailsStatistics`

GetLatency returns the Latency field if non-nil, zero value otherwise.

### GetLatencyOk

`func (o *AssuranceClientSessionEndpointDetails) GetLatencyOk() (*AssuranceClientSessionEndpointDetailsStatistics, bool)`

GetLatencyOk returns a tuple with the Latency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatency

`func (o *AssuranceClientSessionEndpointDetails) SetLatency(v AssuranceClientSessionEndpointDetailsStatistics)`

SetLatency sets Latency field to given value.

### HasLatency

`func (o *AssuranceClientSessionEndpointDetails) HasLatency() bool`

HasLatency returns a boolean if a field has been set.

### GetLoss

`func (o *AssuranceClientSessionEndpointDetails) GetLoss() AssuranceClientSessionEndpointDetailsStatistics`

GetLoss returns the Loss field if non-nil, zero value otherwise.

### GetLossOk

`func (o *AssuranceClientSessionEndpointDetails) GetLossOk() (*AssuranceClientSessionEndpointDetailsStatistics, bool)`

GetLossOk returns a tuple with the Loss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoss

`func (o *AssuranceClientSessionEndpointDetails) SetLoss(v AssuranceClientSessionEndpointDetailsStatistics)`

SetLoss sets Loss field to given value.

### HasLoss

`func (o *AssuranceClientSessionEndpointDetails) HasLoss() bool`

HasLoss returns a boolean if a field has been set.

### GetSite

`func (o *AssuranceClientSessionEndpointDetails) GetSite() AssuranceSite`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *AssuranceClientSessionEndpointDetails) GetSiteOk() (*AssuranceSite, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *AssuranceClientSessionEndpointDetails) SetSite(v AssuranceSite)`

SetSite sets Site field to given value.

### HasSite

`func (o *AssuranceClientSessionEndpointDetails) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetTotalDownlinkUsage

`func (o *AssuranceClientSessionEndpointDetails) GetTotalDownlinkUsage() int64`

GetTotalDownlinkUsage returns the TotalDownlinkUsage field if non-nil, zero value otherwise.

### GetTotalDownlinkUsageOk

`func (o *AssuranceClientSessionEndpointDetails) GetTotalDownlinkUsageOk() (*int64, bool)`

GetTotalDownlinkUsageOk returns a tuple with the TotalDownlinkUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalDownlinkUsage

`func (o *AssuranceClientSessionEndpointDetails) SetTotalDownlinkUsage(v int64)`

SetTotalDownlinkUsage sets TotalDownlinkUsage field to given value.

### HasTotalDownlinkUsage

`func (o *AssuranceClientSessionEndpointDetails) HasTotalDownlinkUsage() bool`

HasTotalDownlinkUsage returns a boolean if a field has been set.

### GetTotalUplinkUsage

`func (o *AssuranceClientSessionEndpointDetails) GetTotalUplinkUsage() int64`

GetTotalUplinkUsage returns the TotalUplinkUsage field if non-nil, zero value otherwise.

### GetTotalUplinkUsageOk

`func (o *AssuranceClientSessionEndpointDetails) GetTotalUplinkUsageOk() (*int64, bool)`

GetTotalUplinkUsageOk returns a tuple with the TotalUplinkUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUplinkUsage

`func (o *AssuranceClientSessionEndpointDetails) SetTotalUplinkUsage(v int64)`

SetTotalUplinkUsage sets TotalUplinkUsage field to given value.

### HasTotalUplinkUsage

`func (o *AssuranceClientSessionEndpointDetails) HasTotalUplinkUsage() bool`

HasTotalUplinkUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



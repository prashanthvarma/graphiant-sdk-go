# V2AssuranceFlowSummaryPostResponseEndpointDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuits** | Pointer to **[]string** |  | [optional] 
**Edges** | Pointer to [**[]AssuranceEdge**](AssuranceEdge.md) |  | [optional] 
**Jitter** | Pointer to [**V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics**](V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics.md) |  | [optional] 
**Latency** | Pointer to [**V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics**](V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics.md) |  | [optional] 
**Loss** | Pointer to [**V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics**](V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics.md) |  | [optional] 
**Site** | Pointer to [**AssuranceSite**](AssuranceSite.md) |  | [optional] 
**TotalDownlinkUsage** | Pointer to **int64** |  | [optional] 
**TotalUplinkUsage** | Pointer to **int64** |  | [optional] 

## Methods

### NewV2AssuranceFlowSummaryPostResponseEndpointDetails

`func NewV2AssuranceFlowSummaryPostResponseEndpointDetails() *V2AssuranceFlowSummaryPostResponseEndpointDetails`

NewV2AssuranceFlowSummaryPostResponseEndpointDetails instantiates a new V2AssuranceFlowSummaryPostResponseEndpointDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssuranceFlowSummaryPostResponseEndpointDetailsWithDefaults

`func NewV2AssuranceFlowSummaryPostResponseEndpointDetailsWithDefaults() *V2AssuranceFlowSummaryPostResponseEndpointDetails`

NewV2AssuranceFlowSummaryPostResponseEndpointDetailsWithDefaults instantiates a new V2AssuranceFlowSummaryPostResponseEndpointDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuits

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetCircuits() []string`

GetCircuits returns the Circuits field if non-nil, zero value otherwise.

### GetCircuitsOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetCircuitsOk() (*[]string, bool)`

GetCircuitsOk returns a tuple with the Circuits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuits

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetCircuits(v []string)`

SetCircuits sets Circuits field to given value.

### HasCircuits

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasCircuits() bool`

HasCircuits returns a boolean if a field has been set.

### GetEdges

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetEdges() []AssuranceEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetEdgesOk() (*[]AssuranceEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetEdges(v []AssuranceEdge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetJitter

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetJitter() V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics`

GetJitter returns the Jitter field if non-nil, zero value otherwise.

### GetJitterOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetJitterOk() (*V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics, bool)`

GetJitterOk returns a tuple with the Jitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJitter

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetJitter(v V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics)`

SetJitter sets Jitter field to given value.

### HasJitter

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasJitter() bool`

HasJitter returns a boolean if a field has been set.

### GetLatency

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetLatency() V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics`

GetLatency returns the Latency field if non-nil, zero value otherwise.

### GetLatencyOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetLatencyOk() (*V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics, bool)`

GetLatencyOk returns a tuple with the Latency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatency

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetLatency(v V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics)`

SetLatency sets Latency field to given value.

### HasLatency

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasLatency() bool`

HasLatency returns a boolean if a field has been set.

### GetLoss

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetLoss() V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics`

GetLoss returns the Loss field if non-nil, zero value otherwise.

### GetLossOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetLossOk() (*V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics, bool)`

GetLossOk returns a tuple with the Loss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoss

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetLoss(v V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics)`

SetLoss sets Loss field to given value.

### HasLoss

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasLoss() bool`

HasLoss returns a boolean if a field has been set.

### GetSite

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetSite() AssuranceSite`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetSiteOk() (*AssuranceSite, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetSite(v AssuranceSite)`

SetSite sets Site field to given value.

### HasSite

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetTotalDownlinkUsage

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetTotalDownlinkUsage() int64`

GetTotalDownlinkUsage returns the TotalDownlinkUsage field if non-nil, zero value otherwise.

### GetTotalDownlinkUsageOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetTotalDownlinkUsageOk() (*int64, bool)`

GetTotalDownlinkUsageOk returns a tuple with the TotalDownlinkUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalDownlinkUsage

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetTotalDownlinkUsage(v int64)`

SetTotalDownlinkUsage sets TotalDownlinkUsage field to given value.

### HasTotalDownlinkUsage

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasTotalDownlinkUsage() bool`

HasTotalDownlinkUsage returns a boolean if a field has been set.

### GetTotalUplinkUsage

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetTotalUplinkUsage() int64`

GetTotalUplinkUsage returns the TotalUplinkUsage field if non-nil, zero value otherwise.

### GetTotalUplinkUsageOk

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) GetTotalUplinkUsageOk() (*int64, bool)`

GetTotalUplinkUsageOk returns a tuple with the TotalUplinkUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUplinkUsage

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) SetTotalUplinkUsage(v int64)`

SetTotalUplinkUsage sets TotalUplinkUsage field to given value.

### HasTotalUplinkUsage

`func (o *V2AssuranceFlowSummaryPostResponseEndpointDetails) HasTotalUplinkUsage() bool`

HasTotalUplinkUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



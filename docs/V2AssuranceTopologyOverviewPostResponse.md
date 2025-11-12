# V2AssuranceTopologyOverviewPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NumApplications** | Pointer to **int32** |  | [optional] 
**NumFlows** | Pointer to **int32** |  | [optional] 
**Topology** | Pointer to [**AssuranceTopology**](AssuranceTopology.md) |  | [optional] 
**TopologyChangeTs** | Pointer to [**[]GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**TrafficRegions** | Pointer to [**[]V2AssuranceTopologyOverviewPostResponseGeoregion**](V2AssuranceTopologyOverviewPostResponseGeoregion.md) |  | [optional] 

## Methods

### NewV2AssuranceTopologyOverviewPostResponse

`func NewV2AssuranceTopologyOverviewPostResponse() *V2AssuranceTopologyOverviewPostResponse`

NewV2AssuranceTopologyOverviewPostResponse instantiates a new V2AssuranceTopologyOverviewPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssuranceTopologyOverviewPostResponseWithDefaults

`func NewV2AssuranceTopologyOverviewPostResponseWithDefaults() *V2AssuranceTopologyOverviewPostResponse`

NewV2AssuranceTopologyOverviewPostResponseWithDefaults instantiates a new V2AssuranceTopologyOverviewPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumApplications

`func (o *V2AssuranceTopologyOverviewPostResponse) GetNumApplications() int32`

GetNumApplications returns the NumApplications field if non-nil, zero value otherwise.

### GetNumApplicationsOk

`func (o *V2AssuranceTopologyOverviewPostResponse) GetNumApplicationsOk() (*int32, bool)`

GetNumApplicationsOk returns a tuple with the NumApplications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumApplications

`func (o *V2AssuranceTopologyOverviewPostResponse) SetNumApplications(v int32)`

SetNumApplications sets NumApplications field to given value.

### HasNumApplications

`func (o *V2AssuranceTopologyOverviewPostResponse) HasNumApplications() bool`

HasNumApplications returns a boolean if a field has been set.

### GetNumFlows

`func (o *V2AssuranceTopologyOverviewPostResponse) GetNumFlows() int32`

GetNumFlows returns the NumFlows field if non-nil, zero value otherwise.

### GetNumFlowsOk

`func (o *V2AssuranceTopologyOverviewPostResponse) GetNumFlowsOk() (*int32, bool)`

GetNumFlowsOk returns a tuple with the NumFlows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumFlows

`func (o *V2AssuranceTopologyOverviewPostResponse) SetNumFlows(v int32)`

SetNumFlows sets NumFlows field to given value.

### HasNumFlows

`func (o *V2AssuranceTopologyOverviewPostResponse) HasNumFlows() bool`

HasNumFlows returns a boolean if a field has been set.

### GetTopology

`func (o *V2AssuranceTopologyOverviewPostResponse) GetTopology() AssuranceTopology`

GetTopology returns the Topology field if non-nil, zero value otherwise.

### GetTopologyOk

`func (o *V2AssuranceTopologyOverviewPostResponse) GetTopologyOk() (*AssuranceTopology, bool)`

GetTopologyOk returns a tuple with the Topology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopology

`func (o *V2AssuranceTopologyOverviewPostResponse) SetTopology(v AssuranceTopology)`

SetTopology sets Topology field to given value.

### HasTopology

`func (o *V2AssuranceTopologyOverviewPostResponse) HasTopology() bool`

HasTopology returns a boolean if a field has been set.

### GetTopologyChangeTs

`func (o *V2AssuranceTopologyOverviewPostResponse) GetTopologyChangeTs() []GoogleProtobufTimestamp`

GetTopologyChangeTs returns the TopologyChangeTs field if non-nil, zero value otherwise.

### GetTopologyChangeTsOk

`func (o *V2AssuranceTopologyOverviewPostResponse) GetTopologyChangeTsOk() (*[]GoogleProtobufTimestamp, bool)`

GetTopologyChangeTsOk returns a tuple with the TopologyChangeTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyChangeTs

`func (o *V2AssuranceTopologyOverviewPostResponse) SetTopologyChangeTs(v []GoogleProtobufTimestamp)`

SetTopologyChangeTs sets TopologyChangeTs field to given value.

### HasTopologyChangeTs

`func (o *V2AssuranceTopologyOverviewPostResponse) HasTopologyChangeTs() bool`

HasTopologyChangeTs returns a boolean if a field has been set.

### GetTrafficRegions

`func (o *V2AssuranceTopologyOverviewPostResponse) GetTrafficRegions() []V2AssuranceTopologyOverviewPostResponseGeoregion`

GetTrafficRegions returns the TrafficRegions field if non-nil, zero value otherwise.

### GetTrafficRegionsOk

`func (o *V2AssuranceTopologyOverviewPostResponse) GetTrafficRegionsOk() (*[]V2AssuranceTopologyOverviewPostResponseGeoregion, bool)`

GetTrafficRegionsOk returns a tuple with the TrafficRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficRegions

`func (o *V2AssuranceTopologyOverviewPostResponse) SetTrafficRegions(v []V2AssuranceTopologyOverviewPostResponseGeoregion)`

SetTrafficRegions sets TrafficRegions field to given value.

### HasTrafficRegions

`func (o *V2AssuranceTopologyOverviewPostResponse) HasTrafficRegions() bool`

HasTrafficRegions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



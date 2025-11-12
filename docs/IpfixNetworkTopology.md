# IpfixNetworkTopology

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CircuitStatus** | Pointer to **map[string]int32** |  | [optional] 
**Delta** | Pointer to [**IpfixNetworkTopologyDelta**](IpfixNetworkTopologyDelta.md) |  | [optional] 
**Edges** | Pointer to [**[]ManaV2ConnectivityGraphEdge**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**Flows** | Pointer to **int32** | Application flow count | [optional] 
**Nodes** | Pointer to [**[]ManaV2ConnectivityGraphNode**](ManaV2ConnectivityGraphNode.md) |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 

## Methods

### NewIpfixNetworkTopology

`func NewIpfixNetworkTopology() *IpfixNetworkTopology`

NewIpfixNetworkTopology instantiates a new IpfixNetworkTopology object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixNetworkTopologyWithDefaults

`func NewIpfixNetworkTopologyWithDefaults() *IpfixNetworkTopology`

NewIpfixNetworkTopologyWithDefaults instantiates a new IpfixNetworkTopology object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuitStatus

`func (o *IpfixNetworkTopology) GetCircuitStatus() map[string]int32`

GetCircuitStatus returns the CircuitStatus field if non-nil, zero value otherwise.

### GetCircuitStatusOk

`func (o *IpfixNetworkTopology) GetCircuitStatusOk() (*map[string]int32, bool)`

GetCircuitStatusOk returns a tuple with the CircuitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitStatus

`func (o *IpfixNetworkTopology) SetCircuitStatus(v map[string]int32)`

SetCircuitStatus sets CircuitStatus field to given value.

### HasCircuitStatus

`func (o *IpfixNetworkTopology) HasCircuitStatus() bool`

HasCircuitStatus returns a boolean if a field has been set.

### GetDelta

`func (o *IpfixNetworkTopology) GetDelta() IpfixNetworkTopologyDelta`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *IpfixNetworkTopology) GetDeltaOk() (*IpfixNetworkTopologyDelta, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *IpfixNetworkTopology) SetDelta(v IpfixNetworkTopologyDelta)`

SetDelta sets Delta field to given value.

### HasDelta

`func (o *IpfixNetworkTopology) HasDelta() bool`

HasDelta returns a boolean if a field has been set.

### GetEdges

`func (o *IpfixNetworkTopology) GetEdges() []ManaV2ConnectivityGraphEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *IpfixNetworkTopology) GetEdgesOk() (*[]ManaV2ConnectivityGraphEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *IpfixNetworkTopology) SetEdges(v []ManaV2ConnectivityGraphEdge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *IpfixNetworkTopology) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetFlows

`func (o *IpfixNetworkTopology) GetFlows() int32`

GetFlows returns the Flows field if non-nil, zero value otherwise.

### GetFlowsOk

`func (o *IpfixNetworkTopology) GetFlowsOk() (*int32, bool)`

GetFlowsOk returns a tuple with the Flows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlows

`func (o *IpfixNetworkTopology) SetFlows(v int32)`

SetFlows sets Flows field to given value.

### HasFlows

`func (o *IpfixNetworkTopology) HasFlows() bool`

HasFlows returns a boolean if a field has been set.

### GetNodes

`func (o *IpfixNetworkTopology) GetNodes() []ManaV2ConnectivityGraphNode`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *IpfixNetworkTopology) GetNodesOk() (*[]ManaV2ConnectivityGraphNode, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *IpfixNetworkTopology) SetNodes(v []ManaV2ConnectivityGraphNode)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *IpfixNetworkTopology) HasNodes() bool`

HasNodes returns a boolean if a field has been set.

### GetTimeWindow

`func (o *IpfixNetworkTopology) GetTimeWindow() StatsmonTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *IpfixNetworkTopology) GetTimeWindowOk() (*StatsmonTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *IpfixNetworkTopology) SetTimeWindow(v StatsmonTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *IpfixNetworkTopology) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



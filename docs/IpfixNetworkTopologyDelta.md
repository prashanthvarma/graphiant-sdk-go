# IpfixNetworkTopologyDelta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EdgesAdded** | Pointer to [**[]ManaV2ConnectivityGraphEdge**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**EdgesDeleted** | Pointer to [**[]ManaV2ConnectivityGraphEdge**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**NodesAdded** | Pointer to [**[]ManaV2ConnectivityGraphNode**](ManaV2ConnectivityGraphNode.md) |  | [optional] 
**NodesDeleted** | Pointer to [**[]ManaV2ConnectivityGraphNode**](ManaV2ConnectivityGraphNode.md) |  | [optional] 

## Methods

### NewIpfixNetworkTopologyDelta

`func NewIpfixNetworkTopologyDelta() *IpfixNetworkTopologyDelta`

NewIpfixNetworkTopologyDelta instantiates a new IpfixNetworkTopologyDelta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixNetworkTopologyDeltaWithDefaults

`func NewIpfixNetworkTopologyDeltaWithDefaults() *IpfixNetworkTopologyDelta`

NewIpfixNetworkTopologyDeltaWithDefaults instantiates a new IpfixNetworkTopologyDelta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdgesAdded

`func (o *IpfixNetworkTopologyDelta) GetEdgesAdded() []ManaV2ConnectivityGraphEdge`

GetEdgesAdded returns the EdgesAdded field if non-nil, zero value otherwise.

### GetEdgesAddedOk

`func (o *IpfixNetworkTopologyDelta) GetEdgesAddedOk() (*[]ManaV2ConnectivityGraphEdge, bool)`

GetEdgesAddedOk returns a tuple with the EdgesAdded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgesAdded

`func (o *IpfixNetworkTopologyDelta) SetEdgesAdded(v []ManaV2ConnectivityGraphEdge)`

SetEdgesAdded sets EdgesAdded field to given value.

### HasEdgesAdded

`func (o *IpfixNetworkTopologyDelta) HasEdgesAdded() bool`

HasEdgesAdded returns a boolean if a field has been set.

### GetEdgesDeleted

`func (o *IpfixNetworkTopologyDelta) GetEdgesDeleted() []ManaV2ConnectivityGraphEdge`

GetEdgesDeleted returns the EdgesDeleted field if non-nil, zero value otherwise.

### GetEdgesDeletedOk

`func (o *IpfixNetworkTopologyDelta) GetEdgesDeletedOk() (*[]ManaV2ConnectivityGraphEdge, bool)`

GetEdgesDeletedOk returns a tuple with the EdgesDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgesDeleted

`func (o *IpfixNetworkTopologyDelta) SetEdgesDeleted(v []ManaV2ConnectivityGraphEdge)`

SetEdgesDeleted sets EdgesDeleted field to given value.

### HasEdgesDeleted

`func (o *IpfixNetworkTopologyDelta) HasEdgesDeleted() bool`

HasEdgesDeleted returns a boolean if a field has been set.

### GetNodesAdded

`func (o *IpfixNetworkTopologyDelta) GetNodesAdded() []ManaV2ConnectivityGraphNode`

GetNodesAdded returns the NodesAdded field if non-nil, zero value otherwise.

### GetNodesAddedOk

`func (o *IpfixNetworkTopologyDelta) GetNodesAddedOk() (*[]ManaV2ConnectivityGraphNode, bool)`

GetNodesAddedOk returns a tuple with the NodesAdded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodesAdded

`func (o *IpfixNetworkTopologyDelta) SetNodesAdded(v []ManaV2ConnectivityGraphNode)`

SetNodesAdded sets NodesAdded field to given value.

### HasNodesAdded

`func (o *IpfixNetworkTopologyDelta) HasNodesAdded() bool`

HasNodesAdded returns a boolean if a field has been set.

### GetNodesDeleted

`func (o *IpfixNetworkTopologyDelta) GetNodesDeleted() []ManaV2ConnectivityGraphNode`

GetNodesDeleted returns the NodesDeleted field if non-nil, zero value otherwise.

### GetNodesDeletedOk

`func (o *IpfixNetworkTopologyDelta) GetNodesDeletedOk() (*[]ManaV2ConnectivityGraphNode, bool)`

GetNodesDeletedOk returns a tuple with the NodesDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodesDeleted

`func (o *IpfixNetworkTopologyDelta) SetNodesDeleted(v []ManaV2ConnectivityGraphNode)`

SetNodesDeleted sets NodesDeleted field to given value.

### HasNodesDeleted

`func (o *IpfixNetworkTopologyDelta) HasNodesDeleted() bool`

HasNodesDeleted returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



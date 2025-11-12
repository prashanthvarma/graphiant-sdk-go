# AssuranceTopology

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Edges** | Pointer to [**[]AssuranceTopologyEdge**](AssuranceTopologyEdge.md) |  | [optional] 
**Nodes** | Pointer to [**[]AssuranceTopologyNode**](AssuranceTopologyNode.md) |  | [optional] 
**Paths** | Pointer to [**[]AssuranceTopologyPath**](AssuranceTopologyPath.md) |  | [optional] 

## Methods

### NewAssuranceTopology

`func NewAssuranceTopology() *AssuranceTopology`

NewAssuranceTopology instantiates a new AssuranceTopology object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceTopologyWithDefaults

`func NewAssuranceTopologyWithDefaults() *AssuranceTopology`

NewAssuranceTopologyWithDefaults instantiates a new AssuranceTopology object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdges

`func (o *AssuranceTopology) GetEdges() []AssuranceTopologyEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *AssuranceTopology) GetEdgesOk() (*[]AssuranceTopologyEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *AssuranceTopology) SetEdges(v []AssuranceTopologyEdge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *AssuranceTopology) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetNodes

`func (o *AssuranceTopology) GetNodes() []AssuranceTopologyNode`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *AssuranceTopology) GetNodesOk() (*[]AssuranceTopologyNode, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *AssuranceTopology) SetNodes(v []AssuranceTopologyNode)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *AssuranceTopology) HasNodes() bool`

HasNodes returns a boolean if a field has been set.

### GetPaths

`func (o *AssuranceTopology) GetPaths() []AssuranceTopologyPath`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *AssuranceTopology) GetPathsOk() (*[]AssuranceTopologyPath, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *AssuranceTopology) SetPaths(v []AssuranceTopologyPath)`

SetPaths sets Paths field to given value.

### HasPaths

`func (o *AssuranceTopology) HasPaths() bool`

HasPaths returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



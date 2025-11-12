# V2SiteSiteIdTopologyPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Edges** | Pointer to [**[]StatsmonV2Edge**](StatsmonV2Edge.md) |  | [optional] 
**Nodes** | Pointer to [**[]StatsmonV2Node**](StatsmonV2Node.md) |  | [optional] 
**Snapshots** | Pointer to [**[]V2SiteSiteIdTopologyPostResponseSnapshot**](V2SiteSiteIdTopologyPostResponseSnapshot.md) |  | [optional] 

## Methods

### NewV2SiteSiteIdTopologyPostResponse

`func NewV2SiteSiteIdTopologyPostResponse() *V2SiteSiteIdTopologyPostResponse`

NewV2SiteSiteIdTopologyPostResponse instantiates a new V2SiteSiteIdTopologyPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2SiteSiteIdTopologyPostResponseWithDefaults

`func NewV2SiteSiteIdTopologyPostResponseWithDefaults() *V2SiteSiteIdTopologyPostResponse`

NewV2SiteSiteIdTopologyPostResponseWithDefaults instantiates a new V2SiteSiteIdTopologyPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdges

`func (o *V2SiteSiteIdTopologyPostResponse) GetEdges() []StatsmonV2Edge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *V2SiteSiteIdTopologyPostResponse) GetEdgesOk() (*[]StatsmonV2Edge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *V2SiteSiteIdTopologyPostResponse) SetEdges(v []StatsmonV2Edge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *V2SiteSiteIdTopologyPostResponse) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetNodes

`func (o *V2SiteSiteIdTopologyPostResponse) GetNodes() []StatsmonV2Node`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *V2SiteSiteIdTopologyPostResponse) GetNodesOk() (*[]StatsmonV2Node, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *V2SiteSiteIdTopologyPostResponse) SetNodes(v []StatsmonV2Node)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *V2SiteSiteIdTopologyPostResponse) HasNodes() bool`

HasNodes returns a boolean if a field has been set.

### GetSnapshots

`func (o *V2SiteSiteIdTopologyPostResponse) GetSnapshots() []V2SiteSiteIdTopologyPostResponseSnapshot`

GetSnapshots returns the Snapshots field if non-nil, zero value otherwise.

### GetSnapshotsOk

`func (o *V2SiteSiteIdTopologyPostResponse) GetSnapshotsOk() (*[]V2SiteSiteIdTopologyPostResponseSnapshot, bool)`

GetSnapshotsOk returns a tuple with the Snapshots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshots

`func (o *V2SiteSiteIdTopologyPostResponse) SetSnapshots(v []V2SiteSiteIdTopologyPostResponseSnapshot)`

SetSnapshots sets Snapshots field to given value.

### HasSnapshots

`func (o *V2SiteSiteIdTopologyPostResponse) HasSnapshots() bool`

HasSnapshots returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



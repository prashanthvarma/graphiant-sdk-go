# V2DeviceDeviceIdTopologyPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Edges** | Pointer to [**[]StatsmonV2Edge**](StatsmonV2Edge.md) |  | [optional] 
**Nodes** | Pointer to [**[]StatsmonV2Node**](StatsmonV2Node.md) |  | [optional] 
**Snapshots** | Pointer to [**[]V2DeviceDeviceIdTopologyPostResponseSnapshot**](V2DeviceDeviceIdTopologyPostResponseSnapshot.md) |  | [optional] 

## Methods

### NewV2DeviceDeviceIdTopologyPostResponse

`func NewV2DeviceDeviceIdTopologyPostResponse() *V2DeviceDeviceIdTopologyPostResponse`

NewV2DeviceDeviceIdTopologyPostResponse instantiates a new V2DeviceDeviceIdTopologyPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2DeviceDeviceIdTopologyPostResponseWithDefaults

`func NewV2DeviceDeviceIdTopologyPostResponseWithDefaults() *V2DeviceDeviceIdTopologyPostResponse`

NewV2DeviceDeviceIdTopologyPostResponseWithDefaults instantiates a new V2DeviceDeviceIdTopologyPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdges

`func (o *V2DeviceDeviceIdTopologyPostResponse) GetEdges() []StatsmonV2Edge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *V2DeviceDeviceIdTopologyPostResponse) GetEdgesOk() (*[]StatsmonV2Edge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *V2DeviceDeviceIdTopologyPostResponse) SetEdges(v []StatsmonV2Edge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *V2DeviceDeviceIdTopologyPostResponse) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetNodes

`func (o *V2DeviceDeviceIdTopologyPostResponse) GetNodes() []StatsmonV2Node`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *V2DeviceDeviceIdTopologyPostResponse) GetNodesOk() (*[]StatsmonV2Node, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *V2DeviceDeviceIdTopologyPostResponse) SetNodes(v []StatsmonV2Node)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *V2DeviceDeviceIdTopologyPostResponse) HasNodes() bool`

HasNodes returns a boolean if a field has been set.

### GetSnapshots

`func (o *V2DeviceDeviceIdTopologyPostResponse) GetSnapshots() []V2DeviceDeviceIdTopologyPostResponseSnapshot`

GetSnapshots returns the Snapshots field if non-nil, zero value otherwise.

### GetSnapshotsOk

`func (o *V2DeviceDeviceIdTopologyPostResponse) GetSnapshotsOk() (*[]V2DeviceDeviceIdTopologyPostResponseSnapshot, bool)`

GetSnapshotsOk returns a tuple with the Snapshots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshots

`func (o *V2DeviceDeviceIdTopologyPostResponse) SetSnapshots(v []V2DeviceDeviceIdTopologyPostResponseSnapshot)`

SetSnapshots sets Snapshots field to given value.

### HasSnapshots

`func (o *V2DeviceDeviceIdTopologyPostResponse) HasSnapshots() bool`

HasSnapshots returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesDeviceIdConnectivityGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Edges** | Pointer to [**[]ManaV2ConnectivityGraphEdge**](ManaV2ConnectivityGraphEdge.md) |  | [optional] 
**Nodes** | Pointer to [**[]ManaV2ConnectivityGraphNode**](ManaV2ConnectivityGraphNode.md) |  | [optional] 

## Methods

### NewV1DevicesDeviceIdConnectivityGetResponse

`func NewV1DevicesDeviceIdConnectivityGetResponse() *V1DevicesDeviceIdConnectivityGetResponse`

NewV1DevicesDeviceIdConnectivityGetResponse instantiates a new V1DevicesDeviceIdConnectivityGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdConnectivityGetResponseWithDefaults

`func NewV1DevicesDeviceIdConnectivityGetResponseWithDefaults() *V1DevicesDeviceIdConnectivityGetResponse`

NewV1DevicesDeviceIdConnectivityGetResponseWithDefaults instantiates a new V1DevicesDeviceIdConnectivityGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdges

`func (o *V1DevicesDeviceIdConnectivityGetResponse) GetEdges() []ManaV2ConnectivityGraphEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *V1DevicesDeviceIdConnectivityGetResponse) GetEdgesOk() (*[]ManaV2ConnectivityGraphEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *V1DevicesDeviceIdConnectivityGetResponse) SetEdges(v []ManaV2ConnectivityGraphEdge)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *V1DevicesDeviceIdConnectivityGetResponse) HasEdges() bool`

HasEdges returns a boolean if a field has been set.

### GetNodes

`func (o *V1DevicesDeviceIdConnectivityGetResponse) GetNodes() []ManaV2ConnectivityGraphNode`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *V1DevicesDeviceIdConnectivityGetResponse) GetNodesOk() (*[]ManaV2ConnectivityGraphNode, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *V1DevicesDeviceIdConnectivityGetResponse) SetNodes(v []ManaV2ConnectivityGraphNode)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *V1DevicesDeviceIdConnectivityGetResponse) HasNodes() bool`

HasNodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



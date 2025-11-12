# AssuranceTopologyNode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | Pointer to **bool** |  | [optional] 
**Location** | Pointer to [**AssuranceGeolocation**](AssuranceGeolocation.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NodeId** | Pointer to **string** |  | [optional] 
**NodeType** | Pointer to **string** |  | [optional] 

## Methods

### NewAssuranceTopologyNode

`func NewAssuranceTopologyNode() *AssuranceTopologyNode`

NewAssuranceTopologyNode instantiates a new AssuranceTopologyNode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceTopologyNodeWithDefaults

`func NewAssuranceTopologyNodeWithDefaults() *AssuranceTopologyNode`

NewAssuranceTopologyNodeWithDefaults instantiates a new AssuranceTopologyNode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *AssuranceTopologyNode) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *AssuranceTopologyNode) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *AssuranceTopologyNode) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *AssuranceTopologyNode) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetLocation

`func (o *AssuranceTopologyNode) GetLocation() AssuranceGeolocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *AssuranceTopologyNode) GetLocationOk() (*AssuranceGeolocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *AssuranceTopologyNode) SetLocation(v AssuranceGeolocation)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *AssuranceTopologyNode) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetName

`func (o *AssuranceTopologyNode) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AssuranceTopologyNode) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AssuranceTopologyNode) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AssuranceTopologyNode) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNodeId

`func (o *AssuranceTopologyNode) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *AssuranceTopologyNode) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *AssuranceTopologyNode) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.

### HasNodeId

`func (o *AssuranceTopologyNode) HasNodeId() bool`

HasNodeId returns a boolean if a field has been set.

### GetNodeType

`func (o *AssuranceTopologyNode) GetNodeType() string`

GetNodeType returns the NodeType field if non-nil, zero value otherwise.

### GetNodeTypeOk

`func (o *AssuranceTopologyNode) GetNodeTypeOk() (*string, bool)`

GetNodeTypeOk returns a tuple with the NodeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeType

`func (o *AssuranceTopologyNode) SetNodeType(v string)`

SetNodeType sets NodeType field to given value.

### HasNodeType

`func (o *AssuranceTopologyNode) HasNodeType() bool`

HasNodeType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



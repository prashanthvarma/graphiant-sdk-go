# AssuranceTopologyEdge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationNodeId** | Pointer to **string** |  | [optional] 
**Performance** | Pointer to [**[]AssuranceTopologyEdgeLinkPerformance**](AssuranceTopologyEdgeLinkPerformance.md) |  | [optional] 
**SourceNodeId** | Pointer to **string** |  | [optional] 

## Methods

### NewAssuranceTopologyEdge

`func NewAssuranceTopologyEdge() *AssuranceTopologyEdge`

NewAssuranceTopologyEdge instantiates a new AssuranceTopologyEdge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceTopologyEdgeWithDefaults

`func NewAssuranceTopologyEdgeWithDefaults() *AssuranceTopologyEdge`

NewAssuranceTopologyEdgeWithDefaults instantiates a new AssuranceTopologyEdge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationNodeId

`func (o *AssuranceTopologyEdge) GetDestinationNodeId() string`

GetDestinationNodeId returns the DestinationNodeId field if non-nil, zero value otherwise.

### GetDestinationNodeIdOk

`func (o *AssuranceTopologyEdge) GetDestinationNodeIdOk() (*string, bool)`

GetDestinationNodeIdOk returns a tuple with the DestinationNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationNodeId

`func (o *AssuranceTopologyEdge) SetDestinationNodeId(v string)`

SetDestinationNodeId sets DestinationNodeId field to given value.

### HasDestinationNodeId

`func (o *AssuranceTopologyEdge) HasDestinationNodeId() bool`

HasDestinationNodeId returns a boolean if a field has been set.

### GetPerformance

`func (o *AssuranceTopologyEdge) GetPerformance() []AssuranceTopologyEdgeLinkPerformance`

GetPerformance returns the Performance field if non-nil, zero value otherwise.

### GetPerformanceOk

`func (o *AssuranceTopologyEdge) GetPerformanceOk() (*[]AssuranceTopologyEdgeLinkPerformance, bool)`

GetPerformanceOk returns a tuple with the Performance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerformance

`func (o *AssuranceTopologyEdge) SetPerformance(v []AssuranceTopologyEdgeLinkPerformance)`

SetPerformance sets Performance field to given value.

### HasPerformance

`func (o *AssuranceTopologyEdge) HasPerformance() bool`

HasPerformance returns a boolean if a field has been set.

### GetSourceNodeId

`func (o *AssuranceTopologyEdge) GetSourceNodeId() string`

GetSourceNodeId returns the SourceNodeId field if non-nil, zero value otherwise.

### GetSourceNodeIdOk

`func (o *AssuranceTopologyEdge) GetSourceNodeIdOk() (*string, bool)`

GetSourceNodeIdOk returns a tuple with the SourceNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNodeId

`func (o *AssuranceTopologyEdge) SetSourceNodeId(v string)`

SetSourceNodeId sets SourceNodeId field to given value.

### HasSourceNodeId

`func (o *AssuranceTopologyEdge) HasSourceNodeId() bool`

HasSourceNodeId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



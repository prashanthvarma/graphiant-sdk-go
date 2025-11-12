# V1FlowsFlowTablePostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CursorRef** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**FlowTable** | Pointer to [**[]IpfixAppFlowTable**](IpfixAppFlowTable.md) |  | [optional] 

## Methods

### NewV1FlowsFlowTablePostResponse

`func NewV1FlowsFlowTablePostResponse() *V1FlowsFlowTablePostResponse`

NewV1FlowsFlowTablePostResponse instantiates a new V1FlowsFlowTablePostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1FlowsFlowTablePostResponseWithDefaults

`func NewV1FlowsFlowTablePostResponseWithDefaults() *V1FlowsFlowTablePostResponse`

NewV1FlowsFlowTablePostResponseWithDefaults instantiates a new V1FlowsFlowTablePostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCursorRef

`func (o *V1FlowsFlowTablePostResponse) GetCursorRef() GoogleProtobufTimestamp`

GetCursorRef returns the CursorRef field if non-nil, zero value otherwise.

### GetCursorRefOk

`func (o *V1FlowsFlowTablePostResponse) GetCursorRefOk() (*GoogleProtobufTimestamp, bool)`

GetCursorRefOk returns a tuple with the CursorRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorRef

`func (o *V1FlowsFlowTablePostResponse) SetCursorRef(v GoogleProtobufTimestamp)`

SetCursorRef sets CursorRef field to given value.

### HasCursorRef

`func (o *V1FlowsFlowTablePostResponse) HasCursorRef() bool`

HasCursorRef returns a boolean if a field has been set.

### GetFlowTable

`func (o *V1FlowsFlowTablePostResponse) GetFlowTable() []IpfixAppFlowTable`

GetFlowTable returns the FlowTable field if non-nil, zero value otherwise.

### GetFlowTableOk

`func (o *V1FlowsFlowTablePostResponse) GetFlowTableOk() (*[]IpfixAppFlowTable, bool)`

GetFlowTableOk returns a tuple with the FlowTable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlowTable

`func (o *V1FlowsFlowTablePostResponse) SetFlowTable(v []IpfixAppFlowTable)`

SetFlowTable sets FlowTable field to given value.

### HasFlowTable

`func (o *V1FlowsFlowTablePostResponse) HasFlowTable() bool`

HasFlowTable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



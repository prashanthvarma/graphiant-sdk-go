# V1EdgesSummaryGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EdgesSummary** | Pointer to [**[]SearchEdgeSummary**](SearchEdgeSummary.md) |  | [optional] 
**IsNewCount** | Pointer to **int32** |  | [optional] 

## Methods

### NewV1EdgesSummaryGetResponse

`func NewV1EdgesSummaryGetResponse() *V1EdgesSummaryGetResponse`

NewV1EdgesSummaryGetResponse instantiates a new V1EdgesSummaryGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EdgesSummaryGetResponseWithDefaults

`func NewV1EdgesSummaryGetResponseWithDefaults() *V1EdgesSummaryGetResponse`

NewV1EdgesSummaryGetResponseWithDefaults instantiates a new V1EdgesSummaryGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdgesSummary

`func (o *V1EdgesSummaryGetResponse) GetEdgesSummary() []SearchEdgeSummary`

GetEdgesSummary returns the EdgesSummary field if non-nil, zero value otherwise.

### GetEdgesSummaryOk

`func (o *V1EdgesSummaryGetResponse) GetEdgesSummaryOk() (*[]SearchEdgeSummary, bool)`

GetEdgesSummaryOk returns a tuple with the EdgesSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgesSummary

`func (o *V1EdgesSummaryGetResponse) SetEdgesSummary(v []SearchEdgeSummary)`

SetEdgesSummary sets EdgesSummary field to given value.

### HasEdgesSummary

`func (o *V1EdgesSummaryGetResponse) HasEdgesSummary() bool`

HasEdgesSummary returns a boolean if a field has been set.

### GetIsNewCount

`func (o *V1EdgesSummaryGetResponse) GetIsNewCount() int32`

GetIsNewCount returns the IsNewCount field if non-nil, zero value otherwise.

### GetIsNewCountOk

`func (o *V1EdgesSummaryGetResponse) GetIsNewCountOk() (*int32, bool)`

GetIsNewCountOk returns a tuple with the IsNewCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNewCount

`func (o *V1EdgesSummaryGetResponse) SetIsNewCount(v int32)`

SetIsNewCount sets IsNewCount field to given value.

### HasIsNewCount

`func (o *V1EdgesSummaryGetResponse) HasIsNewCount() bool`

HasIsNewCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



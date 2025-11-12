# V1SearchGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | Pointer to [**[]SearchSearchResult**](SearchSearchResult.md) |  | [optional] 

## Methods

### NewV1SearchGetResponse

`func NewV1SearchGetResponse() *V1SearchGetResponse`

NewV1SearchGetResponse instantiates a new V1SearchGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1SearchGetResponseWithDefaults

`func NewV1SearchGetResponseWithDefaults() *V1SearchGetResponse`

NewV1SearchGetResponseWithDefaults instantiates a new V1SearchGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *V1SearchGetResponse) GetResults() []SearchSearchResult`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *V1SearchGetResponse) GetResultsOk() (*[]SearchSearchResult, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *V1SearchGetResponse) SetResults(v []SearchSearchResult)`

SetResults sets Results field to given value.

### HasResults

`func (o *V1SearchGetResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



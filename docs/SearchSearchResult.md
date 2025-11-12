# SearchSearchResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Context** | Pointer to **string** | A search context from the SearchContext enum (required) | [optional] 
**Id** | Pointer to **int64** | A search context from the SearchContext enum (required) | [optional] 
**Result** | Pointer to **string** | A search result (required) | [optional] 

## Methods

### NewSearchSearchResult

`func NewSearchSearchResult() *SearchSearchResult`

NewSearchSearchResult instantiates a new SearchSearchResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchSearchResultWithDefaults

`func NewSearchSearchResultWithDefaults() *SearchSearchResult`

NewSearchSearchResultWithDefaults instantiates a new SearchSearchResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContext

`func (o *SearchSearchResult) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *SearchSearchResult) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *SearchSearchResult) SetContext(v string)`

SetContext sets Context field to given value.

### HasContext

`func (o *SearchSearchResult) HasContext() bool`

HasContext returns a boolean if a field has been set.

### GetId

`func (o *SearchSearchResult) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SearchSearchResult) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SearchSearchResult) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *SearchSearchResult) HasId() bool`

HasId returns a boolean if a field has been set.

### GetResult

`func (o *SearchSearchResult) GetResult() string`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *SearchSearchResult) GetResultOk() (*string, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *SearchSearchResult) SetResult(v string)`

SetResult sets Result field to given value.

### HasResult

`func (o *SearchSearchResult) HasResult() bool`

HasResult returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



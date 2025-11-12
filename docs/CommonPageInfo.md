# CommonPageInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** | The page number we are currently on (required) | [optional] 
**EndCursor** | Pointer to **string** | Cursor pointing to the last record on the current page | [optional] 
**HasNextPage** | Pointer to **bool** | An indicator whether there is a page after this one in the resultset based on current position | [optional] 
**HasPrevPage** | Pointer to **bool** | An indicator whether there is a page before this one in the resultset based on current position | [optional] 
**StartCursor** | Pointer to **string** | Cursor pointing to the first record on the current page | [optional] 
**TotalPages** | Pointer to **int32** | The number of pages in the complete resultset based on the current length of the page (required) | [optional] 
**TotalRecords** | Pointer to **int32** | Describes the total number of records in the complete resultset (required) | [optional] 

## Methods

### NewCommonPageInfo

`func NewCommonPageInfo() *CommonPageInfo`

NewCommonPageInfo instantiates a new CommonPageInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCommonPageInfoWithDefaults

`func NewCommonPageInfoWithDefaults() *CommonPageInfo`

NewCommonPageInfoWithDefaults instantiates a new CommonPageInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *CommonPageInfo) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *CommonPageInfo) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *CommonPageInfo) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *CommonPageInfo) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetEndCursor

`func (o *CommonPageInfo) GetEndCursor() string`

GetEndCursor returns the EndCursor field if non-nil, zero value otherwise.

### GetEndCursorOk

`func (o *CommonPageInfo) GetEndCursorOk() (*string, bool)`

GetEndCursorOk returns a tuple with the EndCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndCursor

`func (o *CommonPageInfo) SetEndCursor(v string)`

SetEndCursor sets EndCursor field to given value.

### HasEndCursor

`func (o *CommonPageInfo) HasEndCursor() bool`

HasEndCursor returns a boolean if a field has been set.

### GetHasNextPage

`func (o *CommonPageInfo) GetHasNextPage() bool`

GetHasNextPage returns the HasNextPage field if non-nil, zero value otherwise.

### GetHasNextPageOk

`func (o *CommonPageInfo) GetHasNextPageOk() (*bool, bool)`

GetHasNextPageOk returns a tuple with the HasNextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNextPage

`func (o *CommonPageInfo) SetHasNextPage(v bool)`

SetHasNextPage sets HasNextPage field to given value.

### HasHasNextPage

`func (o *CommonPageInfo) HasHasNextPage() bool`

HasHasNextPage returns a boolean if a field has been set.

### GetHasPrevPage

`func (o *CommonPageInfo) GetHasPrevPage() bool`

GetHasPrevPage returns the HasPrevPage field if non-nil, zero value otherwise.

### GetHasPrevPageOk

`func (o *CommonPageInfo) GetHasPrevPageOk() (*bool, bool)`

GetHasPrevPageOk returns a tuple with the HasPrevPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasPrevPage

`func (o *CommonPageInfo) SetHasPrevPage(v bool)`

SetHasPrevPage sets HasPrevPage field to given value.

### HasHasPrevPage

`func (o *CommonPageInfo) HasHasPrevPage() bool`

HasHasPrevPage returns a boolean if a field has been set.

### GetStartCursor

`func (o *CommonPageInfo) GetStartCursor() string`

GetStartCursor returns the StartCursor field if non-nil, zero value otherwise.

### GetStartCursorOk

`func (o *CommonPageInfo) GetStartCursorOk() (*string, bool)`

GetStartCursorOk returns a tuple with the StartCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartCursor

`func (o *CommonPageInfo) SetStartCursor(v string)`

SetStartCursor sets StartCursor field to given value.

### HasStartCursor

`func (o *CommonPageInfo) HasStartCursor() bool`

HasStartCursor returns a boolean if a field has been set.

### GetTotalPages

`func (o *CommonPageInfo) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *CommonPageInfo) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *CommonPageInfo) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *CommonPageInfo) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetTotalRecords

`func (o *CommonPageInfo) GetTotalRecords() int32`

GetTotalRecords returns the TotalRecords field if non-nil, zero value otherwise.

### GetTotalRecordsOk

`func (o *CommonPageInfo) GetTotalRecordsOk() (*int32, bool)`

GetTotalRecordsOk returns a tuple with the TotalRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRecords

`func (o *CommonPageInfo) SetTotalRecords(v int32)`

SetTotalRecords sets TotalRecords field to given value.

### HasTotalRecords

`func (o *CommonPageInfo) HasTotalRecords() bool`

HasTotalRecords returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



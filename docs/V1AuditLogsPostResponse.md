# V1AuditLogsPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CursorRef** | Pointer to **string** |  | [optional] 
**Histogram** | Pointer to [**[]AuditmonHistogram**](AuditmonHistogram.md) |  | [optional] 
**Logs** | Pointer to [**[]AuditAuditEntry**](AuditAuditEntry.md) |  | [optional] 
**TotalLogs** | Pointer to **int64** |  | [optional] 

## Methods

### NewV1AuditLogsPostResponse

`func NewV1AuditLogsPostResponse() *V1AuditLogsPostResponse`

NewV1AuditLogsPostResponse instantiates a new V1AuditLogsPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuditLogsPostResponseWithDefaults

`func NewV1AuditLogsPostResponseWithDefaults() *V1AuditLogsPostResponse`

NewV1AuditLogsPostResponseWithDefaults instantiates a new V1AuditLogsPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCursorRef

`func (o *V1AuditLogsPostResponse) GetCursorRef() string`

GetCursorRef returns the CursorRef field if non-nil, zero value otherwise.

### GetCursorRefOk

`func (o *V1AuditLogsPostResponse) GetCursorRefOk() (*string, bool)`

GetCursorRefOk returns a tuple with the CursorRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorRef

`func (o *V1AuditLogsPostResponse) SetCursorRef(v string)`

SetCursorRef sets CursorRef field to given value.

### HasCursorRef

`func (o *V1AuditLogsPostResponse) HasCursorRef() bool`

HasCursorRef returns a boolean if a field has been set.

### GetHistogram

`func (o *V1AuditLogsPostResponse) GetHistogram() []AuditmonHistogram`

GetHistogram returns the Histogram field if non-nil, zero value otherwise.

### GetHistogramOk

`func (o *V1AuditLogsPostResponse) GetHistogramOk() (*[]AuditmonHistogram, bool)`

GetHistogramOk returns a tuple with the Histogram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistogram

`func (o *V1AuditLogsPostResponse) SetHistogram(v []AuditmonHistogram)`

SetHistogram sets Histogram field to given value.

### HasHistogram

`func (o *V1AuditLogsPostResponse) HasHistogram() bool`

HasHistogram returns a boolean if a field has been set.

### GetLogs

`func (o *V1AuditLogsPostResponse) GetLogs() []AuditAuditEntry`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *V1AuditLogsPostResponse) GetLogsOk() (*[]AuditAuditEntry, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *V1AuditLogsPostResponse) SetLogs(v []AuditAuditEntry)`

SetLogs sets Logs field to given value.

### HasLogs

`func (o *V1AuditLogsPostResponse) HasLogs() bool`

HasLogs returns a boolean if a field has been set.

### GetTotalLogs

`func (o *V1AuditLogsPostResponse) GetTotalLogs() int64`

GetTotalLogs returns the TotalLogs field if non-nil, zero value otherwise.

### GetTotalLogsOk

`func (o *V1AuditLogsPostResponse) GetTotalLogsOk() (*int64, bool)`

GetTotalLogsOk returns a tuple with the TotalLogs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalLogs

`func (o *V1AuditLogsPostResponse) SetTotalLogs(v int64)`

SetTotalLogs sets TotalLogs field to given value.

### HasTotalLogs

`func (o *V1AuditLogsPostResponse) HasTotalLogs() bool`

HasTotalLogs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



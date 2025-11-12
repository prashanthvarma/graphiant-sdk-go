# V1LogsPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CursorRef** | Pointer to **string** |  | [optional] 
**Histogram** | Pointer to [**[]SyslogmonHistogram**](SyslogmonHistogram.md) |  | [optional] 
**Logs** | Pointer to [**[]SyslogmonLog**](SyslogmonLog.md) |  | [optional] 
**TotalLogs** | Pointer to **int64** |  | [optional] 

## Methods

### NewV1LogsPostResponse

`func NewV1LogsPostResponse() *V1LogsPostResponse`

NewV1LogsPostResponse instantiates a new V1LogsPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1LogsPostResponseWithDefaults

`func NewV1LogsPostResponseWithDefaults() *V1LogsPostResponse`

NewV1LogsPostResponseWithDefaults instantiates a new V1LogsPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCursorRef

`func (o *V1LogsPostResponse) GetCursorRef() string`

GetCursorRef returns the CursorRef field if non-nil, zero value otherwise.

### GetCursorRefOk

`func (o *V1LogsPostResponse) GetCursorRefOk() (*string, bool)`

GetCursorRefOk returns a tuple with the CursorRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorRef

`func (o *V1LogsPostResponse) SetCursorRef(v string)`

SetCursorRef sets CursorRef field to given value.

### HasCursorRef

`func (o *V1LogsPostResponse) HasCursorRef() bool`

HasCursorRef returns a boolean if a field has been set.

### GetHistogram

`func (o *V1LogsPostResponse) GetHistogram() []SyslogmonHistogram`

GetHistogram returns the Histogram field if non-nil, zero value otherwise.

### GetHistogramOk

`func (o *V1LogsPostResponse) GetHistogramOk() (*[]SyslogmonHistogram, bool)`

GetHistogramOk returns a tuple with the Histogram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistogram

`func (o *V1LogsPostResponse) SetHistogram(v []SyslogmonHistogram)`

SetHistogram sets Histogram field to given value.

### HasHistogram

`func (o *V1LogsPostResponse) HasHistogram() bool`

HasHistogram returns a boolean if a field has been set.

### GetLogs

`func (o *V1LogsPostResponse) GetLogs() []SyslogmonLog`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *V1LogsPostResponse) GetLogsOk() (*[]SyslogmonLog, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *V1LogsPostResponse) SetLogs(v []SyslogmonLog)`

SetLogs sets Logs field to given value.

### HasLogs

`func (o *V1LogsPostResponse) HasLogs() bool`

HasLogs returns a boolean if a field has been set.

### GetTotalLogs

`func (o *V1LogsPostResponse) GetTotalLogs() int64`

GetTotalLogs returns the TotalLogs field if non-nil, zero value otherwise.

### GetTotalLogsOk

`func (o *V1LogsPostResponse) GetTotalLogsOk() (*int64, bool)`

GetTotalLogsOk returns a tuple with the TotalLogs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalLogs

`func (o *V1LogsPostResponse) SetTotalLogs(v int64)`

SetTotalLogs sets TotalLogs field to given value.

### HasTotalLogs

`func (o *V1LogsPostResponse) HasTotalLogs() bool`

HasTotalLogs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



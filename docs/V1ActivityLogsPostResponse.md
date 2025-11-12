# V1ActivityLogsPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CursorRef** | Pointer to **string** |  | [optional] 
**Details** | Pointer to [**[]AuditmonActivityDetails**](AuditmonActivityDetails.md) |  | [optional] 
**FilterEntities** | Pointer to [**map[string]V1ActivityLogsPostResponseActivityItems**](V1ActivityLogsPostResponseActivityItems.md) |  | [optional] 
**FilterJobTypes** | Pointer to **[]string** |  | [optional] 
**TotalLogs** | Pointer to **int64** |  | [optional] 

## Methods

### NewV1ActivityLogsPostResponse

`func NewV1ActivityLogsPostResponse() *V1ActivityLogsPostResponse`

NewV1ActivityLogsPostResponse instantiates a new V1ActivityLogsPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ActivityLogsPostResponseWithDefaults

`func NewV1ActivityLogsPostResponseWithDefaults() *V1ActivityLogsPostResponse`

NewV1ActivityLogsPostResponseWithDefaults instantiates a new V1ActivityLogsPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCursorRef

`func (o *V1ActivityLogsPostResponse) GetCursorRef() string`

GetCursorRef returns the CursorRef field if non-nil, zero value otherwise.

### GetCursorRefOk

`func (o *V1ActivityLogsPostResponse) GetCursorRefOk() (*string, bool)`

GetCursorRefOk returns a tuple with the CursorRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorRef

`func (o *V1ActivityLogsPostResponse) SetCursorRef(v string)`

SetCursorRef sets CursorRef field to given value.

### HasCursorRef

`func (o *V1ActivityLogsPostResponse) HasCursorRef() bool`

HasCursorRef returns a boolean if a field has been set.

### GetDetails

`func (o *V1ActivityLogsPostResponse) GetDetails() []AuditmonActivityDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *V1ActivityLogsPostResponse) GetDetailsOk() (*[]AuditmonActivityDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *V1ActivityLogsPostResponse) SetDetails(v []AuditmonActivityDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *V1ActivityLogsPostResponse) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetFilterEntities

`func (o *V1ActivityLogsPostResponse) GetFilterEntities() map[string]V1ActivityLogsPostResponseActivityItems`

GetFilterEntities returns the FilterEntities field if non-nil, zero value otherwise.

### GetFilterEntitiesOk

`func (o *V1ActivityLogsPostResponse) GetFilterEntitiesOk() (*map[string]V1ActivityLogsPostResponseActivityItems, bool)`

GetFilterEntitiesOk returns a tuple with the FilterEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterEntities

`func (o *V1ActivityLogsPostResponse) SetFilterEntities(v map[string]V1ActivityLogsPostResponseActivityItems)`

SetFilterEntities sets FilterEntities field to given value.

### HasFilterEntities

`func (o *V1ActivityLogsPostResponse) HasFilterEntities() bool`

HasFilterEntities returns a boolean if a field has been set.

### GetFilterJobTypes

`func (o *V1ActivityLogsPostResponse) GetFilterJobTypes() []string`

GetFilterJobTypes returns the FilterJobTypes field if non-nil, zero value otherwise.

### GetFilterJobTypesOk

`func (o *V1ActivityLogsPostResponse) GetFilterJobTypesOk() (*[]string, bool)`

GetFilterJobTypesOk returns a tuple with the FilterJobTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterJobTypes

`func (o *V1ActivityLogsPostResponse) SetFilterJobTypes(v []string)`

SetFilterJobTypes sets FilterJobTypes field to given value.

### HasFilterJobTypes

`func (o *V1ActivityLogsPostResponse) HasFilterJobTypes() bool`

HasFilterJobTypes returns a boolean if a field has been set.

### GetTotalLogs

`func (o *V1ActivityLogsPostResponse) GetTotalLogs() int64`

GetTotalLogs returns the TotalLogs field if non-nil, zero value otherwise.

### GetTotalLogsOk

`func (o *V1ActivityLogsPostResponse) GetTotalLogsOk() (*int64, bool)`

GetTotalLogsOk returns a tuple with the TotalLogs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalLogs

`func (o *V1ActivityLogsPostResponse) SetTotalLogs(v int64)`

SetTotalLogs sets TotalLogs field to given value.

### HasTotalLogs

`func (o *V1ActivityLogsPostResponse) HasTotalLogs() bool`

HasTotalLogs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



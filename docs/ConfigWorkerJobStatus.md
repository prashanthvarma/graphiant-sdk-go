# ConfigWorkerJobStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**CreatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**ErrorCount** | Pointer to **int32** |  | [optional] 
**JobId** | Pointer to **int64** |  | [optional] 
**JobState** | Pointer to **string** |  | [optional] 

## Methods

### NewConfigWorkerJobStatus

`func NewConfigWorkerJobStatus() *ConfigWorkerJobStatus`

NewConfigWorkerJobStatus instantiates a new ConfigWorkerJobStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigWorkerJobStatusWithDefaults

`func NewConfigWorkerJobStatusWithDefaults() *ConfigWorkerJobStatus`

NewConfigWorkerJobStatusWithDefaults instantiates a new ConfigWorkerJobStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *ConfigWorkerJobStatus) GetCompletedAt() GoogleProtobufTimestamp`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ConfigWorkerJobStatus) GetCompletedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ConfigWorkerJobStatus) SetCompletedAt(v GoogleProtobufTimestamp)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ConfigWorkerJobStatus) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ConfigWorkerJobStatus) GetCreatedAt() GoogleProtobufTimestamp`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ConfigWorkerJobStatus) GetCreatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ConfigWorkerJobStatus) SetCreatedAt(v GoogleProtobufTimestamp)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ConfigWorkerJobStatus) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetError

`func (o *ConfigWorkerJobStatus) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ConfigWorkerJobStatus) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ConfigWorkerJobStatus) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ConfigWorkerJobStatus) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorCount

`func (o *ConfigWorkerJobStatus) GetErrorCount() int32`

GetErrorCount returns the ErrorCount field if non-nil, zero value otherwise.

### GetErrorCountOk

`func (o *ConfigWorkerJobStatus) GetErrorCountOk() (*int32, bool)`

GetErrorCountOk returns a tuple with the ErrorCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCount

`func (o *ConfigWorkerJobStatus) SetErrorCount(v int32)`

SetErrorCount sets ErrorCount field to given value.

### HasErrorCount

`func (o *ConfigWorkerJobStatus) HasErrorCount() bool`

HasErrorCount returns a boolean if a field has been set.

### GetJobId

`func (o *ConfigWorkerJobStatus) GetJobId() int64`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ConfigWorkerJobStatus) GetJobIdOk() (*int64, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ConfigWorkerJobStatus) SetJobId(v int64)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *ConfigWorkerJobStatus) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetJobState

`func (o *ConfigWorkerJobStatus) GetJobState() string`

GetJobState returns the JobState field if non-nil, zero value otherwise.

### GetJobStateOk

`func (o *ConfigWorkerJobStatus) GetJobStateOk() (*string, bool)`

GetJobStateOk returns a tuple with the JobState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobState

`func (o *ConfigWorkerJobStatus) SetJobState(v string)`

SetJobState sets JobState field to given value.

### HasJobState

`func (o *ConfigWorkerJobStatus) HasJobState() bool`

HasJobState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



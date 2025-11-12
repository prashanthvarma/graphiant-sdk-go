# V1DevicesDeviceIdJobsJobIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**JobStatus** | Pointer to [**ConfigWorkerJobStatus**](ConfigWorkerJobStatus.md) |  | [optional] 

## Methods

### NewV1DevicesDeviceIdJobsJobIdGetResponse

`func NewV1DevicesDeviceIdJobsJobIdGetResponse() *V1DevicesDeviceIdJobsJobIdGetResponse`

NewV1DevicesDeviceIdJobsJobIdGetResponse instantiates a new V1DevicesDeviceIdJobsJobIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdJobsJobIdGetResponseWithDefaults

`func NewV1DevicesDeviceIdJobsJobIdGetResponseWithDefaults() *V1DevicesDeviceIdJobsJobIdGetResponse`

NewV1DevicesDeviceIdJobsJobIdGetResponseWithDefaults instantiates a new V1DevicesDeviceIdJobsJobIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetJobStatus

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) GetJobStatus() ConfigWorkerJobStatus`

GetJobStatus returns the JobStatus field if non-nil, zero value otherwise.

### GetJobStatusOk

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) GetJobStatusOk() (*ConfigWorkerJobStatus, bool)`

GetJobStatusOk returns a tuple with the JobStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobStatus

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) SetJobStatus(v ConfigWorkerJobStatus)`

SetJobStatus sets JobStatus field to given value.

### HasJobStatus

`func (o *V1DevicesDeviceIdJobsJobIdGetResponse) HasJobStatus() bool`

HasJobStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



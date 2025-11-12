# V1DiagnosticPacketcapturePcapIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FailureReason** | Pointer to **string** | Error message if the packet capture generation/upload failed | [optional] 
**FileName** | Pointer to **string** | The PCap file name. | [optional] 
**Status** | Pointer to **string** | The status of the requested packet capture | [optional] 
**UploadProgress** | Pointer to **int32** | upload progress in percentage | [optional] 
**Url** | Pointer to **string** | The URL to download this packet capture. | [optional] 

## Methods

### NewV1DiagnosticPacketcapturePcapIdGetResponse

`func NewV1DiagnosticPacketcapturePcapIdGetResponse() *V1DiagnosticPacketcapturePcapIdGetResponse`

NewV1DiagnosticPacketcapturePcapIdGetResponse instantiates a new V1DiagnosticPacketcapturePcapIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticPacketcapturePcapIdGetResponseWithDefaults

`func NewV1DiagnosticPacketcapturePcapIdGetResponseWithDefaults() *V1DiagnosticPacketcapturePcapIdGetResponse`

NewV1DiagnosticPacketcapturePcapIdGetResponseWithDefaults instantiates a new V1DiagnosticPacketcapturePcapIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFailureReason

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### GetFileName

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) SetFileName(v string)`

SetFileName sets FileName field to given value.

### HasFileName

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) HasFileName() bool`

HasFileName returns a boolean if a field has been set.

### GetStatus

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUploadProgress

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetUploadProgress() int32`

GetUploadProgress returns the UploadProgress field if non-nil, zero value otherwise.

### GetUploadProgressOk

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetUploadProgressOk() (*int32, bool)`

GetUploadProgressOk returns a tuple with the UploadProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadProgress

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) SetUploadProgress(v int32)`

SetUploadProgress sets UploadProgress field to given value.

### HasUploadProgress

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) HasUploadProgress() bool`

HasUploadProgress returns a boolean if a field has been set.

### GetUrl

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *V1DiagnosticPacketcapturePcapIdGetResponse) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



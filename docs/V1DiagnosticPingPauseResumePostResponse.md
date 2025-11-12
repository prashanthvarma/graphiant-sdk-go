# V1DiagnosticPingPauseResumePostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | Pointer to [**DiagnosticToolsDiagnosticResult**](DiagnosticToolsDiagnosticResult.md) |  | [optional] 
**Token** | Pointer to **string** | Token to be sent in subsequent lookup (required) | [optional] 

## Methods

### NewV1DiagnosticPingPauseResumePostResponse

`func NewV1DiagnosticPingPauseResumePostResponse() *V1DiagnosticPingPauseResumePostResponse`

NewV1DiagnosticPingPauseResumePostResponse instantiates a new V1DiagnosticPingPauseResumePostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticPingPauseResumePostResponseWithDefaults

`func NewV1DiagnosticPingPauseResumePostResponseWithDefaults() *V1DiagnosticPingPauseResumePostResponse`

NewV1DiagnosticPingPauseResumePostResponseWithDefaults instantiates a new V1DiagnosticPingPauseResumePostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *V1DiagnosticPingPauseResumePostResponse) GetResult() DiagnosticToolsDiagnosticResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *V1DiagnosticPingPauseResumePostResponse) GetResultOk() (*DiagnosticToolsDiagnosticResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *V1DiagnosticPingPauseResumePostResponse) SetResult(v DiagnosticToolsDiagnosticResult)`

SetResult sets Result field to given value.

### HasResult

`func (o *V1DiagnosticPingPauseResumePostResponse) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetToken

`func (o *V1DiagnosticPingPauseResumePostResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DiagnosticPingPauseResumePostResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DiagnosticPingPauseResumePostResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DiagnosticPingPauseResumePostResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



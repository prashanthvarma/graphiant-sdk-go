# V1DiagnosticPingPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | Pointer to [**DiagnosticToolsDiagnosticResult**](DiagnosticToolsDiagnosticResult.md) |  | [optional] 
**Token** | Pointer to **string** | Token to be sent in subsequent lookup (required) | [optional] 

## Methods

### NewV1DiagnosticPingPostResponse

`func NewV1DiagnosticPingPostResponse() *V1DiagnosticPingPostResponse`

NewV1DiagnosticPingPostResponse instantiates a new V1DiagnosticPingPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticPingPostResponseWithDefaults

`func NewV1DiagnosticPingPostResponseWithDefaults() *V1DiagnosticPingPostResponse`

NewV1DiagnosticPingPostResponseWithDefaults instantiates a new V1DiagnosticPingPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *V1DiagnosticPingPostResponse) GetResult() DiagnosticToolsDiagnosticResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *V1DiagnosticPingPostResponse) GetResultOk() (*DiagnosticToolsDiagnosticResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *V1DiagnosticPingPostResponse) SetResult(v DiagnosticToolsDiagnosticResult)`

SetResult sets Result field to given value.

### HasResult

`func (o *V1DiagnosticPingPostResponse) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetToken

`func (o *V1DiagnosticPingPostResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DiagnosticPingPostResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DiagnosticPingPostResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DiagnosticPingPostResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



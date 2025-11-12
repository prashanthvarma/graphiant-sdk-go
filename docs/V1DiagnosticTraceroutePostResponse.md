# V1DiagnosticTraceroutePostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | Pointer to [**DiagnosticToolsDiagnosticResult**](DiagnosticToolsDiagnosticResult.md) |  | [optional] 
**Token** | Pointer to **string** | Token to be sent in subsequent lookup (required) | [optional] 

## Methods

### NewV1DiagnosticTraceroutePostResponse

`func NewV1DiagnosticTraceroutePostResponse() *V1DiagnosticTraceroutePostResponse`

NewV1DiagnosticTraceroutePostResponse instantiates a new V1DiagnosticTraceroutePostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticTraceroutePostResponseWithDefaults

`func NewV1DiagnosticTraceroutePostResponseWithDefaults() *V1DiagnosticTraceroutePostResponse`

NewV1DiagnosticTraceroutePostResponseWithDefaults instantiates a new V1DiagnosticTraceroutePostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *V1DiagnosticTraceroutePostResponse) GetResult() DiagnosticToolsDiagnosticResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *V1DiagnosticTraceroutePostResponse) GetResultOk() (*DiagnosticToolsDiagnosticResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *V1DiagnosticTraceroutePostResponse) SetResult(v DiagnosticToolsDiagnosticResult)`

SetResult sets Result field to given value.

### HasResult

`func (o *V1DiagnosticTraceroutePostResponse) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetToken

`func (o *V1DiagnosticTraceroutePostResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DiagnosticTraceroutePostResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DiagnosticTraceroutePostResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DiagnosticTraceroutePostResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



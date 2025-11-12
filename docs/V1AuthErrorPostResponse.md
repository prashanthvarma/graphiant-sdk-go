# V1AuthErrorPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Auth** | **bool** |  | 
**Token** | **NullableString** |  | 
**Error** | **string** |  | 

## Methods

### NewV1AuthErrorPostResponse

`func NewV1AuthErrorPostResponse(auth bool, token NullableString, error_ string, ) *V1AuthErrorPostResponse`

NewV1AuthErrorPostResponse instantiates a new V1AuthErrorPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthErrorPostResponseWithDefaults

`func NewV1AuthErrorPostResponseWithDefaults() *V1AuthErrorPostResponse`

NewV1AuthErrorPostResponseWithDefaults instantiates a new V1AuthErrorPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuth

`func (o *V1AuthErrorPostResponse) GetAuth() bool`

GetAuth returns the Auth field if non-nil, zero value otherwise.

### GetAuthOk

`func (o *V1AuthErrorPostResponse) GetAuthOk() (*bool, bool)`

GetAuthOk returns a tuple with the Auth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuth

`func (o *V1AuthErrorPostResponse) SetAuth(v bool)`

SetAuth sets Auth field to given value.


### GetToken

`func (o *V1AuthErrorPostResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1AuthErrorPostResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1AuthErrorPostResponse) SetToken(v string)`

SetToken sets Token field to given value.


### SetTokenNil

`func (o *V1AuthErrorPostResponse) SetTokenNil(b bool)`

 SetTokenNil sets the value for Token to be an explicit nil

### UnsetToken
`func (o *V1AuthErrorPostResponse) UnsetToken()`

UnsetToken ensures that no value is present for Token, not even an explicit nil
### GetError

`func (o *V1AuthErrorPostResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *V1AuthErrorPostResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *V1AuthErrorPostResponse) SetError(v string)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



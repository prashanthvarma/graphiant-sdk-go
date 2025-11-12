# V1AuthMfaPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**MfaType** | **string** |  | 
**Code** | **string** |  | 
**StateToken** | Pointer to **string** |  | [optional] 

## Methods

### NewV1AuthMfaPostRequest

`func NewV1AuthMfaPostRequest(email string, mfaType string, code string, ) *V1AuthMfaPostRequest`

NewV1AuthMfaPostRequest instantiates a new V1AuthMfaPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthMfaPostRequestWithDefaults

`func NewV1AuthMfaPostRequestWithDefaults() *V1AuthMfaPostRequest`

NewV1AuthMfaPostRequestWithDefaults instantiates a new V1AuthMfaPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *V1AuthMfaPostRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *V1AuthMfaPostRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *V1AuthMfaPostRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetMfaType

`func (o *V1AuthMfaPostRequest) GetMfaType() string`

GetMfaType returns the MfaType field if non-nil, zero value otherwise.

### GetMfaTypeOk

`func (o *V1AuthMfaPostRequest) GetMfaTypeOk() (*string, bool)`

GetMfaTypeOk returns a tuple with the MfaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMfaType

`func (o *V1AuthMfaPostRequest) SetMfaType(v string)`

SetMfaType sets MfaType field to given value.


### GetCode

`func (o *V1AuthMfaPostRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *V1AuthMfaPostRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *V1AuthMfaPostRequest) SetCode(v string)`

SetCode sets Code field to given value.


### GetStateToken

`func (o *V1AuthMfaPostRequest) GetStateToken() string`

GetStateToken returns the StateToken field if non-nil, zero value otherwise.

### GetStateTokenOk

`func (o *V1AuthMfaPostRequest) GetStateTokenOk() (*string, bool)`

GetStateTokenOk returns a tuple with the StateToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateToken

`func (o *V1AuthMfaPostRequest) SetStateToken(v string)`

SetStateToken sets StateToken field to given value.

### HasStateToken

`func (o *V1AuthMfaPostRequest) HasStateToken() bool`

HasStateToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



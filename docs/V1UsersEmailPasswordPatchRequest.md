# V1UsersEmailPasswordPatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | **string** | New password for the user | 

## Methods

### NewV1UsersEmailPasswordPatchRequest

`func NewV1UsersEmailPasswordPatchRequest(password string, ) *V1UsersEmailPasswordPatchRequest`

NewV1UsersEmailPasswordPatchRequest instantiates a new V1UsersEmailPasswordPatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UsersEmailPasswordPatchRequestWithDefaults

`func NewV1UsersEmailPasswordPatchRequestWithDefaults() *V1UsersEmailPasswordPatchRequest`

NewV1UsersEmailPasswordPatchRequestWithDefaults instantiates a new V1UsersEmailPasswordPatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *V1UsersEmailPasswordPatchRequest) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *V1UsersEmailPasswordPatchRequest) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *V1UsersEmailPasswordPatchRequest) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1AccountPasswordPatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OldPassword** | **string** |  (required) | 
**Password** | **string** |  (required) | 

## Methods

### NewV1AccountPasswordPatchRequest

`func NewV1AccountPasswordPatchRequest(oldPassword string, password string, ) *V1AccountPasswordPatchRequest`

NewV1AccountPasswordPatchRequest instantiates a new V1AccountPasswordPatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AccountPasswordPatchRequestWithDefaults

`func NewV1AccountPasswordPatchRequestWithDefaults() *V1AccountPasswordPatchRequest`

NewV1AccountPasswordPatchRequestWithDefaults instantiates a new V1AccountPasswordPatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOldPassword

`func (o *V1AccountPasswordPatchRequest) GetOldPassword() string`

GetOldPassword returns the OldPassword field if non-nil, zero value otherwise.

### GetOldPasswordOk

`func (o *V1AccountPasswordPatchRequest) GetOldPasswordOk() (*string, bool)`

GetOldPasswordOk returns a tuple with the OldPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldPassword

`func (o *V1AccountPasswordPatchRequest) SetOldPassword(v string)`

SetOldPassword sets OldPassword field to given value.


### GetPassword

`func (o *V1AccountPasswordPatchRequest) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *V1AccountPasswordPatchRequest) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *V1AccountPasswordPatchRequest) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



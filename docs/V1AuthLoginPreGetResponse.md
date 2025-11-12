# V1AuthLoginPreGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Method** | **string** | Authentication method to use | 
**Email** | **string** | User email address | 
**Iam** | Pointer to **string** | Identity provider name (Azure/Okta) | [optional] 
**RelayState** | Pointer to **string** | State to relay after authentication | [optional] 
**EntryPoint** | Pointer to **string** | SSO entry point URL | [optional] 

## Methods

### NewV1AuthLoginPreGetResponse

`func NewV1AuthLoginPreGetResponse(method string, email string, ) *V1AuthLoginPreGetResponse`

NewV1AuthLoginPreGetResponse instantiates a new V1AuthLoginPreGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthLoginPreGetResponseWithDefaults

`func NewV1AuthLoginPreGetResponseWithDefaults() *V1AuthLoginPreGetResponse`

NewV1AuthLoginPreGetResponseWithDefaults instantiates a new V1AuthLoginPreGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethod

`func (o *V1AuthLoginPreGetResponse) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *V1AuthLoginPreGetResponse) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *V1AuthLoginPreGetResponse) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetEmail

`func (o *V1AuthLoginPreGetResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *V1AuthLoginPreGetResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *V1AuthLoginPreGetResponse) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetIam

`func (o *V1AuthLoginPreGetResponse) GetIam() string`

GetIam returns the Iam field if non-nil, zero value otherwise.

### GetIamOk

`func (o *V1AuthLoginPreGetResponse) GetIamOk() (*string, bool)`

GetIamOk returns a tuple with the Iam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIam

`func (o *V1AuthLoginPreGetResponse) SetIam(v string)`

SetIam sets Iam field to given value.

### HasIam

`func (o *V1AuthLoginPreGetResponse) HasIam() bool`

HasIam returns a boolean if a field has been set.

### GetRelayState

`func (o *V1AuthLoginPreGetResponse) GetRelayState() string`

GetRelayState returns the RelayState field if non-nil, zero value otherwise.

### GetRelayStateOk

`func (o *V1AuthLoginPreGetResponse) GetRelayStateOk() (*string, bool)`

GetRelayStateOk returns a tuple with the RelayState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelayState

`func (o *V1AuthLoginPreGetResponse) SetRelayState(v string)`

SetRelayState sets RelayState field to given value.

### HasRelayState

`func (o *V1AuthLoginPreGetResponse) HasRelayState() bool`

HasRelayState returns a boolean if a field has been set.

### GetEntryPoint

`func (o *V1AuthLoginPreGetResponse) GetEntryPoint() string`

GetEntryPoint returns the EntryPoint field if non-nil, zero value otherwise.

### GetEntryPointOk

`func (o *V1AuthLoginPreGetResponse) GetEntryPointOk() (*string, bool)`

GetEntryPointOk returns a tuple with the EntryPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryPoint

`func (o *V1AuthLoginPreGetResponse) SetEntryPoint(v string)`

SetEntryPoint sets EntryPoint field to given value.

### HasEntryPoint

`func (o *V1AuthLoginPreGetResponse) HasEntryPoint() bool`

HasEntryPoint returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



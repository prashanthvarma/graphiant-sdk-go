# V1UsersGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Users** | Pointer to [**[]CommonUser**](CommonUser.md) |  | [optional] 

## Methods

### NewV1UsersGetResponse

`func NewV1UsersGetResponse() *V1UsersGetResponse`

NewV1UsersGetResponse instantiates a new V1UsersGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UsersGetResponseWithDefaults

`func NewV1UsersGetResponseWithDefaults() *V1UsersGetResponse`

NewV1UsersGetResponseWithDefaults instantiates a new V1UsersGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsers

`func (o *V1UsersGetResponse) GetUsers() []CommonUser`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *V1UsersGetResponse) GetUsersOk() (*[]CommonUser, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *V1UsersGetResponse) SetUsers(v []CommonUser)`

SetUsers sets Users field to given value.

### HasUsers

`func (o *V1UsersGetResponse) HasUsers() bool`

HasUsers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



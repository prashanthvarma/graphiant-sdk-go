# V1AuthPatchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AffectedUsers** | Pointer to **[]string** |  | [optional] 
**AllGroups** | Pointer to **bool** |  | [optional] 

## Methods

### NewV1AuthPatchResponse

`func NewV1AuthPatchResponse() *V1AuthPatchResponse`

NewV1AuthPatchResponse instantiates a new V1AuthPatchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthPatchResponseWithDefaults

`func NewV1AuthPatchResponseWithDefaults() *V1AuthPatchResponse`

NewV1AuthPatchResponseWithDefaults instantiates a new V1AuthPatchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAffectedUsers

`func (o *V1AuthPatchResponse) GetAffectedUsers() []string`

GetAffectedUsers returns the AffectedUsers field if non-nil, zero value otherwise.

### GetAffectedUsersOk

`func (o *V1AuthPatchResponse) GetAffectedUsersOk() (*[]string, bool)`

GetAffectedUsersOk returns a tuple with the AffectedUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffectedUsers

`func (o *V1AuthPatchResponse) SetAffectedUsers(v []string)`

SetAffectedUsers sets AffectedUsers field to given value.

### HasAffectedUsers

`func (o *V1AuthPatchResponse) HasAffectedUsers() bool`

HasAffectedUsers returns a boolean if a field has been set.

### GetAllGroups

`func (o *V1AuthPatchResponse) GetAllGroups() bool`

GetAllGroups returns the AllGroups field if non-nil, zero value otherwise.

### GetAllGroupsOk

`func (o *V1AuthPatchResponse) GetAllGroupsOk() (*bool, bool)`

GetAllGroupsOk returns a tuple with the AllGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllGroups

`func (o *V1AuthPatchResponse) SetAllGroups(v bool)`

SetAllGroups sets AllGroups field to given value.

### HasAllGroups

`func (o *V1AuthPatchResponse) HasAllGroups() bool`

HasAllGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



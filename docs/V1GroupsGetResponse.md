# V1GroupsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groups** | Pointer to [**[]IamGroup**](IamGroup.md) |  | [optional] 

## Methods

### NewV1GroupsGetResponse

`func NewV1GroupsGetResponse() *V1GroupsGetResponse`

NewV1GroupsGetResponse instantiates a new V1GroupsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GroupsGetResponseWithDefaults

`func NewV1GroupsGetResponseWithDefaults() *V1GroupsGetResponse`

NewV1GroupsGetResponseWithDefaults instantiates a new V1GroupsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroups

`func (o *V1GroupsGetResponse) GetGroups() []IamGroup`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *V1GroupsGetResponse) GetGroupsOk() (*[]IamGroup, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *V1GroupsGetResponse) SetGroups(v []IamGroup)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *V1GroupsGetResponse) HasGroups() bool`

HasGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



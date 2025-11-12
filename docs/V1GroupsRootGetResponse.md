# V1GroupsRootGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groups** | Pointer to [**[]IamGroup**](IamGroup.md) |  | [optional] 

## Methods

### NewV1GroupsRootGetResponse

`func NewV1GroupsRootGetResponse() *V1GroupsRootGetResponse`

NewV1GroupsRootGetResponse instantiates a new V1GroupsRootGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GroupsRootGetResponseWithDefaults

`func NewV1GroupsRootGetResponseWithDefaults() *V1GroupsRootGetResponse`

NewV1GroupsRootGetResponseWithDefaults instantiates a new V1GroupsRootGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroups

`func (o *V1GroupsRootGetResponse) GetGroups() []IamGroup`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *V1GroupsRootGetResponse) GetGroupsOk() (*[]IamGroup, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *V1GroupsRootGetResponse) SetGroups(v []IamGroup)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *V1GroupsRootGetResponse) HasGroups() bool`

HasGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AssuranceBucketAppServerList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**App** | Pointer to [**AssuranceBucketAppIdentifier**](AssuranceBucketAppIdentifier.md) |  | [optional] 
**Servers** | Pointer to [**[]AssuranceServer**](AssuranceServer.md) |  | [optional] 

## Methods

### NewAssuranceBucketAppServerList

`func NewAssuranceBucketAppServerList() *AssuranceBucketAppServerList`

NewAssuranceBucketAppServerList instantiates a new AssuranceBucketAppServerList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceBucketAppServerListWithDefaults

`func NewAssuranceBucketAppServerListWithDefaults() *AssuranceBucketAppServerList`

NewAssuranceBucketAppServerListWithDefaults instantiates a new AssuranceBucketAppServerList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApp

`func (o *AssuranceBucketAppServerList) GetApp() AssuranceBucketAppIdentifier`

GetApp returns the App field if non-nil, zero value otherwise.

### GetAppOk

`func (o *AssuranceBucketAppServerList) GetAppOk() (*AssuranceBucketAppIdentifier, bool)`

GetAppOk returns a tuple with the App field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApp

`func (o *AssuranceBucketAppServerList) SetApp(v AssuranceBucketAppIdentifier)`

SetApp sets App field to given value.

### HasApp

`func (o *AssuranceBucketAppServerList) HasApp() bool`

HasApp returns a boolean if a field has been set.

### GetServers

`func (o *AssuranceBucketAppServerList) GetServers() []AssuranceServer`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *AssuranceBucketAppServerList) GetServersOk() (*[]AssuranceServer, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *AssuranceBucketAppServerList) SetServers(v []AssuranceServer)`

SetServers sets Servers field to given value.

### HasServers

`func (o *AssuranceBucketAppServerList) HasServers() bool`

HasServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



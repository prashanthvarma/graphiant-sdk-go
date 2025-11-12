# AssuranceBucketAppServerChangesList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddedServers** | Pointer to [**[]AssuranceServer**](AssuranceServer.md) |  | [optional] 
**App** | Pointer to [**AssuranceBucketAppIdentifier**](AssuranceBucketAppIdentifier.md) |  | [optional] 
**RemovedServers** | Pointer to [**[]AssuranceServer**](AssuranceServer.md) |  | [optional] 

## Methods

### NewAssuranceBucketAppServerChangesList

`func NewAssuranceBucketAppServerChangesList() *AssuranceBucketAppServerChangesList`

NewAssuranceBucketAppServerChangesList instantiates a new AssuranceBucketAppServerChangesList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceBucketAppServerChangesListWithDefaults

`func NewAssuranceBucketAppServerChangesListWithDefaults() *AssuranceBucketAppServerChangesList`

NewAssuranceBucketAppServerChangesListWithDefaults instantiates a new AssuranceBucketAppServerChangesList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddedServers

`func (o *AssuranceBucketAppServerChangesList) GetAddedServers() []AssuranceServer`

GetAddedServers returns the AddedServers field if non-nil, zero value otherwise.

### GetAddedServersOk

`func (o *AssuranceBucketAppServerChangesList) GetAddedServersOk() (*[]AssuranceServer, bool)`

GetAddedServersOk returns a tuple with the AddedServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddedServers

`func (o *AssuranceBucketAppServerChangesList) SetAddedServers(v []AssuranceServer)`

SetAddedServers sets AddedServers field to given value.

### HasAddedServers

`func (o *AssuranceBucketAppServerChangesList) HasAddedServers() bool`

HasAddedServers returns a boolean if a field has been set.

### GetApp

`func (o *AssuranceBucketAppServerChangesList) GetApp() AssuranceBucketAppIdentifier`

GetApp returns the App field if non-nil, zero value otherwise.

### GetAppOk

`func (o *AssuranceBucketAppServerChangesList) GetAppOk() (*AssuranceBucketAppIdentifier, bool)`

GetAppOk returns a tuple with the App field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApp

`func (o *AssuranceBucketAppServerChangesList) SetApp(v AssuranceBucketAppIdentifier)`

SetApp sets App field to given value.

### HasApp

`func (o *AssuranceBucketAppServerChangesList) HasApp() bool`

HasApp returns a boolean if a field has been set.

### GetRemovedServers

`func (o *AssuranceBucketAppServerChangesList) GetRemovedServers() []AssuranceServer`

GetRemovedServers returns the RemovedServers field if non-nil, zero value otherwise.

### GetRemovedServersOk

`func (o *AssuranceBucketAppServerChangesList) GetRemovedServersOk() (*[]AssuranceServer, bool)`

GetRemovedServersOk returns a tuple with the RemovedServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovedServers

`func (o *AssuranceBucketAppServerChangesList) SetRemovedServers(v []AssuranceServer)`

SetRemovedServers sets RemovedServers field to given value.

### HasRemovedServers

`func (o *AssuranceBucketAppServerChangesList) HasRemovedServers() bool`

HasRemovedServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



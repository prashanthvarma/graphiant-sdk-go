# ManaV2BucketApp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BucketId** | Pointer to **int32** |  | [optional] 
**BuiltinAppId** | Pointer to **int64** |  | [optional] 
**CustomAppId** | Pointer to **int64** |  | [optional] 
**IsDomain** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Servers** | Pointer to [**[]ManaV2BucketAppServer**](ManaV2BucketAppServer.md) |  | [optional] 
**UseAllServers** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2BucketApp

`func NewManaV2BucketApp() *ManaV2BucketApp`

NewManaV2BucketApp instantiates a new ManaV2BucketApp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BucketAppWithDefaults

`func NewManaV2BucketAppWithDefaults() *ManaV2BucketApp`

NewManaV2BucketAppWithDefaults instantiates a new ManaV2BucketApp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBucketId

`func (o *ManaV2BucketApp) GetBucketId() int32`

GetBucketId returns the BucketId field if non-nil, zero value otherwise.

### GetBucketIdOk

`func (o *ManaV2BucketApp) GetBucketIdOk() (*int32, bool)`

GetBucketIdOk returns a tuple with the BucketId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketId

`func (o *ManaV2BucketApp) SetBucketId(v int32)`

SetBucketId sets BucketId field to given value.

### HasBucketId

`func (o *ManaV2BucketApp) HasBucketId() bool`

HasBucketId returns a boolean if a field has been set.

### GetBuiltinAppId

`func (o *ManaV2BucketApp) GetBuiltinAppId() int64`

GetBuiltinAppId returns the BuiltinAppId field if non-nil, zero value otherwise.

### GetBuiltinAppIdOk

`func (o *ManaV2BucketApp) GetBuiltinAppIdOk() (*int64, bool)`

GetBuiltinAppIdOk returns a tuple with the BuiltinAppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuiltinAppId

`func (o *ManaV2BucketApp) SetBuiltinAppId(v int64)`

SetBuiltinAppId sets BuiltinAppId field to given value.

### HasBuiltinAppId

`func (o *ManaV2BucketApp) HasBuiltinAppId() bool`

HasBuiltinAppId returns a boolean if a field has been set.

### GetCustomAppId

`func (o *ManaV2BucketApp) GetCustomAppId() int64`

GetCustomAppId returns the CustomAppId field if non-nil, zero value otherwise.

### GetCustomAppIdOk

`func (o *ManaV2BucketApp) GetCustomAppIdOk() (*int64, bool)`

GetCustomAppIdOk returns a tuple with the CustomAppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomAppId

`func (o *ManaV2BucketApp) SetCustomAppId(v int64)`

SetCustomAppId sets CustomAppId field to given value.

### HasCustomAppId

`func (o *ManaV2BucketApp) HasCustomAppId() bool`

HasCustomAppId returns a boolean if a field has been set.

### GetIsDomain

`func (o *ManaV2BucketApp) GetIsDomain() bool`

GetIsDomain returns the IsDomain field if non-nil, zero value otherwise.

### GetIsDomainOk

`func (o *ManaV2BucketApp) GetIsDomainOk() (*bool, bool)`

GetIsDomainOk returns a tuple with the IsDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDomain

`func (o *ManaV2BucketApp) SetIsDomain(v bool)`

SetIsDomain sets IsDomain field to given value.

### HasIsDomain

`func (o *ManaV2BucketApp) HasIsDomain() bool`

HasIsDomain returns a boolean if a field has been set.

### GetName

`func (o *ManaV2BucketApp) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2BucketApp) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2BucketApp) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2BucketApp) HasName() bool`

HasName returns a boolean if a field has been set.

### GetServers

`func (o *ManaV2BucketApp) GetServers() []ManaV2BucketAppServer`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *ManaV2BucketApp) GetServersOk() (*[]ManaV2BucketAppServer, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *ManaV2BucketApp) SetServers(v []ManaV2BucketAppServer)`

SetServers sets Servers field to given value.

### HasServers

`func (o *ManaV2BucketApp) HasServers() bool`

HasServers returns a boolean if a field has been set.

### GetUseAllServers

`func (o *ManaV2BucketApp) GetUseAllServers() bool`

GetUseAllServers returns the UseAllServers field if non-nil, zero value otherwise.

### GetUseAllServersOk

`func (o *ManaV2BucketApp) GetUseAllServersOk() (*bool, bool)`

GetUseAllServersOk returns a tuple with the UseAllServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseAllServers

`func (o *ManaV2BucketApp) SetUseAllServers(v bool)`

SetUseAllServers sets UseAllServers field to given value.

### HasUseAllServers

`func (o *ManaV2BucketApp) HasUseAllServers() bool`

HasUseAllServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



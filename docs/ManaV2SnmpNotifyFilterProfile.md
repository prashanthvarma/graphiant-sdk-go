# ManaV2SnmpNotifyFilterProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** |  | [optional] 
**IncludeExcludeList** | Pointer to [**[]ManaV2NotifyFilterProfileInclude**](ManaV2NotifyFilterProfileInclude.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SnmpNotifyFilterProfile

`func NewManaV2SnmpNotifyFilterProfile() *ManaV2SnmpNotifyFilterProfile`

NewManaV2SnmpNotifyFilterProfile instantiates a new ManaV2SnmpNotifyFilterProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpNotifyFilterProfileWithDefaults

`func NewManaV2SnmpNotifyFilterProfileWithDefaults() *ManaV2SnmpNotifyFilterProfile`

NewManaV2SnmpNotifyFilterProfileWithDefaults instantiates a new ManaV2SnmpNotifyFilterProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManaV2SnmpNotifyFilterProfile) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2SnmpNotifyFilterProfile) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2SnmpNotifyFilterProfile) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2SnmpNotifyFilterProfile) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIncludeExcludeList

`func (o *ManaV2SnmpNotifyFilterProfile) GetIncludeExcludeList() []ManaV2NotifyFilterProfileInclude`

GetIncludeExcludeList returns the IncludeExcludeList field if non-nil, zero value otherwise.

### GetIncludeExcludeListOk

`func (o *ManaV2SnmpNotifyFilterProfile) GetIncludeExcludeListOk() (*[]ManaV2NotifyFilterProfileInclude, bool)`

GetIncludeExcludeListOk returns a tuple with the IncludeExcludeList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeExcludeList

`func (o *ManaV2SnmpNotifyFilterProfile) SetIncludeExcludeList(v []ManaV2NotifyFilterProfileInclude)`

SetIncludeExcludeList sets IncludeExcludeList field to given value.

### HasIncludeExcludeList

`func (o *ManaV2SnmpNotifyFilterProfile) HasIncludeExcludeList() bool`

HasIncludeExcludeList returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SnmpNotifyFilterProfile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SnmpNotifyFilterProfile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SnmpNotifyFilterProfile) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SnmpNotifyFilterProfile) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2SnmpNotifyFilterProfileConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IncludeExcludeList** | Pointer to [**map[string]ManaV2NotifyFilterProfileIncludeConfig**](ManaV2NotifyFilterProfileIncludeConfig.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SnmpNotifyFilterProfileConfig

`func NewManaV2SnmpNotifyFilterProfileConfig() *ManaV2SnmpNotifyFilterProfileConfig`

NewManaV2SnmpNotifyFilterProfileConfig instantiates a new ManaV2SnmpNotifyFilterProfileConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpNotifyFilterProfileConfigWithDefaults

`func NewManaV2SnmpNotifyFilterProfileConfigWithDefaults() *ManaV2SnmpNotifyFilterProfileConfig`

NewManaV2SnmpNotifyFilterProfileConfigWithDefaults instantiates a new ManaV2SnmpNotifyFilterProfileConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIncludeExcludeList

`func (o *ManaV2SnmpNotifyFilterProfileConfig) GetIncludeExcludeList() map[string]ManaV2NotifyFilterProfileIncludeConfig`

GetIncludeExcludeList returns the IncludeExcludeList field if non-nil, zero value otherwise.

### GetIncludeExcludeListOk

`func (o *ManaV2SnmpNotifyFilterProfileConfig) GetIncludeExcludeListOk() (*map[string]ManaV2NotifyFilterProfileIncludeConfig, bool)`

GetIncludeExcludeListOk returns a tuple with the IncludeExcludeList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeExcludeList

`func (o *ManaV2SnmpNotifyFilterProfileConfig) SetIncludeExcludeList(v map[string]ManaV2NotifyFilterProfileIncludeConfig)`

SetIncludeExcludeList sets IncludeExcludeList field to given value.

### HasIncludeExcludeList

`func (o *ManaV2SnmpNotifyFilterProfileConfig) HasIncludeExcludeList() bool`

HasIncludeExcludeList returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SnmpNotifyFilterProfileConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SnmpNotifyFilterProfileConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SnmpNotifyFilterProfileConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SnmpNotifyFilterProfileConfig) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



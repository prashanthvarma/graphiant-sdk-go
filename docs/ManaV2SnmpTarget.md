# ManaV2SnmpTarget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Community** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NotifyFilterProfile** | Pointer to **string** |  | [optional] 
**NotifyType** | Pointer to **string** |  | [optional] 
**SourceIp** | Pointer to **string** |  | [optional] 
**TargetIp** | Pointer to **string** |  | [optional] 
**TargetType** | Pointer to **string** |  | [optional] 
**UsmSecurityLevel** | Pointer to **string** |  | [optional] 
**UsmUserName** | Pointer to **string** |  | [optional] 
**VrfName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SnmpTarget

`func NewManaV2SnmpTarget() *ManaV2SnmpTarget`

NewManaV2SnmpTarget instantiates a new ManaV2SnmpTarget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpTargetWithDefaults

`func NewManaV2SnmpTargetWithDefaults() *ManaV2SnmpTarget`

NewManaV2SnmpTargetWithDefaults instantiates a new ManaV2SnmpTarget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommunity

`func (o *ManaV2SnmpTarget) GetCommunity() string`

GetCommunity returns the Community field if non-nil, zero value otherwise.

### GetCommunityOk

`func (o *ManaV2SnmpTarget) GetCommunityOk() (*string, bool)`

GetCommunityOk returns a tuple with the Community field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunity

`func (o *ManaV2SnmpTarget) SetCommunity(v string)`

SetCommunity sets Community field to given value.

### HasCommunity

`func (o *ManaV2SnmpTarget) HasCommunity() bool`

HasCommunity returns a boolean if a field has been set.

### GetId

`func (o *ManaV2SnmpTarget) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2SnmpTarget) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2SnmpTarget) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2SnmpTarget) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SnmpTarget) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SnmpTarget) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SnmpTarget) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SnmpTarget) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotifyFilterProfile

`func (o *ManaV2SnmpTarget) GetNotifyFilterProfile() string`

GetNotifyFilterProfile returns the NotifyFilterProfile field if non-nil, zero value otherwise.

### GetNotifyFilterProfileOk

`func (o *ManaV2SnmpTarget) GetNotifyFilterProfileOk() (*string, bool)`

GetNotifyFilterProfileOk returns a tuple with the NotifyFilterProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyFilterProfile

`func (o *ManaV2SnmpTarget) SetNotifyFilterProfile(v string)`

SetNotifyFilterProfile sets NotifyFilterProfile field to given value.

### HasNotifyFilterProfile

`func (o *ManaV2SnmpTarget) HasNotifyFilterProfile() bool`

HasNotifyFilterProfile returns a boolean if a field has been set.

### GetNotifyType

`func (o *ManaV2SnmpTarget) GetNotifyType() string`

GetNotifyType returns the NotifyType field if non-nil, zero value otherwise.

### GetNotifyTypeOk

`func (o *ManaV2SnmpTarget) GetNotifyTypeOk() (*string, bool)`

GetNotifyTypeOk returns a tuple with the NotifyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyType

`func (o *ManaV2SnmpTarget) SetNotifyType(v string)`

SetNotifyType sets NotifyType field to given value.

### HasNotifyType

`func (o *ManaV2SnmpTarget) HasNotifyType() bool`

HasNotifyType returns a boolean if a field has been set.

### GetSourceIp

`func (o *ManaV2SnmpTarget) GetSourceIp() string`

GetSourceIp returns the SourceIp field if non-nil, zero value otherwise.

### GetSourceIpOk

`func (o *ManaV2SnmpTarget) GetSourceIpOk() (*string, bool)`

GetSourceIpOk returns a tuple with the SourceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceIp

`func (o *ManaV2SnmpTarget) SetSourceIp(v string)`

SetSourceIp sets SourceIp field to given value.

### HasSourceIp

`func (o *ManaV2SnmpTarget) HasSourceIp() bool`

HasSourceIp returns a boolean if a field has been set.

### GetTargetIp

`func (o *ManaV2SnmpTarget) GetTargetIp() string`

GetTargetIp returns the TargetIp field if non-nil, zero value otherwise.

### GetTargetIpOk

`func (o *ManaV2SnmpTarget) GetTargetIpOk() (*string, bool)`

GetTargetIpOk returns a tuple with the TargetIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetIp

`func (o *ManaV2SnmpTarget) SetTargetIp(v string)`

SetTargetIp sets TargetIp field to given value.

### HasTargetIp

`func (o *ManaV2SnmpTarget) HasTargetIp() bool`

HasTargetIp returns a boolean if a field has been set.

### GetTargetType

`func (o *ManaV2SnmpTarget) GetTargetType() string`

GetTargetType returns the TargetType field if non-nil, zero value otherwise.

### GetTargetTypeOk

`func (o *ManaV2SnmpTarget) GetTargetTypeOk() (*string, bool)`

GetTargetTypeOk returns a tuple with the TargetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetType

`func (o *ManaV2SnmpTarget) SetTargetType(v string)`

SetTargetType sets TargetType field to given value.

### HasTargetType

`func (o *ManaV2SnmpTarget) HasTargetType() bool`

HasTargetType returns a boolean if a field has been set.

### GetUsmSecurityLevel

`func (o *ManaV2SnmpTarget) GetUsmSecurityLevel() string`

GetUsmSecurityLevel returns the UsmSecurityLevel field if non-nil, zero value otherwise.

### GetUsmSecurityLevelOk

`func (o *ManaV2SnmpTarget) GetUsmSecurityLevelOk() (*string, bool)`

GetUsmSecurityLevelOk returns a tuple with the UsmSecurityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmSecurityLevel

`func (o *ManaV2SnmpTarget) SetUsmSecurityLevel(v string)`

SetUsmSecurityLevel sets UsmSecurityLevel field to given value.

### HasUsmSecurityLevel

`func (o *ManaV2SnmpTarget) HasUsmSecurityLevel() bool`

HasUsmSecurityLevel returns a boolean if a field has been set.

### GetUsmUserName

`func (o *ManaV2SnmpTarget) GetUsmUserName() string`

GetUsmUserName returns the UsmUserName field if non-nil, zero value otherwise.

### GetUsmUserNameOk

`func (o *ManaV2SnmpTarget) GetUsmUserNameOk() (*string, bool)`

GetUsmUserNameOk returns a tuple with the UsmUserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmUserName

`func (o *ManaV2SnmpTarget) SetUsmUserName(v string)`

SetUsmUserName sets UsmUserName field to given value.

### HasUsmUserName

`func (o *ManaV2SnmpTarget) HasUsmUserName() bool`

HasUsmUserName returns a boolean if a field has been set.

### GetVrfName

`func (o *ManaV2SnmpTarget) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *ManaV2SnmpTarget) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *ManaV2SnmpTarget) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *ManaV2SnmpTarget) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



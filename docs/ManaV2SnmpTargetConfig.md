# ManaV2SnmpTargetConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Community** | Pointer to **string** |  | [optional] 
**LanSegment** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NotifyFilterProfile** | Pointer to **string** |  | [optional] 
**NotifyType** | Pointer to **string** |  | [optional] 
**SourceIp** | Pointer to **string** |  | [optional] 
**TargetIp** | Pointer to **string** |  | [optional] 
**TargetType** | Pointer to **string** |  | [optional] 
**UsmSecurityLevel** | Pointer to **string** |  | [optional] 
**UsmUserName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SnmpTargetConfig

`func NewManaV2SnmpTargetConfig() *ManaV2SnmpTargetConfig`

NewManaV2SnmpTargetConfig instantiates a new ManaV2SnmpTargetConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpTargetConfigWithDefaults

`func NewManaV2SnmpTargetConfigWithDefaults() *ManaV2SnmpTargetConfig`

NewManaV2SnmpTargetConfigWithDefaults instantiates a new ManaV2SnmpTargetConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommunity

`func (o *ManaV2SnmpTargetConfig) GetCommunity() string`

GetCommunity returns the Community field if non-nil, zero value otherwise.

### GetCommunityOk

`func (o *ManaV2SnmpTargetConfig) GetCommunityOk() (*string, bool)`

GetCommunityOk returns a tuple with the Community field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunity

`func (o *ManaV2SnmpTargetConfig) SetCommunity(v string)`

SetCommunity sets Community field to given value.

### HasCommunity

`func (o *ManaV2SnmpTargetConfig) HasCommunity() bool`

HasCommunity returns a boolean if a field has been set.

### GetLanSegment

`func (o *ManaV2SnmpTargetConfig) GetLanSegment() string`

GetLanSegment returns the LanSegment field if non-nil, zero value otherwise.

### GetLanSegmentOk

`func (o *ManaV2SnmpTargetConfig) GetLanSegmentOk() (*string, bool)`

GetLanSegmentOk returns a tuple with the LanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegment

`func (o *ManaV2SnmpTargetConfig) SetLanSegment(v string)`

SetLanSegment sets LanSegment field to given value.

### HasLanSegment

`func (o *ManaV2SnmpTargetConfig) HasLanSegment() bool`

HasLanSegment returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SnmpTargetConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SnmpTargetConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SnmpTargetConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SnmpTargetConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotifyFilterProfile

`func (o *ManaV2SnmpTargetConfig) GetNotifyFilterProfile() string`

GetNotifyFilterProfile returns the NotifyFilterProfile field if non-nil, zero value otherwise.

### GetNotifyFilterProfileOk

`func (o *ManaV2SnmpTargetConfig) GetNotifyFilterProfileOk() (*string, bool)`

GetNotifyFilterProfileOk returns a tuple with the NotifyFilterProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyFilterProfile

`func (o *ManaV2SnmpTargetConfig) SetNotifyFilterProfile(v string)`

SetNotifyFilterProfile sets NotifyFilterProfile field to given value.

### HasNotifyFilterProfile

`func (o *ManaV2SnmpTargetConfig) HasNotifyFilterProfile() bool`

HasNotifyFilterProfile returns a boolean if a field has been set.

### GetNotifyType

`func (o *ManaV2SnmpTargetConfig) GetNotifyType() string`

GetNotifyType returns the NotifyType field if non-nil, zero value otherwise.

### GetNotifyTypeOk

`func (o *ManaV2SnmpTargetConfig) GetNotifyTypeOk() (*string, bool)`

GetNotifyTypeOk returns a tuple with the NotifyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyType

`func (o *ManaV2SnmpTargetConfig) SetNotifyType(v string)`

SetNotifyType sets NotifyType field to given value.

### HasNotifyType

`func (o *ManaV2SnmpTargetConfig) HasNotifyType() bool`

HasNotifyType returns a boolean if a field has been set.

### GetSourceIp

`func (o *ManaV2SnmpTargetConfig) GetSourceIp() string`

GetSourceIp returns the SourceIp field if non-nil, zero value otherwise.

### GetSourceIpOk

`func (o *ManaV2SnmpTargetConfig) GetSourceIpOk() (*string, bool)`

GetSourceIpOk returns a tuple with the SourceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceIp

`func (o *ManaV2SnmpTargetConfig) SetSourceIp(v string)`

SetSourceIp sets SourceIp field to given value.

### HasSourceIp

`func (o *ManaV2SnmpTargetConfig) HasSourceIp() bool`

HasSourceIp returns a boolean if a field has been set.

### GetTargetIp

`func (o *ManaV2SnmpTargetConfig) GetTargetIp() string`

GetTargetIp returns the TargetIp field if non-nil, zero value otherwise.

### GetTargetIpOk

`func (o *ManaV2SnmpTargetConfig) GetTargetIpOk() (*string, bool)`

GetTargetIpOk returns a tuple with the TargetIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetIp

`func (o *ManaV2SnmpTargetConfig) SetTargetIp(v string)`

SetTargetIp sets TargetIp field to given value.

### HasTargetIp

`func (o *ManaV2SnmpTargetConfig) HasTargetIp() bool`

HasTargetIp returns a boolean if a field has been set.

### GetTargetType

`func (o *ManaV2SnmpTargetConfig) GetTargetType() string`

GetTargetType returns the TargetType field if non-nil, zero value otherwise.

### GetTargetTypeOk

`func (o *ManaV2SnmpTargetConfig) GetTargetTypeOk() (*string, bool)`

GetTargetTypeOk returns a tuple with the TargetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetType

`func (o *ManaV2SnmpTargetConfig) SetTargetType(v string)`

SetTargetType sets TargetType field to given value.

### HasTargetType

`func (o *ManaV2SnmpTargetConfig) HasTargetType() bool`

HasTargetType returns a boolean if a field has been set.

### GetUsmSecurityLevel

`func (o *ManaV2SnmpTargetConfig) GetUsmSecurityLevel() string`

GetUsmSecurityLevel returns the UsmSecurityLevel field if non-nil, zero value otherwise.

### GetUsmSecurityLevelOk

`func (o *ManaV2SnmpTargetConfig) GetUsmSecurityLevelOk() (*string, bool)`

GetUsmSecurityLevelOk returns a tuple with the UsmSecurityLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmSecurityLevel

`func (o *ManaV2SnmpTargetConfig) SetUsmSecurityLevel(v string)`

SetUsmSecurityLevel sets UsmSecurityLevel field to given value.

### HasUsmSecurityLevel

`func (o *ManaV2SnmpTargetConfig) HasUsmSecurityLevel() bool`

HasUsmSecurityLevel returns a boolean if a field has been set.

### GetUsmUserName

`func (o *ManaV2SnmpTargetConfig) GetUsmUserName() string`

GetUsmUserName returns the UsmUserName field if non-nil, zero value otherwise.

### GetUsmUserNameOk

`func (o *ManaV2SnmpTargetConfig) GetUsmUserNameOk() (*string, bool)`

GetUsmUserNameOk returns a tuple with the UsmUserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmUserName

`func (o *ManaV2SnmpTargetConfig) SetUsmUserName(v string)`

SetUsmUserName sets UsmUserName field to given value.

### HasUsmUserName

`func (o *ManaV2SnmpTargetConfig) HasUsmUserName() bool`

HasUsmUserName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2SnmpConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Communities** | Pointer to [**map[string]ManaV2NullableSnmpCommunityConfigValue**](ManaV2NullableSnmpCommunityConfigValue.md) |  | [optional] 
**EngineAuthenTraps** | Pointer to **bool** |  | [optional] 
**EngineEnabled** | Pointer to **bool** |  | [optional] 
**EngineEndpoints** | Pointer to [**map[string]ManaV2NullableSnmpEngineEndpointConfigValue**](ManaV2NullableSnmpEngineEndpointConfigValue.md) |  | [optional] 
**EngineHighCpuTraps** | Pointer to **bool** |  | [optional] 
**EngineHighMemoryTraps** | Pointer to **bool** |  | [optional] 
**EngineIdAdminOctets** | Pointer to **string** |  | [optional] 
**EngineIdAdminText** | Pointer to **string** |  | [optional] 
**EngineIdIpv4** | Pointer to **string** |  | [optional] 
**EngineIdIpv6** | Pointer to **string** |  | [optional] 
**EngineIdMac** | Pointer to **string** |  | [optional] 
**EngineIdRaw** | Pointer to **string** |  | [optional] 
**EngineLocalAcessV4** | Pointer to **bool** |  | [optional] 
**EngineLocalAcessV6** | Pointer to **bool** |  | [optional] 
**EngineUserHints** | Pointer to **bool** |  | [optional] 
**EngineUserValidation** | Pointer to **bool** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**IsGlobalSync** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NotifyFilterProfiles** | Pointer to [**map[string]ManaV2NullableSnmpNotifyFilterProfileConfigValue**](ManaV2NullableSnmpNotifyFilterProfileConfigValue.md) |  | [optional] 
**SnmpVersion** | Pointer to **string** |  | [optional] 
**Targets** | Pointer to [**map[string]ManaV2NullableSnmpTargetConfigValue**](ManaV2NullableSnmpTargetConfigValue.md) |  | [optional] 
**UsmLocalUsers** | Pointer to [**map[string]ManaV2NullableUsmLocalUserConfigValue**](ManaV2NullableUsmLocalUserConfigValue.md) |  | [optional] 
**UsmRemoteUsers** | Pointer to [**map[string]ManaV2NullableUsmRemoteUserConfigValue**](ManaV2NullableUsmRemoteUserConfigValue.md) |  | [optional] 
**V2cEnabled** | Pointer to **bool** |  | [optional] 
**V3Enabled** | Pointer to **bool** |  | [optional] 
**VacmGroups** | Pointer to [**map[string]ManaV2NullableVacmGroupValue**](ManaV2NullableVacmGroupValue.md) |  | [optional] 
**VacmViews** | Pointer to [**map[string]ManaV2NullableSnmpVacmViewValue**](ManaV2NullableSnmpVacmViewValue.md) |  | [optional] 

## Methods

### NewManaV2SnmpConfig

`func NewManaV2SnmpConfig() *ManaV2SnmpConfig`

NewManaV2SnmpConfig instantiates a new ManaV2SnmpConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpConfigWithDefaults

`func NewManaV2SnmpConfigWithDefaults() *ManaV2SnmpConfig`

NewManaV2SnmpConfigWithDefaults instantiates a new ManaV2SnmpConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommunities

`func (o *ManaV2SnmpConfig) GetCommunities() map[string]ManaV2NullableSnmpCommunityConfigValue`

GetCommunities returns the Communities field if non-nil, zero value otherwise.

### GetCommunitiesOk

`func (o *ManaV2SnmpConfig) GetCommunitiesOk() (*map[string]ManaV2NullableSnmpCommunityConfigValue, bool)`

GetCommunitiesOk returns a tuple with the Communities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunities

`func (o *ManaV2SnmpConfig) SetCommunities(v map[string]ManaV2NullableSnmpCommunityConfigValue)`

SetCommunities sets Communities field to given value.

### HasCommunities

`func (o *ManaV2SnmpConfig) HasCommunities() bool`

HasCommunities returns a boolean if a field has been set.

### GetEngineAuthenTraps

`func (o *ManaV2SnmpConfig) GetEngineAuthenTraps() bool`

GetEngineAuthenTraps returns the EngineAuthenTraps field if non-nil, zero value otherwise.

### GetEngineAuthenTrapsOk

`func (o *ManaV2SnmpConfig) GetEngineAuthenTrapsOk() (*bool, bool)`

GetEngineAuthenTrapsOk returns a tuple with the EngineAuthenTraps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineAuthenTraps

`func (o *ManaV2SnmpConfig) SetEngineAuthenTraps(v bool)`

SetEngineAuthenTraps sets EngineAuthenTraps field to given value.

### HasEngineAuthenTraps

`func (o *ManaV2SnmpConfig) HasEngineAuthenTraps() bool`

HasEngineAuthenTraps returns a boolean if a field has been set.

### GetEngineEnabled

`func (o *ManaV2SnmpConfig) GetEngineEnabled() bool`

GetEngineEnabled returns the EngineEnabled field if non-nil, zero value otherwise.

### GetEngineEnabledOk

`func (o *ManaV2SnmpConfig) GetEngineEnabledOk() (*bool, bool)`

GetEngineEnabledOk returns a tuple with the EngineEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnabled

`func (o *ManaV2SnmpConfig) SetEngineEnabled(v bool)`

SetEngineEnabled sets EngineEnabled field to given value.

### HasEngineEnabled

`func (o *ManaV2SnmpConfig) HasEngineEnabled() bool`

HasEngineEnabled returns a boolean if a field has been set.

### GetEngineEndpoints

`func (o *ManaV2SnmpConfig) GetEngineEndpoints() map[string]ManaV2NullableSnmpEngineEndpointConfigValue`

GetEngineEndpoints returns the EngineEndpoints field if non-nil, zero value otherwise.

### GetEngineEndpointsOk

`func (o *ManaV2SnmpConfig) GetEngineEndpointsOk() (*map[string]ManaV2NullableSnmpEngineEndpointConfigValue, bool)`

GetEngineEndpointsOk returns a tuple with the EngineEndpoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEndpoints

`func (o *ManaV2SnmpConfig) SetEngineEndpoints(v map[string]ManaV2NullableSnmpEngineEndpointConfigValue)`

SetEngineEndpoints sets EngineEndpoints field to given value.

### HasEngineEndpoints

`func (o *ManaV2SnmpConfig) HasEngineEndpoints() bool`

HasEngineEndpoints returns a boolean if a field has been set.

### GetEngineHighCpuTraps

`func (o *ManaV2SnmpConfig) GetEngineHighCpuTraps() bool`

GetEngineHighCpuTraps returns the EngineHighCpuTraps field if non-nil, zero value otherwise.

### GetEngineHighCpuTrapsOk

`func (o *ManaV2SnmpConfig) GetEngineHighCpuTrapsOk() (*bool, bool)`

GetEngineHighCpuTrapsOk returns a tuple with the EngineHighCpuTraps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineHighCpuTraps

`func (o *ManaV2SnmpConfig) SetEngineHighCpuTraps(v bool)`

SetEngineHighCpuTraps sets EngineHighCpuTraps field to given value.

### HasEngineHighCpuTraps

`func (o *ManaV2SnmpConfig) HasEngineHighCpuTraps() bool`

HasEngineHighCpuTraps returns a boolean if a field has been set.

### GetEngineHighMemoryTraps

`func (o *ManaV2SnmpConfig) GetEngineHighMemoryTraps() bool`

GetEngineHighMemoryTraps returns the EngineHighMemoryTraps field if non-nil, zero value otherwise.

### GetEngineHighMemoryTrapsOk

`func (o *ManaV2SnmpConfig) GetEngineHighMemoryTrapsOk() (*bool, bool)`

GetEngineHighMemoryTrapsOk returns a tuple with the EngineHighMemoryTraps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineHighMemoryTraps

`func (o *ManaV2SnmpConfig) SetEngineHighMemoryTraps(v bool)`

SetEngineHighMemoryTraps sets EngineHighMemoryTraps field to given value.

### HasEngineHighMemoryTraps

`func (o *ManaV2SnmpConfig) HasEngineHighMemoryTraps() bool`

HasEngineHighMemoryTraps returns a boolean if a field has been set.

### GetEngineIdAdminOctets

`func (o *ManaV2SnmpConfig) GetEngineIdAdminOctets() string`

GetEngineIdAdminOctets returns the EngineIdAdminOctets field if non-nil, zero value otherwise.

### GetEngineIdAdminOctetsOk

`func (o *ManaV2SnmpConfig) GetEngineIdAdminOctetsOk() (*string, bool)`

GetEngineIdAdminOctetsOk returns a tuple with the EngineIdAdminOctets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdAdminOctets

`func (o *ManaV2SnmpConfig) SetEngineIdAdminOctets(v string)`

SetEngineIdAdminOctets sets EngineIdAdminOctets field to given value.

### HasEngineIdAdminOctets

`func (o *ManaV2SnmpConfig) HasEngineIdAdminOctets() bool`

HasEngineIdAdminOctets returns a boolean if a field has been set.

### GetEngineIdAdminText

`func (o *ManaV2SnmpConfig) GetEngineIdAdminText() string`

GetEngineIdAdminText returns the EngineIdAdminText field if non-nil, zero value otherwise.

### GetEngineIdAdminTextOk

`func (o *ManaV2SnmpConfig) GetEngineIdAdminTextOk() (*string, bool)`

GetEngineIdAdminTextOk returns a tuple with the EngineIdAdminText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdAdminText

`func (o *ManaV2SnmpConfig) SetEngineIdAdminText(v string)`

SetEngineIdAdminText sets EngineIdAdminText field to given value.

### HasEngineIdAdminText

`func (o *ManaV2SnmpConfig) HasEngineIdAdminText() bool`

HasEngineIdAdminText returns a boolean if a field has been set.

### GetEngineIdIpv4

`func (o *ManaV2SnmpConfig) GetEngineIdIpv4() string`

GetEngineIdIpv4 returns the EngineIdIpv4 field if non-nil, zero value otherwise.

### GetEngineIdIpv4Ok

`func (o *ManaV2SnmpConfig) GetEngineIdIpv4Ok() (*string, bool)`

GetEngineIdIpv4Ok returns a tuple with the EngineIdIpv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdIpv4

`func (o *ManaV2SnmpConfig) SetEngineIdIpv4(v string)`

SetEngineIdIpv4 sets EngineIdIpv4 field to given value.

### HasEngineIdIpv4

`func (o *ManaV2SnmpConfig) HasEngineIdIpv4() bool`

HasEngineIdIpv4 returns a boolean if a field has been set.

### GetEngineIdIpv6

`func (o *ManaV2SnmpConfig) GetEngineIdIpv6() string`

GetEngineIdIpv6 returns the EngineIdIpv6 field if non-nil, zero value otherwise.

### GetEngineIdIpv6Ok

`func (o *ManaV2SnmpConfig) GetEngineIdIpv6Ok() (*string, bool)`

GetEngineIdIpv6Ok returns a tuple with the EngineIdIpv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdIpv6

`func (o *ManaV2SnmpConfig) SetEngineIdIpv6(v string)`

SetEngineIdIpv6 sets EngineIdIpv6 field to given value.

### HasEngineIdIpv6

`func (o *ManaV2SnmpConfig) HasEngineIdIpv6() bool`

HasEngineIdIpv6 returns a boolean if a field has been set.

### GetEngineIdMac

`func (o *ManaV2SnmpConfig) GetEngineIdMac() string`

GetEngineIdMac returns the EngineIdMac field if non-nil, zero value otherwise.

### GetEngineIdMacOk

`func (o *ManaV2SnmpConfig) GetEngineIdMacOk() (*string, bool)`

GetEngineIdMacOk returns a tuple with the EngineIdMac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdMac

`func (o *ManaV2SnmpConfig) SetEngineIdMac(v string)`

SetEngineIdMac sets EngineIdMac field to given value.

### HasEngineIdMac

`func (o *ManaV2SnmpConfig) HasEngineIdMac() bool`

HasEngineIdMac returns a boolean if a field has been set.

### GetEngineIdRaw

`func (o *ManaV2SnmpConfig) GetEngineIdRaw() string`

GetEngineIdRaw returns the EngineIdRaw field if non-nil, zero value otherwise.

### GetEngineIdRawOk

`func (o *ManaV2SnmpConfig) GetEngineIdRawOk() (*string, bool)`

GetEngineIdRawOk returns a tuple with the EngineIdRaw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdRaw

`func (o *ManaV2SnmpConfig) SetEngineIdRaw(v string)`

SetEngineIdRaw sets EngineIdRaw field to given value.

### HasEngineIdRaw

`func (o *ManaV2SnmpConfig) HasEngineIdRaw() bool`

HasEngineIdRaw returns a boolean if a field has been set.

### GetEngineLocalAcessV4

`func (o *ManaV2SnmpConfig) GetEngineLocalAcessV4() bool`

GetEngineLocalAcessV4 returns the EngineLocalAcessV4 field if non-nil, zero value otherwise.

### GetEngineLocalAcessV4Ok

`func (o *ManaV2SnmpConfig) GetEngineLocalAcessV4Ok() (*bool, bool)`

GetEngineLocalAcessV4Ok returns a tuple with the EngineLocalAcessV4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineLocalAcessV4

`func (o *ManaV2SnmpConfig) SetEngineLocalAcessV4(v bool)`

SetEngineLocalAcessV4 sets EngineLocalAcessV4 field to given value.

### HasEngineLocalAcessV4

`func (o *ManaV2SnmpConfig) HasEngineLocalAcessV4() bool`

HasEngineLocalAcessV4 returns a boolean if a field has been set.

### GetEngineLocalAcessV6

`func (o *ManaV2SnmpConfig) GetEngineLocalAcessV6() bool`

GetEngineLocalAcessV6 returns the EngineLocalAcessV6 field if non-nil, zero value otherwise.

### GetEngineLocalAcessV6Ok

`func (o *ManaV2SnmpConfig) GetEngineLocalAcessV6Ok() (*bool, bool)`

GetEngineLocalAcessV6Ok returns a tuple with the EngineLocalAcessV6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineLocalAcessV6

`func (o *ManaV2SnmpConfig) SetEngineLocalAcessV6(v bool)`

SetEngineLocalAcessV6 sets EngineLocalAcessV6 field to given value.

### HasEngineLocalAcessV6

`func (o *ManaV2SnmpConfig) HasEngineLocalAcessV6() bool`

HasEngineLocalAcessV6 returns a boolean if a field has been set.

### GetEngineUserHints

`func (o *ManaV2SnmpConfig) GetEngineUserHints() bool`

GetEngineUserHints returns the EngineUserHints field if non-nil, zero value otherwise.

### GetEngineUserHintsOk

`func (o *ManaV2SnmpConfig) GetEngineUserHintsOk() (*bool, bool)`

GetEngineUserHintsOk returns a tuple with the EngineUserHints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineUserHints

`func (o *ManaV2SnmpConfig) SetEngineUserHints(v bool)`

SetEngineUserHints sets EngineUserHints field to given value.

### HasEngineUserHints

`func (o *ManaV2SnmpConfig) HasEngineUserHints() bool`

HasEngineUserHints returns a boolean if a field has been set.

### GetEngineUserValidation

`func (o *ManaV2SnmpConfig) GetEngineUserValidation() bool`

GetEngineUserValidation returns the EngineUserValidation field if non-nil, zero value otherwise.

### GetEngineUserValidationOk

`func (o *ManaV2SnmpConfig) GetEngineUserValidationOk() (*bool, bool)`

GetEngineUserValidationOk returns a tuple with the EngineUserValidation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineUserValidation

`func (o *ManaV2SnmpConfig) SetEngineUserValidation(v bool)`

SetEngineUserValidation sets EngineUserValidation field to given value.

### HasEngineUserValidation

`func (o *ManaV2SnmpConfig) HasEngineUserValidation() bool`

HasEngineUserValidation returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2SnmpConfig) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2SnmpConfig) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2SnmpConfig) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2SnmpConfig) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetIsGlobalSync

`func (o *ManaV2SnmpConfig) GetIsGlobalSync() bool`

GetIsGlobalSync returns the IsGlobalSync field if non-nil, zero value otherwise.

### GetIsGlobalSyncOk

`func (o *ManaV2SnmpConfig) GetIsGlobalSyncOk() (*bool, bool)`

GetIsGlobalSyncOk returns a tuple with the IsGlobalSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobalSync

`func (o *ManaV2SnmpConfig) SetIsGlobalSync(v bool)`

SetIsGlobalSync sets IsGlobalSync field to given value.

### HasIsGlobalSync

`func (o *ManaV2SnmpConfig) HasIsGlobalSync() bool`

HasIsGlobalSync returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SnmpConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SnmpConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SnmpConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SnmpConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotifyFilterProfiles

`func (o *ManaV2SnmpConfig) GetNotifyFilterProfiles() map[string]ManaV2NullableSnmpNotifyFilterProfileConfigValue`

GetNotifyFilterProfiles returns the NotifyFilterProfiles field if non-nil, zero value otherwise.

### GetNotifyFilterProfilesOk

`func (o *ManaV2SnmpConfig) GetNotifyFilterProfilesOk() (*map[string]ManaV2NullableSnmpNotifyFilterProfileConfigValue, bool)`

GetNotifyFilterProfilesOk returns a tuple with the NotifyFilterProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyFilterProfiles

`func (o *ManaV2SnmpConfig) SetNotifyFilterProfiles(v map[string]ManaV2NullableSnmpNotifyFilterProfileConfigValue)`

SetNotifyFilterProfiles sets NotifyFilterProfiles field to given value.

### HasNotifyFilterProfiles

`func (o *ManaV2SnmpConfig) HasNotifyFilterProfiles() bool`

HasNotifyFilterProfiles returns a boolean if a field has been set.

### GetSnmpVersion

`func (o *ManaV2SnmpConfig) GetSnmpVersion() string`

GetSnmpVersion returns the SnmpVersion field if non-nil, zero value otherwise.

### GetSnmpVersionOk

`func (o *ManaV2SnmpConfig) GetSnmpVersionOk() (*string, bool)`

GetSnmpVersionOk returns a tuple with the SnmpVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnmpVersion

`func (o *ManaV2SnmpConfig) SetSnmpVersion(v string)`

SetSnmpVersion sets SnmpVersion field to given value.

### HasSnmpVersion

`func (o *ManaV2SnmpConfig) HasSnmpVersion() bool`

HasSnmpVersion returns a boolean if a field has been set.

### GetTargets

`func (o *ManaV2SnmpConfig) GetTargets() map[string]ManaV2NullableSnmpTargetConfigValue`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *ManaV2SnmpConfig) GetTargetsOk() (*map[string]ManaV2NullableSnmpTargetConfigValue, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *ManaV2SnmpConfig) SetTargets(v map[string]ManaV2NullableSnmpTargetConfigValue)`

SetTargets sets Targets field to given value.

### HasTargets

`func (o *ManaV2SnmpConfig) HasTargets() bool`

HasTargets returns a boolean if a field has been set.

### GetUsmLocalUsers

`func (o *ManaV2SnmpConfig) GetUsmLocalUsers() map[string]ManaV2NullableUsmLocalUserConfigValue`

GetUsmLocalUsers returns the UsmLocalUsers field if non-nil, zero value otherwise.

### GetUsmLocalUsersOk

`func (o *ManaV2SnmpConfig) GetUsmLocalUsersOk() (*map[string]ManaV2NullableUsmLocalUserConfigValue, bool)`

GetUsmLocalUsersOk returns a tuple with the UsmLocalUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmLocalUsers

`func (o *ManaV2SnmpConfig) SetUsmLocalUsers(v map[string]ManaV2NullableUsmLocalUserConfigValue)`

SetUsmLocalUsers sets UsmLocalUsers field to given value.

### HasUsmLocalUsers

`func (o *ManaV2SnmpConfig) HasUsmLocalUsers() bool`

HasUsmLocalUsers returns a boolean if a field has been set.

### GetUsmRemoteUsers

`func (o *ManaV2SnmpConfig) GetUsmRemoteUsers() map[string]ManaV2NullableUsmRemoteUserConfigValue`

GetUsmRemoteUsers returns the UsmRemoteUsers field if non-nil, zero value otherwise.

### GetUsmRemoteUsersOk

`func (o *ManaV2SnmpConfig) GetUsmRemoteUsersOk() (*map[string]ManaV2NullableUsmRemoteUserConfigValue, bool)`

GetUsmRemoteUsersOk returns a tuple with the UsmRemoteUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmRemoteUsers

`func (o *ManaV2SnmpConfig) SetUsmRemoteUsers(v map[string]ManaV2NullableUsmRemoteUserConfigValue)`

SetUsmRemoteUsers sets UsmRemoteUsers field to given value.

### HasUsmRemoteUsers

`func (o *ManaV2SnmpConfig) HasUsmRemoteUsers() bool`

HasUsmRemoteUsers returns a boolean if a field has been set.

### GetV2cEnabled

`func (o *ManaV2SnmpConfig) GetV2cEnabled() bool`

GetV2cEnabled returns the V2cEnabled field if non-nil, zero value otherwise.

### GetV2cEnabledOk

`func (o *ManaV2SnmpConfig) GetV2cEnabledOk() (*bool, bool)`

GetV2cEnabledOk returns a tuple with the V2cEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetV2cEnabled

`func (o *ManaV2SnmpConfig) SetV2cEnabled(v bool)`

SetV2cEnabled sets V2cEnabled field to given value.

### HasV2cEnabled

`func (o *ManaV2SnmpConfig) HasV2cEnabled() bool`

HasV2cEnabled returns a boolean if a field has been set.

### GetV3Enabled

`func (o *ManaV2SnmpConfig) GetV3Enabled() bool`

GetV3Enabled returns the V3Enabled field if non-nil, zero value otherwise.

### GetV3EnabledOk

`func (o *ManaV2SnmpConfig) GetV3EnabledOk() (*bool, bool)`

GetV3EnabledOk returns a tuple with the V3Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetV3Enabled

`func (o *ManaV2SnmpConfig) SetV3Enabled(v bool)`

SetV3Enabled sets V3Enabled field to given value.

### HasV3Enabled

`func (o *ManaV2SnmpConfig) HasV3Enabled() bool`

HasV3Enabled returns a boolean if a field has been set.

### GetVacmGroups

`func (o *ManaV2SnmpConfig) GetVacmGroups() map[string]ManaV2NullableVacmGroupValue`

GetVacmGroups returns the VacmGroups field if non-nil, zero value otherwise.

### GetVacmGroupsOk

`func (o *ManaV2SnmpConfig) GetVacmGroupsOk() (*map[string]ManaV2NullableVacmGroupValue, bool)`

GetVacmGroupsOk returns a tuple with the VacmGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVacmGroups

`func (o *ManaV2SnmpConfig) SetVacmGroups(v map[string]ManaV2NullableVacmGroupValue)`

SetVacmGroups sets VacmGroups field to given value.

### HasVacmGroups

`func (o *ManaV2SnmpConfig) HasVacmGroups() bool`

HasVacmGroups returns a boolean if a field has been set.

### GetVacmViews

`func (o *ManaV2SnmpConfig) GetVacmViews() map[string]ManaV2NullableSnmpVacmViewValue`

GetVacmViews returns the VacmViews field if non-nil, zero value otherwise.

### GetVacmViewsOk

`func (o *ManaV2SnmpConfig) GetVacmViewsOk() (*map[string]ManaV2NullableSnmpVacmViewValue, bool)`

GetVacmViewsOk returns a tuple with the VacmViews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVacmViews

`func (o *ManaV2SnmpConfig) SetVacmViews(v map[string]ManaV2NullableSnmpVacmViewValue)`

SetVacmViews sets VacmViews field to given value.

### HasVacmViews

`func (o *ManaV2SnmpConfig) HasVacmViews() bool`

HasVacmViews returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



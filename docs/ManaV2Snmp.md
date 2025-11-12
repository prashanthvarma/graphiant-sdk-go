# ManaV2Snmp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Communities** | Pointer to [**[]ManaV2SnmpCommunity**](ManaV2SnmpCommunity.md) |  | [optional] 
**EngineEnableAuthenTraps** | Pointer to **bool** |  | [optional] 
**EngineEnableHighMemoryTraps** | Pointer to **bool** |  | [optional] 
**EngineEnableHighCpuTraps** | Pointer to **bool** |  | [optional] 
**EngineEnableLocalAcessV4** | Pointer to **bool** |  | [optional] 
**EngineEnableLocalAcessV6** | Pointer to **bool** |  | [optional] 
**EngineEnableUserHints** | Pointer to **bool** |  | [optional] 
**EngineEnableUserValidation** | Pointer to **bool** |  | [optional] 
**EngineEnabled** | Pointer to **bool** |  | [optional] 
**EngineEndpoints** | Pointer to [**[]ManaV2SnmpEngineEndpoint**](ManaV2SnmpEngineEndpoint.md) |  | [optional] 
**EngineIdAdminOctets** | Pointer to **string** |  | [optional] 
**EngineIdAdminText** | Pointer to **string** |  | [optional] 
**EngineIdIpv4** | Pointer to **string** |  | [optional] 
**EngineIdIpv6** | Pointer to **string** |  | [optional] 
**EngineIdMac** | Pointer to **string** |  | [optional] 
**EngineIdRaw** | Pointer to **string** |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NotifyFilterProfiles** | Pointer to [**[]ManaV2SnmpNotifyFilterProfile**](ManaV2SnmpNotifyFilterProfile.md) |  | [optional] 
**SnmpVersion** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Targets** | Pointer to [**[]ManaV2SnmpTarget**](ManaV2SnmpTarget.md) |  | [optional] 
**UsmLocalUsers** | Pointer to [**[]ManaV2SnmpUsmLocalUser**](ManaV2SnmpUsmLocalUser.md) |  | [optional] 
**UsmRemoteUsers** | Pointer to [**[]ManaV2SnmpUsmRemoteUser**](ManaV2SnmpUsmRemoteUser.md) |  | [optional] 
**V2cEnabled** | Pointer to **bool** |  | [optional] 
**V3Enabled** | Pointer to **bool** |  | [optional] 
**VacmGroups** | Pointer to [**[]ManaV2SnmpVacmGroup**](ManaV2SnmpVacmGroup.md) |  | [optional] 

## Methods

### NewManaV2Snmp

`func NewManaV2Snmp() *ManaV2Snmp`

NewManaV2Snmp instantiates a new ManaV2Snmp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SnmpWithDefaults

`func NewManaV2SnmpWithDefaults() *ManaV2Snmp`

NewManaV2SnmpWithDefaults instantiates a new ManaV2Snmp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommunities

`func (o *ManaV2Snmp) GetCommunities() []ManaV2SnmpCommunity`

GetCommunities returns the Communities field if non-nil, zero value otherwise.

### GetCommunitiesOk

`func (o *ManaV2Snmp) GetCommunitiesOk() (*[]ManaV2SnmpCommunity, bool)`

GetCommunitiesOk returns a tuple with the Communities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunities

`func (o *ManaV2Snmp) SetCommunities(v []ManaV2SnmpCommunity)`

SetCommunities sets Communities field to given value.

### HasCommunities

`func (o *ManaV2Snmp) HasCommunities() bool`

HasCommunities returns a boolean if a field has been set.

### GetEngineEnableAuthenTraps

`func (o *ManaV2Snmp) GetEngineEnableAuthenTraps() bool`

GetEngineEnableAuthenTraps returns the EngineEnableAuthenTraps field if non-nil, zero value otherwise.

### GetEngineEnableAuthenTrapsOk

`func (o *ManaV2Snmp) GetEngineEnableAuthenTrapsOk() (*bool, bool)`

GetEngineEnableAuthenTrapsOk returns a tuple with the EngineEnableAuthenTraps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableAuthenTraps

`func (o *ManaV2Snmp) SetEngineEnableAuthenTraps(v bool)`

SetEngineEnableAuthenTraps sets EngineEnableAuthenTraps field to given value.

### HasEngineEnableAuthenTraps

`func (o *ManaV2Snmp) HasEngineEnableAuthenTraps() bool`

HasEngineEnableAuthenTraps returns a boolean if a field has been set.

### GetEngineEnableHighMemoryTraps

`func (o *ManaV2Snmp) GetEngineEnableHighMemoryTraps() bool`

GetEngineEnableHighMemoryTraps returns the EngineEnableHighMemoryTraps field if non-nil, zero value otherwise.

### GetEngineEnableHighMemoryTrapsOk

`func (o *ManaV2Snmp) GetEngineEnableHighMemoryTrapsOk() (*bool, bool)`

GetEngineEnableHighMemoryTrapsOk returns a tuple with the EngineEnableHighMemoryTraps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableHighMemoryTraps

`func (o *ManaV2Snmp) SetEngineEnableHighMemoryTraps(v bool)`

SetEngineEnableHighMemoryTraps sets EngineEnableHighMemoryTraps field to given value.

### HasEngineEnableHighMemoryTraps

`func (o *ManaV2Snmp) HasEngineEnableHighMemoryTraps() bool`

HasEngineEnableHighMemoryTraps returns a boolean if a field has been set.

### GetEngineEnableHighCpuTraps

`func (o *ManaV2Snmp) GetEngineEnableHighCpuTraps() bool`

GetEngineEnableHighCpuTraps returns the EngineEnableHighCpuTraps field if non-nil, zero value otherwise.

### GetEngineEnableHighCpuTrapsOk

`func (o *ManaV2Snmp) GetEngineEnableHighCpuTrapsOk() (*bool, bool)`

GetEngineEnableHighCpuTrapsOk returns a tuple with the EngineEnableHighCpuTraps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableHighCpuTraps

`func (o *ManaV2Snmp) SetEngineEnableHighCpuTraps(v bool)`

SetEngineEnableHighCpuTraps sets EngineEnableHighCpuTraps field to given value.

### HasEngineEnableHighCpuTraps

`func (o *ManaV2Snmp) HasEngineEnableHighCpuTraps() bool`

HasEngineEnableHighCpuTraps returns a boolean if a field has been set.

### GetEngineEnableLocalAcessV4

`func (o *ManaV2Snmp) GetEngineEnableLocalAcessV4() bool`

GetEngineEnableLocalAcessV4 returns the EngineEnableLocalAcessV4 field if non-nil, zero value otherwise.

### GetEngineEnableLocalAcessV4Ok

`func (o *ManaV2Snmp) GetEngineEnableLocalAcessV4Ok() (*bool, bool)`

GetEngineEnableLocalAcessV4Ok returns a tuple with the EngineEnableLocalAcessV4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableLocalAcessV4

`func (o *ManaV2Snmp) SetEngineEnableLocalAcessV4(v bool)`

SetEngineEnableLocalAcessV4 sets EngineEnableLocalAcessV4 field to given value.

### HasEngineEnableLocalAcessV4

`func (o *ManaV2Snmp) HasEngineEnableLocalAcessV4() bool`

HasEngineEnableLocalAcessV4 returns a boolean if a field has been set.

### GetEngineEnableLocalAcessV6

`func (o *ManaV2Snmp) GetEngineEnableLocalAcessV6() bool`

GetEngineEnableLocalAcessV6 returns the EngineEnableLocalAcessV6 field if non-nil, zero value otherwise.

### GetEngineEnableLocalAcessV6Ok

`func (o *ManaV2Snmp) GetEngineEnableLocalAcessV6Ok() (*bool, bool)`

GetEngineEnableLocalAcessV6Ok returns a tuple with the EngineEnableLocalAcessV6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableLocalAcessV6

`func (o *ManaV2Snmp) SetEngineEnableLocalAcessV6(v bool)`

SetEngineEnableLocalAcessV6 sets EngineEnableLocalAcessV6 field to given value.

### HasEngineEnableLocalAcessV6

`func (o *ManaV2Snmp) HasEngineEnableLocalAcessV6() bool`

HasEngineEnableLocalAcessV6 returns a boolean if a field has been set.

### GetEngineEnableUserHints

`func (o *ManaV2Snmp) GetEngineEnableUserHints() bool`

GetEngineEnableUserHints returns the EngineEnableUserHints field if non-nil, zero value otherwise.

### GetEngineEnableUserHintsOk

`func (o *ManaV2Snmp) GetEngineEnableUserHintsOk() (*bool, bool)`

GetEngineEnableUserHintsOk returns a tuple with the EngineEnableUserHints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableUserHints

`func (o *ManaV2Snmp) SetEngineEnableUserHints(v bool)`

SetEngineEnableUserHints sets EngineEnableUserHints field to given value.

### HasEngineEnableUserHints

`func (o *ManaV2Snmp) HasEngineEnableUserHints() bool`

HasEngineEnableUserHints returns a boolean if a field has been set.

### GetEngineEnableUserValidation

`func (o *ManaV2Snmp) GetEngineEnableUserValidation() bool`

GetEngineEnableUserValidation returns the EngineEnableUserValidation field if non-nil, zero value otherwise.

### GetEngineEnableUserValidationOk

`func (o *ManaV2Snmp) GetEngineEnableUserValidationOk() (*bool, bool)`

GetEngineEnableUserValidationOk returns a tuple with the EngineEnableUserValidation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnableUserValidation

`func (o *ManaV2Snmp) SetEngineEnableUserValidation(v bool)`

SetEngineEnableUserValidation sets EngineEnableUserValidation field to given value.

### HasEngineEnableUserValidation

`func (o *ManaV2Snmp) HasEngineEnableUserValidation() bool`

HasEngineEnableUserValidation returns a boolean if a field has been set.

### GetEngineEnabled

`func (o *ManaV2Snmp) GetEngineEnabled() bool`

GetEngineEnabled returns the EngineEnabled field if non-nil, zero value otherwise.

### GetEngineEnabledOk

`func (o *ManaV2Snmp) GetEngineEnabledOk() (*bool, bool)`

GetEngineEnabledOk returns a tuple with the EngineEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEnabled

`func (o *ManaV2Snmp) SetEngineEnabled(v bool)`

SetEngineEnabled sets EngineEnabled field to given value.

### HasEngineEnabled

`func (o *ManaV2Snmp) HasEngineEnabled() bool`

HasEngineEnabled returns a boolean if a field has been set.

### GetEngineEndpoints

`func (o *ManaV2Snmp) GetEngineEndpoints() []ManaV2SnmpEngineEndpoint`

GetEngineEndpoints returns the EngineEndpoints field if non-nil, zero value otherwise.

### GetEngineEndpointsOk

`func (o *ManaV2Snmp) GetEngineEndpointsOk() (*[]ManaV2SnmpEngineEndpoint, bool)`

GetEngineEndpointsOk returns a tuple with the EngineEndpoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineEndpoints

`func (o *ManaV2Snmp) SetEngineEndpoints(v []ManaV2SnmpEngineEndpoint)`

SetEngineEndpoints sets EngineEndpoints field to given value.

### HasEngineEndpoints

`func (o *ManaV2Snmp) HasEngineEndpoints() bool`

HasEngineEndpoints returns a boolean if a field has been set.

### GetEngineIdAdminOctets

`func (o *ManaV2Snmp) GetEngineIdAdminOctets() string`

GetEngineIdAdminOctets returns the EngineIdAdminOctets field if non-nil, zero value otherwise.

### GetEngineIdAdminOctetsOk

`func (o *ManaV2Snmp) GetEngineIdAdminOctetsOk() (*string, bool)`

GetEngineIdAdminOctetsOk returns a tuple with the EngineIdAdminOctets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdAdminOctets

`func (o *ManaV2Snmp) SetEngineIdAdminOctets(v string)`

SetEngineIdAdminOctets sets EngineIdAdminOctets field to given value.

### HasEngineIdAdminOctets

`func (o *ManaV2Snmp) HasEngineIdAdminOctets() bool`

HasEngineIdAdminOctets returns a boolean if a field has been set.

### GetEngineIdAdminText

`func (o *ManaV2Snmp) GetEngineIdAdminText() string`

GetEngineIdAdminText returns the EngineIdAdminText field if non-nil, zero value otherwise.

### GetEngineIdAdminTextOk

`func (o *ManaV2Snmp) GetEngineIdAdminTextOk() (*string, bool)`

GetEngineIdAdminTextOk returns a tuple with the EngineIdAdminText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdAdminText

`func (o *ManaV2Snmp) SetEngineIdAdminText(v string)`

SetEngineIdAdminText sets EngineIdAdminText field to given value.

### HasEngineIdAdminText

`func (o *ManaV2Snmp) HasEngineIdAdminText() bool`

HasEngineIdAdminText returns a boolean if a field has been set.

### GetEngineIdIpv4

`func (o *ManaV2Snmp) GetEngineIdIpv4() string`

GetEngineIdIpv4 returns the EngineIdIpv4 field if non-nil, zero value otherwise.

### GetEngineIdIpv4Ok

`func (o *ManaV2Snmp) GetEngineIdIpv4Ok() (*string, bool)`

GetEngineIdIpv4Ok returns a tuple with the EngineIdIpv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdIpv4

`func (o *ManaV2Snmp) SetEngineIdIpv4(v string)`

SetEngineIdIpv4 sets EngineIdIpv4 field to given value.

### HasEngineIdIpv4

`func (o *ManaV2Snmp) HasEngineIdIpv4() bool`

HasEngineIdIpv4 returns a boolean if a field has been set.

### GetEngineIdIpv6

`func (o *ManaV2Snmp) GetEngineIdIpv6() string`

GetEngineIdIpv6 returns the EngineIdIpv6 field if non-nil, zero value otherwise.

### GetEngineIdIpv6Ok

`func (o *ManaV2Snmp) GetEngineIdIpv6Ok() (*string, bool)`

GetEngineIdIpv6Ok returns a tuple with the EngineIdIpv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdIpv6

`func (o *ManaV2Snmp) SetEngineIdIpv6(v string)`

SetEngineIdIpv6 sets EngineIdIpv6 field to given value.

### HasEngineIdIpv6

`func (o *ManaV2Snmp) HasEngineIdIpv6() bool`

HasEngineIdIpv6 returns a boolean if a field has been set.

### GetEngineIdMac

`func (o *ManaV2Snmp) GetEngineIdMac() string`

GetEngineIdMac returns the EngineIdMac field if non-nil, zero value otherwise.

### GetEngineIdMacOk

`func (o *ManaV2Snmp) GetEngineIdMacOk() (*string, bool)`

GetEngineIdMacOk returns a tuple with the EngineIdMac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdMac

`func (o *ManaV2Snmp) SetEngineIdMac(v string)`

SetEngineIdMac sets EngineIdMac field to given value.

### HasEngineIdMac

`func (o *ManaV2Snmp) HasEngineIdMac() bool`

HasEngineIdMac returns a boolean if a field has been set.

### GetEngineIdRaw

`func (o *ManaV2Snmp) GetEngineIdRaw() string`

GetEngineIdRaw returns the EngineIdRaw field if non-nil, zero value otherwise.

### GetEngineIdRawOk

`func (o *ManaV2Snmp) GetEngineIdRawOk() (*string, bool)`

GetEngineIdRawOk returns a tuple with the EngineIdRaw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineIdRaw

`func (o *ManaV2Snmp) SetEngineIdRaw(v string)`

SetEngineIdRaw sets EngineIdRaw field to given value.

### HasEngineIdRaw

`func (o *ManaV2Snmp) HasEngineIdRaw() bool`

HasEngineIdRaw returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ManaV2Snmp) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ManaV2Snmp) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ManaV2Snmp) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ManaV2Snmp) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2Snmp) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2Snmp) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2Snmp) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2Snmp) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetId

`func (o *ManaV2Snmp) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2Snmp) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2Snmp) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2Snmp) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2Snmp) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2Snmp) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2Snmp) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2Snmp) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNotifyFilterProfiles

`func (o *ManaV2Snmp) GetNotifyFilterProfiles() []ManaV2SnmpNotifyFilterProfile`

GetNotifyFilterProfiles returns the NotifyFilterProfiles field if non-nil, zero value otherwise.

### GetNotifyFilterProfilesOk

`func (o *ManaV2Snmp) GetNotifyFilterProfilesOk() (*[]ManaV2SnmpNotifyFilterProfile, bool)`

GetNotifyFilterProfilesOk returns a tuple with the NotifyFilterProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyFilterProfiles

`func (o *ManaV2Snmp) SetNotifyFilterProfiles(v []ManaV2SnmpNotifyFilterProfile)`

SetNotifyFilterProfiles sets NotifyFilterProfiles field to given value.

### HasNotifyFilterProfiles

`func (o *ManaV2Snmp) HasNotifyFilterProfiles() bool`

HasNotifyFilterProfiles returns a boolean if a field has been set.

### GetSnmpVersion

`func (o *ManaV2Snmp) GetSnmpVersion() string`

GetSnmpVersion returns the SnmpVersion field if non-nil, zero value otherwise.

### GetSnmpVersionOk

`func (o *ManaV2Snmp) GetSnmpVersionOk() (*string, bool)`

GetSnmpVersionOk returns a tuple with the SnmpVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnmpVersion

`func (o *ManaV2Snmp) SetSnmpVersion(v string)`

SetSnmpVersion sets SnmpVersion field to given value.

### HasSnmpVersion

`func (o *ManaV2Snmp) HasSnmpVersion() bool`

HasSnmpVersion returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2Snmp) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2Snmp) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2Snmp) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2Snmp) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTargets

`func (o *ManaV2Snmp) GetTargets() []ManaV2SnmpTarget`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *ManaV2Snmp) GetTargetsOk() (*[]ManaV2SnmpTarget, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *ManaV2Snmp) SetTargets(v []ManaV2SnmpTarget)`

SetTargets sets Targets field to given value.

### HasTargets

`func (o *ManaV2Snmp) HasTargets() bool`

HasTargets returns a boolean if a field has been set.

### GetUsmLocalUsers

`func (o *ManaV2Snmp) GetUsmLocalUsers() []ManaV2SnmpUsmLocalUser`

GetUsmLocalUsers returns the UsmLocalUsers field if non-nil, zero value otherwise.

### GetUsmLocalUsersOk

`func (o *ManaV2Snmp) GetUsmLocalUsersOk() (*[]ManaV2SnmpUsmLocalUser, bool)`

GetUsmLocalUsersOk returns a tuple with the UsmLocalUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmLocalUsers

`func (o *ManaV2Snmp) SetUsmLocalUsers(v []ManaV2SnmpUsmLocalUser)`

SetUsmLocalUsers sets UsmLocalUsers field to given value.

### HasUsmLocalUsers

`func (o *ManaV2Snmp) HasUsmLocalUsers() bool`

HasUsmLocalUsers returns a boolean if a field has been set.

### GetUsmRemoteUsers

`func (o *ManaV2Snmp) GetUsmRemoteUsers() []ManaV2SnmpUsmRemoteUser`

GetUsmRemoteUsers returns the UsmRemoteUsers field if non-nil, zero value otherwise.

### GetUsmRemoteUsersOk

`func (o *ManaV2Snmp) GetUsmRemoteUsersOk() (*[]ManaV2SnmpUsmRemoteUser, bool)`

GetUsmRemoteUsersOk returns a tuple with the UsmRemoteUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsmRemoteUsers

`func (o *ManaV2Snmp) SetUsmRemoteUsers(v []ManaV2SnmpUsmRemoteUser)`

SetUsmRemoteUsers sets UsmRemoteUsers field to given value.

### HasUsmRemoteUsers

`func (o *ManaV2Snmp) HasUsmRemoteUsers() bool`

HasUsmRemoteUsers returns a boolean if a field has been set.

### GetV2cEnabled

`func (o *ManaV2Snmp) GetV2cEnabled() bool`

GetV2cEnabled returns the V2cEnabled field if non-nil, zero value otherwise.

### GetV2cEnabledOk

`func (o *ManaV2Snmp) GetV2cEnabledOk() (*bool, bool)`

GetV2cEnabledOk returns a tuple with the V2cEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetV2cEnabled

`func (o *ManaV2Snmp) SetV2cEnabled(v bool)`

SetV2cEnabled sets V2cEnabled field to given value.

### HasV2cEnabled

`func (o *ManaV2Snmp) HasV2cEnabled() bool`

HasV2cEnabled returns a boolean if a field has been set.

### GetV3Enabled

`func (o *ManaV2Snmp) GetV3Enabled() bool`

GetV3Enabled returns the V3Enabled field if non-nil, zero value otherwise.

### GetV3EnabledOk

`func (o *ManaV2Snmp) GetV3EnabledOk() (*bool, bool)`

GetV3EnabledOk returns a tuple with the V3Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetV3Enabled

`func (o *ManaV2Snmp) SetV3Enabled(v bool)`

SetV3Enabled sets V3Enabled field to given value.

### HasV3Enabled

`func (o *ManaV2Snmp) HasV3Enabled() bool`

HasV3Enabled returns a boolean if a field has been set.

### GetVacmGroups

`func (o *ManaV2Snmp) GetVacmGroups() []ManaV2SnmpVacmGroup`

GetVacmGroups returns the VacmGroups field if non-nil, zero value otherwise.

### GetVacmGroupsOk

`func (o *ManaV2Snmp) GetVacmGroupsOk() (*[]ManaV2SnmpVacmGroup, bool)`

GetVacmGroupsOk returns a tuple with the VacmGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVacmGroups

`func (o *ManaV2Snmp) SetVacmGroups(v []ManaV2SnmpVacmGroup)`

SetVacmGroups sets VacmGroups field to given value.

### HasVacmGroups

`func (o *ManaV2Snmp) HasVacmGroups() bool`

HasVacmGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



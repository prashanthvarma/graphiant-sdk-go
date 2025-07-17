# V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminStatus** | Pointer to **bool** |  | [optional] 
**Alias** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Ipv4** | Pointer to [**V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw**](V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw.md) |  | [optional] 
**Ipv6** | Pointer to [**V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw**](V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw.md) |  | [optional] 
**Lacp** | Pointer to [**V1ExtranetsGet200ResponsePoliciesInnerBranchesExcludedDevicesInnerInterfacesInnerLagInterfaceLacpConfig**](V1ExtranetsGet200ResponsePoliciesInnerBranchesExcludedDevicesInnerInterfacesInnerLagInterfaceLacpConfig.md) |  | [optional] 
**LagMembers** | Pointer to [**map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceLagMembersValue**](V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceLagMembersValue.md) |  | [optional] 
**MinimumMembers** | Pointer to **int32** |  | [optional] 
**Mtu** | Pointer to **int32** |  | [optional] 
**Segment** | Pointer to **string** |  | [optional] 
**Subinterfaces** | Pointer to [**map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceSubinterfacesValue**](V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceSubinterfacesValue.md) |  | [optional] 

## Methods

### NewV1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface

`func NewV1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface() *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface`

NewV1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface instantiates a new V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceWithDefaults

`func NewV1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceWithDefaults() *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface`

NewV1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceWithDefaults instantiates a new V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminStatus

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetAdminStatus() bool`

GetAdminStatus returns the AdminStatus field if non-nil, zero value otherwise.

### GetAdminStatusOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetAdminStatusOk() (*bool, bool)`

GetAdminStatusOk returns a tuple with the AdminStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminStatus

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetAdminStatus(v bool)`

SetAdminStatus sets AdminStatus field to given value.

### HasAdminStatus

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasAdminStatus() bool`

HasAdminStatus returns a boolean if a field has been set.

### GetAlias

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetAlias() string`

GetAlias returns the Alias field if non-nil, zero value otherwise.

### GetAliasOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetAliasOk() (*string, bool)`

GetAliasOk returns a tuple with the Alias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlias

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetAlias(v string)`

SetAlias sets Alias field to given value.

### HasAlias

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasAlias() bool`

HasAlias returns a boolean if a field has been set.

### GetDescription

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIpv4

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetIpv4() V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetIpv4Ok() (*V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetIpv4(v V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw)`

SetIpv4 sets Ipv4 field to given value.

### HasIpv4

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasIpv4() bool`

HasIpv4 returns a boolean if a field has been set.

### GetIpv6

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetIpv6() V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetIpv6Ok() (*V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetIpv6(v V1DevicesDeviceIdConfigPutRequestCoreInterfacesValueInterfaceGwGw)`

SetIpv6 sets Ipv6 field to given value.

### HasIpv6

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasIpv6() bool`

HasIpv6 returns a boolean if a field has been set.

### GetLacp

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetLacp() V1ExtranetsGet200ResponsePoliciesInnerBranchesExcludedDevicesInnerInterfacesInnerLagInterfaceLacpConfig`

GetLacp returns the Lacp field if non-nil, zero value otherwise.

### GetLacpOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetLacpOk() (*V1ExtranetsGet200ResponsePoliciesInnerBranchesExcludedDevicesInnerInterfacesInnerLagInterfaceLacpConfig, bool)`

GetLacpOk returns a tuple with the Lacp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLacp

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetLacp(v V1ExtranetsGet200ResponsePoliciesInnerBranchesExcludedDevicesInnerInterfacesInnerLagInterfaceLacpConfig)`

SetLacp sets Lacp field to given value.

### HasLacp

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasLacp() bool`

HasLacp returns a boolean if a field has been set.

### GetLagMembers

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetLagMembers() map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceLagMembersValue`

GetLagMembers returns the LagMembers field if non-nil, zero value otherwise.

### GetLagMembersOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetLagMembersOk() (*map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceLagMembersValue, bool)`

GetLagMembersOk returns a tuple with the LagMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLagMembers

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetLagMembers(v map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceLagMembersValue)`

SetLagMembers sets LagMembers field to given value.

### HasLagMembers

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasLagMembers() bool`

HasLagMembers returns a boolean if a field has been set.

### GetMinimumMembers

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetMinimumMembers() int32`

GetMinimumMembers returns the MinimumMembers field if non-nil, zero value otherwise.

### GetMinimumMembersOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetMinimumMembersOk() (*int32, bool)`

GetMinimumMembersOk returns a tuple with the MinimumMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumMembers

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetMinimumMembers(v int32)`

SetMinimumMembers sets MinimumMembers field to given value.

### HasMinimumMembers

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasMinimumMembers() bool`

HasMinimumMembers returns a boolean if a field has been set.

### GetMtu

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetMtu() int32`

GetMtu returns the Mtu field if non-nil, zero value otherwise.

### GetMtuOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetMtuOk() (*int32, bool)`

GetMtuOk returns a tuple with the Mtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMtu

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetMtu(v int32)`

SetMtu sets Mtu field to given value.

### HasMtu

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasMtu() bool`

HasMtu returns a boolean if a field has been set.

### GetSegment

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetSegment() string`

GetSegment returns the Segment field if non-nil, zero value otherwise.

### GetSegmentOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetSegmentOk() (*string, bool)`

GetSegmentOk returns a tuple with the Segment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegment

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetSegment(v string)`

SetSegment sets Segment field to given value.

### HasSegment

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasSegment() bool`

HasSegment returns a boolean if a field has been set.

### GetSubinterfaces

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetSubinterfaces() map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceSubinterfacesValue`

GetSubinterfaces returns the Subinterfaces field if non-nil, zero value otherwise.

### GetSubinterfacesOk

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) GetSubinterfacesOk() (*map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceSubinterfacesValue, bool)`

GetSubinterfacesOk returns a tuple with the Subinterfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubinterfaces

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) SetSubinterfaces(v map[string]V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterfaceSubinterfacesValue)`

SetSubinterfaces sets Subinterfaces field to given value.

### HasSubinterfaces

`func (o *V1DevicesDeviceIdConfigPutRequestEdgeLagInterfacesValueInterface) HasSubinterfaces() bool`

HasSubinterfaces returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



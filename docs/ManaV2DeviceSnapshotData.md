# ManaV2DeviceSnapshotData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OSPFInstalledRouteCount** | Pointer to **int32** |  | [optional] 
**T2SessionCount** | Pointer to **int32** |  | [optional] 
**TWAMPSessionCount** | Pointer to **int32** |  | [optional] 
**BfdSessionCount** | Pointer to **int32** |  | [optional] 
**BgpNeighborIpList** | Pointer to **[]string** |  | [optional] 
**BgpSessionCount** | Pointer to **int32** |  | [optional] 
**DeviceRole** | Pointer to **string** |  | [optional] 
**FailedServicesCount** | Pointer to **int32** |  | [optional] 
**GraphnosVersion** | Pointer to **string** |  | [optional] 
**InstalledLabels** | Pointer to **int32** |  | [optional] 
**IpsecSessionCount** | Pointer to **int32** |  | [optional] 
**OngoingAlerts** | Pointer to **int32** |  | [optional] 
**OspfNeighborIpList** | Pointer to **[]string** |  | [optional] 
**OspfSessionCount** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2DeviceSnapshotData

`func NewManaV2DeviceSnapshotData() *ManaV2DeviceSnapshotData`

NewManaV2DeviceSnapshotData instantiates a new ManaV2DeviceSnapshotData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DeviceSnapshotDataWithDefaults

`func NewManaV2DeviceSnapshotDataWithDefaults() *ManaV2DeviceSnapshotData`

NewManaV2DeviceSnapshotDataWithDefaults instantiates a new ManaV2DeviceSnapshotData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOSPFInstalledRouteCount

`func (o *ManaV2DeviceSnapshotData) GetOSPFInstalledRouteCount() int32`

GetOSPFInstalledRouteCount returns the OSPFInstalledRouteCount field if non-nil, zero value otherwise.

### GetOSPFInstalledRouteCountOk

`func (o *ManaV2DeviceSnapshotData) GetOSPFInstalledRouteCountOk() (*int32, bool)`

GetOSPFInstalledRouteCountOk returns a tuple with the OSPFInstalledRouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOSPFInstalledRouteCount

`func (o *ManaV2DeviceSnapshotData) SetOSPFInstalledRouteCount(v int32)`

SetOSPFInstalledRouteCount sets OSPFInstalledRouteCount field to given value.

### HasOSPFInstalledRouteCount

`func (o *ManaV2DeviceSnapshotData) HasOSPFInstalledRouteCount() bool`

HasOSPFInstalledRouteCount returns a boolean if a field has been set.

### GetT2SessionCount

`func (o *ManaV2DeviceSnapshotData) GetT2SessionCount() int32`

GetT2SessionCount returns the T2SessionCount field if non-nil, zero value otherwise.

### GetT2SessionCountOk

`func (o *ManaV2DeviceSnapshotData) GetT2SessionCountOk() (*int32, bool)`

GetT2SessionCountOk returns a tuple with the T2SessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetT2SessionCount

`func (o *ManaV2DeviceSnapshotData) SetT2SessionCount(v int32)`

SetT2SessionCount sets T2SessionCount field to given value.

### HasT2SessionCount

`func (o *ManaV2DeviceSnapshotData) HasT2SessionCount() bool`

HasT2SessionCount returns a boolean if a field has been set.

### GetTWAMPSessionCount

`func (o *ManaV2DeviceSnapshotData) GetTWAMPSessionCount() int32`

GetTWAMPSessionCount returns the TWAMPSessionCount field if non-nil, zero value otherwise.

### GetTWAMPSessionCountOk

`func (o *ManaV2DeviceSnapshotData) GetTWAMPSessionCountOk() (*int32, bool)`

GetTWAMPSessionCountOk returns a tuple with the TWAMPSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTWAMPSessionCount

`func (o *ManaV2DeviceSnapshotData) SetTWAMPSessionCount(v int32)`

SetTWAMPSessionCount sets TWAMPSessionCount field to given value.

### HasTWAMPSessionCount

`func (o *ManaV2DeviceSnapshotData) HasTWAMPSessionCount() bool`

HasTWAMPSessionCount returns a boolean if a field has been set.

### GetBfdSessionCount

`func (o *ManaV2DeviceSnapshotData) GetBfdSessionCount() int32`

GetBfdSessionCount returns the BfdSessionCount field if non-nil, zero value otherwise.

### GetBfdSessionCountOk

`func (o *ManaV2DeviceSnapshotData) GetBfdSessionCountOk() (*int32, bool)`

GetBfdSessionCountOk returns a tuple with the BfdSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBfdSessionCount

`func (o *ManaV2DeviceSnapshotData) SetBfdSessionCount(v int32)`

SetBfdSessionCount sets BfdSessionCount field to given value.

### HasBfdSessionCount

`func (o *ManaV2DeviceSnapshotData) HasBfdSessionCount() bool`

HasBfdSessionCount returns a boolean if a field has been set.

### GetBgpNeighborIpList

`func (o *ManaV2DeviceSnapshotData) GetBgpNeighborIpList() []string`

GetBgpNeighborIpList returns the BgpNeighborIpList field if non-nil, zero value otherwise.

### GetBgpNeighborIpListOk

`func (o *ManaV2DeviceSnapshotData) GetBgpNeighborIpListOk() (*[]string, bool)`

GetBgpNeighborIpListOk returns a tuple with the BgpNeighborIpList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighborIpList

`func (o *ManaV2DeviceSnapshotData) SetBgpNeighborIpList(v []string)`

SetBgpNeighborIpList sets BgpNeighborIpList field to given value.

### HasBgpNeighborIpList

`func (o *ManaV2DeviceSnapshotData) HasBgpNeighborIpList() bool`

HasBgpNeighborIpList returns a boolean if a field has been set.

### GetBgpSessionCount

`func (o *ManaV2DeviceSnapshotData) GetBgpSessionCount() int32`

GetBgpSessionCount returns the BgpSessionCount field if non-nil, zero value otherwise.

### GetBgpSessionCountOk

`func (o *ManaV2DeviceSnapshotData) GetBgpSessionCountOk() (*int32, bool)`

GetBgpSessionCountOk returns a tuple with the BgpSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpSessionCount

`func (o *ManaV2DeviceSnapshotData) SetBgpSessionCount(v int32)`

SetBgpSessionCount sets BgpSessionCount field to given value.

### HasBgpSessionCount

`func (o *ManaV2DeviceSnapshotData) HasBgpSessionCount() bool`

HasBgpSessionCount returns a boolean if a field has been set.

### GetDeviceRole

`func (o *ManaV2DeviceSnapshotData) GetDeviceRole() string`

GetDeviceRole returns the DeviceRole field if non-nil, zero value otherwise.

### GetDeviceRoleOk

`func (o *ManaV2DeviceSnapshotData) GetDeviceRoleOk() (*string, bool)`

GetDeviceRoleOk returns a tuple with the DeviceRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceRole

`func (o *ManaV2DeviceSnapshotData) SetDeviceRole(v string)`

SetDeviceRole sets DeviceRole field to given value.

### HasDeviceRole

`func (o *ManaV2DeviceSnapshotData) HasDeviceRole() bool`

HasDeviceRole returns a boolean if a field has been set.

### GetFailedServicesCount

`func (o *ManaV2DeviceSnapshotData) GetFailedServicesCount() int32`

GetFailedServicesCount returns the FailedServicesCount field if non-nil, zero value otherwise.

### GetFailedServicesCountOk

`func (o *ManaV2DeviceSnapshotData) GetFailedServicesCountOk() (*int32, bool)`

GetFailedServicesCountOk returns a tuple with the FailedServicesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedServicesCount

`func (o *ManaV2DeviceSnapshotData) SetFailedServicesCount(v int32)`

SetFailedServicesCount sets FailedServicesCount field to given value.

### HasFailedServicesCount

`func (o *ManaV2DeviceSnapshotData) HasFailedServicesCount() bool`

HasFailedServicesCount returns a boolean if a field has been set.

### GetGraphnosVersion

`func (o *ManaV2DeviceSnapshotData) GetGraphnosVersion() string`

GetGraphnosVersion returns the GraphnosVersion field if non-nil, zero value otherwise.

### GetGraphnosVersionOk

`func (o *ManaV2DeviceSnapshotData) GetGraphnosVersionOk() (*string, bool)`

GetGraphnosVersionOk returns a tuple with the GraphnosVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphnosVersion

`func (o *ManaV2DeviceSnapshotData) SetGraphnosVersion(v string)`

SetGraphnosVersion sets GraphnosVersion field to given value.

### HasGraphnosVersion

`func (o *ManaV2DeviceSnapshotData) HasGraphnosVersion() bool`

HasGraphnosVersion returns a boolean if a field has been set.

### GetInstalledLabels

`func (o *ManaV2DeviceSnapshotData) GetInstalledLabels() int32`

GetInstalledLabels returns the InstalledLabels field if non-nil, zero value otherwise.

### GetInstalledLabelsOk

`func (o *ManaV2DeviceSnapshotData) GetInstalledLabelsOk() (*int32, bool)`

GetInstalledLabelsOk returns a tuple with the InstalledLabels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstalledLabels

`func (o *ManaV2DeviceSnapshotData) SetInstalledLabels(v int32)`

SetInstalledLabels sets InstalledLabels field to given value.

### HasInstalledLabels

`func (o *ManaV2DeviceSnapshotData) HasInstalledLabels() bool`

HasInstalledLabels returns a boolean if a field has been set.

### GetIpsecSessionCount

`func (o *ManaV2DeviceSnapshotData) GetIpsecSessionCount() int32`

GetIpsecSessionCount returns the IpsecSessionCount field if non-nil, zero value otherwise.

### GetIpsecSessionCountOk

`func (o *ManaV2DeviceSnapshotData) GetIpsecSessionCountOk() (*int32, bool)`

GetIpsecSessionCountOk returns a tuple with the IpsecSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecSessionCount

`func (o *ManaV2DeviceSnapshotData) SetIpsecSessionCount(v int32)`

SetIpsecSessionCount sets IpsecSessionCount field to given value.

### HasIpsecSessionCount

`func (o *ManaV2DeviceSnapshotData) HasIpsecSessionCount() bool`

HasIpsecSessionCount returns a boolean if a field has been set.

### GetOngoingAlerts

`func (o *ManaV2DeviceSnapshotData) GetOngoingAlerts() int32`

GetOngoingAlerts returns the OngoingAlerts field if non-nil, zero value otherwise.

### GetOngoingAlertsOk

`func (o *ManaV2DeviceSnapshotData) GetOngoingAlertsOk() (*int32, bool)`

GetOngoingAlertsOk returns a tuple with the OngoingAlerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOngoingAlerts

`func (o *ManaV2DeviceSnapshotData) SetOngoingAlerts(v int32)`

SetOngoingAlerts sets OngoingAlerts field to given value.

### HasOngoingAlerts

`func (o *ManaV2DeviceSnapshotData) HasOngoingAlerts() bool`

HasOngoingAlerts returns a boolean if a field has been set.

### GetOspfNeighborIpList

`func (o *ManaV2DeviceSnapshotData) GetOspfNeighborIpList() []string`

GetOspfNeighborIpList returns the OspfNeighborIpList field if non-nil, zero value otherwise.

### GetOspfNeighborIpListOk

`func (o *ManaV2DeviceSnapshotData) GetOspfNeighborIpListOk() (*[]string, bool)`

GetOspfNeighborIpListOk returns a tuple with the OspfNeighborIpList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOspfNeighborIpList

`func (o *ManaV2DeviceSnapshotData) SetOspfNeighborIpList(v []string)`

SetOspfNeighborIpList sets OspfNeighborIpList field to given value.

### HasOspfNeighborIpList

`func (o *ManaV2DeviceSnapshotData) HasOspfNeighborIpList() bool`

HasOspfNeighborIpList returns a boolean if a field has been set.

### GetOspfSessionCount

`func (o *ManaV2DeviceSnapshotData) GetOspfSessionCount() int32`

GetOspfSessionCount returns the OspfSessionCount field if non-nil, zero value otherwise.

### GetOspfSessionCountOk

`func (o *ManaV2DeviceSnapshotData) GetOspfSessionCountOk() (*int32, bool)`

GetOspfSessionCountOk returns a tuple with the OspfSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOspfSessionCount

`func (o *ManaV2DeviceSnapshotData) SetOspfSessionCount(v int32)`

SetOspfSessionCount sets OspfSessionCount field to given value.

### HasOspfSessionCount

`func (o *ManaV2DeviceSnapshotData) HasOspfSessionCount() bool`

HasOspfSessionCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



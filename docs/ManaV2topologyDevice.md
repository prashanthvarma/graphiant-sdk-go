# ManaV2topologyDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**Location** | Pointer to **string** |  | [optional] 
**MaintenanceMode** | Pointer to **bool** |  | [optional] 
**ManagementIp** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**SerialNumber** | Pointer to **string** |  | [optional] 
**SiteId** | Pointer to **int64** |  | [optional] 
**SoftwareVersion** | Pointer to **string** |  | [optional] 
**StagingMode** | Pointer to **bool** |  | [optional] 
**Uptime** | Pointer to [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**VrrpInterface** | Pointer to **string** |  | [optional] 
**VrrpState** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2topologyDevice

`func NewManaV2topologyDevice() *ManaV2topologyDevice`

NewManaV2topologyDevice instantiates a new ManaV2topologyDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2topologyDeviceWithDefaults

`func NewManaV2topologyDeviceWithDefaults() *ManaV2topologyDevice`

NewManaV2topologyDeviceWithDefaults instantiates a new ManaV2topologyDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *ManaV2topologyDevice) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *ManaV2topologyDevice) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *ManaV2topologyDevice) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *ManaV2topologyDevice) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetHostname

`func (o *ManaV2topologyDevice) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *ManaV2topologyDevice) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *ManaV2topologyDevice) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *ManaV2topologyDevice) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetLocation

`func (o *ManaV2topologyDevice) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *ManaV2topologyDevice) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *ManaV2topologyDevice) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *ManaV2topologyDevice) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetMaintenanceMode

`func (o *ManaV2topologyDevice) GetMaintenanceMode() bool`

GetMaintenanceMode returns the MaintenanceMode field if non-nil, zero value otherwise.

### GetMaintenanceModeOk

`func (o *ManaV2topologyDevice) GetMaintenanceModeOk() (*bool, bool)`

GetMaintenanceModeOk returns a tuple with the MaintenanceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceMode

`func (o *ManaV2topologyDevice) SetMaintenanceMode(v bool)`

SetMaintenanceMode sets MaintenanceMode field to given value.

### HasMaintenanceMode

`func (o *ManaV2topologyDevice) HasMaintenanceMode() bool`

HasMaintenanceMode returns a boolean if a field has been set.

### GetManagementIp

`func (o *ManaV2topologyDevice) GetManagementIp() string`

GetManagementIp returns the ManagementIp field if non-nil, zero value otherwise.

### GetManagementIpOk

`func (o *ManaV2topologyDevice) GetManagementIpOk() (*string, bool)`

GetManagementIpOk returns a tuple with the ManagementIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagementIp

`func (o *ManaV2topologyDevice) SetManagementIp(v string)`

SetManagementIp sets ManagementIp field to given value.

### HasManagementIp

`func (o *ManaV2topologyDevice) HasManagementIp() bool`

HasManagementIp returns a boolean if a field has been set.

### GetModel

`func (o *ManaV2topologyDevice) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ManaV2topologyDevice) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ManaV2topologyDevice) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *ManaV2topologyDevice) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetRole

`func (o *ManaV2topologyDevice) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ManaV2topologyDevice) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ManaV2topologyDevice) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *ManaV2topologyDevice) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetSerialNumber

`func (o *ManaV2topologyDevice) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *ManaV2topologyDevice) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *ManaV2topologyDevice) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *ManaV2topologyDevice) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetSiteId

`func (o *ManaV2topologyDevice) GetSiteId() int64`

GetSiteId returns the SiteId field if non-nil, zero value otherwise.

### GetSiteIdOk

`func (o *ManaV2topologyDevice) GetSiteIdOk() (*int64, bool)`

GetSiteIdOk returns a tuple with the SiteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteId

`func (o *ManaV2topologyDevice) SetSiteId(v int64)`

SetSiteId sets SiteId field to given value.

### HasSiteId

`func (o *ManaV2topologyDevice) HasSiteId() bool`

HasSiteId returns a boolean if a field has been set.

### GetSoftwareVersion

`func (o *ManaV2topologyDevice) GetSoftwareVersion() string`

GetSoftwareVersion returns the SoftwareVersion field if non-nil, zero value otherwise.

### GetSoftwareVersionOk

`func (o *ManaV2topologyDevice) GetSoftwareVersionOk() (*string, bool)`

GetSoftwareVersionOk returns a tuple with the SoftwareVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoftwareVersion

`func (o *ManaV2topologyDevice) SetSoftwareVersion(v string)`

SetSoftwareVersion sets SoftwareVersion field to given value.

### HasSoftwareVersion

`func (o *ManaV2topologyDevice) HasSoftwareVersion() bool`

HasSoftwareVersion returns a boolean if a field has been set.

### GetStagingMode

`func (o *ManaV2topologyDevice) GetStagingMode() bool`

GetStagingMode returns the StagingMode field if non-nil, zero value otherwise.

### GetStagingModeOk

`func (o *ManaV2topologyDevice) GetStagingModeOk() (*bool, bool)`

GetStagingModeOk returns a tuple with the StagingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStagingMode

`func (o *ManaV2topologyDevice) SetStagingMode(v bool)`

SetStagingMode sets StagingMode field to given value.

### HasStagingMode

`func (o *ManaV2topologyDevice) HasStagingMode() bool`

HasStagingMode returns a boolean if a field has been set.

### GetUptime

`func (o *ManaV2topologyDevice) GetUptime() GoogleProtobufDuration`

GetUptime returns the Uptime field if non-nil, zero value otherwise.

### GetUptimeOk

`func (o *ManaV2topologyDevice) GetUptimeOk() (*GoogleProtobufDuration, bool)`

GetUptimeOk returns a tuple with the Uptime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUptime

`func (o *ManaV2topologyDevice) SetUptime(v GoogleProtobufDuration)`

SetUptime sets Uptime field to given value.

### HasUptime

`func (o *ManaV2topologyDevice) HasUptime() bool`

HasUptime returns a boolean if a field has been set.

### GetVrrpInterface

`func (o *ManaV2topologyDevice) GetVrrpInterface() string`

GetVrrpInterface returns the VrrpInterface field if non-nil, zero value otherwise.

### GetVrrpInterfaceOk

`func (o *ManaV2topologyDevice) GetVrrpInterfaceOk() (*string, bool)`

GetVrrpInterfaceOk returns a tuple with the VrrpInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrrpInterface

`func (o *ManaV2topologyDevice) SetVrrpInterface(v string)`

SetVrrpInterface sets VrrpInterface field to given value.

### HasVrrpInterface

`func (o *ManaV2topologyDevice) HasVrrpInterface() bool`

HasVrrpInterface returns a boolean if a field has been set.

### GetVrrpState

`func (o *ManaV2topologyDevice) GetVrrpState() string`

GetVrrpState returns the VrrpState field if non-nil, zero value otherwise.

### GetVrrpStateOk

`func (o *ManaV2topologyDevice) GetVrrpStateOk() (*string, bool)`

GetVrrpStateOk returns a tuple with the VrrpState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrrpState

`func (o *ManaV2topologyDevice) SetVrrpState(v string)`

SetVrrpState sets VrrpState field to given value.

### HasVrrpState

`func (o *ManaV2topologyDevice) HasVrrpState() bool`

HasVrrpState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



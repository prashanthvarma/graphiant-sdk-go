# StatsmonV2NodeDeviceInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlQuality** | Pointer to **string** |  | [optional] 
**Cpu** | Pointer to **float32** |  | [optional] 
**DataQuality** | Pointer to **string** |  | [optional] 
**DeviceId** | Pointer to **int64** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**Location** | Pointer to **string** |  | [optional] 
**MaintenanceMode** | Pointer to **bool** |  | [optional] 
**Memory** | Pointer to **float32** |  | [optional] 
**MgmtIp** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** |  | [optional] 
**PortalQuality** | Pointer to **string** |  | [optional] 
**SerialNumber** | Pointer to **string** |  | [optional] 
**SoftwareVersion** | Pointer to **string** |  | [optional] 
**StagingMode** | Pointer to **bool** |  | [optional] 
**Temperature** | Pointer to **float32** |  | [optional] 
**Uptime** | Pointer to [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 

## Methods

### NewStatsmonV2NodeDeviceInfo

`func NewStatsmonV2NodeDeviceInfo() *StatsmonV2NodeDeviceInfo`

NewStatsmonV2NodeDeviceInfo instantiates a new StatsmonV2NodeDeviceInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2NodeDeviceInfoWithDefaults

`func NewStatsmonV2NodeDeviceInfoWithDefaults() *StatsmonV2NodeDeviceInfo`

NewStatsmonV2NodeDeviceInfoWithDefaults instantiates a new StatsmonV2NodeDeviceInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlQuality

`func (o *StatsmonV2NodeDeviceInfo) GetControlQuality() string`

GetControlQuality returns the ControlQuality field if non-nil, zero value otherwise.

### GetControlQualityOk

`func (o *StatsmonV2NodeDeviceInfo) GetControlQualityOk() (*string, bool)`

GetControlQualityOk returns a tuple with the ControlQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlQuality

`func (o *StatsmonV2NodeDeviceInfo) SetControlQuality(v string)`

SetControlQuality sets ControlQuality field to given value.

### HasControlQuality

`func (o *StatsmonV2NodeDeviceInfo) HasControlQuality() bool`

HasControlQuality returns a boolean if a field has been set.

### GetCpu

`func (o *StatsmonV2NodeDeviceInfo) GetCpu() float32`

GetCpu returns the Cpu field if non-nil, zero value otherwise.

### GetCpuOk

`func (o *StatsmonV2NodeDeviceInfo) GetCpuOk() (*float32, bool)`

GetCpuOk returns a tuple with the Cpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpu

`func (o *StatsmonV2NodeDeviceInfo) SetCpu(v float32)`

SetCpu sets Cpu field to given value.

### HasCpu

`func (o *StatsmonV2NodeDeviceInfo) HasCpu() bool`

HasCpu returns a boolean if a field has been set.

### GetDataQuality

`func (o *StatsmonV2NodeDeviceInfo) GetDataQuality() string`

GetDataQuality returns the DataQuality field if non-nil, zero value otherwise.

### GetDataQualityOk

`func (o *StatsmonV2NodeDeviceInfo) GetDataQualityOk() (*string, bool)`

GetDataQualityOk returns a tuple with the DataQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataQuality

`func (o *StatsmonV2NodeDeviceInfo) SetDataQuality(v string)`

SetDataQuality sets DataQuality field to given value.

### HasDataQuality

`func (o *StatsmonV2NodeDeviceInfo) HasDataQuality() bool`

HasDataQuality returns a boolean if a field has been set.

### GetDeviceId

`func (o *StatsmonV2NodeDeviceInfo) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *StatsmonV2NodeDeviceInfo) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *StatsmonV2NodeDeviceInfo) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *StatsmonV2NodeDeviceInfo) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetHostname

`func (o *StatsmonV2NodeDeviceInfo) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *StatsmonV2NodeDeviceInfo) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *StatsmonV2NodeDeviceInfo) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *StatsmonV2NodeDeviceInfo) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetLocation

`func (o *StatsmonV2NodeDeviceInfo) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *StatsmonV2NodeDeviceInfo) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *StatsmonV2NodeDeviceInfo) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *StatsmonV2NodeDeviceInfo) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetMaintenanceMode

`func (o *StatsmonV2NodeDeviceInfo) GetMaintenanceMode() bool`

GetMaintenanceMode returns the MaintenanceMode field if non-nil, zero value otherwise.

### GetMaintenanceModeOk

`func (o *StatsmonV2NodeDeviceInfo) GetMaintenanceModeOk() (*bool, bool)`

GetMaintenanceModeOk returns a tuple with the MaintenanceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceMode

`func (o *StatsmonV2NodeDeviceInfo) SetMaintenanceMode(v bool)`

SetMaintenanceMode sets MaintenanceMode field to given value.

### HasMaintenanceMode

`func (o *StatsmonV2NodeDeviceInfo) HasMaintenanceMode() bool`

HasMaintenanceMode returns a boolean if a field has been set.

### GetMemory

`func (o *StatsmonV2NodeDeviceInfo) GetMemory() float32`

GetMemory returns the Memory field if non-nil, zero value otherwise.

### GetMemoryOk

`func (o *StatsmonV2NodeDeviceInfo) GetMemoryOk() (*float32, bool)`

GetMemoryOk returns a tuple with the Memory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemory

`func (o *StatsmonV2NodeDeviceInfo) SetMemory(v float32)`

SetMemory sets Memory field to given value.

### HasMemory

`func (o *StatsmonV2NodeDeviceInfo) HasMemory() bool`

HasMemory returns a boolean if a field has been set.

### GetMgmtIp

`func (o *StatsmonV2NodeDeviceInfo) GetMgmtIp() string`

GetMgmtIp returns the MgmtIp field if non-nil, zero value otherwise.

### GetMgmtIpOk

`func (o *StatsmonV2NodeDeviceInfo) GetMgmtIpOk() (*string, bool)`

GetMgmtIpOk returns a tuple with the MgmtIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMgmtIp

`func (o *StatsmonV2NodeDeviceInfo) SetMgmtIp(v string)`

SetMgmtIp sets MgmtIp field to given value.

### HasMgmtIp

`func (o *StatsmonV2NodeDeviceInfo) HasMgmtIp() bool`

HasMgmtIp returns a boolean if a field has been set.

### GetModel

`func (o *StatsmonV2NodeDeviceInfo) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *StatsmonV2NodeDeviceInfo) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *StatsmonV2NodeDeviceInfo) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *StatsmonV2NodeDeviceInfo) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetPortalQuality

`func (o *StatsmonV2NodeDeviceInfo) GetPortalQuality() string`

GetPortalQuality returns the PortalQuality field if non-nil, zero value otherwise.

### GetPortalQualityOk

`func (o *StatsmonV2NodeDeviceInfo) GetPortalQualityOk() (*string, bool)`

GetPortalQualityOk returns a tuple with the PortalQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortalQuality

`func (o *StatsmonV2NodeDeviceInfo) SetPortalQuality(v string)`

SetPortalQuality sets PortalQuality field to given value.

### HasPortalQuality

`func (o *StatsmonV2NodeDeviceInfo) HasPortalQuality() bool`

HasPortalQuality returns a boolean if a field has been set.

### GetSerialNumber

`func (o *StatsmonV2NodeDeviceInfo) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *StatsmonV2NodeDeviceInfo) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *StatsmonV2NodeDeviceInfo) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *StatsmonV2NodeDeviceInfo) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetSoftwareVersion

`func (o *StatsmonV2NodeDeviceInfo) GetSoftwareVersion() string`

GetSoftwareVersion returns the SoftwareVersion field if non-nil, zero value otherwise.

### GetSoftwareVersionOk

`func (o *StatsmonV2NodeDeviceInfo) GetSoftwareVersionOk() (*string, bool)`

GetSoftwareVersionOk returns a tuple with the SoftwareVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSoftwareVersion

`func (o *StatsmonV2NodeDeviceInfo) SetSoftwareVersion(v string)`

SetSoftwareVersion sets SoftwareVersion field to given value.

### HasSoftwareVersion

`func (o *StatsmonV2NodeDeviceInfo) HasSoftwareVersion() bool`

HasSoftwareVersion returns a boolean if a field has been set.

### GetStagingMode

`func (o *StatsmonV2NodeDeviceInfo) GetStagingMode() bool`

GetStagingMode returns the StagingMode field if non-nil, zero value otherwise.

### GetStagingModeOk

`func (o *StatsmonV2NodeDeviceInfo) GetStagingModeOk() (*bool, bool)`

GetStagingModeOk returns a tuple with the StagingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStagingMode

`func (o *StatsmonV2NodeDeviceInfo) SetStagingMode(v bool)`

SetStagingMode sets StagingMode field to given value.

### HasStagingMode

`func (o *StatsmonV2NodeDeviceInfo) HasStagingMode() bool`

HasStagingMode returns a boolean if a field has been set.

### GetTemperature

`func (o *StatsmonV2NodeDeviceInfo) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *StatsmonV2NodeDeviceInfo) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *StatsmonV2NodeDeviceInfo) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *StatsmonV2NodeDeviceInfo) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetUptime

`func (o *StatsmonV2NodeDeviceInfo) GetUptime() GoogleProtobufDuration`

GetUptime returns the Uptime field if non-nil, zero value otherwise.

### GetUptimeOk

`func (o *StatsmonV2NodeDeviceInfo) GetUptimeOk() (*GoogleProtobufDuration, bool)`

GetUptimeOk returns a tuple with the Uptime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUptime

`func (o *StatsmonV2NodeDeviceInfo) SetUptime(v GoogleProtobufDuration)`

SetUptime sets Uptime field to given value.

### HasUptime

`func (o *StatsmonV2NodeDeviceInfo) HasUptime() bool`

HasUptime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



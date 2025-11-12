# StatsmonTroubleshootingSystemPlane

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cpu** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**Crashes** | Pointer to [**[]StatsmonTroubleshootingCrash**](StatsmonTroubleshootingCrash.md) |  | [optional] 
**Disk** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**LastCrash** | Pointer to [**StatsmonTroubleshootingLastCrash**](StatsmonTroubleshootingLastCrash.md) |  | [optional] 
**MaintenanceWindows** | Pointer to [**[]StatsmonTroubleshootingMaintenanceWindow**](StatsmonTroubleshootingMaintenanceWindow.md) |  | [optional] 
**Memory** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Temperature** | Pointer to [**[]StatsmonTroubleshootingOverheating**](StatsmonTroubleshootingOverheating.md) |  | [optional] 
**TemperatureSeries** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 

## Methods

### NewStatsmonTroubleshootingSystemPlane

`func NewStatsmonTroubleshootingSystemPlane() *StatsmonTroubleshootingSystemPlane`

NewStatsmonTroubleshootingSystemPlane instantiates a new StatsmonTroubleshootingSystemPlane object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonTroubleshootingSystemPlaneWithDefaults

`func NewStatsmonTroubleshootingSystemPlaneWithDefaults() *StatsmonTroubleshootingSystemPlane`

NewStatsmonTroubleshootingSystemPlaneWithDefaults instantiates a new StatsmonTroubleshootingSystemPlane object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCpu

`func (o *StatsmonTroubleshootingSystemPlane) GetCpu() []StatsmonTroubleshootingSystemStat`

GetCpu returns the Cpu field if non-nil, zero value otherwise.

### GetCpuOk

`func (o *StatsmonTroubleshootingSystemPlane) GetCpuOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetCpuOk returns a tuple with the Cpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpu

`func (o *StatsmonTroubleshootingSystemPlane) SetCpu(v []StatsmonTroubleshootingSystemStat)`

SetCpu sets Cpu field to given value.

### HasCpu

`func (o *StatsmonTroubleshootingSystemPlane) HasCpu() bool`

HasCpu returns a boolean if a field has been set.

### GetCrashes

`func (o *StatsmonTroubleshootingSystemPlane) GetCrashes() []StatsmonTroubleshootingCrash`

GetCrashes returns the Crashes field if non-nil, zero value otherwise.

### GetCrashesOk

`func (o *StatsmonTroubleshootingSystemPlane) GetCrashesOk() (*[]StatsmonTroubleshootingCrash, bool)`

GetCrashesOk returns a tuple with the Crashes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrashes

`func (o *StatsmonTroubleshootingSystemPlane) SetCrashes(v []StatsmonTroubleshootingCrash)`

SetCrashes sets Crashes field to given value.

### HasCrashes

`func (o *StatsmonTroubleshootingSystemPlane) HasCrashes() bool`

HasCrashes returns a boolean if a field has been set.

### GetDisk

`func (o *StatsmonTroubleshootingSystemPlane) GetDisk() []StatsmonTroubleshootingSystemStat`

GetDisk returns the Disk field if non-nil, zero value otherwise.

### GetDiskOk

`func (o *StatsmonTroubleshootingSystemPlane) GetDiskOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetDiskOk returns a tuple with the Disk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisk

`func (o *StatsmonTroubleshootingSystemPlane) SetDisk(v []StatsmonTroubleshootingSystemStat)`

SetDisk sets Disk field to given value.

### HasDisk

`func (o *StatsmonTroubleshootingSystemPlane) HasDisk() bool`

HasDisk returns a boolean if a field has been set.

### GetLastCrash

`func (o *StatsmonTroubleshootingSystemPlane) GetLastCrash() StatsmonTroubleshootingLastCrash`

GetLastCrash returns the LastCrash field if non-nil, zero value otherwise.

### GetLastCrashOk

`func (o *StatsmonTroubleshootingSystemPlane) GetLastCrashOk() (*StatsmonTroubleshootingLastCrash, bool)`

GetLastCrashOk returns a tuple with the LastCrash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCrash

`func (o *StatsmonTroubleshootingSystemPlane) SetLastCrash(v StatsmonTroubleshootingLastCrash)`

SetLastCrash sets LastCrash field to given value.

### HasLastCrash

`func (o *StatsmonTroubleshootingSystemPlane) HasLastCrash() bool`

HasLastCrash returns a boolean if a field has been set.

### GetMaintenanceWindows

`func (o *StatsmonTroubleshootingSystemPlane) GetMaintenanceWindows() []StatsmonTroubleshootingMaintenanceWindow`

GetMaintenanceWindows returns the MaintenanceWindows field if non-nil, zero value otherwise.

### GetMaintenanceWindowsOk

`func (o *StatsmonTroubleshootingSystemPlane) GetMaintenanceWindowsOk() (*[]StatsmonTroubleshootingMaintenanceWindow, bool)`

GetMaintenanceWindowsOk returns a tuple with the MaintenanceWindows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceWindows

`func (o *StatsmonTroubleshootingSystemPlane) SetMaintenanceWindows(v []StatsmonTroubleshootingMaintenanceWindow)`

SetMaintenanceWindows sets MaintenanceWindows field to given value.

### HasMaintenanceWindows

`func (o *StatsmonTroubleshootingSystemPlane) HasMaintenanceWindows() bool`

HasMaintenanceWindows returns a boolean if a field has been set.

### GetMemory

`func (o *StatsmonTroubleshootingSystemPlane) GetMemory() []StatsmonTroubleshootingSystemStat`

GetMemory returns the Memory field if non-nil, zero value otherwise.

### GetMemoryOk

`func (o *StatsmonTroubleshootingSystemPlane) GetMemoryOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetMemoryOk returns a tuple with the Memory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemory

`func (o *StatsmonTroubleshootingSystemPlane) SetMemory(v []StatsmonTroubleshootingSystemStat)`

SetMemory sets Memory field to given value.

### HasMemory

`func (o *StatsmonTroubleshootingSystemPlane) HasMemory() bool`

HasMemory returns a boolean if a field has been set.

### GetStatus

`func (o *StatsmonTroubleshootingSystemPlane) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonTroubleshootingSystemPlane) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonTroubleshootingSystemPlane) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonTroubleshootingSystemPlane) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTemperature

`func (o *StatsmonTroubleshootingSystemPlane) GetTemperature() []StatsmonTroubleshootingOverheating`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *StatsmonTroubleshootingSystemPlane) GetTemperatureOk() (*[]StatsmonTroubleshootingOverheating, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *StatsmonTroubleshootingSystemPlane) SetTemperature(v []StatsmonTroubleshootingOverheating)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *StatsmonTroubleshootingSystemPlane) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetTemperatureSeries

`func (o *StatsmonTroubleshootingSystemPlane) GetTemperatureSeries() []StatsmonTroubleshootingSystemStat`

GetTemperatureSeries returns the TemperatureSeries field if non-nil, zero value otherwise.

### GetTemperatureSeriesOk

`func (o *StatsmonTroubleshootingSystemPlane) GetTemperatureSeriesOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetTemperatureSeriesOk returns a tuple with the TemperatureSeries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperatureSeries

`func (o *StatsmonTroubleshootingSystemPlane) SetTemperatureSeries(v []StatsmonTroubleshootingSystemStat)`

SetTemperatureSeries sets TemperatureSeries field to given value.

### HasTemperatureSeries

`func (o *StatsmonTroubleshootingSystemPlane) HasTemperatureSeries() bool`

HasTemperatureSeries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# StatsmonBackbonehealthSystemPlane

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cpu** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**Crashes** | Pointer to [**[]StatsmonTroubleshootingCrash**](StatsmonTroubleshootingCrash.md) |  | [optional] 
**Disk** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**LastCrash** | Pointer to [**StatsmonTroubleshootingLastCrash**](StatsmonTroubleshootingLastCrash.md) |  | [optional] 
**MaintenanceWindows** | Pointer to [**[]StatsmonTroubleshootingMaintenanceWindow**](StatsmonTroubleshootingMaintenanceWindow.md) |  | [optional] 
**Memory** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 
**Overheating** | Pointer to [**[]StatsmonTroubleshootingOverheating**](StatsmonTroubleshootingOverheating.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**TemperatureSeries** | Pointer to [**[]StatsmonTroubleshootingSystemStat**](StatsmonTroubleshootingSystemStat.md) |  | [optional] 

## Methods

### NewStatsmonBackbonehealthSystemPlane

`func NewStatsmonBackbonehealthSystemPlane() *StatsmonBackbonehealthSystemPlane`

NewStatsmonBackbonehealthSystemPlane instantiates a new StatsmonBackbonehealthSystemPlane object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonBackbonehealthSystemPlaneWithDefaults

`func NewStatsmonBackbonehealthSystemPlaneWithDefaults() *StatsmonBackbonehealthSystemPlane`

NewStatsmonBackbonehealthSystemPlaneWithDefaults instantiates a new StatsmonBackbonehealthSystemPlane object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCpu

`func (o *StatsmonBackbonehealthSystemPlane) GetCpu() []StatsmonTroubleshootingSystemStat`

GetCpu returns the Cpu field if non-nil, zero value otherwise.

### GetCpuOk

`func (o *StatsmonBackbonehealthSystemPlane) GetCpuOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetCpuOk returns a tuple with the Cpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpu

`func (o *StatsmonBackbonehealthSystemPlane) SetCpu(v []StatsmonTroubleshootingSystemStat)`

SetCpu sets Cpu field to given value.

### HasCpu

`func (o *StatsmonBackbonehealthSystemPlane) HasCpu() bool`

HasCpu returns a boolean if a field has been set.

### GetCrashes

`func (o *StatsmonBackbonehealthSystemPlane) GetCrashes() []StatsmonTroubleshootingCrash`

GetCrashes returns the Crashes field if non-nil, zero value otherwise.

### GetCrashesOk

`func (o *StatsmonBackbonehealthSystemPlane) GetCrashesOk() (*[]StatsmonTroubleshootingCrash, bool)`

GetCrashesOk returns a tuple with the Crashes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrashes

`func (o *StatsmonBackbonehealthSystemPlane) SetCrashes(v []StatsmonTroubleshootingCrash)`

SetCrashes sets Crashes field to given value.

### HasCrashes

`func (o *StatsmonBackbonehealthSystemPlane) HasCrashes() bool`

HasCrashes returns a boolean if a field has been set.

### GetDisk

`func (o *StatsmonBackbonehealthSystemPlane) GetDisk() []StatsmonTroubleshootingSystemStat`

GetDisk returns the Disk field if non-nil, zero value otherwise.

### GetDiskOk

`func (o *StatsmonBackbonehealthSystemPlane) GetDiskOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetDiskOk returns a tuple with the Disk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisk

`func (o *StatsmonBackbonehealthSystemPlane) SetDisk(v []StatsmonTroubleshootingSystemStat)`

SetDisk sets Disk field to given value.

### HasDisk

`func (o *StatsmonBackbonehealthSystemPlane) HasDisk() bool`

HasDisk returns a boolean if a field has been set.

### GetLastCrash

`func (o *StatsmonBackbonehealthSystemPlane) GetLastCrash() StatsmonTroubleshootingLastCrash`

GetLastCrash returns the LastCrash field if non-nil, zero value otherwise.

### GetLastCrashOk

`func (o *StatsmonBackbonehealthSystemPlane) GetLastCrashOk() (*StatsmonTroubleshootingLastCrash, bool)`

GetLastCrashOk returns a tuple with the LastCrash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCrash

`func (o *StatsmonBackbonehealthSystemPlane) SetLastCrash(v StatsmonTroubleshootingLastCrash)`

SetLastCrash sets LastCrash field to given value.

### HasLastCrash

`func (o *StatsmonBackbonehealthSystemPlane) HasLastCrash() bool`

HasLastCrash returns a boolean if a field has been set.

### GetMaintenanceWindows

`func (o *StatsmonBackbonehealthSystemPlane) GetMaintenanceWindows() []StatsmonTroubleshootingMaintenanceWindow`

GetMaintenanceWindows returns the MaintenanceWindows field if non-nil, zero value otherwise.

### GetMaintenanceWindowsOk

`func (o *StatsmonBackbonehealthSystemPlane) GetMaintenanceWindowsOk() (*[]StatsmonTroubleshootingMaintenanceWindow, bool)`

GetMaintenanceWindowsOk returns a tuple with the MaintenanceWindows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceWindows

`func (o *StatsmonBackbonehealthSystemPlane) SetMaintenanceWindows(v []StatsmonTroubleshootingMaintenanceWindow)`

SetMaintenanceWindows sets MaintenanceWindows field to given value.

### HasMaintenanceWindows

`func (o *StatsmonBackbonehealthSystemPlane) HasMaintenanceWindows() bool`

HasMaintenanceWindows returns a boolean if a field has been set.

### GetMemory

`func (o *StatsmonBackbonehealthSystemPlane) GetMemory() []StatsmonTroubleshootingSystemStat`

GetMemory returns the Memory field if non-nil, zero value otherwise.

### GetMemoryOk

`func (o *StatsmonBackbonehealthSystemPlane) GetMemoryOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetMemoryOk returns a tuple with the Memory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemory

`func (o *StatsmonBackbonehealthSystemPlane) SetMemory(v []StatsmonTroubleshootingSystemStat)`

SetMemory sets Memory field to given value.

### HasMemory

`func (o *StatsmonBackbonehealthSystemPlane) HasMemory() bool`

HasMemory returns a boolean if a field has been set.

### GetOverheating

`func (o *StatsmonBackbonehealthSystemPlane) GetOverheating() []StatsmonTroubleshootingOverheating`

GetOverheating returns the Overheating field if non-nil, zero value otherwise.

### GetOverheatingOk

`func (o *StatsmonBackbonehealthSystemPlane) GetOverheatingOk() (*[]StatsmonTroubleshootingOverheating, bool)`

GetOverheatingOk returns a tuple with the Overheating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverheating

`func (o *StatsmonBackbonehealthSystemPlane) SetOverheating(v []StatsmonTroubleshootingOverheating)`

SetOverheating sets Overheating field to given value.

### HasOverheating

`func (o *StatsmonBackbonehealthSystemPlane) HasOverheating() bool`

HasOverheating returns a boolean if a field has been set.

### GetStatus

`func (o *StatsmonBackbonehealthSystemPlane) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonBackbonehealthSystemPlane) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonBackbonehealthSystemPlane) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonBackbonehealthSystemPlane) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTemperatureSeries

`func (o *StatsmonBackbonehealthSystemPlane) GetTemperatureSeries() []StatsmonTroubleshootingSystemStat`

GetTemperatureSeries returns the TemperatureSeries field if non-nil, zero value otherwise.

### GetTemperatureSeriesOk

`func (o *StatsmonBackbonehealthSystemPlane) GetTemperatureSeriesOk() (*[]StatsmonTroubleshootingSystemStat, bool)`

GetTemperatureSeriesOk returns a tuple with the TemperatureSeries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperatureSeries

`func (o *StatsmonBackbonehealthSystemPlane) SetTemperatureSeries(v []StatsmonTroubleshootingSystemStat)`

SetTemperatureSeries sets TemperatureSeries field to given value.

### HasTemperatureSeries

`func (o *StatsmonBackbonehealthSystemPlane) HasTemperatureSeries() bool`

HasTemperatureSeries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



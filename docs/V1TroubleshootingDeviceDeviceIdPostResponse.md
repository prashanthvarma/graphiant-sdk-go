# V1TroubleshootingDeviceDeviceIdPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaintenanceMode** | Pointer to **bool** |  | [optional] 
**ColrActive** | Pointer to **bool** |  | [optional] 
**ControlPlane** | Pointer to [**StatsmonTroubleshootingControlPlane**](StatsmonTroubleshootingControlPlane.md) |  | [optional] 
**DataPlane** | Pointer to [**StatsmonTroubleshootingDataPlane**](StatsmonTroubleshootingDataPlane.md) |  | [optional] 
**Issues** | Pointer to [**[]StatsmonTroubleshootingIssue**](StatsmonTroubleshootingIssue.md) |  | [optional] 
**LifecycleStatus** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SwVersion** | Pointer to **string** |  | [optional] 
**SwVersionV2** | Pointer to [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 
**SystemPlane** | Pointer to [**StatsmonTroubleshootingSystemPlane**](StatsmonTroubleshootingSystemPlane.md) |  | [optional] 
**UpSinceTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1TroubleshootingDeviceDeviceIdPostResponse

`func NewV1TroubleshootingDeviceDeviceIdPostResponse() *V1TroubleshootingDeviceDeviceIdPostResponse`

NewV1TroubleshootingDeviceDeviceIdPostResponse instantiates a new V1TroubleshootingDeviceDeviceIdPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1TroubleshootingDeviceDeviceIdPostResponseWithDefaults

`func NewV1TroubleshootingDeviceDeviceIdPostResponseWithDefaults() *V1TroubleshootingDeviceDeviceIdPostResponse`

NewV1TroubleshootingDeviceDeviceIdPostResponseWithDefaults instantiates a new V1TroubleshootingDeviceDeviceIdPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaintenanceMode

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetMaintenanceMode() bool`

GetMaintenanceMode returns the MaintenanceMode field if non-nil, zero value otherwise.

### GetMaintenanceModeOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetMaintenanceModeOk() (*bool, bool)`

GetMaintenanceModeOk returns a tuple with the MaintenanceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceMode

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetMaintenanceMode(v bool)`

SetMaintenanceMode sets MaintenanceMode field to given value.

### HasMaintenanceMode

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasMaintenanceMode() bool`

HasMaintenanceMode returns a boolean if a field has been set.

### GetColrActive

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetColrActive() bool`

GetColrActive returns the ColrActive field if non-nil, zero value otherwise.

### GetColrActiveOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetColrActiveOk() (*bool, bool)`

GetColrActiveOk returns a tuple with the ColrActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColrActive

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetColrActive(v bool)`

SetColrActive sets ColrActive field to given value.

### HasColrActive

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasColrActive() bool`

HasColrActive returns a boolean if a field has been set.

### GetControlPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetControlPlane() StatsmonTroubleshootingControlPlane`

GetControlPlane returns the ControlPlane field if non-nil, zero value otherwise.

### GetControlPlaneOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetControlPlaneOk() (*StatsmonTroubleshootingControlPlane, bool)`

GetControlPlaneOk returns a tuple with the ControlPlane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetControlPlane(v StatsmonTroubleshootingControlPlane)`

SetControlPlane sets ControlPlane field to given value.

### HasControlPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasControlPlane() bool`

HasControlPlane returns a boolean if a field has been set.

### GetDataPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetDataPlane() StatsmonTroubleshootingDataPlane`

GetDataPlane returns the DataPlane field if non-nil, zero value otherwise.

### GetDataPlaneOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetDataPlaneOk() (*StatsmonTroubleshootingDataPlane, bool)`

GetDataPlaneOk returns a tuple with the DataPlane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetDataPlane(v StatsmonTroubleshootingDataPlane)`

SetDataPlane sets DataPlane field to given value.

### HasDataPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasDataPlane() bool`

HasDataPlane returns a boolean if a field has been set.

### GetIssues

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetIssues() []StatsmonTroubleshootingIssue`

GetIssues returns the Issues field if non-nil, zero value otherwise.

### GetIssuesOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetIssuesOk() (*[]StatsmonTroubleshootingIssue, bool)`

GetIssuesOk returns a tuple with the Issues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssues

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetIssues(v []StatsmonTroubleshootingIssue)`

SetIssues sets Issues field to given value.

### HasIssues

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasIssues() bool`

HasIssues returns a boolean if a field has been set.

### GetLifecycleStatus

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetLifecycleStatus() string`

GetLifecycleStatus returns the LifecycleStatus field if non-nil, zero value otherwise.

### GetLifecycleStatusOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetLifecycleStatusOk() (*string, bool)`

GetLifecycleStatusOk returns a tuple with the LifecycleStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifecycleStatus

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetLifecycleStatus(v string)`

SetLifecycleStatus sets LifecycleStatus field to given value.

### HasLifecycleStatus

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasLifecycleStatus() bool`

HasLifecycleStatus returns a boolean if a field has been set.

### GetStatus

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSwVersion

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetSwVersion() string`

GetSwVersion returns the SwVersion field if non-nil, zero value otherwise.

### GetSwVersionOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetSwVersionOk() (*string, bool)`

GetSwVersionOk returns a tuple with the SwVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwVersion

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetSwVersion(v string)`

SetSwVersion sets SwVersion field to given value.

### HasSwVersion

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasSwVersion() bool`

HasSwVersion returns a boolean if a field has been set.

### GetSwVersionV2

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetSwVersionV2() UpgradeSwVersion`

GetSwVersionV2 returns the SwVersionV2 field if non-nil, zero value otherwise.

### GetSwVersionV2Ok

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetSwVersionV2Ok() (*UpgradeSwVersion, bool)`

GetSwVersionV2Ok returns a tuple with the SwVersionV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwVersionV2

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetSwVersionV2(v UpgradeSwVersion)`

SetSwVersionV2 sets SwVersionV2 field to given value.

### HasSwVersionV2

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasSwVersionV2() bool`

HasSwVersionV2 returns a boolean if a field has been set.

### GetSystemPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetSystemPlane() StatsmonTroubleshootingSystemPlane`

GetSystemPlane returns the SystemPlane field if non-nil, zero value otherwise.

### GetSystemPlaneOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetSystemPlaneOk() (*StatsmonTroubleshootingSystemPlane, bool)`

GetSystemPlaneOk returns a tuple with the SystemPlane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetSystemPlane(v StatsmonTroubleshootingSystemPlane)`

SetSystemPlane sets SystemPlane field to given value.

### HasSystemPlane

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasSystemPlane() bool`

HasSystemPlane returns a boolean if a field has been set.

### GetUpSinceTs

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetUpSinceTs() GoogleProtobufTimestamp`

GetUpSinceTs returns the UpSinceTs field if non-nil, zero value otherwise.

### GetUpSinceTsOk

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) GetUpSinceTsOk() (*GoogleProtobufTimestamp, bool)`

GetUpSinceTsOk returns a tuple with the UpSinceTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpSinceTs

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) SetUpSinceTs(v GoogleProtobufTimestamp)`

SetUpSinceTs sets UpSinceTs field to given value.

### HasUpSinceTs

`func (o *V1TroubleshootingDeviceDeviceIdPostResponse) HasUpSinceTs() bool`

HasUpSinceTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



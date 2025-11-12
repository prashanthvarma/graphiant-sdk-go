# V1BackboneHealthDeviceDeviceIdPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlPlane** | Pointer to [**StatsmonBackbonehealthControlPlane**](StatsmonBackbonehealthControlPlane.md) |  | [optional] 
**DataPlane** | Pointer to [**StatsmonBackbonehealthDataPlane**](StatsmonBackbonehealthDataPlane.md) |  | [optional] 
**Issues** | Pointer to [**[]StatsmonTroubleshootingIssue**](StatsmonTroubleshootingIssue.md) |  | [optional] 
**QoeMatrix** | Pointer to [**StatsmonBackbonehealthGetQoeMatrixResponse**](StatsmonBackbonehealthGetQoeMatrixResponse.md) |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SwVersion** | Pointer to **string** |  | [optional] 
**SwVersionV2** | Pointer to [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 
**SystemPlane** | Pointer to [**StatsmonBackbonehealthSystemPlane**](StatsmonBackbonehealthSystemPlane.md) |  | [optional] 
**UpSinceTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1BackboneHealthDeviceDeviceIdPostResponse

`func NewV1BackboneHealthDeviceDeviceIdPostResponse() *V1BackboneHealthDeviceDeviceIdPostResponse`

NewV1BackboneHealthDeviceDeviceIdPostResponse instantiates a new V1BackboneHealthDeviceDeviceIdPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1BackboneHealthDeviceDeviceIdPostResponseWithDefaults

`func NewV1BackboneHealthDeviceDeviceIdPostResponseWithDefaults() *V1BackboneHealthDeviceDeviceIdPostResponse`

NewV1BackboneHealthDeviceDeviceIdPostResponseWithDefaults instantiates a new V1BackboneHealthDeviceDeviceIdPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetControlPlane() StatsmonBackbonehealthControlPlane`

GetControlPlane returns the ControlPlane field if non-nil, zero value otherwise.

### GetControlPlaneOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetControlPlaneOk() (*StatsmonBackbonehealthControlPlane, bool)`

GetControlPlaneOk returns a tuple with the ControlPlane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetControlPlane(v StatsmonBackbonehealthControlPlane)`

SetControlPlane sets ControlPlane field to given value.

### HasControlPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasControlPlane() bool`

HasControlPlane returns a boolean if a field has been set.

### GetDataPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetDataPlane() StatsmonBackbonehealthDataPlane`

GetDataPlane returns the DataPlane field if non-nil, zero value otherwise.

### GetDataPlaneOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetDataPlaneOk() (*StatsmonBackbonehealthDataPlane, bool)`

GetDataPlaneOk returns a tuple with the DataPlane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetDataPlane(v StatsmonBackbonehealthDataPlane)`

SetDataPlane sets DataPlane field to given value.

### HasDataPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasDataPlane() bool`

HasDataPlane returns a boolean if a field has been set.

### GetIssues

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetIssues() []StatsmonTroubleshootingIssue`

GetIssues returns the Issues field if non-nil, zero value otherwise.

### GetIssuesOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetIssuesOk() (*[]StatsmonTroubleshootingIssue, bool)`

GetIssuesOk returns a tuple with the Issues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssues

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetIssues(v []StatsmonTroubleshootingIssue)`

SetIssues sets Issues field to given value.

### HasIssues

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasIssues() bool`

HasIssues returns a boolean if a field has been set.

### GetQoeMatrix

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetQoeMatrix() StatsmonBackbonehealthGetQoeMatrixResponse`

GetQoeMatrix returns the QoeMatrix field if non-nil, zero value otherwise.

### GetQoeMatrixOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetQoeMatrixOk() (*StatsmonBackbonehealthGetQoeMatrixResponse, bool)`

GetQoeMatrixOk returns a tuple with the QoeMatrix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQoeMatrix

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetQoeMatrix(v StatsmonBackbonehealthGetQoeMatrixResponse)`

SetQoeMatrix sets QoeMatrix field to given value.

### HasQoeMatrix

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasQoeMatrix() bool`

HasQoeMatrix returns a boolean if a field has been set.

### GetRole

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetStatus

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSwVersion

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetSwVersion() string`

GetSwVersion returns the SwVersion field if non-nil, zero value otherwise.

### GetSwVersionOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetSwVersionOk() (*string, bool)`

GetSwVersionOk returns a tuple with the SwVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwVersion

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetSwVersion(v string)`

SetSwVersion sets SwVersion field to given value.

### HasSwVersion

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasSwVersion() bool`

HasSwVersion returns a boolean if a field has been set.

### GetSwVersionV2

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetSwVersionV2() UpgradeSwVersion`

GetSwVersionV2 returns the SwVersionV2 field if non-nil, zero value otherwise.

### GetSwVersionV2Ok

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetSwVersionV2Ok() (*UpgradeSwVersion, bool)`

GetSwVersionV2Ok returns a tuple with the SwVersionV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwVersionV2

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetSwVersionV2(v UpgradeSwVersion)`

SetSwVersionV2 sets SwVersionV2 field to given value.

### HasSwVersionV2

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasSwVersionV2() bool`

HasSwVersionV2 returns a boolean if a field has been set.

### GetSystemPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetSystemPlane() StatsmonBackbonehealthSystemPlane`

GetSystemPlane returns the SystemPlane field if non-nil, zero value otherwise.

### GetSystemPlaneOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetSystemPlaneOk() (*StatsmonBackbonehealthSystemPlane, bool)`

GetSystemPlaneOk returns a tuple with the SystemPlane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetSystemPlane(v StatsmonBackbonehealthSystemPlane)`

SetSystemPlane sets SystemPlane field to given value.

### HasSystemPlane

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasSystemPlane() bool`

HasSystemPlane returns a boolean if a field has been set.

### GetUpSinceTs

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetUpSinceTs() GoogleProtobufTimestamp`

GetUpSinceTs returns the UpSinceTs field if non-nil, zero value otherwise.

### GetUpSinceTsOk

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) GetUpSinceTsOk() (*GoogleProtobufTimestamp, bool)`

GetUpSinceTsOk returns a tuple with the UpSinceTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpSinceTs

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) SetUpSinceTs(v GoogleProtobufTimestamp)`

SetUpSinceTs sets UpSinceTs field to given value.

### HasUpSinceTs

`func (o *V1BackboneHealthDeviceDeviceIdPostResponse) HasUpSinceTs() bool`

HasUpSinceTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



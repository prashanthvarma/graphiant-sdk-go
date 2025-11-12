# StatsmonTroubleshootingControlPlane

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlTransitions** | Pointer to [**[]StatsmonTroubleshootingTransitions**](StatsmonTroubleshootingTransitions.md) |  | [optional] 
**ManagementTransitions** | Pointer to [**[]StatsmonTroubleshootingTransitions**](StatsmonTroubleshootingTransitions.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonTroubleshootingControlPlane

`func NewStatsmonTroubleshootingControlPlane() *StatsmonTroubleshootingControlPlane`

NewStatsmonTroubleshootingControlPlane instantiates a new StatsmonTroubleshootingControlPlane object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonTroubleshootingControlPlaneWithDefaults

`func NewStatsmonTroubleshootingControlPlaneWithDefaults() *StatsmonTroubleshootingControlPlane`

NewStatsmonTroubleshootingControlPlaneWithDefaults instantiates a new StatsmonTroubleshootingControlPlane object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlTransitions

`func (o *StatsmonTroubleshootingControlPlane) GetControlTransitions() []StatsmonTroubleshootingTransitions`

GetControlTransitions returns the ControlTransitions field if non-nil, zero value otherwise.

### GetControlTransitionsOk

`func (o *StatsmonTroubleshootingControlPlane) GetControlTransitionsOk() (*[]StatsmonTroubleshootingTransitions, bool)`

GetControlTransitionsOk returns a tuple with the ControlTransitions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlTransitions

`func (o *StatsmonTroubleshootingControlPlane) SetControlTransitions(v []StatsmonTroubleshootingTransitions)`

SetControlTransitions sets ControlTransitions field to given value.

### HasControlTransitions

`func (o *StatsmonTroubleshootingControlPlane) HasControlTransitions() bool`

HasControlTransitions returns a boolean if a field has been set.

### GetManagementTransitions

`func (o *StatsmonTroubleshootingControlPlane) GetManagementTransitions() []StatsmonTroubleshootingTransitions`

GetManagementTransitions returns the ManagementTransitions field if non-nil, zero value otherwise.

### GetManagementTransitionsOk

`func (o *StatsmonTroubleshootingControlPlane) GetManagementTransitionsOk() (*[]StatsmonTroubleshootingTransitions, bool)`

GetManagementTransitionsOk returns a tuple with the ManagementTransitions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagementTransitions

`func (o *StatsmonTroubleshootingControlPlane) SetManagementTransitions(v []StatsmonTroubleshootingTransitions)`

SetManagementTransitions sets ManagementTransitions field to given value.

### HasManagementTransitions

`func (o *StatsmonTroubleshootingControlPlane) HasManagementTransitions() bool`

HasManagementTransitions returns a boolean if a field has been set.

### GetStatus

`func (o *StatsmonTroubleshootingControlPlane) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonTroubleshootingControlPlane) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonTroubleshootingControlPlane) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonTroubleshootingControlPlane) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



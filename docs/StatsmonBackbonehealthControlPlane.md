# StatsmonBackbonehealthControlPlane

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlTransitions** | Pointer to [**StatsmonBackbonehealthTransitionSeries**](StatsmonBackbonehealthTransitionSeries.md) |  | [optional] 
**ManagementTransitions** | Pointer to [**StatsmonBackbonehealthTransitionSeries**](StatsmonBackbonehealthTransitionSeries.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonBackbonehealthControlPlane

`func NewStatsmonBackbonehealthControlPlane() *StatsmonBackbonehealthControlPlane`

NewStatsmonBackbonehealthControlPlane instantiates a new StatsmonBackbonehealthControlPlane object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonBackbonehealthControlPlaneWithDefaults

`func NewStatsmonBackbonehealthControlPlaneWithDefaults() *StatsmonBackbonehealthControlPlane`

NewStatsmonBackbonehealthControlPlaneWithDefaults instantiates a new StatsmonBackbonehealthControlPlane object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlTransitions

`func (o *StatsmonBackbonehealthControlPlane) GetControlTransitions() StatsmonBackbonehealthTransitionSeries`

GetControlTransitions returns the ControlTransitions field if non-nil, zero value otherwise.

### GetControlTransitionsOk

`func (o *StatsmonBackbonehealthControlPlane) GetControlTransitionsOk() (*StatsmonBackbonehealthTransitionSeries, bool)`

GetControlTransitionsOk returns a tuple with the ControlTransitions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlTransitions

`func (o *StatsmonBackbonehealthControlPlane) SetControlTransitions(v StatsmonBackbonehealthTransitionSeries)`

SetControlTransitions sets ControlTransitions field to given value.

### HasControlTransitions

`func (o *StatsmonBackbonehealthControlPlane) HasControlTransitions() bool`

HasControlTransitions returns a boolean if a field has been set.

### GetManagementTransitions

`func (o *StatsmonBackbonehealthControlPlane) GetManagementTransitions() StatsmonBackbonehealthTransitionSeries`

GetManagementTransitions returns the ManagementTransitions field if non-nil, zero value otherwise.

### GetManagementTransitionsOk

`func (o *StatsmonBackbonehealthControlPlane) GetManagementTransitionsOk() (*StatsmonBackbonehealthTransitionSeries, bool)`

GetManagementTransitionsOk returns a tuple with the ManagementTransitions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagementTransitions

`func (o *StatsmonBackbonehealthControlPlane) SetManagementTransitions(v StatsmonBackbonehealthTransitionSeries)`

SetManagementTransitions sets ManagementTransitions field to given value.

### HasManagementTransitions

`func (o *StatsmonBackbonehealthControlPlane) HasManagementTransitions() bool`

HasManagementTransitions returns a boolean if a field has been set.

### GetStatus

`func (o *StatsmonBackbonehealthControlPlane) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonBackbonehealthControlPlane) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonBackbonehealthControlPlane) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonBackbonehealthControlPlane) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



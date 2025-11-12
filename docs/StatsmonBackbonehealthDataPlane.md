# StatsmonBackbonehealthDataPlane

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DownTransitions** | Pointer to [**[]StatsmonBackbonehealthTransitions**](StatsmonBackbonehealthTransitions.md) |  | [optional] 
**SessionSlas** | Pointer to [**[]StatsmonTroubleshootingSessionSla**](StatsmonTroubleshootingSessionSla.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonBackbonehealthDataPlane

`func NewStatsmonBackbonehealthDataPlane() *StatsmonBackbonehealthDataPlane`

NewStatsmonBackbonehealthDataPlane instantiates a new StatsmonBackbonehealthDataPlane object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonBackbonehealthDataPlaneWithDefaults

`func NewStatsmonBackbonehealthDataPlaneWithDefaults() *StatsmonBackbonehealthDataPlane`

NewStatsmonBackbonehealthDataPlaneWithDefaults instantiates a new StatsmonBackbonehealthDataPlane object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDownTransitions

`func (o *StatsmonBackbonehealthDataPlane) GetDownTransitions() []StatsmonBackbonehealthTransitions`

GetDownTransitions returns the DownTransitions field if non-nil, zero value otherwise.

### GetDownTransitionsOk

`func (o *StatsmonBackbonehealthDataPlane) GetDownTransitionsOk() (*[]StatsmonBackbonehealthTransitions, bool)`

GetDownTransitionsOk returns a tuple with the DownTransitions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownTransitions

`func (o *StatsmonBackbonehealthDataPlane) SetDownTransitions(v []StatsmonBackbonehealthTransitions)`

SetDownTransitions sets DownTransitions field to given value.

### HasDownTransitions

`func (o *StatsmonBackbonehealthDataPlane) HasDownTransitions() bool`

HasDownTransitions returns a boolean if a field has been set.

### GetSessionSlas

`func (o *StatsmonBackbonehealthDataPlane) GetSessionSlas() []StatsmonTroubleshootingSessionSla`

GetSessionSlas returns the SessionSlas field if non-nil, zero value otherwise.

### GetSessionSlasOk

`func (o *StatsmonBackbonehealthDataPlane) GetSessionSlasOk() (*[]StatsmonTroubleshootingSessionSla, bool)`

GetSessionSlasOk returns a tuple with the SessionSlas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionSlas

`func (o *StatsmonBackbonehealthDataPlane) SetSessionSlas(v []StatsmonTroubleshootingSessionSla)`

SetSessionSlas sets SessionSlas field to given value.

### HasSessionSlas

`func (o *StatsmonBackbonehealthDataPlane) HasSessionSlas() bool`

HasSessionSlas returns a boolean if a field has been set.

### GetStatus

`func (o *StatsmonBackbonehealthDataPlane) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatsmonBackbonehealthDataPlane) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatsmonBackbonehealthDataPlane) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatsmonBackbonehealthDataPlane) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



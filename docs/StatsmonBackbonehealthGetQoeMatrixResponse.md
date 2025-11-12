# StatsmonBackbonehealthGetQoeMatrixResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Devices** | Pointer to [**[]StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary**](StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary.md) |  | [optional] 
**QoeMatrix** | Pointer to [**[]StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary**](StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary.md) |  | [optional] 

## Methods

### NewStatsmonBackbonehealthGetQoeMatrixResponse

`func NewStatsmonBackbonehealthGetQoeMatrixResponse() *StatsmonBackbonehealthGetQoeMatrixResponse`

NewStatsmonBackbonehealthGetQoeMatrixResponse instantiates a new StatsmonBackbonehealthGetQoeMatrixResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonBackbonehealthGetQoeMatrixResponseWithDefaults

`func NewStatsmonBackbonehealthGetQoeMatrixResponseWithDefaults() *StatsmonBackbonehealthGetQoeMatrixResponse`

NewStatsmonBackbonehealthGetQoeMatrixResponseWithDefaults instantiates a new StatsmonBackbonehealthGetQoeMatrixResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevices

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) GetDevices() []StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) GetDevicesOk() (*[]StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) SetDevices(v []StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetQoeMatrix

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) GetQoeMatrix() []StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary`

GetQoeMatrix returns the QoeMatrix field if non-nil, zero value otherwise.

### GetQoeMatrixOk

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) GetQoeMatrixOk() (*[]StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary, bool)`

GetQoeMatrixOk returns a tuple with the QoeMatrix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQoeMatrix

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) SetQoeMatrix(v []StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary)`

SetQoeMatrix sets QoeMatrix field to given value.

### HasQoeMatrix

`func (o *StatsmonBackbonehealthGetQoeMatrixResponse) HasQoeMatrix() bool`

HasQoeMatrix returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



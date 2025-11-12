# StatsmonV2Edge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**A** | Pointer to **int32** |  | [optional] 
**B** | Pointer to **int32** |  | [optional] 
**CircuitsInfo** | Pointer to [**[]StatsmonV2EdgeedgeCircuitInfo**](StatsmonV2EdgeedgeCircuitInfo.md) |  | [optional] 
**Connections** | Pointer to [**[]StatsmonV2Connection**](StatsmonV2Connection.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Quality** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonV2Edge

`func NewStatsmonV2Edge() *StatsmonV2Edge`

NewStatsmonV2Edge instantiates a new StatsmonV2Edge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonV2EdgeWithDefaults

`func NewStatsmonV2EdgeWithDefaults() *StatsmonV2Edge`

NewStatsmonV2EdgeWithDefaults instantiates a new StatsmonV2Edge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetA

`func (o *StatsmonV2Edge) GetA() int32`

GetA returns the A field if non-nil, zero value otherwise.

### GetAOk

`func (o *StatsmonV2Edge) GetAOk() (*int32, bool)`

GetAOk returns a tuple with the A field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetA

`func (o *StatsmonV2Edge) SetA(v int32)`

SetA sets A field to given value.

### HasA

`func (o *StatsmonV2Edge) HasA() bool`

HasA returns a boolean if a field has been set.

### GetB

`func (o *StatsmonV2Edge) GetB() int32`

GetB returns the B field if non-nil, zero value otherwise.

### GetBOk

`func (o *StatsmonV2Edge) GetBOk() (*int32, bool)`

GetBOk returns a tuple with the B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetB

`func (o *StatsmonV2Edge) SetB(v int32)`

SetB sets B field to given value.

### HasB

`func (o *StatsmonV2Edge) HasB() bool`

HasB returns a boolean if a field has been set.

### GetCircuitsInfo

`func (o *StatsmonV2Edge) GetCircuitsInfo() []StatsmonV2EdgeedgeCircuitInfo`

GetCircuitsInfo returns the CircuitsInfo field if non-nil, zero value otherwise.

### GetCircuitsInfoOk

`func (o *StatsmonV2Edge) GetCircuitsInfoOk() (*[]StatsmonV2EdgeedgeCircuitInfo, bool)`

GetCircuitsInfoOk returns a tuple with the CircuitsInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitsInfo

`func (o *StatsmonV2Edge) SetCircuitsInfo(v []StatsmonV2EdgeedgeCircuitInfo)`

SetCircuitsInfo sets CircuitsInfo field to given value.

### HasCircuitsInfo

`func (o *StatsmonV2Edge) HasCircuitsInfo() bool`

HasCircuitsInfo returns a boolean if a field has been set.

### GetConnections

`func (o *StatsmonV2Edge) GetConnections() []StatsmonV2Connection`

GetConnections returns the Connections field if non-nil, zero value otherwise.

### GetConnectionsOk

`func (o *StatsmonV2Edge) GetConnectionsOk() (*[]StatsmonV2Connection, bool)`

GetConnectionsOk returns a tuple with the Connections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnections

`func (o *StatsmonV2Edge) SetConnections(v []StatsmonV2Connection)`

SetConnections sets Connections field to given value.

### HasConnections

`func (o *StatsmonV2Edge) HasConnections() bool`

HasConnections returns a boolean if a field has been set.

### GetName

`func (o *StatsmonV2Edge) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StatsmonV2Edge) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StatsmonV2Edge) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *StatsmonV2Edge) HasName() bool`

HasName returns a boolean if a field has been set.

### GetQuality

`func (o *StatsmonV2Edge) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *StatsmonV2Edge) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *StatsmonV2Edge) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *StatsmonV2Edge) HasQuality() bool`

HasQuality returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# IpfixAppStateSummaryCount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppHealth** | Pointer to **map[string]int32** |  | [optional] 
**AppIncidents** | Pointer to [**IpfixAppIncidents**](IpfixAppIncidents.md) |  | [optional] 
**AppsOnDeviceCount** | Pointer to **int32** |  | [optional] 
**AverageQoe** | Pointer to **float64** |  | [optional] 
**CircuitsIncidents** | Pointer to [**[]StatsmonCircuitsIncidents**](StatsmonCircuitsIncidents.md) |  | [optional] 
**CircuitsIncidentsv2** | Pointer to [**[]StatsmonV2CircuitIncidents**](StatsmonV2CircuitIncidents.md) |  | [optional] 

## Methods

### NewIpfixAppStateSummaryCount

`func NewIpfixAppStateSummaryCount() *IpfixAppStateSummaryCount`

NewIpfixAppStateSummaryCount instantiates a new IpfixAppStateSummaryCount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppStateSummaryCountWithDefaults

`func NewIpfixAppStateSummaryCountWithDefaults() *IpfixAppStateSummaryCount`

NewIpfixAppStateSummaryCountWithDefaults instantiates a new IpfixAppStateSummaryCount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppHealth

`func (o *IpfixAppStateSummaryCount) GetAppHealth() map[string]int32`

GetAppHealth returns the AppHealth field if non-nil, zero value otherwise.

### GetAppHealthOk

`func (o *IpfixAppStateSummaryCount) GetAppHealthOk() (*map[string]int32, bool)`

GetAppHealthOk returns a tuple with the AppHealth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppHealth

`func (o *IpfixAppStateSummaryCount) SetAppHealth(v map[string]int32)`

SetAppHealth sets AppHealth field to given value.

### HasAppHealth

`func (o *IpfixAppStateSummaryCount) HasAppHealth() bool`

HasAppHealth returns a boolean if a field has been set.

### GetAppIncidents

`func (o *IpfixAppStateSummaryCount) GetAppIncidents() IpfixAppIncidents`

GetAppIncidents returns the AppIncidents field if non-nil, zero value otherwise.

### GetAppIncidentsOk

`func (o *IpfixAppStateSummaryCount) GetAppIncidentsOk() (*IpfixAppIncidents, bool)`

GetAppIncidentsOk returns a tuple with the AppIncidents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppIncidents

`func (o *IpfixAppStateSummaryCount) SetAppIncidents(v IpfixAppIncidents)`

SetAppIncidents sets AppIncidents field to given value.

### HasAppIncidents

`func (o *IpfixAppStateSummaryCount) HasAppIncidents() bool`

HasAppIncidents returns a boolean if a field has been set.

### GetAppsOnDeviceCount

`func (o *IpfixAppStateSummaryCount) GetAppsOnDeviceCount() int32`

GetAppsOnDeviceCount returns the AppsOnDeviceCount field if non-nil, zero value otherwise.

### GetAppsOnDeviceCountOk

`func (o *IpfixAppStateSummaryCount) GetAppsOnDeviceCountOk() (*int32, bool)`

GetAppsOnDeviceCountOk returns a tuple with the AppsOnDeviceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppsOnDeviceCount

`func (o *IpfixAppStateSummaryCount) SetAppsOnDeviceCount(v int32)`

SetAppsOnDeviceCount sets AppsOnDeviceCount field to given value.

### HasAppsOnDeviceCount

`func (o *IpfixAppStateSummaryCount) HasAppsOnDeviceCount() bool`

HasAppsOnDeviceCount returns a boolean if a field has been set.

### GetAverageQoe

`func (o *IpfixAppStateSummaryCount) GetAverageQoe() float64`

GetAverageQoe returns the AverageQoe field if non-nil, zero value otherwise.

### GetAverageQoeOk

`func (o *IpfixAppStateSummaryCount) GetAverageQoeOk() (*float64, bool)`

GetAverageQoeOk returns a tuple with the AverageQoe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageQoe

`func (o *IpfixAppStateSummaryCount) SetAverageQoe(v float64)`

SetAverageQoe sets AverageQoe field to given value.

### HasAverageQoe

`func (o *IpfixAppStateSummaryCount) HasAverageQoe() bool`

HasAverageQoe returns a boolean if a field has been set.

### GetCircuitsIncidents

`func (o *IpfixAppStateSummaryCount) GetCircuitsIncidents() []StatsmonCircuitsIncidents`

GetCircuitsIncidents returns the CircuitsIncidents field if non-nil, zero value otherwise.

### GetCircuitsIncidentsOk

`func (o *IpfixAppStateSummaryCount) GetCircuitsIncidentsOk() (*[]StatsmonCircuitsIncidents, bool)`

GetCircuitsIncidentsOk returns a tuple with the CircuitsIncidents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitsIncidents

`func (o *IpfixAppStateSummaryCount) SetCircuitsIncidents(v []StatsmonCircuitsIncidents)`

SetCircuitsIncidents sets CircuitsIncidents field to given value.

### HasCircuitsIncidents

`func (o *IpfixAppStateSummaryCount) HasCircuitsIncidents() bool`

HasCircuitsIncidents returns a boolean if a field has been set.

### GetCircuitsIncidentsv2

`func (o *IpfixAppStateSummaryCount) GetCircuitsIncidentsv2() []StatsmonV2CircuitIncidents`

GetCircuitsIncidentsv2 returns the CircuitsIncidentsv2 field if non-nil, zero value otherwise.

### GetCircuitsIncidentsv2Ok

`func (o *IpfixAppStateSummaryCount) GetCircuitsIncidentsv2Ok() (*[]StatsmonV2CircuitIncidents, bool)`

GetCircuitsIncidentsv2Ok returns a tuple with the CircuitsIncidentsv2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitsIncidentsv2

`func (o *IpfixAppStateSummaryCount) SetCircuitsIncidentsv2(v []StatsmonV2CircuitIncidents)`

SetCircuitsIncidentsv2 sets CircuitsIncidentsv2 field to given value.

### HasCircuitsIncidentsv2

`func (o *IpfixAppStateSummaryCount) HasCircuitsIncidentsv2() bool`

HasCircuitsIncidentsv2 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



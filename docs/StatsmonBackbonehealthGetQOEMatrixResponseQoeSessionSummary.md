# StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Box** | Pointer to [**[]StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox**](StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox.md) |  | [optional] 
**DeviceId** | Pointer to **int64** |  | [optional] 
**DeviceRegion** | Pointer to [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**PeerDeviceId** | Pointer to **int64** |  | [optional] 
**PeerDeviceRegion** | Pointer to [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**SessionName** | Pointer to **string** |  | [optional] 

## Methods

### NewStatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary

`func NewStatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary() *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary`

NewStatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary instantiates a new StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryWithDefaults

`func NewStatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryWithDefaults() *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary`

NewStatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryWithDefaults instantiates a new StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBox

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetBox() []StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox`

GetBox returns the Box field if non-nil, zero value otherwise.

### GetBoxOk

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetBoxOk() (*[]StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox, bool)`

GetBoxOk returns a tuple with the Box field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBox

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) SetBox(v []StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox)`

SetBox sets Box field to given value.

### HasBox

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) HasBox() bool`

HasBox returns a boolean if a field has been set.

### GetDeviceId

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetDeviceRegion

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetDeviceRegion() StatsmonTroubleshootingRegion`

GetDeviceRegion returns the DeviceRegion field if non-nil, zero value otherwise.

### GetDeviceRegionOk

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetDeviceRegionOk() (*StatsmonTroubleshootingRegion, bool)`

GetDeviceRegionOk returns a tuple with the DeviceRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceRegion

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) SetDeviceRegion(v StatsmonTroubleshootingRegion)`

SetDeviceRegion sets DeviceRegion field to given value.

### HasDeviceRegion

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) HasDeviceRegion() bool`

HasDeviceRegion returns a boolean if a field has been set.

### GetPeerDeviceId

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetPeerDeviceId() int64`

GetPeerDeviceId returns the PeerDeviceId field if non-nil, zero value otherwise.

### GetPeerDeviceIdOk

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetPeerDeviceIdOk() (*int64, bool)`

GetPeerDeviceIdOk returns a tuple with the PeerDeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerDeviceId

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) SetPeerDeviceId(v int64)`

SetPeerDeviceId sets PeerDeviceId field to given value.

### HasPeerDeviceId

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) HasPeerDeviceId() bool`

HasPeerDeviceId returns a boolean if a field has been set.

### GetPeerDeviceRegion

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetPeerDeviceRegion() StatsmonTroubleshootingRegion`

GetPeerDeviceRegion returns the PeerDeviceRegion field if non-nil, zero value otherwise.

### GetPeerDeviceRegionOk

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetPeerDeviceRegionOk() (*StatsmonTroubleshootingRegion, bool)`

GetPeerDeviceRegionOk returns a tuple with the PeerDeviceRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerDeviceRegion

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) SetPeerDeviceRegion(v StatsmonTroubleshootingRegion)`

SetPeerDeviceRegion sets PeerDeviceRegion field to given value.

### HasPeerDeviceRegion

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) HasPeerDeviceRegion() bool`

HasPeerDeviceRegion returns a boolean if a field has been set.

### GetSessionName

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetSessionName() string`

GetSessionName returns the SessionName field if non-nil, zero value otherwise.

### GetSessionNameOk

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) GetSessionNameOk() (*string, bool)`

GetSessionNameOk returns a tuple with the SessionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionName

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) SetSessionName(v string)`

SetSessionName sets SessionName field to given value.

### HasSessionName

`func (o *StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary) HasSessionName() bool`

HasSessionName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1BackboneHealthFilterGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuits** | Pointer to [**[]StatsmonTroubleshootingCircuitFilter**](StatsmonTroubleshootingCircuitFilter.md) |  | [optional] 
**Devices** | Pointer to [**[]StatsmonTroubleshootingDeviceFilter**](StatsmonTroubleshootingDeviceFilter.md) |  | [optional] 
**LanSegments** | Pointer to [**[]StatsmonTroubleshootingLanSegmentFilter**](StatsmonTroubleshootingLanSegmentFilter.md) |  | [optional] 
**Regions** | Pointer to [**[]StatsmonTroubleshootingRegionFilter**](StatsmonTroubleshootingRegionFilter.md) |  | [optional] 
**Sites** | Pointer to [**[]StatsmonTroubleshootingSiteFilter**](StatsmonTroubleshootingSiteFilter.md) |  | [optional] 

## Methods

### NewV1BackboneHealthFilterGetResponse

`func NewV1BackboneHealthFilterGetResponse() *V1BackboneHealthFilterGetResponse`

NewV1BackboneHealthFilterGetResponse instantiates a new V1BackboneHealthFilterGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1BackboneHealthFilterGetResponseWithDefaults

`func NewV1BackboneHealthFilterGetResponseWithDefaults() *V1BackboneHealthFilterGetResponse`

NewV1BackboneHealthFilterGetResponseWithDefaults instantiates a new V1BackboneHealthFilterGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuits

`func (o *V1BackboneHealthFilterGetResponse) GetCircuits() []StatsmonTroubleshootingCircuitFilter`

GetCircuits returns the Circuits field if non-nil, zero value otherwise.

### GetCircuitsOk

`func (o *V1BackboneHealthFilterGetResponse) GetCircuitsOk() (*[]StatsmonTroubleshootingCircuitFilter, bool)`

GetCircuitsOk returns a tuple with the Circuits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuits

`func (o *V1BackboneHealthFilterGetResponse) SetCircuits(v []StatsmonTroubleshootingCircuitFilter)`

SetCircuits sets Circuits field to given value.

### HasCircuits

`func (o *V1BackboneHealthFilterGetResponse) HasCircuits() bool`

HasCircuits returns a boolean if a field has been set.

### GetDevices

`func (o *V1BackboneHealthFilterGetResponse) GetDevices() []StatsmonTroubleshootingDeviceFilter`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *V1BackboneHealthFilterGetResponse) GetDevicesOk() (*[]StatsmonTroubleshootingDeviceFilter, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *V1BackboneHealthFilterGetResponse) SetDevices(v []StatsmonTroubleshootingDeviceFilter)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *V1BackboneHealthFilterGetResponse) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetLanSegments

`func (o *V1BackboneHealthFilterGetResponse) GetLanSegments() []StatsmonTroubleshootingLanSegmentFilter`

GetLanSegments returns the LanSegments field if non-nil, zero value otherwise.

### GetLanSegmentsOk

`func (o *V1BackboneHealthFilterGetResponse) GetLanSegmentsOk() (*[]StatsmonTroubleshootingLanSegmentFilter, bool)`

GetLanSegmentsOk returns a tuple with the LanSegments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegments

`func (o *V1BackboneHealthFilterGetResponse) SetLanSegments(v []StatsmonTroubleshootingLanSegmentFilter)`

SetLanSegments sets LanSegments field to given value.

### HasLanSegments

`func (o *V1BackboneHealthFilterGetResponse) HasLanSegments() bool`

HasLanSegments returns a boolean if a field has been set.

### GetRegions

`func (o *V1BackboneHealthFilterGetResponse) GetRegions() []StatsmonTroubleshootingRegionFilter`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *V1BackboneHealthFilterGetResponse) GetRegionsOk() (*[]StatsmonTroubleshootingRegionFilter, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *V1BackboneHealthFilterGetResponse) SetRegions(v []StatsmonTroubleshootingRegionFilter)`

SetRegions sets Regions field to given value.

### HasRegions

`func (o *V1BackboneHealthFilterGetResponse) HasRegions() bool`

HasRegions returns a boolean if a field has been set.

### GetSites

`func (o *V1BackboneHealthFilterGetResponse) GetSites() []StatsmonTroubleshootingSiteFilter`

GetSites returns the Sites field if non-nil, zero value otherwise.

### GetSitesOk

`func (o *V1BackboneHealthFilterGetResponse) GetSitesOk() (*[]StatsmonTroubleshootingSiteFilter, bool)`

GetSitesOk returns a tuple with the Sites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSites

`func (o *V1BackboneHealthFilterGetResponse) SetSites(v []StatsmonTroubleshootingSiteFilter)`

SetSites sets Sites field to given value.

### HasSites

`func (o *V1BackboneHealthFilterGetResponse) HasSites() bool`

HasSites returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



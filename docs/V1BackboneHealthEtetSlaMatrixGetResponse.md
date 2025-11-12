# V1BackboneHealthEtetSlaMatrixGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Devices** | Pointer to [**[]V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary**](V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary.md) |  | [optional] 
**RegionStatus** | Pointer to [**[]V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus**](V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus.md) |  | [optional] 
**SlaMatrix** | Pointer to [**[]V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary**](V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary.md) |  | [optional] 

## Methods

### NewV1BackboneHealthEtetSlaMatrixGetResponse

`func NewV1BackboneHealthEtetSlaMatrixGetResponse() *V1BackboneHealthEtetSlaMatrixGetResponse`

NewV1BackboneHealthEtetSlaMatrixGetResponse instantiates a new V1BackboneHealthEtetSlaMatrixGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1BackboneHealthEtetSlaMatrixGetResponseWithDefaults

`func NewV1BackboneHealthEtetSlaMatrixGetResponseWithDefaults() *V1BackboneHealthEtetSlaMatrixGetResponse`

NewV1BackboneHealthEtetSlaMatrixGetResponseWithDefaults instantiates a new V1BackboneHealthEtetSlaMatrixGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevices

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) GetDevices() []V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) GetDevicesOk() (*[]V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) SetDevices(v []V1BackboneHealthEtetSlaMatrixGetResponseDevicesSummary)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetRegionStatus

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) GetRegionStatus() []V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus`

GetRegionStatus returns the RegionStatus field if non-nil, zero value otherwise.

### GetRegionStatusOk

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) GetRegionStatusOk() (*[]V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus, bool)`

GetRegionStatusOk returns a tuple with the RegionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionStatus

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) SetRegionStatus(v []V1BackboneHealthEtetSlaMatrixGetResponseRegionStatus)`

SetRegionStatus sets RegionStatus field to given value.

### HasRegionStatus

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) HasRegionStatus() bool`

HasRegionStatus returns a boolean if a field has been set.

### GetSlaMatrix

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) GetSlaMatrix() []V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary`

GetSlaMatrix returns the SlaMatrix field if non-nil, zero value otherwise.

### GetSlaMatrixOk

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) GetSlaMatrixOk() (*[]V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary, bool)`

GetSlaMatrixOk returns a tuple with the SlaMatrix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlaMatrix

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) SetSlaMatrix(v []V1BackboneHealthEtetSlaMatrixGetResponseSlaSummary)`

SetSlaMatrix sets SlaMatrix field to given value.

### HasSlaMatrix

`func (o *V1BackboneHealthEtetSlaMatrixGetResponse) HasSlaMatrix() bool`

HasSlaMatrix returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



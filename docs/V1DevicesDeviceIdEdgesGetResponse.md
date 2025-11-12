# V1DevicesDeviceIdEdgesGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Devices** | Pointer to [**[]ManaV2Device**](ManaV2Device.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Methods

### NewV1DevicesDeviceIdEdgesGetResponse

`func NewV1DevicesDeviceIdEdgesGetResponse() *V1DevicesDeviceIdEdgesGetResponse`

NewV1DevicesDeviceIdEdgesGetResponse instantiates a new V1DevicesDeviceIdEdgesGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdEdgesGetResponseWithDefaults

`func NewV1DevicesDeviceIdEdgesGetResponseWithDefaults() *V1DevicesDeviceIdEdgesGetResponse`

NewV1DevicesDeviceIdEdgesGetResponseWithDefaults instantiates a new V1DevicesDeviceIdEdgesGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevices

`func (o *V1DevicesDeviceIdEdgesGetResponse) GetDevices() []ManaV2Device`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *V1DevicesDeviceIdEdgesGetResponse) GetDevicesOk() (*[]ManaV2Device, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *V1DevicesDeviceIdEdgesGetResponse) SetDevices(v []ManaV2Device)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *V1DevicesDeviceIdEdgesGetResponse) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DevicesDeviceIdEdgesGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DevicesDeviceIdEdgesGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DevicesDeviceIdEdgesGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DevicesDeviceIdEdgesGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



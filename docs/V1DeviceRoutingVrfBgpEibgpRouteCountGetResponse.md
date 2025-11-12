# V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EbgpRouteCount** | Pointer to [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**GraphiantRouteCount** | Pointer to [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**IbgpRouteCount** | Pointer to [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**LocalSourcedRouteCount** | Pointer to [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 
**TotalRouteCount** | Pointer to [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 

## Methods

### NewV1DeviceRoutingVrfBgpEibgpRouteCountGetResponse

`func NewV1DeviceRoutingVrfBgpEibgpRouteCountGetResponse() *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse`

NewV1DeviceRoutingVrfBgpEibgpRouteCountGetResponse instantiates a new V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingVrfBgpEibgpRouteCountGetResponseWithDefaults

`func NewV1DeviceRoutingVrfBgpEibgpRouteCountGetResponseWithDefaults() *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse`

NewV1DeviceRoutingVrfBgpEibgpRouteCountGetResponseWithDefaults instantiates a new V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEbgpRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetEbgpRouteCount() RoutingAfiRouteCount`

GetEbgpRouteCount returns the EbgpRouteCount field if non-nil, zero value otherwise.

### GetEbgpRouteCountOk

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetEbgpRouteCountOk() (*RoutingAfiRouteCount, bool)`

GetEbgpRouteCountOk returns a tuple with the EbgpRouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEbgpRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) SetEbgpRouteCount(v RoutingAfiRouteCount)`

SetEbgpRouteCount sets EbgpRouteCount field to given value.

### HasEbgpRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) HasEbgpRouteCount() bool`

HasEbgpRouteCount returns a boolean if a field has been set.

### GetGraphiantRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetGraphiantRouteCount() RoutingAfiRouteCount`

GetGraphiantRouteCount returns the GraphiantRouteCount field if non-nil, zero value otherwise.

### GetGraphiantRouteCountOk

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetGraphiantRouteCountOk() (*RoutingAfiRouteCount, bool)`

GetGraphiantRouteCountOk returns a tuple with the GraphiantRouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) SetGraphiantRouteCount(v RoutingAfiRouteCount)`

SetGraphiantRouteCount sets GraphiantRouteCount field to given value.

### HasGraphiantRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) HasGraphiantRouteCount() bool`

HasGraphiantRouteCount returns a boolean if a field has been set.

### GetIbgpRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetIbgpRouteCount() RoutingAfiRouteCount`

GetIbgpRouteCount returns the IbgpRouteCount field if non-nil, zero value otherwise.

### GetIbgpRouteCountOk

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetIbgpRouteCountOk() (*RoutingAfiRouteCount, bool)`

GetIbgpRouteCountOk returns a tuple with the IbgpRouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbgpRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) SetIbgpRouteCount(v RoutingAfiRouteCount)`

SetIbgpRouteCount sets IbgpRouteCount field to given value.

### HasIbgpRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) HasIbgpRouteCount() bool`

HasIbgpRouteCount returns a boolean if a field has been set.

### GetLocalSourcedRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetLocalSourcedRouteCount() RoutingAfiRouteCount`

GetLocalSourcedRouteCount returns the LocalSourcedRouteCount field if non-nil, zero value otherwise.

### GetLocalSourcedRouteCountOk

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetLocalSourcedRouteCountOk() (*RoutingAfiRouteCount, bool)`

GetLocalSourcedRouteCountOk returns a tuple with the LocalSourcedRouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalSourcedRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) SetLocalSourcedRouteCount(v RoutingAfiRouteCount)`

SetLocalSourcedRouteCount sets LocalSourcedRouteCount field to given value.

### HasLocalSourcedRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) HasLocalSourcedRouteCount() bool`

HasLocalSourcedRouteCount returns a boolean if a field has been set.

### GetTotalRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetTotalRouteCount() RoutingAfiRouteCount`

GetTotalRouteCount returns the TotalRouteCount field if non-nil, zero value otherwise.

### GetTotalRouteCountOk

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) GetTotalRouteCountOk() (*RoutingAfiRouteCount, bool)`

GetTotalRouteCountOk returns a tuple with the TotalRouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) SetTotalRouteCount(v RoutingAfiRouteCount)`

SetTotalRouteCount sets TotalRouteCount field to given value.

### HasTotalRouteCount

`func (o *V1DeviceRoutingVrfBgpEibgpRouteCountGetResponse) HasTotalRouteCount() bool`

HasTotalRouteCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



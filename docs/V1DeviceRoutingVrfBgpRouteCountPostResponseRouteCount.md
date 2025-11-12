# V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RouteCount** | Pointer to **int64** | total route count in a vrf (required) | [optional] 
**VrfName** | Pointer to **string** | Valid configured VRF name (required) | [optional] 

## Methods

### NewV1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount

`func NewV1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount() *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount`

NewV1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount instantiates a new V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingVrfBgpRouteCountPostResponseRouteCountWithDefaults

`func NewV1DeviceRoutingVrfBgpRouteCountPostResponseRouteCountWithDefaults() *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount`

NewV1DeviceRoutingVrfBgpRouteCountPostResponseRouteCountWithDefaults instantiates a new V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRouteCount

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) GetRouteCount() int64`

GetRouteCount returns the RouteCount field if non-nil, zero value otherwise.

### GetRouteCountOk

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) GetRouteCountOk() (*int64, bool)`

GetRouteCountOk returns a tuple with the RouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteCount

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) SetRouteCount(v int64)`

SetRouteCount sets RouteCount field to given value.

### HasRouteCount

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) HasRouteCount() bool`

HasRouteCount returns a boolean if a field has been set.

### GetVrfName

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *V1DeviceRoutingVrfBgpRouteCountPostResponseRouteCount) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



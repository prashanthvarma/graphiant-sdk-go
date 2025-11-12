# V1DeviceRoutingRibRouteCountPostResponseRouteCount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RouteCount** | Pointer to **int64** | Total installed route count in a vrf (required) | [optional] 
**VrfName** | Pointer to **string** | Valid configured VRF name (required) | [optional] 

## Methods

### NewV1DeviceRoutingRibRouteCountPostResponseRouteCount

`func NewV1DeviceRoutingRibRouteCountPostResponseRouteCount() *V1DeviceRoutingRibRouteCountPostResponseRouteCount`

NewV1DeviceRoutingRibRouteCountPostResponseRouteCount instantiates a new V1DeviceRoutingRibRouteCountPostResponseRouteCount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingRibRouteCountPostResponseRouteCountWithDefaults

`func NewV1DeviceRoutingRibRouteCountPostResponseRouteCountWithDefaults() *V1DeviceRoutingRibRouteCountPostResponseRouteCount`

NewV1DeviceRoutingRibRouteCountPostResponseRouteCountWithDefaults instantiates a new V1DeviceRoutingRibRouteCountPostResponseRouteCount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRouteCount

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) GetRouteCount() int64`

GetRouteCount returns the RouteCount field if non-nil, zero value otherwise.

### GetRouteCountOk

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) GetRouteCountOk() (*int64, bool)`

GetRouteCountOk returns a tuple with the RouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteCount

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) SetRouteCount(v int64)`

SetRouteCount sets RouteCount field to given value.

### HasRouteCount

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) HasRouteCount() bool`

HasRouteCount returns a boolean if a field has been set.

### GetVrfName

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *V1DeviceRoutingRibRouteCountPostResponseRouteCount) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



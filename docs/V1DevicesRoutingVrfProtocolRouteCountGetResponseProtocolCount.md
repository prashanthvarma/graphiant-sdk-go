# V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Protocol** | Pointer to **string** | Configured protocol (required) | [optional] 
**RouteCount** | Pointer to [**RoutingAfiRouteCount**](RoutingAfiRouteCount.md) |  | [optional] 

## Methods

### NewV1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount

`func NewV1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount() *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount`

NewV1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount instantiates a new V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCountWithDefaults

`func NewV1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCountWithDefaults() *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount`

NewV1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCountWithDefaults instantiates a new V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProtocol

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetRouteCount

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) GetRouteCount() RoutingAfiRouteCount`

GetRouteCount returns the RouteCount field if non-nil, zero value otherwise.

### GetRouteCountOk

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) GetRouteCountOk() (*RoutingAfiRouteCount, bool)`

GetRouteCountOk returns a tuple with the RouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteCount

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) SetRouteCount(v RoutingAfiRouteCount)`

SetRouteCount sets RouteCount field to given value.

### HasRouteCount

`func (o *V1DevicesRoutingVrfProtocolRouteCountGetResponseProtocolCount) HasRouteCount() bool`

HasRouteCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



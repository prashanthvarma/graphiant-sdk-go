# RoutingOspfRoute

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IpPrefix** | Pointer to **string** | IPv4 or IPv6 Prefix (required) | [optional] 
**Path** | Pointer to [**[]RoutingOspfNextHop**](RoutingOspfNextHop.md) |  | [optional] 

## Methods

### NewRoutingOspfRoute

`func NewRoutingOspfRoute() *RoutingOspfRoute`

NewRoutingOspfRoute instantiates a new RoutingOspfRoute object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspfRouteWithDefaults

`func NewRoutingOspfRouteWithDefaults() *RoutingOspfRoute`

NewRoutingOspfRouteWithDefaults instantiates a new RoutingOspfRoute object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIpPrefix

`func (o *RoutingOspfRoute) GetIpPrefix() string`

GetIpPrefix returns the IpPrefix field if non-nil, zero value otherwise.

### GetIpPrefixOk

`func (o *RoutingOspfRoute) GetIpPrefixOk() (*string, bool)`

GetIpPrefixOk returns a tuple with the IpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpPrefix

`func (o *RoutingOspfRoute) SetIpPrefix(v string)`

SetIpPrefix sets IpPrefix field to given value.

### HasIpPrefix

`func (o *RoutingOspfRoute) HasIpPrefix() bool`

HasIpPrefix returns a boolean if a field has been set.

### GetPath

`func (o *RoutingOspfRoute) GetPath() []RoutingOspfNextHop`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *RoutingOspfRoute) GetPathOk() (*[]RoutingOspfNextHop, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *RoutingOspfRoute) SetPath(v []RoutingOspfNextHop)`

SetPath sets Path field to given value.

### HasPath

`func (o *RoutingOspfRoute) HasPath() bool`

HasPath returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



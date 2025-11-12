# RoutingOspfNextHop

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EgressInterface** | Pointer to **string** | Interface name (required) | [optional] 
**LastModified** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Metric** | Pointer to **int32** | value &gt; 0 (required) | [optional] 
**NextHop** | Pointer to **string** | IPv4 or IPv6 Nexthop (required) | [optional] 
**Tag** | Pointer to **int32** | admin assigned number (required) | [optional] 
**Type** | Pointer to **string** | route type (required) | [optional] 

## Methods

### NewRoutingOspfNextHop

`func NewRoutingOspfNextHop() *RoutingOspfNextHop`

NewRoutingOspfNextHop instantiates a new RoutingOspfNextHop object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspfNextHopWithDefaults

`func NewRoutingOspfNextHopWithDefaults() *RoutingOspfNextHop`

NewRoutingOspfNextHopWithDefaults instantiates a new RoutingOspfNextHop object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEgressInterface

`func (o *RoutingOspfNextHop) GetEgressInterface() string`

GetEgressInterface returns the EgressInterface field if non-nil, zero value otherwise.

### GetEgressInterfaceOk

`func (o *RoutingOspfNextHop) GetEgressInterfaceOk() (*string, bool)`

GetEgressInterfaceOk returns a tuple with the EgressInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEgressInterface

`func (o *RoutingOspfNextHop) SetEgressInterface(v string)`

SetEgressInterface sets EgressInterface field to given value.

### HasEgressInterface

`func (o *RoutingOspfNextHop) HasEgressInterface() bool`

HasEgressInterface returns a boolean if a field has been set.

### GetLastModified

`func (o *RoutingOspfNextHop) GetLastModified() GoogleProtobufTimestamp`

GetLastModified returns the LastModified field if non-nil, zero value otherwise.

### GetLastModifiedOk

`func (o *RoutingOspfNextHop) GetLastModifiedOk() (*GoogleProtobufTimestamp, bool)`

GetLastModifiedOk returns a tuple with the LastModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModified

`func (o *RoutingOspfNextHop) SetLastModified(v GoogleProtobufTimestamp)`

SetLastModified sets LastModified field to given value.

### HasLastModified

`func (o *RoutingOspfNextHop) HasLastModified() bool`

HasLastModified returns a boolean if a field has been set.

### GetMetric

`func (o *RoutingOspfNextHop) GetMetric() int32`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *RoutingOspfNextHop) GetMetricOk() (*int32, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *RoutingOspfNextHop) SetMetric(v int32)`

SetMetric sets Metric field to given value.

### HasMetric

`func (o *RoutingOspfNextHop) HasMetric() bool`

HasMetric returns a boolean if a field has been set.

### GetNextHop

`func (o *RoutingOspfNextHop) GetNextHop() string`

GetNextHop returns the NextHop field if non-nil, zero value otherwise.

### GetNextHopOk

`func (o *RoutingOspfNextHop) GetNextHopOk() (*string, bool)`

GetNextHopOk returns a tuple with the NextHop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHop

`func (o *RoutingOspfNextHop) SetNextHop(v string)`

SetNextHop sets NextHop field to given value.

### HasNextHop

`func (o *RoutingOspfNextHop) HasNextHop() bool`

HasNextHop returns a boolean if a field has been set.

### GetTag

`func (o *RoutingOspfNextHop) GetTag() int32`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *RoutingOspfNextHop) GetTagOk() (*int32, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *RoutingOspfNextHop) SetTag(v int32)`

SetTag sets Tag field to given value.

### HasTag

`func (o *RoutingOspfNextHop) HasTag() bool`

HasTag returns a boolean if a field has been set.

### GetType

`func (o *RoutingOspfNextHop) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RoutingOspfNextHop) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RoutingOspfNextHop) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RoutingOspfNextHop) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



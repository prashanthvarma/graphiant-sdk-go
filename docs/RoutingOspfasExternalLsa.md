# RoutingOspfasExternalLsa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ForwardingAddress** | Pointer to **string** |  | [optional] 
**Metric** | Pointer to **int32** |  | [optional] 
**MetricType** | Pointer to **string** |  | [optional] 
**NetworkMask** | Pointer to **int32** |  | [optional] 
**Tag** | Pointer to **int32** |  | [optional] 
**TosMetric** | Pointer to [**RoutingOspflsaTosMetric**](RoutingOspflsaTosMetric.md) |  | [optional] 

## Methods

### NewRoutingOspfasExternalLsa

`func NewRoutingOspfasExternalLsa() *RoutingOspfasExternalLsa`

NewRoutingOspfasExternalLsa instantiates a new RoutingOspfasExternalLsa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspfasExternalLsaWithDefaults

`func NewRoutingOspfasExternalLsaWithDefaults() *RoutingOspfasExternalLsa`

NewRoutingOspfasExternalLsaWithDefaults instantiates a new RoutingOspfasExternalLsa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForwardingAddress

`func (o *RoutingOspfasExternalLsa) GetForwardingAddress() string`

GetForwardingAddress returns the ForwardingAddress field if non-nil, zero value otherwise.

### GetForwardingAddressOk

`func (o *RoutingOspfasExternalLsa) GetForwardingAddressOk() (*string, bool)`

GetForwardingAddressOk returns a tuple with the ForwardingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardingAddress

`func (o *RoutingOspfasExternalLsa) SetForwardingAddress(v string)`

SetForwardingAddress sets ForwardingAddress field to given value.

### HasForwardingAddress

`func (o *RoutingOspfasExternalLsa) HasForwardingAddress() bool`

HasForwardingAddress returns a boolean if a field has been set.

### GetMetric

`func (o *RoutingOspfasExternalLsa) GetMetric() int32`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *RoutingOspfasExternalLsa) GetMetricOk() (*int32, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *RoutingOspfasExternalLsa) SetMetric(v int32)`

SetMetric sets Metric field to given value.

### HasMetric

`func (o *RoutingOspfasExternalLsa) HasMetric() bool`

HasMetric returns a boolean if a field has been set.

### GetMetricType

`func (o *RoutingOspfasExternalLsa) GetMetricType() string`

GetMetricType returns the MetricType field if non-nil, zero value otherwise.

### GetMetricTypeOk

`func (o *RoutingOspfasExternalLsa) GetMetricTypeOk() (*string, bool)`

GetMetricTypeOk returns a tuple with the MetricType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricType

`func (o *RoutingOspfasExternalLsa) SetMetricType(v string)`

SetMetricType sets MetricType field to given value.

### HasMetricType

`func (o *RoutingOspfasExternalLsa) HasMetricType() bool`

HasMetricType returns a boolean if a field has been set.

### GetNetworkMask

`func (o *RoutingOspfasExternalLsa) GetNetworkMask() int32`

GetNetworkMask returns the NetworkMask field if non-nil, zero value otherwise.

### GetNetworkMaskOk

`func (o *RoutingOspfasExternalLsa) GetNetworkMaskOk() (*int32, bool)`

GetNetworkMaskOk returns a tuple with the NetworkMask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkMask

`func (o *RoutingOspfasExternalLsa) SetNetworkMask(v int32)`

SetNetworkMask sets NetworkMask field to given value.

### HasNetworkMask

`func (o *RoutingOspfasExternalLsa) HasNetworkMask() bool`

HasNetworkMask returns a boolean if a field has been set.

### GetTag

`func (o *RoutingOspfasExternalLsa) GetTag() int32`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *RoutingOspfasExternalLsa) GetTagOk() (*int32, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *RoutingOspfasExternalLsa) SetTag(v int32)`

SetTag sets Tag field to given value.

### HasTag

`func (o *RoutingOspfasExternalLsa) HasTag() bool`

HasTag returns a boolean if a field has been set.

### GetTosMetric

`func (o *RoutingOspfasExternalLsa) GetTosMetric() RoutingOspflsaTosMetric`

GetTosMetric returns the TosMetric field if non-nil, zero value otherwise.

### GetTosMetricOk

`func (o *RoutingOspfasExternalLsa) GetTosMetricOk() (*RoutingOspflsaTosMetric, bool)`

GetTosMetricOk returns a tuple with the TosMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTosMetric

`func (o *RoutingOspfasExternalLsa) SetTosMetric(v RoutingOspflsaTosMetric)`

SetTosMetric sets TosMetric field to given value.

### HasTosMetric

`func (o *RoutingOspfasExternalLsa) HasTosMetric() bool`

HasTosMetric returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



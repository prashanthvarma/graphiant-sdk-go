# RoutingOspfSummaryLsa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NetworkMask** | Pointer to **int32** |  | [optional] 
**TosMetric** | Pointer to [**RoutingOspflsaTosMetric**](RoutingOspflsaTosMetric.md) |  | [optional] 

## Methods

### NewRoutingOspfSummaryLsa

`func NewRoutingOspfSummaryLsa() *RoutingOspfSummaryLsa`

NewRoutingOspfSummaryLsa instantiates a new RoutingOspfSummaryLsa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspfSummaryLsaWithDefaults

`func NewRoutingOspfSummaryLsaWithDefaults() *RoutingOspfSummaryLsa`

NewRoutingOspfSummaryLsaWithDefaults instantiates a new RoutingOspfSummaryLsa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworkMask

`func (o *RoutingOspfSummaryLsa) GetNetworkMask() int32`

GetNetworkMask returns the NetworkMask field if non-nil, zero value otherwise.

### GetNetworkMaskOk

`func (o *RoutingOspfSummaryLsa) GetNetworkMaskOk() (*int32, bool)`

GetNetworkMaskOk returns a tuple with the NetworkMask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkMask

`func (o *RoutingOspfSummaryLsa) SetNetworkMask(v int32)`

SetNetworkMask sets NetworkMask field to given value.

### HasNetworkMask

`func (o *RoutingOspfSummaryLsa) HasNetworkMask() bool`

HasNetworkMask returns a boolean if a field has been set.

### GetTosMetric

`func (o *RoutingOspfSummaryLsa) GetTosMetric() RoutingOspflsaTosMetric`

GetTosMetric returns the TosMetric field if non-nil, zero value otherwise.

### GetTosMetricOk

`func (o *RoutingOspfSummaryLsa) GetTosMetricOk() (*RoutingOspflsaTosMetric, bool)`

GetTosMetricOk returns a tuple with the TosMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTosMetric

`func (o *RoutingOspfSummaryLsa) SetTosMetric(v RoutingOspflsaTosMetric)`

SetTosMetric sets TosMetric field to given value.

### HasTosMetric

`func (o *RoutingOspfSummaryLsa) HasTosMetric() bool`

HasTosMetric returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



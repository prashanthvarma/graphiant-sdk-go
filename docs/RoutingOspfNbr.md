# RoutingOspfNbr

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** | v4 or v6 Address (required) | [optional] 
**Cost** | Pointer to **int32** | cost (required) | [optional] 
**DeadTimer** | Pointer to **int32** | Dead Timer (required) | [optional] 
**LastStateChange** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**RouterId** | Pointer to **string** | Router ID (required) | [optional] 
**State** | Pointer to **string** | interface state (required) | [optional] 

## Methods

### NewRoutingOspfNbr

`func NewRoutingOspfNbr() *RoutingOspfNbr`

NewRoutingOspfNbr instantiates a new RoutingOspfNbr object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspfNbrWithDefaults

`func NewRoutingOspfNbrWithDefaults() *RoutingOspfNbr`

NewRoutingOspfNbrWithDefaults instantiates a new RoutingOspfNbr object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *RoutingOspfNbr) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *RoutingOspfNbr) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *RoutingOspfNbr) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *RoutingOspfNbr) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetCost

`func (o *RoutingOspfNbr) GetCost() int32`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *RoutingOspfNbr) GetCostOk() (*int32, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *RoutingOspfNbr) SetCost(v int32)`

SetCost sets Cost field to given value.

### HasCost

`func (o *RoutingOspfNbr) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetDeadTimer

`func (o *RoutingOspfNbr) GetDeadTimer() int32`

GetDeadTimer returns the DeadTimer field if non-nil, zero value otherwise.

### GetDeadTimerOk

`func (o *RoutingOspfNbr) GetDeadTimerOk() (*int32, bool)`

GetDeadTimerOk returns a tuple with the DeadTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadTimer

`func (o *RoutingOspfNbr) SetDeadTimer(v int32)`

SetDeadTimer sets DeadTimer field to given value.

### HasDeadTimer

`func (o *RoutingOspfNbr) HasDeadTimer() bool`

HasDeadTimer returns a boolean if a field has been set.

### GetLastStateChange

`func (o *RoutingOspfNbr) GetLastStateChange() GoogleProtobufTimestamp`

GetLastStateChange returns the LastStateChange field if non-nil, zero value otherwise.

### GetLastStateChangeOk

`func (o *RoutingOspfNbr) GetLastStateChangeOk() (*GoogleProtobufTimestamp, bool)`

GetLastStateChangeOk returns a tuple with the LastStateChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastStateChange

`func (o *RoutingOspfNbr) SetLastStateChange(v GoogleProtobufTimestamp)`

SetLastStateChange sets LastStateChange field to given value.

### HasLastStateChange

`func (o *RoutingOspfNbr) HasLastStateChange() bool`

HasLastStateChange returns a boolean if a field has been set.

### GetRouterId

`func (o *RoutingOspfNbr) GetRouterId() string`

GetRouterId returns the RouterId field if non-nil, zero value otherwise.

### GetRouterIdOk

`func (o *RoutingOspfNbr) GetRouterIdOk() (*string, bool)`

GetRouterIdOk returns a tuple with the RouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterId

`func (o *RoutingOspfNbr) SetRouterId(v string)`

SetRouterId sets RouterId field to given value.

### HasRouterId

`func (o *RoutingOspfNbr) HasRouterId() bool`

HasRouterId returns a boolean if a field has been set.

### GetState

`func (o *RoutingOspfNbr) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *RoutingOspfNbr) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *RoutingOspfNbr) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *RoutingOspfNbr) HasState() bool`

HasState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# RoutingOspfInterface

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BdrIpAddr** | Pointer to **string** | Router IP Address (required) | [optional] 
**BdrRouterId** | Pointer to **string** | BDR Router ID (required) | [optional] 
**DrIpAddr** | Pointer to **string** | Router IP Address (required) | [optional] 
**DrRouterId** | Pointer to **string** | Router ID (required) | [optional] 
**HelloInterval** | Pointer to **string** |  | [optional] 
**HelloTimer** | Pointer to **string** | Timer in seconds (required) | [optional] 
**Name** | Pointer to **string** | Interface name (required) | [optional] 
**Neighbors** | Pointer to **[]string** |  | [optional] 
**State** | Pointer to **string** | interface state (required) | [optional] 
**WaitTimer** | Pointer to **string** | Timer in seconds (required) | [optional] 

## Methods

### NewRoutingOspfInterface

`func NewRoutingOspfInterface() *RoutingOspfInterface`

NewRoutingOspfInterface instantiates a new RoutingOspfInterface object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspfInterfaceWithDefaults

`func NewRoutingOspfInterfaceWithDefaults() *RoutingOspfInterface`

NewRoutingOspfInterfaceWithDefaults instantiates a new RoutingOspfInterface object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBdrIpAddr

`func (o *RoutingOspfInterface) GetBdrIpAddr() string`

GetBdrIpAddr returns the BdrIpAddr field if non-nil, zero value otherwise.

### GetBdrIpAddrOk

`func (o *RoutingOspfInterface) GetBdrIpAddrOk() (*string, bool)`

GetBdrIpAddrOk returns a tuple with the BdrIpAddr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdrIpAddr

`func (o *RoutingOspfInterface) SetBdrIpAddr(v string)`

SetBdrIpAddr sets BdrIpAddr field to given value.

### HasBdrIpAddr

`func (o *RoutingOspfInterface) HasBdrIpAddr() bool`

HasBdrIpAddr returns a boolean if a field has been set.

### GetBdrRouterId

`func (o *RoutingOspfInterface) GetBdrRouterId() string`

GetBdrRouterId returns the BdrRouterId field if non-nil, zero value otherwise.

### GetBdrRouterIdOk

`func (o *RoutingOspfInterface) GetBdrRouterIdOk() (*string, bool)`

GetBdrRouterIdOk returns a tuple with the BdrRouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdrRouterId

`func (o *RoutingOspfInterface) SetBdrRouterId(v string)`

SetBdrRouterId sets BdrRouterId field to given value.

### HasBdrRouterId

`func (o *RoutingOspfInterface) HasBdrRouterId() bool`

HasBdrRouterId returns a boolean if a field has been set.

### GetDrIpAddr

`func (o *RoutingOspfInterface) GetDrIpAddr() string`

GetDrIpAddr returns the DrIpAddr field if non-nil, zero value otherwise.

### GetDrIpAddrOk

`func (o *RoutingOspfInterface) GetDrIpAddrOk() (*string, bool)`

GetDrIpAddrOk returns a tuple with the DrIpAddr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrIpAddr

`func (o *RoutingOspfInterface) SetDrIpAddr(v string)`

SetDrIpAddr sets DrIpAddr field to given value.

### HasDrIpAddr

`func (o *RoutingOspfInterface) HasDrIpAddr() bool`

HasDrIpAddr returns a boolean if a field has been set.

### GetDrRouterId

`func (o *RoutingOspfInterface) GetDrRouterId() string`

GetDrRouterId returns the DrRouterId field if non-nil, zero value otherwise.

### GetDrRouterIdOk

`func (o *RoutingOspfInterface) GetDrRouterIdOk() (*string, bool)`

GetDrRouterIdOk returns a tuple with the DrRouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrRouterId

`func (o *RoutingOspfInterface) SetDrRouterId(v string)`

SetDrRouterId sets DrRouterId field to given value.

### HasDrRouterId

`func (o *RoutingOspfInterface) HasDrRouterId() bool`

HasDrRouterId returns a boolean if a field has been set.

### GetHelloInterval

`func (o *RoutingOspfInterface) GetHelloInterval() string`

GetHelloInterval returns the HelloInterval field if non-nil, zero value otherwise.

### GetHelloIntervalOk

`func (o *RoutingOspfInterface) GetHelloIntervalOk() (*string, bool)`

GetHelloIntervalOk returns a tuple with the HelloInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelloInterval

`func (o *RoutingOspfInterface) SetHelloInterval(v string)`

SetHelloInterval sets HelloInterval field to given value.

### HasHelloInterval

`func (o *RoutingOspfInterface) HasHelloInterval() bool`

HasHelloInterval returns a boolean if a field has been set.

### GetHelloTimer

`func (o *RoutingOspfInterface) GetHelloTimer() string`

GetHelloTimer returns the HelloTimer field if non-nil, zero value otherwise.

### GetHelloTimerOk

`func (o *RoutingOspfInterface) GetHelloTimerOk() (*string, bool)`

GetHelloTimerOk returns a tuple with the HelloTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelloTimer

`func (o *RoutingOspfInterface) SetHelloTimer(v string)`

SetHelloTimer sets HelloTimer field to given value.

### HasHelloTimer

`func (o *RoutingOspfInterface) HasHelloTimer() bool`

HasHelloTimer returns a boolean if a field has been set.

### GetName

`func (o *RoutingOspfInterface) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoutingOspfInterface) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoutingOspfInterface) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RoutingOspfInterface) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNeighbors

`func (o *RoutingOspfInterface) GetNeighbors() []string`

GetNeighbors returns the Neighbors field if non-nil, zero value otherwise.

### GetNeighborsOk

`func (o *RoutingOspfInterface) GetNeighborsOk() (*[]string, bool)`

GetNeighborsOk returns a tuple with the Neighbors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeighbors

`func (o *RoutingOspfInterface) SetNeighbors(v []string)`

SetNeighbors sets Neighbors field to given value.

### HasNeighbors

`func (o *RoutingOspfInterface) HasNeighbors() bool`

HasNeighbors returns a boolean if a field has been set.

### GetState

`func (o *RoutingOspfInterface) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *RoutingOspfInterface) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *RoutingOspfInterface) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *RoutingOspfInterface) HasState() bool`

HasState returns a boolean if a field has been set.

### GetWaitTimer

`func (o *RoutingOspfInterface) GetWaitTimer() string`

GetWaitTimer returns the WaitTimer field if non-nil, zero value otherwise.

### GetWaitTimerOk

`func (o *RoutingOspfInterface) GetWaitTimerOk() (*string, bool)`

GetWaitTimerOk returns a tuple with the WaitTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaitTimer

`func (o *RoutingOspfInterface) SetWaitTimer(v string)`

SetWaitTimer sets WaitTimer field to given value.

### HasWaitTimer

`func (o *RoutingOspfInterface) HasWaitTimer() bool`

HasWaitTimer returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



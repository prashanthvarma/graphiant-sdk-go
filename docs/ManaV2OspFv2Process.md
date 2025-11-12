# ManaV2OspFv2Process

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminDistance** | Pointer to **int32** | Administrative Distance for routes installed | [optional] 
**Areas** | Pointer to [**[]ManaV2OspfArea**](ManaV2OspfArea.md) |  | [optional] 
**AutoRouterId** | Pointer to **bool** |  | [optional] 
**DefaultOriginate** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**RedistributedProtocols** | Pointer to [**[]ManaV2OspfRedistribute**](ManaV2OspfRedistribute.md) |  | [optional] 
**RouterId** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2OspFv2Process

`func NewManaV2OspFv2Process() *ManaV2OspFv2Process`

NewManaV2OspFv2Process instantiates a new ManaV2OspFv2Process object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2OspFv2ProcessWithDefaults

`func NewManaV2OspFv2ProcessWithDefaults() *ManaV2OspFv2Process`

NewManaV2OspFv2ProcessWithDefaults instantiates a new ManaV2OspFv2Process object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminDistance

`func (o *ManaV2OspFv2Process) GetAdminDistance() int32`

GetAdminDistance returns the AdminDistance field if non-nil, zero value otherwise.

### GetAdminDistanceOk

`func (o *ManaV2OspFv2Process) GetAdminDistanceOk() (*int32, bool)`

GetAdminDistanceOk returns a tuple with the AdminDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminDistance

`func (o *ManaV2OspFv2Process) SetAdminDistance(v int32)`

SetAdminDistance sets AdminDistance field to given value.

### HasAdminDistance

`func (o *ManaV2OspFv2Process) HasAdminDistance() bool`

HasAdminDistance returns a boolean if a field has been set.

### GetAreas

`func (o *ManaV2OspFv2Process) GetAreas() []ManaV2OspfArea`

GetAreas returns the Areas field if non-nil, zero value otherwise.

### GetAreasOk

`func (o *ManaV2OspFv2Process) GetAreasOk() (*[]ManaV2OspfArea, bool)`

GetAreasOk returns a tuple with the Areas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreas

`func (o *ManaV2OspFv2Process) SetAreas(v []ManaV2OspfArea)`

SetAreas sets Areas field to given value.

### HasAreas

`func (o *ManaV2OspFv2Process) HasAreas() bool`

HasAreas returns a boolean if a field has been set.

### GetAutoRouterId

`func (o *ManaV2OspFv2Process) GetAutoRouterId() bool`

GetAutoRouterId returns the AutoRouterId field if non-nil, zero value otherwise.

### GetAutoRouterIdOk

`func (o *ManaV2OspFv2Process) GetAutoRouterIdOk() (*bool, bool)`

GetAutoRouterIdOk returns a tuple with the AutoRouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRouterId

`func (o *ManaV2OspFv2Process) SetAutoRouterId(v bool)`

SetAutoRouterId sets AutoRouterId field to given value.

### HasAutoRouterId

`func (o *ManaV2OspFv2Process) HasAutoRouterId() bool`

HasAutoRouterId returns a boolean if a field has been set.

### GetDefaultOriginate

`func (o *ManaV2OspFv2Process) GetDefaultOriginate() string`

GetDefaultOriginate returns the DefaultOriginate field if non-nil, zero value otherwise.

### GetDefaultOriginateOk

`func (o *ManaV2OspFv2Process) GetDefaultOriginateOk() (*string, bool)`

GetDefaultOriginateOk returns a tuple with the DefaultOriginate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultOriginate

`func (o *ManaV2OspFv2Process) SetDefaultOriginate(v string)`

SetDefaultOriginate sets DefaultOriginate field to given value.

### HasDefaultOriginate

`func (o *ManaV2OspFv2Process) HasDefaultOriginate() bool`

HasDefaultOriginate returns a boolean if a field has been set.

### GetId

`func (o *ManaV2OspFv2Process) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2OspFv2Process) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2OspFv2Process) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2OspFv2Process) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRedistributedProtocols

`func (o *ManaV2OspFv2Process) GetRedistributedProtocols() []ManaV2OspfRedistribute`

GetRedistributedProtocols returns the RedistributedProtocols field if non-nil, zero value otherwise.

### GetRedistributedProtocolsOk

`func (o *ManaV2OspFv2Process) GetRedistributedProtocolsOk() (*[]ManaV2OspfRedistribute, bool)`

GetRedistributedProtocolsOk returns a tuple with the RedistributedProtocols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedistributedProtocols

`func (o *ManaV2OspFv2Process) SetRedistributedProtocols(v []ManaV2OspfRedistribute)`

SetRedistributedProtocols sets RedistributedProtocols field to given value.

### HasRedistributedProtocols

`func (o *ManaV2OspFv2Process) HasRedistributedProtocols() bool`

HasRedistributedProtocols returns a boolean if a field has been set.

### GetRouterId

`func (o *ManaV2OspFv2Process) GetRouterId() string`

GetRouterId returns the RouterId field if non-nil, zero value otherwise.

### GetRouterIdOk

`func (o *ManaV2OspFv2Process) GetRouterIdOk() (*string, bool)`

GetRouterIdOk returns a tuple with the RouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterId

`func (o *ManaV2OspFv2Process) SetRouterId(v string)`

SetRouterId sets RouterId field to given value.

### HasRouterId

`func (o *ManaV2OspFv2Process) HasRouterId() bool`

HasRouterId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2OspFv3Process

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminDistance** | Pointer to **int32** | Administrative Distance for routes installed | [optional] 
**Areas** | Pointer to [**[]ManaV2OspfArea**](ManaV2OspfArea.md) |  | [optional] 
**DefaultOriginate** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**RedistributedProtocols** | Pointer to [**[]ManaV2OspfRedistribute**](ManaV2OspfRedistribute.md) |  | [optional] 
**RouterId** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2OspFv3Process

`func NewManaV2OspFv3Process() *ManaV2OspFv3Process`

NewManaV2OspFv3Process instantiates a new ManaV2OspFv3Process object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2OspFv3ProcessWithDefaults

`func NewManaV2OspFv3ProcessWithDefaults() *ManaV2OspFv3Process`

NewManaV2OspFv3ProcessWithDefaults instantiates a new ManaV2OspFv3Process object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminDistance

`func (o *ManaV2OspFv3Process) GetAdminDistance() int32`

GetAdminDistance returns the AdminDistance field if non-nil, zero value otherwise.

### GetAdminDistanceOk

`func (o *ManaV2OspFv3Process) GetAdminDistanceOk() (*int32, bool)`

GetAdminDistanceOk returns a tuple with the AdminDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminDistance

`func (o *ManaV2OspFv3Process) SetAdminDistance(v int32)`

SetAdminDistance sets AdminDistance field to given value.

### HasAdminDistance

`func (o *ManaV2OspFv3Process) HasAdminDistance() bool`

HasAdminDistance returns a boolean if a field has been set.

### GetAreas

`func (o *ManaV2OspFv3Process) GetAreas() []ManaV2OspfArea`

GetAreas returns the Areas field if non-nil, zero value otherwise.

### GetAreasOk

`func (o *ManaV2OspFv3Process) GetAreasOk() (*[]ManaV2OspfArea, bool)`

GetAreasOk returns a tuple with the Areas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreas

`func (o *ManaV2OspFv3Process) SetAreas(v []ManaV2OspfArea)`

SetAreas sets Areas field to given value.

### HasAreas

`func (o *ManaV2OspFv3Process) HasAreas() bool`

HasAreas returns a boolean if a field has been set.

### GetDefaultOriginate

`func (o *ManaV2OspFv3Process) GetDefaultOriginate() string`

GetDefaultOriginate returns the DefaultOriginate field if non-nil, zero value otherwise.

### GetDefaultOriginateOk

`func (o *ManaV2OspFv3Process) GetDefaultOriginateOk() (*string, bool)`

GetDefaultOriginateOk returns a tuple with the DefaultOriginate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultOriginate

`func (o *ManaV2OspFv3Process) SetDefaultOriginate(v string)`

SetDefaultOriginate sets DefaultOriginate field to given value.

### HasDefaultOriginate

`func (o *ManaV2OspFv3Process) HasDefaultOriginate() bool`

HasDefaultOriginate returns a boolean if a field has been set.

### GetId

`func (o *ManaV2OspFv3Process) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2OspFv3Process) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2OspFv3Process) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2OspFv3Process) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRedistributedProtocols

`func (o *ManaV2OspFv3Process) GetRedistributedProtocols() []ManaV2OspfRedistribute`

GetRedistributedProtocols returns the RedistributedProtocols field if non-nil, zero value otherwise.

### GetRedistributedProtocolsOk

`func (o *ManaV2OspFv3Process) GetRedistributedProtocolsOk() (*[]ManaV2OspfRedistribute, bool)`

GetRedistributedProtocolsOk returns a tuple with the RedistributedProtocols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedistributedProtocols

`func (o *ManaV2OspFv3Process) SetRedistributedProtocols(v []ManaV2OspfRedistribute)`

SetRedistributedProtocols sets RedistributedProtocols field to given value.

### HasRedistributedProtocols

`func (o *ManaV2OspFv3Process) HasRedistributedProtocols() bool`

HasRedistributedProtocols returns a boolean if a field has been set.

### GetRouterId

`func (o *ManaV2OspFv3Process) GetRouterId() string`

GetRouterId returns the RouterId field if non-nil, zero value otherwise.

### GetRouterIdOk

`func (o *ManaV2OspFv3Process) GetRouterIdOk() (*string, bool)`

GetRouterIdOk returns a tuple with the RouterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterId

`func (o *ManaV2OspFv3Process) SetRouterId(v string)`

SetRouterId sets RouterId field to given value.

### HasRouterId

`func (o *ManaV2OspFv3Process) HasRouterId() bool`

HasRouterId returns a boolean if a field has been set.

### GetVersion

`func (o *ManaV2OspFv3Process) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ManaV2OspFv3Process) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ManaV2OspFv3Process) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ManaV2OspFv3Process) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



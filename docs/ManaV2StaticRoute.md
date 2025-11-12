# ManaV2StaticRoute

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdministrativeDistance** | Pointer to **int32** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**NextHop** | Pointer to [**ManaV2StaticRouteNexthop**](ManaV2StaticRouteNexthop.md) |  | [optional] 
**NextHops** | Pointer to [**[]ManaV2StaticRouteNexthop**](ManaV2StaticRouteNexthop.md) |  | [optional] 
**Prefix** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2StaticRoute

`func NewManaV2StaticRoute() *ManaV2StaticRoute`

NewManaV2StaticRoute instantiates a new ManaV2StaticRoute object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2StaticRouteWithDefaults

`func NewManaV2StaticRouteWithDefaults() *ManaV2StaticRoute`

NewManaV2StaticRouteWithDefaults instantiates a new ManaV2StaticRoute object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdministrativeDistance

`func (o *ManaV2StaticRoute) GetAdministrativeDistance() int32`

GetAdministrativeDistance returns the AdministrativeDistance field if non-nil, zero value otherwise.

### GetAdministrativeDistanceOk

`func (o *ManaV2StaticRoute) GetAdministrativeDistanceOk() (*int32, bool)`

GetAdministrativeDistanceOk returns a tuple with the AdministrativeDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrativeDistance

`func (o *ManaV2StaticRoute) SetAdministrativeDistance(v int32)`

SetAdministrativeDistance sets AdministrativeDistance field to given value.

### HasAdministrativeDistance

`func (o *ManaV2StaticRoute) HasAdministrativeDistance() bool`

HasAdministrativeDistance returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2StaticRoute) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2StaticRoute) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2StaticRoute) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2StaticRoute) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *ManaV2StaticRoute) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2StaticRoute) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2StaticRoute) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2StaticRoute) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNextHop

`func (o *ManaV2StaticRoute) GetNextHop() ManaV2StaticRouteNexthop`

GetNextHop returns the NextHop field if non-nil, zero value otherwise.

### GetNextHopOk

`func (o *ManaV2StaticRoute) GetNextHopOk() (*ManaV2StaticRouteNexthop, bool)`

GetNextHopOk returns a tuple with the NextHop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHop

`func (o *ManaV2StaticRoute) SetNextHop(v ManaV2StaticRouteNexthop)`

SetNextHop sets NextHop field to given value.

### HasNextHop

`func (o *ManaV2StaticRoute) HasNextHop() bool`

HasNextHop returns a boolean if a field has been set.

### GetNextHops

`func (o *ManaV2StaticRoute) GetNextHops() []ManaV2StaticRouteNexthop`

GetNextHops returns the NextHops field if non-nil, zero value otherwise.

### GetNextHopsOk

`func (o *ManaV2StaticRoute) GetNextHopsOk() (*[]ManaV2StaticRouteNexthop, bool)`

GetNextHopsOk returns a tuple with the NextHops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHops

`func (o *ManaV2StaticRoute) SetNextHops(v []ManaV2StaticRouteNexthop)`

SetNextHops sets NextHops field to given value.

### HasNextHops

`func (o *ManaV2StaticRoute) HasNextHops() bool`

HasNextHops returns a boolean if a field has been set.

### GetPrefix

`func (o *ManaV2StaticRoute) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *ManaV2StaticRoute) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *ManaV2StaticRoute) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.

### HasPrefix

`func (o *ManaV2StaticRoute) HasPrefix() bool`

HasPrefix returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



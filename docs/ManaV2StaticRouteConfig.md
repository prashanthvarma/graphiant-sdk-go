# ManaV2StaticRouteConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminDistance** | Pointer to **int32** |  | [optional] 
**AdministrativeDistance** | Pointer to [**ManaV2NullableAdministrativeDistance**](ManaV2NullableAdministrativeDistance.md) |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DestinationPrefix** | Pointer to **string** |  | [optional] 
**IpVersion** | Pointer to **int32** |  | [optional] 
**NextHop** | Pointer to [**ManaV2StaticRouteNexthopConfig**](ManaV2StaticRouteNexthopConfig.md) |  | [optional] 
**NextHops** | Pointer to [**[]ManaV2StaticRouteNexthopConfig**](ManaV2StaticRouteNexthopConfig.md) |  | [optional] 

## Methods

### NewManaV2StaticRouteConfig

`func NewManaV2StaticRouteConfig() *ManaV2StaticRouteConfig`

NewManaV2StaticRouteConfig instantiates a new ManaV2StaticRouteConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2StaticRouteConfigWithDefaults

`func NewManaV2StaticRouteConfigWithDefaults() *ManaV2StaticRouteConfig`

NewManaV2StaticRouteConfigWithDefaults instantiates a new ManaV2StaticRouteConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminDistance

`func (o *ManaV2StaticRouteConfig) GetAdminDistance() int32`

GetAdminDistance returns the AdminDistance field if non-nil, zero value otherwise.

### GetAdminDistanceOk

`func (o *ManaV2StaticRouteConfig) GetAdminDistanceOk() (*int32, bool)`

GetAdminDistanceOk returns a tuple with the AdminDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminDistance

`func (o *ManaV2StaticRouteConfig) SetAdminDistance(v int32)`

SetAdminDistance sets AdminDistance field to given value.

### HasAdminDistance

`func (o *ManaV2StaticRouteConfig) HasAdminDistance() bool`

HasAdminDistance returns a boolean if a field has been set.

### GetAdministrativeDistance

`func (o *ManaV2StaticRouteConfig) GetAdministrativeDistance() ManaV2NullableAdministrativeDistance`

GetAdministrativeDistance returns the AdministrativeDistance field if non-nil, zero value otherwise.

### GetAdministrativeDistanceOk

`func (o *ManaV2StaticRouteConfig) GetAdministrativeDistanceOk() (*ManaV2NullableAdministrativeDistance, bool)`

GetAdministrativeDistanceOk returns a tuple with the AdministrativeDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrativeDistance

`func (o *ManaV2StaticRouteConfig) SetAdministrativeDistance(v ManaV2NullableAdministrativeDistance)`

SetAdministrativeDistance sets AdministrativeDistance field to given value.

### HasAdministrativeDistance

`func (o *ManaV2StaticRouteConfig) HasAdministrativeDistance() bool`

HasAdministrativeDistance returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2StaticRouteConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2StaticRouteConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2StaticRouteConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2StaticRouteConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDestinationPrefix

`func (o *ManaV2StaticRouteConfig) GetDestinationPrefix() string`

GetDestinationPrefix returns the DestinationPrefix field if non-nil, zero value otherwise.

### GetDestinationPrefixOk

`func (o *ManaV2StaticRouteConfig) GetDestinationPrefixOk() (*string, bool)`

GetDestinationPrefixOk returns a tuple with the DestinationPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPrefix

`func (o *ManaV2StaticRouteConfig) SetDestinationPrefix(v string)`

SetDestinationPrefix sets DestinationPrefix field to given value.

### HasDestinationPrefix

`func (o *ManaV2StaticRouteConfig) HasDestinationPrefix() bool`

HasDestinationPrefix returns a boolean if a field has been set.

### GetIpVersion

`func (o *ManaV2StaticRouteConfig) GetIpVersion() int32`

GetIpVersion returns the IpVersion field if non-nil, zero value otherwise.

### GetIpVersionOk

`func (o *ManaV2StaticRouteConfig) GetIpVersionOk() (*int32, bool)`

GetIpVersionOk returns a tuple with the IpVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpVersion

`func (o *ManaV2StaticRouteConfig) SetIpVersion(v int32)`

SetIpVersion sets IpVersion field to given value.

### HasIpVersion

`func (o *ManaV2StaticRouteConfig) HasIpVersion() bool`

HasIpVersion returns a boolean if a field has been set.

### GetNextHop

`func (o *ManaV2StaticRouteConfig) GetNextHop() ManaV2StaticRouteNexthopConfig`

GetNextHop returns the NextHop field if non-nil, zero value otherwise.

### GetNextHopOk

`func (o *ManaV2StaticRouteConfig) GetNextHopOk() (*ManaV2StaticRouteNexthopConfig, bool)`

GetNextHopOk returns a tuple with the NextHop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHop

`func (o *ManaV2StaticRouteConfig) SetNextHop(v ManaV2StaticRouteNexthopConfig)`

SetNextHop sets NextHop field to given value.

### HasNextHop

`func (o *ManaV2StaticRouteConfig) HasNextHop() bool`

HasNextHop returns a boolean if a field has been set.

### GetNextHops

`func (o *ManaV2StaticRouteConfig) GetNextHops() []ManaV2StaticRouteNexthopConfig`

GetNextHops returns the NextHops field if non-nil, zero value otherwise.

### GetNextHopsOk

`func (o *ManaV2StaticRouteConfig) GetNextHopsOk() (*[]ManaV2StaticRouteNexthopConfig, bool)`

GetNextHopsOk returns a tuple with the NextHops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHops

`func (o *ManaV2StaticRouteConfig) SetNextHops(v []ManaV2StaticRouteNexthopConfig)`

SetNextHops sets NextHops field to given value.

### HasNextHops

`func (o *ManaV2StaticRouteConfig) HasNextHops() bool`

HasNextHops returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



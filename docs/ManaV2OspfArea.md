# ManaV2OspfArea

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AreaId** | Pointer to **string** |  | [optional] 
**Bfd** | Pointer to [**ManaV2BfdInstance**](ManaV2BfdInstance.md) |  | [optional] 
**BfdNeighbors** | Pointer to [**[]ManaV2BfdNeighbor**](ManaV2BfdNeighbor.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Interfaces** | Pointer to [**[]ManaV2OspfInterface**](ManaV2OspfInterface.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2OspfArea

`func NewManaV2OspfArea() *ManaV2OspfArea`

NewManaV2OspfArea instantiates a new ManaV2OspfArea object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2OspfAreaWithDefaults

`func NewManaV2OspfAreaWithDefaults() *ManaV2OspfArea`

NewManaV2OspfAreaWithDefaults instantiates a new ManaV2OspfArea object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAreaId

`func (o *ManaV2OspfArea) GetAreaId() string`

GetAreaId returns the AreaId field if non-nil, zero value otherwise.

### GetAreaIdOk

`func (o *ManaV2OspfArea) GetAreaIdOk() (*string, bool)`

GetAreaIdOk returns a tuple with the AreaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaId

`func (o *ManaV2OspfArea) SetAreaId(v string)`

SetAreaId sets AreaId field to given value.

### HasAreaId

`func (o *ManaV2OspfArea) HasAreaId() bool`

HasAreaId returns a boolean if a field has been set.

### GetBfd

`func (o *ManaV2OspfArea) GetBfd() ManaV2BfdInstance`

GetBfd returns the Bfd field if non-nil, zero value otherwise.

### GetBfdOk

`func (o *ManaV2OspfArea) GetBfdOk() (*ManaV2BfdInstance, bool)`

GetBfdOk returns a tuple with the Bfd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBfd

`func (o *ManaV2OspfArea) SetBfd(v ManaV2BfdInstance)`

SetBfd sets Bfd field to given value.

### HasBfd

`func (o *ManaV2OspfArea) HasBfd() bool`

HasBfd returns a boolean if a field has been set.

### GetBfdNeighbors

`func (o *ManaV2OspfArea) GetBfdNeighbors() []ManaV2BfdNeighbor`

GetBfdNeighbors returns the BfdNeighbors field if non-nil, zero value otherwise.

### GetBfdNeighborsOk

`func (o *ManaV2OspfArea) GetBfdNeighborsOk() (*[]ManaV2BfdNeighbor, bool)`

GetBfdNeighborsOk returns a tuple with the BfdNeighbors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBfdNeighbors

`func (o *ManaV2OspfArea) SetBfdNeighbors(v []ManaV2BfdNeighbor)`

SetBfdNeighbors sets BfdNeighbors field to given value.

### HasBfdNeighbors

`func (o *ManaV2OspfArea) HasBfdNeighbors() bool`

HasBfdNeighbors returns a boolean if a field has been set.

### GetId

`func (o *ManaV2OspfArea) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2OspfArea) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2OspfArea) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2OspfArea) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInterfaces

`func (o *ManaV2OspfArea) GetInterfaces() []ManaV2OspfInterface`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *ManaV2OspfArea) GetInterfacesOk() (*[]ManaV2OspfInterface, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *ManaV2OspfArea) SetInterfaces(v []ManaV2OspfInterface)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *ManaV2OspfArea) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetName

`func (o *ManaV2OspfArea) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2OspfArea) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2OspfArea) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2OspfArea) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ManaV2OspfArea) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2OspfArea) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2OspfArea) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2OspfArea) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



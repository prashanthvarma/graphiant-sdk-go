# ManaV2DeviceSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Author** | Pointer to [**CommonUserInfo**](CommonUserInfo.md) |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**CreatedOn** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Data** | Pointer to [**ManaV2DeviceSnapshotData**](ManaV2DeviceSnapshotData.md) |  | [optional] 
**Golden** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** | name for the snapshot | [optional] 

## Methods

### NewManaV2DeviceSnapshot

`func NewManaV2DeviceSnapshot() *ManaV2DeviceSnapshot`

NewManaV2DeviceSnapshot instantiates a new ManaV2DeviceSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DeviceSnapshotWithDefaults

`func NewManaV2DeviceSnapshotWithDefaults() *ManaV2DeviceSnapshot`

NewManaV2DeviceSnapshotWithDefaults instantiates a new ManaV2DeviceSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthor

`func (o *ManaV2DeviceSnapshot) GetAuthor() CommonUserInfo`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *ManaV2DeviceSnapshot) GetAuthorOk() (*CommonUserInfo, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *ManaV2DeviceSnapshot) SetAuthor(v CommonUserInfo)`

SetAuthor sets Author field to given value.

### HasAuthor

`func (o *ManaV2DeviceSnapshot) HasAuthor() bool`

HasAuthor returns a boolean if a field has been set.

### GetCategory

`func (o *ManaV2DeviceSnapshot) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *ManaV2DeviceSnapshot) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *ManaV2DeviceSnapshot) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *ManaV2DeviceSnapshot) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetCreatedOn

`func (o *ManaV2DeviceSnapshot) GetCreatedOn() GoogleProtobufTimestamp`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *ManaV2DeviceSnapshot) GetCreatedOnOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *ManaV2DeviceSnapshot) SetCreatedOn(v GoogleProtobufTimestamp)`

SetCreatedOn sets CreatedOn field to given value.

### HasCreatedOn

`func (o *ManaV2DeviceSnapshot) HasCreatedOn() bool`

HasCreatedOn returns a boolean if a field has been set.

### GetData

`func (o *ManaV2DeviceSnapshot) GetData() ManaV2DeviceSnapshotData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ManaV2DeviceSnapshot) GetDataOk() (*ManaV2DeviceSnapshotData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ManaV2DeviceSnapshot) SetData(v ManaV2DeviceSnapshotData)`

SetData sets Data field to given value.

### HasData

`func (o *ManaV2DeviceSnapshot) HasData() bool`

HasData returns a boolean if a field has been set.

### GetGolden

`func (o *ManaV2DeviceSnapshot) GetGolden() bool`

GetGolden returns the Golden field if non-nil, zero value otherwise.

### GetGoldenOk

`func (o *ManaV2DeviceSnapshot) GetGoldenOk() (*bool, bool)`

GetGoldenOk returns a tuple with the Golden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGolden

`func (o *ManaV2DeviceSnapshot) SetGolden(v bool)`

SetGolden sets Golden field to given value.

### HasGolden

`func (o *ManaV2DeviceSnapshot) HasGolden() bool`

HasGolden returns a boolean if a field has been set.

### GetId

`func (o *ManaV2DeviceSnapshot) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2DeviceSnapshot) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2DeviceSnapshot) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2DeviceSnapshot) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2DeviceSnapshot) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2DeviceSnapshot) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2DeviceSnapshot) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2DeviceSnapshot) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



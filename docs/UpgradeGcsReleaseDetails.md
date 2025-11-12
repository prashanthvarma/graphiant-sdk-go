# UpgradeGcsReleaseDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | Pointer to [**[]UpgradeGcsReleaseCategory**](UpgradeGcsReleaseCategory.md) |  | [optional] 
**Major** | Pointer to **bool** |  | [optional] 
**ReleaseTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewUpgradeGcsReleaseDetails

`func NewUpgradeGcsReleaseDetails() *UpgradeGcsReleaseDetails`

NewUpgradeGcsReleaseDetails instantiates a new UpgradeGcsReleaseDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpgradeGcsReleaseDetailsWithDefaults

`func NewUpgradeGcsReleaseDetailsWithDefaults() *UpgradeGcsReleaseDetails`

NewUpgradeGcsReleaseDetailsWithDefaults instantiates a new UpgradeGcsReleaseDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategory

`func (o *UpgradeGcsReleaseDetails) GetCategory() []UpgradeGcsReleaseCategory`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *UpgradeGcsReleaseDetails) GetCategoryOk() (*[]UpgradeGcsReleaseCategory, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *UpgradeGcsReleaseDetails) SetCategory(v []UpgradeGcsReleaseCategory)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *UpgradeGcsReleaseDetails) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetMajor

`func (o *UpgradeGcsReleaseDetails) GetMajor() bool`

GetMajor returns the Major field if non-nil, zero value otherwise.

### GetMajorOk

`func (o *UpgradeGcsReleaseDetails) GetMajorOk() (*bool, bool)`

GetMajorOk returns a tuple with the Major field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMajor

`func (o *UpgradeGcsReleaseDetails) SetMajor(v bool)`

SetMajor sets Major field to given value.

### HasMajor

`func (o *UpgradeGcsReleaseDetails) HasMajor() bool`

HasMajor returns a boolean if a field has been set.

### GetReleaseTs

`func (o *UpgradeGcsReleaseDetails) GetReleaseTs() GoogleProtobufTimestamp`

GetReleaseTs returns the ReleaseTs field if non-nil, zero value otherwise.

### GetReleaseTsOk

`func (o *UpgradeGcsReleaseDetails) GetReleaseTsOk() (*GoogleProtobufTimestamp, bool)`

GetReleaseTsOk returns a tuple with the ReleaseTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseTs

`func (o *UpgradeGcsReleaseDetails) SetReleaseTs(v GoogleProtobufTimestamp)`

SetReleaseTs sets ReleaseTs field to given value.

### HasReleaseTs

`func (o *UpgradeGcsReleaseDetails) HasReleaseTs() bool`

HasReleaseTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



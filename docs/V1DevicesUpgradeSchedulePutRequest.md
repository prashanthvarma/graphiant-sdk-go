# V1DevicesUpgradeSchedulePutRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] 
**DeviceIds** | Pointer to **[]int64** |  | [optional] 
**DeviceVersions** | Pointer to [**[]V1DevicesUpgradeSchedulePutRequestDeviceVersion**](V1DevicesUpgradeSchedulePutRequestDeviceVersion.md) |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Version** | Pointer to [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Methods

### NewV1DevicesUpgradeSchedulePutRequest

`func NewV1DevicesUpgradeSchedulePutRequest() *V1DevicesUpgradeSchedulePutRequest`

NewV1DevicesUpgradeSchedulePutRequest instantiates a new V1DevicesUpgradeSchedulePutRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesUpgradeSchedulePutRequestWithDefaults

`func NewV1DevicesUpgradeSchedulePutRequestWithDefaults() *V1DevicesUpgradeSchedulePutRequest`

NewV1DevicesUpgradeSchedulePutRequestWithDefaults instantiates a new V1DevicesUpgradeSchedulePutRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *V1DevicesUpgradeSchedulePutRequest) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *V1DevicesUpgradeSchedulePutRequest) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *V1DevicesUpgradeSchedulePutRequest) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *V1DevicesUpgradeSchedulePutRequest) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetDeviceIds

`func (o *V1DevicesUpgradeSchedulePutRequest) GetDeviceIds() []int64`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *V1DevicesUpgradeSchedulePutRequest) GetDeviceIdsOk() (*[]int64, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *V1DevicesUpgradeSchedulePutRequest) SetDeviceIds(v []int64)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *V1DevicesUpgradeSchedulePutRequest) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.

### GetDeviceVersions

`func (o *V1DevicesUpgradeSchedulePutRequest) GetDeviceVersions() []V1DevicesUpgradeSchedulePutRequestDeviceVersion`

GetDeviceVersions returns the DeviceVersions field if non-nil, zero value otherwise.

### GetDeviceVersionsOk

`func (o *V1DevicesUpgradeSchedulePutRequest) GetDeviceVersionsOk() (*[]V1DevicesUpgradeSchedulePutRequestDeviceVersion, bool)`

GetDeviceVersionsOk returns a tuple with the DeviceVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceVersions

`func (o *V1DevicesUpgradeSchedulePutRequest) SetDeviceVersions(v []V1DevicesUpgradeSchedulePutRequestDeviceVersion)`

SetDeviceVersions sets DeviceVersions field to given value.

### HasDeviceVersions

`func (o *V1DevicesUpgradeSchedulePutRequest) HasDeviceVersions() bool`

HasDeviceVersions returns a boolean if a field has been set.

### GetTs

`func (o *V1DevicesUpgradeSchedulePutRequest) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *V1DevicesUpgradeSchedulePutRequest) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *V1DevicesUpgradeSchedulePutRequest) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *V1DevicesUpgradeSchedulePutRequest) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetVersion

`func (o *V1DevicesUpgradeSchedulePutRequest) GetVersion() UpgradeSwVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *V1DevicesUpgradeSchedulePutRequest) GetVersionOk() (*UpgradeSwVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *V1DevicesUpgradeSchedulePutRequest) SetVersion(v UpgradeSwVersion)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *V1DevicesUpgradeSchedulePutRequest) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



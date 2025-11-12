# V1DevicesUpgradeSchedulePutRequestDeviceVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Version** | Pointer to [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Methods

### NewV1DevicesUpgradeSchedulePutRequestDeviceVersion

`func NewV1DevicesUpgradeSchedulePutRequestDeviceVersion() *V1DevicesUpgradeSchedulePutRequestDeviceVersion`

NewV1DevicesUpgradeSchedulePutRequestDeviceVersion instantiates a new V1DevicesUpgradeSchedulePutRequestDeviceVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesUpgradeSchedulePutRequestDeviceVersionWithDefaults

`func NewV1DevicesUpgradeSchedulePutRequestDeviceVersionWithDefaults() *V1DevicesUpgradeSchedulePutRequestDeviceVersion`

NewV1DevicesUpgradeSchedulePutRequestDeviceVersionWithDefaults instantiates a new V1DevicesUpgradeSchedulePutRequestDeviceVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetVersion

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) GetVersion() UpgradeSwVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) GetVersionOk() (*UpgradeSwVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) SetVersion(v UpgradeSwVersion)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *V1DevicesUpgradeSchedulePutRequestDeviceVersion) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



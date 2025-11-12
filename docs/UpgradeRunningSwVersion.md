# UpgradeRunningSwVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Version** | Pointer to [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Methods

### NewUpgradeRunningSwVersion

`func NewUpgradeRunningSwVersion() *UpgradeRunningSwVersion`

NewUpgradeRunningSwVersion instantiates a new UpgradeRunningSwVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpgradeRunningSwVersionWithDefaults

`func NewUpgradeRunningSwVersionWithDefaults() *UpgradeRunningSwVersion`

NewUpgradeRunningSwVersionWithDefaults instantiates a new UpgradeRunningSwVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *UpgradeRunningSwVersion) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *UpgradeRunningSwVersion) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *UpgradeRunningSwVersion) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *UpgradeRunningSwVersion) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetVersion

`func (o *UpgradeRunningSwVersion) GetVersion() UpgradeSwVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *UpgradeRunningSwVersion) GetVersionOk() (*UpgradeSwVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *UpgradeRunningSwVersion) SetVersion(v UpgradeSwVersion)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *UpgradeRunningSwVersion) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



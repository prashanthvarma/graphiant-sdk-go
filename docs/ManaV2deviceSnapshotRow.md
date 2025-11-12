# ManaV2deviceSnapshotRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**Region** | Pointer to **string** |  | [optional] 
**Site** | Pointer to **string** |  | [optional] 
**SnapshotCount** | Pointer to **int32** |  | [optional] 
**Snapshots** | Pointer to [**[]ManaV2DeviceSnapshot**](ManaV2DeviceSnapshot.md) |  | [optional] 
**Uptime** | Pointer to [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 

## Methods

### NewManaV2deviceSnapshotRow

`func NewManaV2deviceSnapshotRow() *ManaV2deviceSnapshotRow`

NewManaV2deviceSnapshotRow instantiates a new ManaV2deviceSnapshotRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2deviceSnapshotRowWithDefaults

`func NewManaV2deviceSnapshotRowWithDefaults() *ManaV2deviceSnapshotRow`

NewManaV2deviceSnapshotRowWithDefaults instantiates a new ManaV2deviceSnapshotRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *ManaV2deviceSnapshotRow) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *ManaV2deviceSnapshotRow) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *ManaV2deviceSnapshotRow) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *ManaV2deviceSnapshotRow) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetHostname

`func (o *ManaV2deviceSnapshotRow) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *ManaV2deviceSnapshotRow) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *ManaV2deviceSnapshotRow) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *ManaV2deviceSnapshotRow) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetRegion

`func (o *ManaV2deviceSnapshotRow) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *ManaV2deviceSnapshotRow) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *ManaV2deviceSnapshotRow) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *ManaV2deviceSnapshotRow) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetSite

`func (o *ManaV2deviceSnapshotRow) GetSite() string`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *ManaV2deviceSnapshotRow) GetSiteOk() (*string, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *ManaV2deviceSnapshotRow) SetSite(v string)`

SetSite sets Site field to given value.

### HasSite

`func (o *ManaV2deviceSnapshotRow) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetSnapshotCount

`func (o *ManaV2deviceSnapshotRow) GetSnapshotCount() int32`

GetSnapshotCount returns the SnapshotCount field if non-nil, zero value otherwise.

### GetSnapshotCountOk

`func (o *ManaV2deviceSnapshotRow) GetSnapshotCountOk() (*int32, bool)`

GetSnapshotCountOk returns a tuple with the SnapshotCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotCount

`func (o *ManaV2deviceSnapshotRow) SetSnapshotCount(v int32)`

SetSnapshotCount sets SnapshotCount field to given value.

### HasSnapshotCount

`func (o *ManaV2deviceSnapshotRow) HasSnapshotCount() bool`

HasSnapshotCount returns a boolean if a field has been set.

### GetSnapshots

`func (o *ManaV2deviceSnapshotRow) GetSnapshots() []ManaV2DeviceSnapshot`

GetSnapshots returns the Snapshots field if non-nil, zero value otherwise.

### GetSnapshotsOk

`func (o *ManaV2deviceSnapshotRow) GetSnapshotsOk() (*[]ManaV2DeviceSnapshot, bool)`

GetSnapshotsOk returns a tuple with the Snapshots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshots

`func (o *ManaV2deviceSnapshotRow) SetSnapshots(v []ManaV2DeviceSnapshot)`

SetSnapshots sets Snapshots field to given value.

### HasSnapshots

`func (o *ManaV2deviceSnapshotRow) HasSnapshots() bool`

HasSnapshots returns a boolean if a field has been set.

### GetUptime

`func (o *ManaV2deviceSnapshotRow) GetUptime() GoogleProtobufDuration`

GetUptime returns the Uptime field if non-nil, zero value otherwise.

### GetUptimeOk

`func (o *ManaV2deviceSnapshotRow) GetUptimeOk() (*GoogleProtobufDuration, bool)`

GetUptimeOk returns a tuple with the Uptime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUptime

`func (o *ManaV2deviceSnapshotRow) SetUptime(v GoogleProtobufDuration)`

SetUptime sets Uptime field to given value.

### HasUptime

`func (o *ManaV2deviceSnapshotRow) HasUptime() bool`

HasUptime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



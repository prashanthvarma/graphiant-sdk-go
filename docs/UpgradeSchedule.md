# UpgradeSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] 
**DeviceId** | Pointer to **int64** |  | [optional] 
**DownloadProgress** | Pointer to **int32** |  | [optional] 
**FailureReason** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Version** | Pointer to [**UpgradeSwVersion**](UpgradeSwVersion.md) |  | [optional] 

## Methods

### NewUpgradeSchedule

`func NewUpgradeSchedule() *UpgradeSchedule`

NewUpgradeSchedule instantiates a new UpgradeSchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpgradeScheduleWithDefaults

`func NewUpgradeScheduleWithDefaults() *UpgradeSchedule`

NewUpgradeScheduleWithDefaults instantiates a new UpgradeSchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *UpgradeSchedule) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *UpgradeSchedule) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *UpgradeSchedule) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *UpgradeSchedule) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetDeviceId

`func (o *UpgradeSchedule) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *UpgradeSchedule) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *UpgradeSchedule) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *UpgradeSchedule) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetDownloadProgress

`func (o *UpgradeSchedule) GetDownloadProgress() int32`

GetDownloadProgress returns the DownloadProgress field if non-nil, zero value otherwise.

### GetDownloadProgressOk

`func (o *UpgradeSchedule) GetDownloadProgressOk() (*int32, bool)`

GetDownloadProgressOk returns a tuple with the DownloadProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadProgress

`func (o *UpgradeSchedule) SetDownloadProgress(v int32)`

SetDownloadProgress sets DownloadProgress field to given value.

### HasDownloadProgress

`func (o *UpgradeSchedule) HasDownloadProgress() bool`

HasDownloadProgress returns a boolean if a field has been set.

### GetFailureReason

`func (o *UpgradeSchedule) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *UpgradeSchedule) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *UpgradeSchedule) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *UpgradeSchedule) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### GetState

`func (o *UpgradeSchedule) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *UpgradeSchedule) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *UpgradeSchedule) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *UpgradeSchedule) HasState() bool`

HasState returns a boolean if a field has been set.

### GetTs

`func (o *UpgradeSchedule) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *UpgradeSchedule) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *UpgradeSchedule) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *UpgradeSchedule) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetVersion

`func (o *UpgradeSchedule) GetVersion() UpgradeSwVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *UpgradeSchedule) GetVersionOk() (*UpgradeSwVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *UpgradeSchedule) SetVersion(v UpgradeSwVersion)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *UpgradeSchedule) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



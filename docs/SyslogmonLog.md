# SyslogmonLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Facility** | Pointer to **string** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**Level** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewSyslogmonLog

`func NewSyslogmonLog() *SyslogmonLog`

NewSyslogmonLog instantiates a new SyslogmonLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyslogmonLogWithDefaults

`func NewSyslogmonLogWithDefaults() *SyslogmonLog`

NewSyslogmonLogWithDefaults instantiates a new SyslogmonLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *SyslogmonLog) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *SyslogmonLog) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *SyslogmonLog) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *SyslogmonLog) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetFacility

`func (o *SyslogmonLog) GetFacility() string`

GetFacility returns the Facility field if non-nil, zero value otherwise.

### GetFacilityOk

`func (o *SyslogmonLog) GetFacilityOk() (*string, bool)`

GetFacilityOk returns a tuple with the Facility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacility

`func (o *SyslogmonLog) SetFacility(v string)`

SetFacility sets Facility field to given value.

### HasFacility

`func (o *SyslogmonLog) HasFacility() bool`

HasFacility returns a boolean if a field has been set.

### GetHostname

`func (o *SyslogmonLog) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *SyslogmonLog) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *SyslogmonLog) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *SyslogmonLog) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetLevel

`func (o *SyslogmonLog) GetLevel() string`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *SyslogmonLog) GetLevelOk() (*string, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *SyslogmonLog) SetLevel(v string)`

SetLevel sets Level field to given value.

### HasLevel

`func (o *SyslogmonLog) HasLevel() bool`

HasLevel returns a boolean if a field has been set.

### GetMessage

`func (o *SyslogmonLog) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SyslogmonLog) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SyslogmonLog) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *SyslogmonLog) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetTs

`func (o *SyslogmonLog) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *SyslogmonLog) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *SyslogmonLog) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *SyslogmonLog) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2ConsumerDeviceInformation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**LastUpdated** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Site** | Pointer to **int64** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2ConsumerDeviceInformation

`func NewManaV2ConsumerDeviceInformation() *ManaV2ConsumerDeviceInformation`

NewManaV2ConsumerDeviceInformation instantiates a new ManaV2ConsumerDeviceInformation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ConsumerDeviceInformationWithDefaults

`func NewManaV2ConsumerDeviceInformationWithDefaults() *ManaV2ConsumerDeviceInformation`

NewManaV2ConsumerDeviceInformationWithDefaults instantiates a new ManaV2ConsumerDeviceInformation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *ManaV2ConsumerDeviceInformation) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *ManaV2ConsumerDeviceInformation) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *ManaV2ConsumerDeviceInformation) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *ManaV2ConsumerDeviceInformation) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetLastUpdated

`func (o *ManaV2ConsumerDeviceInformation) GetLastUpdated() GoogleProtobufTimestamp`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *ManaV2ConsumerDeviceInformation) GetLastUpdatedOk() (*GoogleProtobufTimestamp, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *ManaV2ConsumerDeviceInformation) SetLastUpdated(v GoogleProtobufTimestamp)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *ManaV2ConsumerDeviceInformation) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### GetSite

`func (o *ManaV2ConsumerDeviceInformation) GetSite() int64`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *ManaV2ConsumerDeviceInformation) GetSiteOk() (*int64, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *ManaV2ConsumerDeviceInformation) SetSite(v int64)`

SetSite sets Site field to given value.

### HasSite

`func (o *ManaV2ConsumerDeviceInformation) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2ConsumerDeviceInformation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2ConsumerDeviceInformation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2ConsumerDeviceInformation) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2ConsumerDeviceInformation) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



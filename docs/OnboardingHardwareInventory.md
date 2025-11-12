# OnboardingHardwareInventory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedOn** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**CreatedOn** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**DeviceModel** | Pointer to **string** |  | [optional] 
**DeviceSerial** | Pointer to **string** |  | [optional] 
**EkCert** | Pointer to **string** |  | [optional] 
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**EnterpriseName** | Pointer to **string** |  | [optional] 
**GekPub** | Pointer to **string** |  | [optional] 
**IsCore** | Pointer to **bool** |  | [optional] 
**IsNew** | Pointer to **bool** |  | [optional] 
**IsRequested** | Pointer to **bool** |  | [optional] 
**ParentEnterpriseId** | Pointer to **int64** |  | [optional] 
**ParentEnterpriseName** | Pointer to **string** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**UseOauth** | Pointer to **bool** |  | [optional] 
**Uuid** | Pointer to **string** |  | [optional] 

## Methods

### NewOnboardingHardwareInventory

`func NewOnboardingHardwareInventory() *OnboardingHardwareInventory`

NewOnboardingHardwareInventory instantiates a new OnboardingHardwareInventory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOnboardingHardwareInventoryWithDefaults

`func NewOnboardingHardwareInventoryWithDefaults() *OnboardingHardwareInventory`

NewOnboardingHardwareInventoryWithDefaults instantiates a new OnboardingHardwareInventory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedOn

`func (o *OnboardingHardwareInventory) GetAssignedOn() GoogleProtobufTimestamp`

GetAssignedOn returns the AssignedOn field if non-nil, zero value otherwise.

### GetAssignedOnOk

`func (o *OnboardingHardwareInventory) GetAssignedOnOk() (*GoogleProtobufTimestamp, bool)`

GetAssignedOnOk returns a tuple with the AssignedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedOn

`func (o *OnboardingHardwareInventory) SetAssignedOn(v GoogleProtobufTimestamp)`

SetAssignedOn sets AssignedOn field to given value.

### HasAssignedOn

`func (o *OnboardingHardwareInventory) HasAssignedOn() bool`

HasAssignedOn returns a boolean if a field has been set.

### GetCreatedOn

`func (o *OnboardingHardwareInventory) GetCreatedOn() GoogleProtobufTimestamp`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *OnboardingHardwareInventory) GetCreatedOnOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *OnboardingHardwareInventory) SetCreatedOn(v GoogleProtobufTimestamp)`

SetCreatedOn sets CreatedOn field to given value.

### HasCreatedOn

`func (o *OnboardingHardwareInventory) HasCreatedOn() bool`

HasCreatedOn returns a boolean if a field has been set.

### GetDeviceModel

`func (o *OnboardingHardwareInventory) GetDeviceModel() string`

GetDeviceModel returns the DeviceModel field if non-nil, zero value otherwise.

### GetDeviceModelOk

`func (o *OnboardingHardwareInventory) GetDeviceModelOk() (*string, bool)`

GetDeviceModelOk returns a tuple with the DeviceModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceModel

`func (o *OnboardingHardwareInventory) SetDeviceModel(v string)`

SetDeviceModel sets DeviceModel field to given value.

### HasDeviceModel

`func (o *OnboardingHardwareInventory) HasDeviceModel() bool`

HasDeviceModel returns a boolean if a field has been set.

### GetDeviceSerial

`func (o *OnboardingHardwareInventory) GetDeviceSerial() string`

GetDeviceSerial returns the DeviceSerial field if non-nil, zero value otherwise.

### GetDeviceSerialOk

`func (o *OnboardingHardwareInventory) GetDeviceSerialOk() (*string, bool)`

GetDeviceSerialOk returns a tuple with the DeviceSerial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceSerial

`func (o *OnboardingHardwareInventory) SetDeviceSerial(v string)`

SetDeviceSerial sets DeviceSerial field to given value.

### HasDeviceSerial

`func (o *OnboardingHardwareInventory) HasDeviceSerial() bool`

HasDeviceSerial returns a boolean if a field has been set.

### GetEkCert

`func (o *OnboardingHardwareInventory) GetEkCert() string`

GetEkCert returns the EkCert field if non-nil, zero value otherwise.

### GetEkCertOk

`func (o *OnboardingHardwareInventory) GetEkCertOk() (*string, bool)`

GetEkCertOk returns a tuple with the EkCert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEkCert

`func (o *OnboardingHardwareInventory) SetEkCert(v string)`

SetEkCert sets EkCert field to given value.

### HasEkCert

`func (o *OnboardingHardwareInventory) HasEkCert() bool`

HasEkCert returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *OnboardingHardwareInventory) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *OnboardingHardwareInventory) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *OnboardingHardwareInventory) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *OnboardingHardwareInventory) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetEnterpriseName

`func (o *OnboardingHardwareInventory) GetEnterpriseName() string`

GetEnterpriseName returns the EnterpriseName field if non-nil, zero value otherwise.

### GetEnterpriseNameOk

`func (o *OnboardingHardwareInventory) GetEnterpriseNameOk() (*string, bool)`

GetEnterpriseNameOk returns a tuple with the EnterpriseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseName

`func (o *OnboardingHardwareInventory) SetEnterpriseName(v string)`

SetEnterpriseName sets EnterpriseName field to given value.

### HasEnterpriseName

`func (o *OnboardingHardwareInventory) HasEnterpriseName() bool`

HasEnterpriseName returns a boolean if a field has been set.

### GetGekPub

`func (o *OnboardingHardwareInventory) GetGekPub() string`

GetGekPub returns the GekPub field if non-nil, zero value otherwise.

### GetGekPubOk

`func (o *OnboardingHardwareInventory) GetGekPubOk() (*string, bool)`

GetGekPubOk returns a tuple with the GekPub field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGekPub

`func (o *OnboardingHardwareInventory) SetGekPub(v string)`

SetGekPub sets GekPub field to given value.

### HasGekPub

`func (o *OnboardingHardwareInventory) HasGekPub() bool`

HasGekPub returns a boolean if a field has been set.

### GetIsCore

`func (o *OnboardingHardwareInventory) GetIsCore() bool`

GetIsCore returns the IsCore field if non-nil, zero value otherwise.

### GetIsCoreOk

`func (o *OnboardingHardwareInventory) GetIsCoreOk() (*bool, bool)`

GetIsCoreOk returns a tuple with the IsCore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCore

`func (o *OnboardingHardwareInventory) SetIsCore(v bool)`

SetIsCore sets IsCore field to given value.

### HasIsCore

`func (o *OnboardingHardwareInventory) HasIsCore() bool`

HasIsCore returns a boolean if a field has been set.

### GetIsNew

`func (o *OnboardingHardwareInventory) GetIsNew() bool`

GetIsNew returns the IsNew field if non-nil, zero value otherwise.

### GetIsNewOk

`func (o *OnboardingHardwareInventory) GetIsNewOk() (*bool, bool)`

GetIsNewOk returns a tuple with the IsNew field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNew

`func (o *OnboardingHardwareInventory) SetIsNew(v bool)`

SetIsNew sets IsNew field to given value.

### HasIsNew

`func (o *OnboardingHardwareInventory) HasIsNew() bool`

HasIsNew returns a boolean if a field has been set.

### GetIsRequested

`func (o *OnboardingHardwareInventory) GetIsRequested() bool`

GetIsRequested returns the IsRequested field if non-nil, zero value otherwise.

### GetIsRequestedOk

`func (o *OnboardingHardwareInventory) GetIsRequestedOk() (*bool, bool)`

GetIsRequestedOk returns a tuple with the IsRequested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRequested

`func (o *OnboardingHardwareInventory) SetIsRequested(v bool)`

SetIsRequested sets IsRequested field to given value.

### HasIsRequested

`func (o *OnboardingHardwareInventory) HasIsRequested() bool`

HasIsRequested returns a boolean if a field has been set.

### GetParentEnterpriseId

`func (o *OnboardingHardwareInventory) GetParentEnterpriseId() int64`

GetParentEnterpriseId returns the ParentEnterpriseId field if non-nil, zero value otherwise.

### GetParentEnterpriseIdOk

`func (o *OnboardingHardwareInventory) GetParentEnterpriseIdOk() (*int64, bool)`

GetParentEnterpriseIdOk returns a tuple with the ParentEnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentEnterpriseId

`func (o *OnboardingHardwareInventory) SetParentEnterpriseId(v int64)`

SetParentEnterpriseId sets ParentEnterpriseId field to given value.

### HasParentEnterpriseId

`func (o *OnboardingHardwareInventory) HasParentEnterpriseId() bool`

HasParentEnterpriseId returns a boolean if a field has been set.

### GetParentEnterpriseName

`func (o *OnboardingHardwareInventory) GetParentEnterpriseName() string`

GetParentEnterpriseName returns the ParentEnterpriseName field if non-nil, zero value otherwise.

### GetParentEnterpriseNameOk

`func (o *OnboardingHardwareInventory) GetParentEnterpriseNameOk() (*string, bool)`

GetParentEnterpriseNameOk returns a tuple with the ParentEnterpriseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentEnterpriseName

`func (o *OnboardingHardwareInventory) SetParentEnterpriseName(v string)`

SetParentEnterpriseName sets ParentEnterpriseName field to given value.

### HasParentEnterpriseName

`func (o *OnboardingHardwareInventory) HasParentEnterpriseName() bool`

HasParentEnterpriseName returns a boolean if a field has been set.

### GetRole

`func (o *OnboardingHardwareInventory) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *OnboardingHardwareInventory) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *OnboardingHardwareInventory) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *OnboardingHardwareInventory) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetUseOauth

`func (o *OnboardingHardwareInventory) GetUseOauth() bool`

GetUseOauth returns the UseOauth field if non-nil, zero value otherwise.

### GetUseOauthOk

`func (o *OnboardingHardwareInventory) GetUseOauthOk() (*bool, bool)`

GetUseOauthOk returns a tuple with the UseOauth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseOauth

`func (o *OnboardingHardwareInventory) SetUseOauth(v bool)`

SetUseOauth sets UseOauth field to given value.

### HasUseOauth

`func (o *OnboardingHardwareInventory) HasUseOauth() bool`

HasUseOauth returns a boolean if a field has been set.

### GetUuid

`func (o *OnboardingHardwareInventory) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *OnboardingHardwareInventory) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *OnboardingHardwareInventory) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *OnboardingHardwareInventory) HasUuid() bool`

HasUuid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



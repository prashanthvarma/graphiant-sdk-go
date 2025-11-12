# AuditmonActivityLogsSelector

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceIds** | Pointer to **[]int64** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**InProgress** | Pointer to **bool** |  | [optional] 
**JobEntity** | Pointer to [**AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**TargetIds** | Pointer to [**[]AuditActivityItem**](AuditActivityItem.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewAuditmonActivityLogsSelector

`func NewAuditmonActivityLogsSelector() *AuditmonActivityLogsSelector`

NewAuditmonActivityLogsSelector instantiates a new AuditmonActivityLogsSelector object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditmonActivityLogsSelectorWithDefaults

`func NewAuditmonActivityLogsSelectorWithDefaults() *AuditmonActivityLogsSelector`

NewAuditmonActivityLogsSelectorWithDefaults instantiates a new AuditmonActivityLogsSelector object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceIds

`func (o *AuditmonActivityLogsSelector) GetDeviceIds() []int64`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *AuditmonActivityLogsSelector) GetDeviceIdsOk() (*[]int64, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *AuditmonActivityLogsSelector) SetDeviceIds(v []int64)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *AuditmonActivityLogsSelector) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.

### GetId

`func (o *AuditmonActivityLogsSelector) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuditmonActivityLogsSelector) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuditmonActivityLogsSelector) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AuditmonActivityLogsSelector) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInProgress

`func (o *AuditmonActivityLogsSelector) GetInProgress() bool`

GetInProgress returns the InProgress field if non-nil, zero value otherwise.

### GetInProgressOk

`func (o *AuditmonActivityLogsSelector) GetInProgressOk() (*bool, bool)`

GetInProgressOk returns a tuple with the InProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInProgress

`func (o *AuditmonActivityLogsSelector) SetInProgress(v bool)`

SetInProgress sets InProgress field to given value.

### HasInProgress

`func (o *AuditmonActivityLogsSelector) HasInProgress() bool`

HasInProgress returns a boolean if a field has been set.

### GetJobEntity

`func (o *AuditmonActivityLogsSelector) GetJobEntity() AuditActivityItem`

GetJobEntity returns the JobEntity field if non-nil, zero value otherwise.

### GetJobEntityOk

`func (o *AuditmonActivityLogsSelector) GetJobEntityOk() (*AuditActivityItem, bool)`

GetJobEntityOk returns a tuple with the JobEntity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobEntity

`func (o *AuditmonActivityLogsSelector) SetJobEntity(v AuditActivityItem)`

SetJobEntity sets JobEntity field to given value.

### HasJobEntity

`func (o *AuditmonActivityLogsSelector) HasJobEntity() bool`

HasJobEntity returns a boolean if a field has been set.

### GetTargetIds

`func (o *AuditmonActivityLogsSelector) GetTargetIds() []AuditActivityItem`

GetTargetIds returns the TargetIds field if non-nil, zero value otherwise.

### GetTargetIdsOk

`func (o *AuditmonActivityLogsSelector) GetTargetIdsOk() (*[]AuditActivityItem, bool)`

GetTargetIdsOk returns a tuple with the TargetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetIds

`func (o *AuditmonActivityLogsSelector) SetTargetIds(v []AuditActivityItem)`

SetTargetIds sets TargetIds field to given value.

### HasTargetIds

`func (o *AuditmonActivityLogsSelector) HasTargetIds() bool`

HasTargetIds returns a boolean if a field has been set.

### GetType

`func (o *AuditmonActivityLogsSelector) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AuditmonActivityLogsSelector) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AuditmonActivityLogsSelector) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AuditmonActivityLogsSelector) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



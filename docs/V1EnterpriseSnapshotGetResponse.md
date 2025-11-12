# V1EnterpriseSnapshotGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceSnapshotRecords** | Pointer to [**[]ManaV2deviceSnapshotRow**](ManaV2deviceSnapshotRow.md) |  | [optional] 
**DeviceSnapshotMap** | Pointer to [**map[string]ManaV2DeviceSnapshotList**](ManaV2DeviceSnapshotList.md) |  | [optional] 

## Methods

### NewV1EnterpriseSnapshotGetResponse

`func NewV1EnterpriseSnapshotGetResponse() *V1EnterpriseSnapshotGetResponse`

NewV1EnterpriseSnapshotGetResponse instantiates a new V1EnterpriseSnapshotGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EnterpriseSnapshotGetResponseWithDefaults

`func NewV1EnterpriseSnapshotGetResponseWithDefaults() *V1EnterpriseSnapshotGetResponse`

NewV1EnterpriseSnapshotGetResponseWithDefaults instantiates a new V1EnterpriseSnapshotGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceSnapshotRecords

`func (o *V1EnterpriseSnapshotGetResponse) GetDeviceSnapshotRecords() []ManaV2deviceSnapshotRow`

GetDeviceSnapshotRecords returns the DeviceSnapshotRecords field if non-nil, zero value otherwise.

### GetDeviceSnapshotRecordsOk

`func (o *V1EnterpriseSnapshotGetResponse) GetDeviceSnapshotRecordsOk() (*[]ManaV2deviceSnapshotRow, bool)`

GetDeviceSnapshotRecordsOk returns a tuple with the DeviceSnapshotRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceSnapshotRecords

`func (o *V1EnterpriseSnapshotGetResponse) SetDeviceSnapshotRecords(v []ManaV2deviceSnapshotRow)`

SetDeviceSnapshotRecords sets DeviceSnapshotRecords field to given value.

### HasDeviceSnapshotRecords

`func (o *V1EnterpriseSnapshotGetResponse) HasDeviceSnapshotRecords() bool`

HasDeviceSnapshotRecords returns a boolean if a field has been set.

### GetDeviceSnapshotMap

`func (o *V1EnterpriseSnapshotGetResponse) GetDeviceSnapshotMap() map[string]ManaV2DeviceSnapshotList`

GetDeviceSnapshotMap returns the DeviceSnapshotMap field if non-nil, zero value otherwise.

### GetDeviceSnapshotMapOk

`func (o *V1EnterpriseSnapshotGetResponse) GetDeviceSnapshotMapOk() (*map[string]ManaV2DeviceSnapshotList, bool)`

GetDeviceSnapshotMapOk returns a tuple with the DeviceSnapshotMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceSnapshotMap

`func (o *V1EnterpriseSnapshotGetResponse) SetDeviceSnapshotMap(v map[string]ManaV2DeviceSnapshotList)`

SetDeviceSnapshotMap sets DeviceSnapshotMap field to given value.

### HasDeviceSnapshotMap

`func (o *V1EnterpriseSnapshotGetResponse) HasDeviceSnapshotMap() bool`

HasDeviceSnapshotMap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



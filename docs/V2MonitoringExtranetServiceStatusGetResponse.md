# V2MonitoringExtranetServiceStatusGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Statuses** | Pointer to [**[]StatsmonExtranetServerStatus**](StatsmonExtranetServerStatus.md) |  | [optional] 

## Methods

### NewV2MonitoringExtranetServiceStatusGetResponse

`func NewV2MonitoringExtranetServiceStatusGetResponse() *V2MonitoringExtranetServiceStatusGetResponse`

NewV2MonitoringExtranetServiceStatusGetResponse instantiates a new V2MonitoringExtranetServiceStatusGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringExtranetServiceStatusGetResponseWithDefaults

`func NewV2MonitoringExtranetServiceStatusGetResponseWithDefaults() *V2MonitoringExtranetServiceStatusGetResponse`

NewV2MonitoringExtranetServiceStatusGetResponseWithDefaults instantiates a new V2MonitoringExtranetServiceStatusGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatuses

`func (o *V2MonitoringExtranetServiceStatusGetResponse) GetStatuses() []StatsmonExtranetServerStatus`

GetStatuses returns the Statuses field if non-nil, zero value otherwise.

### GetStatusesOk

`func (o *V2MonitoringExtranetServiceStatusGetResponse) GetStatusesOk() (*[]StatsmonExtranetServerStatus, bool)`

GetStatusesOk returns a tuple with the Statuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatuses

`func (o *V2MonitoringExtranetServiceStatusGetResponse) SetStatuses(v []StatsmonExtranetServerStatus)`

SetStatuses sets Statuses field to given value.

### HasStatuses

`func (o *V2MonitoringExtranetServiceStatusGetResponse) HasStatuses() bool`

HasStatuses returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



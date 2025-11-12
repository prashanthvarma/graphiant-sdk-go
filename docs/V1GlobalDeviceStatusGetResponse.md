# V1GlobalDeviceStatusGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Statuses** | Pointer to [**[]ManaV2GlobalObjectDeviceStatus**](ManaV2GlobalObjectDeviceStatus.md) |  | [optional] 

## Methods

### NewV1GlobalDeviceStatusGetResponse

`func NewV1GlobalDeviceStatusGetResponse() *V1GlobalDeviceStatusGetResponse`

NewV1GlobalDeviceStatusGetResponse instantiates a new V1GlobalDeviceStatusGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GlobalDeviceStatusGetResponseWithDefaults

`func NewV1GlobalDeviceStatusGetResponseWithDefaults() *V1GlobalDeviceStatusGetResponse`

NewV1GlobalDeviceStatusGetResponseWithDefaults instantiates a new V1GlobalDeviceStatusGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatuses

`func (o *V1GlobalDeviceStatusGetResponse) GetStatuses() []ManaV2GlobalObjectDeviceStatus`

GetStatuses returns the Statuses field if non-nil, zero value otherwise.

### GetStatusesOk

`func (o *V1GlobalDeviceStatusGetResponse) GetStatusesOk() (*[]ManaV2GlobalObjectDeviceStatus, bool)`

GetStatusesOk returns a tuple with the Statuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatuses

`func (o *V1GlobalDeviceStatusGetResponse) SetStatuses(v []ManaV2GlobalObjectDeviceStatus)`

SetStatuses sets Statuses field to given value.

### HasStatuses

`func (o *V1GlobalDeviceStatusGetResponse) HasStatuses() bool`

HasStatuses returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



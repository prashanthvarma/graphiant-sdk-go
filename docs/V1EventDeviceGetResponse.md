# V1EventDeviceGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Events** | Pointer to [**[]EventEvent**](EventEvent.md) |  | [optional] 

## Methods

### NewV1EventDeviceGetResponse

`func NewV1EventDeviceGetResponse() *V1EventDeviceGetResponse`

NewV1EventDeviceGetResponse instantiates a new V1EventDeviceGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EventDeviceGetResponseWithDefaults

`func NewV1EventDeviceGetResponseWithDefaults() *V1EventDeviceGetResponse`

NewV1EventDeviceGetResponseWithDefaults instantiates a new V1EventDeviceGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvents

`func (o *V1EventDeviceGetResponse) GetEvents() []EventEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *V1EventDeviceGetResponse) GetEventsOk() (*[]EventEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *V1EventDeviceGetResponse) SetEvents(v []EventEvent)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *V1EventDeviceGetResponse) HasEvents() bool`

HasEvents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



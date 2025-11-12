# V1AlarmHistoryGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**History** | Pointer to [**[]AlarmsAlarmHistory**](AlarmsAlarmHistory.md) |  | [optional] 

## Methods

### NewV1AlarmHistoryGetResponse

`func NewV1AlarmHistoryGetResponse() *V1AlarmHistoryGetResponse`

NewV1AlarmHistoryGetResponse instantiates a new V1AlarmHistoryGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AlarmHistoryGetResponseWithDefaults

`func NewV1AlarmHistoryGetResponseWithDefaults() *V1AlarmHistoryGetResponse`

NewV1AlarmHistoryGetResponseWithDefaults instantiates a new V1AlarmHistoryGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHistory

`func (o *V1AlarmHistoryGetResponse) GetHistory() []AlarmsAlarmHistory`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *V1AlarmHistoryGetResponse) GetHistoryOk() (*[]AlarmsAlarmHistory, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *V1AlarmHistoryGetResponse) SetHistory(v []AlarmsAlarmHistory)`

SetHistory sets History field to given value.

### HasHistory

`func (o *V1AlarmHistoryGetResponse) HasHistory() bool`

HasHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



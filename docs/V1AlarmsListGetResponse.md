# V1AlarmsListGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Alarms** | Pointer to [**[]AlarmsAlarmData**](AlarmsAlarmData.md) |  | [optional] 

## Methods

### NewV1AlarmsListGetResponse

`func NewV1AlarmsListGetResponse() *V1AlarmsListGetResponse`

NewV1AlarmsListGetResponse instantiates a new V1AlarmsListGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AlarmsListGetResponseWithDefaults

`func NewV1AlarmsListGetResponseWithDefaults() *V1AlarmsListGetResponse`

NewV1AlarmsListGetResponseWithDefaults instantiates a new V1AlarmsListGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlarms

`func (o *V1AlarmsListGetResponse) GetAlarms() []AlarmsAlarmData`

GetAlarms returns the Alarms field if non-nil, zero value otherwise.

### GetAlarmsOk

`func (o *V1AlarmsListGetResponse) GetAlarmsOk() (*[]AlarmsAlarmData, bool)`

GetAlarmsOk returns a tuple with the Alarms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarms

`func (o *V1AlarmsListGetResponse) SetAlarms(v []AlarmsAlarmData)`

SetAlarms sets Alarms field to given value.

### HasAlarms

`func (o *V1AlarmsListGetResponse) HasAlarms() bool`

HasAlarms returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



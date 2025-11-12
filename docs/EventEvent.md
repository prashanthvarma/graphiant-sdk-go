# EventEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | Pointer to **[]string** |  | [optional] 
**DeviceId** | Pointer to **int64** | If set identifies the device ID (required) | [optional] 
**EnterpriseId** | Pointer to **int64** | If set identifies the Enterprise ID (required) | [optional] 
**EventData** | Pointer to **string** | Json encoded event specific data. Should be decoded using event type (required) | [optional] 
**EventId** | Pointer to **int64** | Event Identifier. Not needed while creating. | [optional] 
**EventTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Hostname** | Pointer to **string** | hostname of the deviceID | [optional] 
**Severity** | Pointer to **string** | Level of event (required) | [optional] 
**Type** | Pointer to **string** | Identifies the event (required) | [optional] 

## Methods

### NewEventEvent

`func NewEventEvent() *EventEvent`

NewEventEvent instantiates a new EventEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventEventWithDefaults

`func NewEventEventWithDefaults() *EventEvent`

NewEventEventWithDefaults instantiates a new EventEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *EventEvent) GetActions() []string`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *EventEvent) GetActionsOk() (*[]string, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *EventEvent) SetActions(v []string)`

SetActions sets Actions field to given value.

### HasActions

`func (o *EventEvent) HasActions() bool`

HasActions returns a boolean if a field has been set.

### GetDeviceId

`func (o *EventEvent) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *EventEvent) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *EventEvent) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *EventEvent) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *EventEvent) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *EventEvent) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *EventEvent) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *EventEvent) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetEventData

`func (o *EventEvent) GetEventData() string`

GetEventData returns the EventData field if non-nil, zero value otherwise.

### GetEventDataOk

`func (o *EventEvent) GetEventDataOk() (*string, bool)`

GetEventDataOk returns a tuple with the EventData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventData

`func (o *EventEvent) SetEventData(v string)`

SetEventData sets EventData field to given value.

### HasEventData

`func (o *EventEvent) HasEventData() bool`

HasEventData returns a boolean if a field has been set.

### GetEventId

`func (o *EventEvent) GetEventId() int64`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *EventEvent) GetEventIdOk() (*int64, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *EventEvent) SetEventId(v int64)`

SetEventId sets EventId field to given value.

### HasEventId

`func (o *EventEvent) HasEventId() bool`

HasEventId returns a boolean if a field has been set.

### GetEventTime

`func (o *EventEvent) GetEventTime() GoogleProtobufTimestamp`

GetEventTime returns the EventTime field if non-nil, zero value otherwise.

### GetEventTimeOk

`func (o *EventEvent) GetEventTimeOk() (*GoogleProtobufTimestamp, bool)`

GetEventTimeOk returns a tuple with the EventTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTime

`func (o *EventEvent) SetEventTime(v GoogleProtobufTimestamp)`

SetEventTime sets EventTime field to given value.

### HasEventTime

`func (o *EventEvent) HasEventTime() bool`

HasEventTime returns a boolean if a field has been set.

### GetHostname

`func (o *EventEvent) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *EventEvent) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *EventEvent) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *EventEvent) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetSeverity

`func (o *EventEvent) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *EventEvent) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *EventEvent) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *EventEvent) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetType

`func (o *EventEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EventEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EventEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EventEvent) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



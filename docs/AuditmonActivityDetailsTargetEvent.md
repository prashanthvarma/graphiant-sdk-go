# AuditmonActivityDetailsTargetEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**State** | Pointer to **string** |  | [optional] 
**StateId** | Pointer to **int32** |  | [optional] 
**TraceSessionId** | Pointer to **string** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewAuditmonActivityDetailsTargetEvent

`func NewAuditmonActivityDetailsTargetEvent() *AuditmonActivityDetailsTargetEvent`

NewAuditmonActivityDetailsTargetEvent instantiates a new AuditmonActivityDetailsTargetEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditmonActivityDetailsTargetEventWithDefaults

`func NewAuditmonActivityDetailsTargetEventWithDefaults() *AuditmonActivityDetailsTargetEvent`

NewAuditmonActivityDetailsTargetEventWithDefaults instantiates a new AuditmonActivityDetailsTargetEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetState

`func (o *AuditmonActivityDetailsTargetEvent) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AuditmonActivityDetailsTargetEvent) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AuditmonActivityDetailsTargetEvent) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *AuditmonActivityDetailsTargetEvent) HasState() bool`

HasState returns a boolean if a field has been set.

### GetStateId

`func (o *AuditmonActivityDetailsTargetEvent) GetStateId() int32`

GetStateId returns the StateId field if non-nil, zero value otherwise.

### GetStateIdOk

`func (o *AuditmonActivityDetailsTargetEvent) GetStateIdOk() (*int32, bool)`

GetStateIdOk returns a tuple with the StateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateId

`func (o *AuditmonActivityDetailsTargetEvent) SetStateId(v int32)`

SetStateId sets StateId field to given value.

### HasStateId

`func (o *AuditmonActivityDetailsTargetEvent) HasStateId() bool`

HasStateId returns a boolean if a field has been set.

### GetTraceSessionId

`func (o *AuditmonActivityDetailsTargetEvent) GetTraceSessionId() string`

GetTraceSessionId returns the TraceSessionId field if non-nil, zero value otherwise.

### GetTraceSessionIdOk

`func (o *AuditmonActivityDetailsTargetEvent) GetTraceSessionIdOk() (*string, bool)`

GetTraceSessionIdOk returns a tuple with the TraceSessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceSessionId

`func (o *AuditmonActivityDetailsTargetEvent) SetTraceSessionId(v string)`

SetTraceSessionId sets TraceSessionId field to given value.

### HasTraceSessionId

`func (o *AuditmonActivityDetailsTargetEvent) HasTraceSessionId() bool`

HasTraceSessionId returns a boolean if a field has been set.

### GetTs

`func (o *AuditmonActivityDetailsTargetEvent) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *AuditmonActivityDetailsTargetEvent) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *AuditmonActivityDetailsTargetEvent) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *AuditmonActivityDetailsTargetEvent) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AuditTargetResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reason** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Target** | Pointer to [**AuditTarget**](AuditTarget.md) |  | [optional] 

## Methods

### NewAuditTargetResult

`func NewAuditTargetResult() *AuditTargetResult`

NewAuditTargetResult instantiates a new AuditTargetResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditTargetResultWithDefaults

`func NewAuditTargetResultWithDefaults() *AuditTargetResult`

NewAuditTargetResultWithDefaults instantiates a new AuditTargetResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReason

`func (o *AuditTargetResult) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuditTargetResult) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuditTargetResult) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AuditTargetResult) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetStatus

`func (o *AuditTargetResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuditTargetResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuditTargetResult) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AuditTargetResult) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTarget

`func (o *AuditTargetResult) GetTarget() AuditTarget`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *AuditTargetResult) GetTargetOk() (*AuditTarget, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *AuditTargetResult) SetTarget(v AuditTarget)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *AuditTargetResult) HasTarget() bool`

HasTarget returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



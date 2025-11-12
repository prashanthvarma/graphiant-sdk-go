# ManaV2RoutingPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttachPoint** | Pointer to **string** |  | [optional] 
**DefaultAction** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Statements** | Pointer to [**[]ManaV2RoutingPolicyStatement**](ManaV2RoutingPolicyStatement.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2RoutingPolicy

`func NewManaV2RoutingPolicy() *ManaV2RoutingPolicy`

NewManaV2RoutingPolicy instantiates a new ManaV2RoutingPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2RoutingPolicyWithDefaults

`func NewManaV2RoutingPolicyWithDefaults() *ManaV2RoutingPolicy`

NewManaV2RoutingPolicyWithDefaults instantiates a new ManaV2RoutingPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachPoint

`func (o *ManaV2RoutingPolicy) GetAttachPoint() string`

GetAttachPoint returns the AttachPoint field if non-nil, zero value otherwise.

### GetAttachPointOk

`func (o *ManaV2RoutingPolicy) GetAttachPointOk() (*string, bool)`

GetAttachPointOk returns a tuple with the AttachPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachPoint

`func (o *ManaV2RoutingPolicy) SetAttachPoint(v string)`

SetAttachPoint sets AttachPoint field to given value.

### HasAttachPoint

`func (o *ManaV2RoutingPolicy) HasAttachPoint() bool`

HasAttachPoint returns a boolean if a field has been set.

### GetDefaultAction

`func (o *ManaV2RoutingPolicy) GetDefaultAction() string`

GetDefaultAction returns the DefaultAction field if non-nil, zero value otherwise.

### GetDefaultActionOk

`func (o *ManaV2RoutingPolicy) GetDefaultActionOk() (*string, bool)`

GetDefaultActionOk returns a tuple with the DefaultAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAction

`func (o *ManaV2RoutingPolicy) SetDefaultAction(v string)`

SetDefaultAction sets DefaultAction field to given value.

### HasDefaultAction

`func (o *ManaV2RoutingPolicy) HasDefaultAction() bool`

HasDefaultAction returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2RoutingPolicy) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2RoutingPolicy) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2RoutingPolicy) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2RoutingPolicy) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ManaV2RoutingPolicy) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ManaV2RoutingPolicy) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ManaV2RoutingPolicy) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ManaV2RoutingPolicy) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2RoutingPolicy) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2RoutingPolicy) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2RoutingPolicy) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2RoutingPolicy) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetId

`func (o *ManaV2RoutingPolicy) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2RoutingPolicy) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2RoutingPolicy) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2RoutingPolicy) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2RoutingPolicy) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2RoutingPolicy) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2RoutingPolicy) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2RoutingPolicy) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatements

`func (o *ManaV2RoutingPolicy) GetStatements() []ManaV2RoutingPolicyStatement`

GetStatements returns the Statements field if non-nil, zero value otherwise.

### GetStatementsOk

`func (o *ManaV2RoutingPolicy) GetStatementsOk() (*[]ManaV2RoutingPolicyStatement, bool)`

GetStatementsOk returns a tuple with the Statements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatements

`func (o *ManaV2RoutingPolicy) SetStatements(v []ManaV2RoutingPolicyStatement)`

SetStatements sets Statements field to given value.

### HasStatements

`func (o *ManaV2RoutingPolicy) HasStatements() bool`

HasStatements returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2RoutingPolicy) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2RoutingPolicy) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2RoutingPolicy) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2RoutingPolicy) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2RoutingPolicyStatement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | Pointer to [**[]ManaV2RoutingPolicyStatementAction**](ManaV2RoutingPolicyStatementAction.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Matches** | Pointer to [**[]ManaV2RoutingPolicyStatementMatch**](ManaV2RoutingPolicyStatementMatch.md) |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2RoutingPolicyStatement

`func NewManaV2RoutingPolicyStatement() *ManaV2RoutingPolicyStatement`

NewManaV2RoutingPolicyStatement instantiates a new ManaV2RoutingPolicyStatement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2RoutingPolicyStatementWithDefaults

`func NewManaV2RoutingPolicyStatementWithDefaults() *ManaV2RoutingPolicyStatement`

NewManaV2RoutingPolicyStatementWithDefaults instantiates a new ManaV2RoutingPolicyStatement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *ManaV2RoutingPolicyStatement) GetActions() []ManaV2RoutingPolicyStatementAction`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *ManaV2RoutingPolicyStatement) GetActionsOk() (*[]ManaV2RoutingPolicyStatementAction, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *ManaV2RoutingPolicyStatement) SetActions(v []ManaV2RoutingPolicyStatementAction)`

SetActions sets Actions field to given value.

### HasActions

`func (o *ManaV2RoutingPolicyStatement) HasActions() bool`

HasActions returns a boolean if a field has been set.

### GetId

`func (o *ManaV2RoutingPolicyStatement) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2RoutingPolicyStatement) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2RoutingPolicyStatement) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2RoutingPolicyStatement) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMatches

`func (o *ManaV2RoutingPolicyStatement) GetMatches() []ManaV2RoutingPolicyStatementMatch`

GetMatches returns the Matches field if non-nil, zero value otherwise.

### GetMatchesOk

`func (o *ManaV2RoutingPolicyStatement) GetMatchesOk() (*[]ManaV2RoutingPolicyStatementMatch, bool)`

GetMatchesOk returns a tuple with the Matches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatches

`func (o *ManaV2RoutingPolicyStatement) SetMatches(v []ManaV2RoutingPolicyStatementMatch)`

SetMatches sets Matches field to given value.

### HasMatches

`func (o *ManaV2RoutingPolicyStatement) HasMatches() bool`

HasMatches returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2RoutingPolicyStatement) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2RoutingPolicyStatement) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2RoutingPolicyStatement) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2RoutingPolicyStatement) HasSeq() bool`

HasSeq returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



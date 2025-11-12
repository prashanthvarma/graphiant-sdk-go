# ManaV2RoutingPolicyStatementAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdministrativeDistance** | Pointer to **int32** |  | [optional] 
**AspathPrepend** | Pointer to **int32** |  | [optional] 
**BgpSetNextHop** | Pointer to **string** |  | [optional] 
**CallPolicy** | Pointer to **string** |  | [optional] 
**Community** | Pointer to [**ManaV2CommunityType**](ManaV2CommunityType.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**LocalPref** | Pointer to **int32** |  | [optional] 
**MetricAbsolute** | Pointer to **int32** |  | [optional] 
**MetricModifier** | Pointer to **int32** |  | [optional] 
**Result** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**Weight** | Pointer to **int32** |  | [optional] 

## Methods

### NewManaV2RoutingPolicyStatementAction

`func NewManaV2RoutingPolicyStatementAction() *ManaV2RoutingPolicyStatementAction`

NewManaV2RoutingPolicyStatementAction instantiates a new ManaV2RoutingPolicyStatementAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2RoutingPolicyStatementActionWithDefaults

`func NewManaV2RoutingPolicyStatementActionWithDefaults() *ManaV2RoutingPolicyStatementAction`

NewManaV2RoutingPolicyStatementActionWithDefaults instantiates a new ManaV2RoutingPolicyStatementAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdministrativeDistance

`func (o *ManaV2RoutingPolicyStatementAction) GetAdministrativeDistance() int32`

GetAdministrativeDistance returns the AdministrativeDistance field if non-nil, zero value otherwise.

### GetAdministrativeDistanceOk

`func (o *ManaV2RoutingPolicyStatementAction) GetAdministrativeDistanceOk() (*int32, bool)`

GetAdministrativeDistanceOk returns a tuple with the AdministrativeDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrativeDistance

`func (o *ManaV2RoutingPolicyStatementAction) SetAdministrativeDistance(v int32)`

SetAdministrativeDistance sets AdministrativeDistance field to given value.

### HasAdministrativeDistance

`func (o *ManaV2RoutingPolicyStatementAction) HasAdministrativeDistance() bool`

HasAdministrativeDistance returns a boolean if a field has been set.

### GetAspathPrepend

`func (o *ManaV2RoutingPolicyStatementAction) GetAspathPrepend() int32`

GetAspathPrepend returns the AspathPrepend field if non-nil, zero value otherwise.

### GetAspathPrependOk

`func (o *ManaV2RoutingPolicyStatementAction) GetAspathPrependOk() (*int32, bool)`

GetAspathPrependOk returns a tuple with the AspathPrepend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspathPrepend

`func (o *ManaV2RoutingPolicyStatementAction) SetAspathPrepend(v int32)`

SetAspathPrepend sets AspathPrepend field to given value.

### HasAspathPrepend

`func (o *ManaV2RoutingPolicyStatementAction) HasAspathPrepend() bool`

HasAspathPrepend returns a boolean if a field has been set.

### GetBgpSetNextHop

`func (o *ManaV2RoutingPolicyStatementAction) GetBgpSetNextHop() string`

GetBgpSetNextHop returns the BgpSetNextHop field if non-nil, zero value otherwise.

### GetBgpSetNextHopOk

`func (o *ManaV2RoutingPolicyStatementAction) GetBgpSetNextHopOk() (*string, bool)`

GetBgpSetNextHopOk returns a tuple with the BgpSetNextHop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpSetNextHop

`func (o *ManaV2RoutingPolicyStatementAction) SetBgpSetNextHop(v string)`

SetBgpSetNextHop sets BgpSetNextHop field to given value.

### HasBgpSetNextHop

`func (o *ManaV2RoutingPolicyStatementAction) HasBgpSetNextHop() bool`

HasBgpSetNextHop returns a boolean if a field has been set.

### GetCallPolicy

`func (o *ManaV2RoutingPolicyStatementAction) GetCallPolicy() string`

GetCallPolicy returns the CallPolicy field if non-nil, zero value otherwise.

### GetCallPolicyOk

`func (o *ManaV2RoutingPolicyStatementAction) GetCallPolicyOk() (*string, bool)`

GetCallPolicyOk returns a tuple with the CallPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallPolicy

`func (o *ManaV2RoutingPolicyStatementAction) SetCallPolicy(v string)`

SetCallPolicy sets CallPolicy field to given value.

### HasCallPolicy

`func (o *ManaV2RoutingPolicyStatementAction) HasCallPolicy() bool`

HasCallPolicy returns a boolean if a field has been set.

### GetCommunity

`func (o *ManaV2RoutingPolicyStatementAction) GetCommunity() ManaV2CommunityType`

GetCommunity returns the Community field if non-nil, zero value otherwise.

### GetCommunityOk

`func (o *ManaV2RoutingPolicyStatementAction) GetCommunityOk() (*ManaV2CommunityType, bool)`

GetCommunityOk returns a tuple with the Community field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunity

`func (o *ManaV2RoutingPolicyStatementAction) SetCommunity(v ManaV2CommunityType)`

SetCommunity sets Community field to given value.

### HasCommunity

`func (o *ManaV2RoutingPolicyStatementAction) HasCommunity() bool`

HasCommunity returns a boolean if a field has been set.

### GetId

`func (o *ManaV2RoutingPolicyStatementAction) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2RoutingPolicyStatementAction) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2RoutingPolicyStatementAction) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2RoutingPolicyStatementAction) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLocalPref

`func (o *ManaV2RoutingPolicyStatementAction) GetLocalPref() int32`

GetLocalPref returns the LocalPref field if non-nil, zero value otherwise.

### GetLocalPrefOk

`func (o *ManaV2RoutingPolicyStatementAction) GetLocalPrefOk() (*int32, bool)`

GetLocalPrefOk returns a tuple with the LocalPref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalPref

`func (o *ManaV2RoutingPolicyStatementAction) SetLocalPref(v int32)`

SetLocalPref sets LocalPref field to given value.

### HasLocalPref

`func (o *ManaV2RoutingPolicyStatementAction) HasLocalPref() bool`

HasLocalPref returns a boolean if a field has been set.

### GetMetricAbsolute

`func (o *ManaV2RoutingPolicyStatementAction) GetMetricAbsolute() int32`

GetMetricAbsolute returns the MetricAbsolute field if non-nil, zero value otherwise.

### GetMetricAbsoluteOk

`func (o *ManaV2RoutingPolicyStatementAction) GetMetricAbsoluteOk() (*int32, bool)`

GetMetricAbsoluteOk returns a tuple with the MetricAbsolute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricAbsolute

`func (o *ManaV2RoutingPolicyStatementAction) SetMetricAbsolute(v int32)`

SetMetricAbsolute sets MetricAbsolute field to given value.

### HasMetricAbsolute

`func (o *ManaV2RoutingPolicyStatementAction) HasMetricAbsolute() bool`

HasMetricAbsolute returns a boolean if a field has been set.

### GetMetricModifier

`func (o *ManaV2RoutingPolicyStatementAction) GetMetricModifier() int32`

GetMetricModifier returns the MetricModifier field if non-nil, zero value otherwise.

### GetMetricModifierOk

`func (o *ManaV2RoutingPolicyStatementAction) GetMetricModifierOk() (*int32, bool)`

GetMetricModifierOk returns a tuple with the MetricModifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricModifier

`func (o *ManaV2RoutingPolicyStatementAction) SetMetricModifier(v int32)`

SetMetricModifier sets MetricModifier field to given value.

### HasMetricModifier

`func (o *ManaV2RoutingPolicyStatementAction) HasMetricModifier() bool`

HasMetricModifier returns a boolean if a field has been set.

### GetResult

`func (o *ManaV2RoutingPolicyStatementAction) GetResult() string`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ManaV2RoutingPolicyStatementAction) GetResultOk() (*string, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ManaV2RoutingPolicyStatementAction) SetResult(v string)`

SetResult sets Result field to given value.

### HasResult

`func (o *ManaV2RoutingPolicyStatementAction) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2RoutingPolicyStatementAction) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2RoutingPolicyStatementAction) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2RoutingPolicyStatementAction) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2RoutingPolicyStatementAction) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

### GetWeight

`func (o *ManaV2RoutingPolicyStatementAction) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *ManaV2RoutingPolicyStatementAction) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *ManaV2RoutingPolicyStatementAction) SetWeight(v int32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *ManaV2RoutingPolicyStatementAction) HasWeight() bool`

HasWeight returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2ExtranetPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Auto** | Pointer to [**ManaV2ExtranetAutoReverseRoutes**](ManaV2ExtranetAutoReverseRoutes.md) |  | [optional] 
**Branches** | Pointer to [**ManaV2PolicyTarget**](ManaV2PolicyTarget.md) |  | [optional] 
**CreatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**CreatedBy** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**HostPrefixSet** | Pointer to [**ManaV2EnterprisePrefixSet**](ManaV2EnterprisePrefixSet.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Manual** | Pointer to [**ManaV2ExtranetManualReverseRoutes**](ManaV2ExtranetManualReverseRoutes.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**SharedPrefixes** | Pointer to **[]string** |  | [optional] 
**SharedSegment** | Pointer to [**ManaV2Vrf**](ManaV2Vrf.md) |  | [optional] 
**Source** | Pointer to [**ManaV2PolicyTarget**](ManaV2PolicyTarget.md) |  | [optional] 
**TargetSegments** | Pointer to [**[]ManaV2Vrf**](ManaV2Vrf.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewManaV2ExtranetPolicy

`func NewManaV2ExtranetPolicy() *ManaV2ExtranetPolicy`

NewManaV2ExtranetPolicy instantiates a new ManaV2ExtranetPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ExtranetPolicyWithDefaults

`func NewManaV2ExtranetPolicyWithDefaults() *ManaV2ExtranetPolicy`

NewManaV2ExtranetPolicyWithDefaults instantiates a new ManaV2ExtranetPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuto

`func (o *ManaV2ExtranetPolicy) GetAuto() ManaV2ExtranetAutoReverseRoutes`

GetAuto returns the Auto field if non-nil, zero value otherwise.

### GetAutoOk

`func (o *ManaV2ExtranetPolicy) GetAutoOk() (*ManaV2ExtranetAutoReverseRoutes, bool)`

GetAutoOk returns a tuple with the Auto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuto

`func (o *ManaV2ExtranetPolicy) SetAuto(v ManaV2ExtranetAutoReverseRoutes)`

SetAuto sets Auto field to given value.

### HasAuto

`func (o *ManaV2ExtranetPolicy) HasAuto() bool`

HasAuto returns a boolean if a field has been set.

### GetBranches

`func (o *ManaV2ExtranetPolicy) GetBranches() ManaV2PolicyTarget`

GetBranches returns the Branches field if non-nil, zero value otherwise.

### GetBranchesOk

`func (o *ManaV2ExtranetPolicy) GetBranchesOk() (*ManaV2PolicyTarget, bool)`

GetBranchesOk returns a tuple with the Branches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranches

`func (o *ManaV2ExtranetPolicy) SetBranches(v ManaV2PolicyTarget)`

SetBranches sets Branches field to given value.

### HasBranches

`func (o *ManaV2ExtranetPolicy) HasBranches() bool`

HasBranches returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ManaV2ExtranetPolicy) GetCreatedAt() GoogleProtobufTimestamp`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManaV2ExtranetPolicy) GetCreatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManaV2ExtranetPolicy) SetCreatedAt(v GoogleProtobufTimestamp)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ManaV2ExtranetPolicy) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetCreatedBy

`func (o *ManaV2ExtranetPolicy) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ManaV2ExtranetPolicy) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ManaV2ExtranetPolicy) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *ManaV2ExtranetPolicy) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2ExtranetPolicy) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2ExtranetPolicy) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2ExtranetPolicy) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2ExtranetPolicy) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetHostPrefixSet

`func (o *ManaV2ExtranetPolicy) GetHostPrefixSet() ManaV2EnterprisePrefixSet`

GetHostPrefixSet returns the HostPrefixSet field if non-nil, zero value otherwise.

### GetHostPrefixSetOk

`func (o *ManaV2ExtranetPolicy) GetHostPrefixSetOk() (*ManaV2EnterprisePrefixSet, bool)`

GetHostPrefixSetOk returns a tuple with the HostPrefixSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostPrefixSet

`func (o *ManaV2ExtranetPolicy) SetHostPrefixSet(v ManaV2EnterprisePrefixSet)`

SetHostPrefixSet sets HostPrefixSet field to given value.

### HasHostPrefixSet

`func (o *ManaV2ExtranetPolicy) HasHostPrefixSet() bool`

HasHostPrefixSet returns a boolean if a field has been set.

### GetId

`func (o *ManaV2ExtranetPolicy) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2ExtranetPolicy) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2ExtranetPolicy) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2ExtranetPolicy) HasId() bool`

HasId returns a boolean if a field has been set.

### GetManual

`func (o *ManaV2ExtranetPolicy) GetManual() ManaV2ExtranetManualReverseRoutes`

GetManual returns the Manual field if non-nil, zero value otherwise.

### GetManualOk

`func (o *ManaV2ExtranetPolicy) GetManualOk() (*ManaV2ExtranetManualReverseRoutes, bool)`

GetManualOk returns a tuple with the Manual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManual

`func (o *ManaV2ExtranetPolicy) SetManual(v ManaV2ExtranetManualReverseRoutes)`

SetManual sets Manual field to given value.

### HasManual

`func (o *ManaV2ExtranetPolicy) HasManual() bool`

HasManual returns a boolean if a field has been set.

### GetName

`func (o *ManaV2ExtranetPolicy) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2ExtranetPolicy) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2ExtranetPolicy) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2ExtranetPolicy) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSharedPrefixes

`func (o *ManaV2ExtranetPolicy) GetSharedPrefixes() []string`

GetSharedPrefixes returns the SharedPrefixes field if non-nil, zero value otherwise.

### GetSharedPrefixesOk

`func (o *ManaV2ExtranetPolicy) GetSharedPrefixesOk() (*[]string, bool)`

GetSharedPrefixesOk returns a tuple with the SharedPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedPrefixes

`func (o *ManaV2ExtranetPolicy) SetSharedPrefixes(v []string)`

SetSharedPrefixes sets SharedPrefixes field to given value.

### HasSharedPrefixes

`func (o *ManaV2ExtranetPolicy) HasSharedPrefixes() bool`

HasSharedPrefixes returns a boolean if a field has been set.

### GetSharedSegment

`func (o *ManaV2ExtranetPolicy) GetSharedSegment() ManaV2Vrf`

GetSharedSegment returns the SharedSegment field if non-nil, zero value otherwise.

### GetSharedSegmentOk

`func (o *ManaV2ExtranetPolicy) GetSharedSegmentOk() (*ManaV2Vrf, bool)`

GetSharedSegmentOk returns a tuple with the SharedSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedSegment

`func (o *ManaV2ExtranetPolicy) SetSharedSegment(v ManaV2Vrf)`

SetSharedSegment sets SharedSegment field to given value.

### HasSharedSegment

`func (o *ManaV2ExtranetPolicy) HasSharedSegment() bool`

HasSharedSegment returns a boolean if a field has been set.

### GetSource

`func (o *ManaV2ExtranetPolicy) GetSource() ManaV2PolicyTarget`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ManaV2ExtranetPolicy) GetSourceOk() (*ManaV2PolicyTarget, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ManaV2ExtranetPolicy) SetSource(v ManaV2PolicyTarget)`

SetSource sets Source field to given value.

### HasSource

`func (o *ManaV2ExtranetPolicy) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetTargetSegments

`func (o *ManaV2ExtranetPolicy) GetTargetSegments() []ManaV2Vrf`

GetTargetSegments returns the TargetSegments field if non-nil, zero value otherwise.

### GetTargetSegmentsOk

`func (o *ManaV2ExtranetPolicy) GetTargetSegmentsOk() (*[]ManaV2Vrf, bool)`

GetTargetSegmentsOk returns a tuple with the TargetSegments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetSegments

`func (o *ManaV2ExtranetPolicy) SetTargetSegments(v []ManaV2Vrf)`

SetTargetSegments sets TargetSegments field to given value.

### HasTargetSegments

`func (o *ManaV2ExtranetPolicy) HasTargetSegments() bool`

HasTargetSegments returns a boolean if a field has been set.

### GetType

`func (o *ManaV2ExtranetPolicy) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2ExtranetPolicy) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2ExtranetPolicy) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2ExtranetPolicy) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ManaV2ExtranetPolicy) GetUpdatedAt() GoogleProtobufTimestamp`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ManaV2ExtranetPolicy) GetUpdatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ManaV2ExtranetPolicy) SetUpdatedAt(v GoogleProtobufTimestamp)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ManaV2ExtranetPolicy) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



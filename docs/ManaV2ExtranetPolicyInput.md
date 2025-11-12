# ManaV2ExtranetPolicyInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Auto** | Pointer to [**ManaV2ExtranetAutoReverseRoutes**](ManaV2ExtranetAutoReverseRoutes.md) |  | [optional] 
**Branches** | Pointer to [**ManaV2PolicyTargetInput**](ManaV2PolicyTargetInput.md) |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**HostPrefixSet** | Pointer to [**ManaV2EnterprisePrefixSetInput**](ManaV2EnterprisePrefixSetInput.md) |  | [optional] 
**Manual** | Pointer to [**ManaV2ExtranetManualReverseRoutes**](ManaV2ExtranetManualReverseRoutes.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**SharedPrefixes** | Pointer to **[]string** |  | [optional] 
**SharedSegment** | Pointer to **int64** |  | [optional] 
**Source** | Pointer to [**ManaV2PolicyTargetInput**](ManaV2PolicyTargetInput.md) |  | [optional] 
**TargetSegments** | Pointer to **[]int64** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2ExtranetPolicyInput

`func NewManaV2ExtranetPolicyInput() *ManaV2ExtranetPolicyInput`

NewManaV2ExtranetPolicyInput instantiates a new ManaV2ExtranetPolicyInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ExtranetPolicyInputWithDefaults

`func NewManaV2ExtranetPolicyInputWithDefaults() *ManaV2ExtranetPolicyInput`

NewManaV2ExtranetPolicyInputWithDefaults instantiates a new ManaV2ExtranetPolicyInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuto

`func (o *ManaV2ExtranetPolicyInput) GetAuto() ManaV2ExtranetAutoReverseRoutes`

GetAuto returns the Auto field if non-nil, zero value otherwise.

### GetAutoOk

`func (o *ManaV2ExtranetPolicyInput) GetAutoOk() (*ManaV2ExtranetAutoReverseRoutes, bool)`

GetAutoOk returns a tuple with the Auto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuto

`func (o *ManaV2ExtranetPolicyInput) SetAuto(v ManaV2ExtranetAutoReverseRoutes)`

SetAuto sets Auto field to given value.

### HasAuto

`func (o *ManaV2ExtranetPolicyInput) HasAuto() bool`

HasAuto returns a boolean if a field has been set.

### GetBranches

`func (o *ManaV2ExtranetPolicyInput) GetBranches() ManaV2PolicyTargetInput`

GetBranches returns the Branches field if non-nil, zero value otherwise.

### GetBranchesOk

`func (o *ManaV2ExtranetPolicyInput) GetBranchesOk() (*ManaV2PolicyTargetInput, bool)`

GetBranchesOk returns a tuple with the Branches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranches

`func (o *ManaV2ExtranetPolicyInput) SetBranches(v ManaV2PolicyTargetInput)`

SetBranches sets Branches field to given value.

### HasBranches

`func (o *ManaV2ExtranetPolicyInput) HasBranches() bool`

HasBranches returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2ExtranetPolicyInput) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2ExtranetPolicyInput) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2ExtranetPolicyInput) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2ExtranetPolicyInput) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetHostPrefixSet

`func (o *ManaV2ExtranetPolicyInput) GetHostPrefixSet() ManaV2EnterprisePrefixSetInput`

GetHostPrefixSet returns the HostPrefixSet field if non-nil, zero value otherwise.

### GetHostPrefixSetOk

`func (o *ManaV2ExtranetPolicyInput) GetHostPrefixSetOk() (*ManaV2EnterprisePrefixSetInput, bool)`

GetHostPrefixSetOk returns a tuple with the HostPrefixSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostPrefixSet

`func (o *ManaV2ExtranetPolicyInput) SetHostPrefixSet(v ManaV2EnterprisePrefixSetInput)`

SetHostPrefixSet sets HostPrefixSet field to given value.

### HasHostPrefixSet

`func (o *ManaV2ExtranetPolicyInput) HasHostPrefixSet() bool`

HasHostPrefixSet returns a boolean if a field has been set.

### GetManual

`func (o *ManaV2ExtranetPolicyInput) GetManual() ManaV2ExtranetManualReverseRoutes`

GetManual returns the Manual field if non-nil, zero value otherwise.

### GetManualOk

`func (o *ManaV2ExtranetPolicyInput) GetManualOk() (*ManaV2ExtranetManualReverseRoutes, bool)`

GetManualOk returns a tuple with the Manual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManual

`func (o *ManaV2ExtranetPolicyInput) SetManual(v ManaV2ExtranetManualReverseRoutes)`

SetManual sets Manual field to given value.

### HasManual

`func (o *ManaV2ExtranetPolicyInput) HasManual() bool`

HasManual returns a boolean if a field has been set.

### GetName

`func (o *ManaV2ExtranetPolicyInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2ExtranetPolicyInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2ExtranetPolicyInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2ExtranetPolicyInput) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSharedPrefixes

`func (o *ManaV2ExtranetPolicyInput) GetSharedPrefixes() []string`

GetSharedPrefixes returns the SharedPrefixes field if non-nil, zero value otherwise.

### GetSharedPrefixesOk

`func (o *ManaV2ExtranetPolicyInput) GetSharedPrefixesOk() (*[]string, bool)`

GetSharedPrefixesOk returns a tuple with the SharedPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedPrefixes

`func (o *ManaV2ExtranetPolicyInput) SetSharedPrefixes(v []string)`

SetSharedPrefixes sets SharedPrefixes field to given value.

### HasSharedPrefixes

`func (o *ManaV2ExtranetPolicyInput) HasSharedPrefixes() bool`

HasSharedPrefixes returns a boolean if a field has been set.

### GetSharedSegment

`func (o *ManaV2ExtranetPolicyInput) GetSharedSegment() int64`

GetSharedSegment returns the SharedSegment field if non-nil, zero value otherwise.

### GetSharedSegmentOk

`func (o *ManaV2ExtranetPolicyInput) GetSharedSegmentOk() (*int64, bool)`

GetSharedSegmentOk returns a tuple with the SharedSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedSegment

`func (o *ManaV2ExtranetPolicyInput) SetSharedSegment(v int64)`

SetSharedSegment sets SharedSegment field to given value.

### HasSharedSegment

`func (o *ManaV2ExtranetPolicyInput) HasSharedSegment() bool`

HasSharedSegment returns a boolean if a field has been set.

### GetSource

`func (o *ManaV2ExtranetPolicyInput) GetSource() ManaV2PolicyTargetInput`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ManaV2ExtranetPolicyInput) GetSourceOk() (*ManaV2PolicyTargetInput, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ManaV2ExtranetPolicyInput) SetSource(v ManaV2PolicyTargetInput)`

SetSource sets Source field to given value.

### HasSource

`func (o *ManaV2ExtranetPolicyInput) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetTargetSegments

`func (o *ManaV2ExtranetPolicyInput) GetTargetSegments() []int64`

GetTargetSegments returns the TargetSegments field if non-nil, zero value otherwise.

### GetTargetSegmentsOk

`func (o *ManaV2ExtranetPolicyInput) GetTargetSegmentsOk() (*[]int64, bool)`

GetTargetSegmentsOk returns a tuple with the TargetSegments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetSegments

`func (o *ManaV2ExtranetPolicyInput) SetTargetSegments(v []int64)`

SetTargetSegments sets TargetSegments field to given value.

### HasTargetSegments

`func (o *ManaV2ExtranetPolicyInput) HasTargetSegments() bool`

HasTargetSegments returns a boolean if a field has been set.

### GetType

`func (o *ManaV2ExtranetPolicyInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2ExtranetPolicyInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2ExtranetPolicyInput) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2ExtranetPolicyInput) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



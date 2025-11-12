# ManaV2NATPolicyRulesetRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdvertisePreNatPrefixes** | Pointer to **bool** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Index** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**OriginalDstIpPrefix** | Pointer to **string** |  | [optional] 
**OriginalSrcIpPrefix** | Pointer to **string** |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**TranslatedDstIpPrefix** | Pointer to **string** |  | [optional] 
**TranslatedSrcIpPrefix** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2NATPolicyRulesetRule

`func NewManaV2NATPolicyRulesetRule() *ManaV2NATPolicyRulesetRule`

NewManaV2NATPolicyRulesetRule instantiates a new ManaV2NATPolicyRulesetRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2NATPolicyRulesetRuleWithDefaults

`func NewManaV2NATPolicyRulesetRuleWithDefaults() *ManaV2NATPolicyRulesetRule`

NewManaV2NATPolicyRulesetRuleWithDefaults instantiates a new ManaV2NATPolicyRulesetRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdvertisePreNatPrefixes

`func (o *ManaV2NATPolicyRulesetRule) GetAdvertisePreNatPrefixes() bool`

GetAdvertisePreNatPrefixes returns the AdvertisePreNatPrefixes field if non-nil, zero value otherwise.

### GetAdvertisePreNatPrefixesOk

`func (o *ManaV2NATPolicyRulesetRule) GetAdvertisePreNatPrefixesOk() (*bool, bool)`

GetAdvertisePreNatPrefixesOk returns a tuple with the AdvertisePreNatPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvertisePreNatPrefixes

`func (o *ManaV2NATPolicyRulesetRule) SetAdvertisePreNatPrefixes(v bool)`

SetAdvertisePreNatPrefixes sets AdvertisePreNatPrefixes field to given value.

### HasAdvertisePreNatPrefixes

`func (o *ManaV2NATPolicyRulesetRule) HasAdvertisePreNatPrefixes() bool`

HasAdvertisePreNatPrefixes returns a boolean if a field has been set.

### GetDescription

`func (o *ManaV2NATPolicyRulesetRule) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2NATPolicyRulesetRule) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2NATPolicyRulesetRule) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2NATPolicyRulesetRule) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *ManaV2NATPolicyRulesetRule) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2NATPolicyRulesetRule) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2NATPolicyRulesetRule) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2NATPolicyRulesetRule) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIndex

`func (o *ManaV2NATPolicyRulesetRule) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *ManaV2NATPolicyRulesetRule) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *ManaV2NATPolicyRulesetRule) SetIndex(v int32)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *ManaV2NATPolicyRulesetRule) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### GetName

`func (o *ManaV2NATPolicyRulesetRule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2NATPolicyRulesetRule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2NATPolicyRulesetRule) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2NATPolicyRulesetRule) HasName() bool`

HasName returns a boolean if a field has been set.

### GetOriginalDstIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) GetOriginalDstIpPrefix() string`

GetOriginalDstIpPrefix returns the OriginalDstIpPrefix field if non-nil, zero value otherwise.

### GetOriginalDstIpPrefixOk

`func (o *ManaV2NATPolicyRulesetRule) GetOriginalDstIpPrefixOk() (*string, bool)`

GetOriginalDstIpPrefixOk returns a tuple with the OriginalDstIpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalDstIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) SetOriginalDstIpPrefix(v string)`

SetOriginalDstIpPrefix sets OriginalDstIpPrefix field to given value.

### HasOriginalDstIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) HasOriginalDstIpPrefix() bool`

HasOriginalDstIpPrefix returns a boolean if a field has been set.

### GetOriginalSrcIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) GetOriginalSrcIpPrefix() string`

GetOriginalSrcIpPrefix returns the OriginalSrcIpPrefix field if non-nil, zero value otherwise.

### GetOriginalSrcIpPrefixOk

`func (o *ManaV2NATPolicyRulesetRule) GetOriginalSrcIpPrefixOk() (*string, bool)`

GetOriginalSrcIpPrefixOk returns a tuple with the OriginalSrcIpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalSrcIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) SetOriginalSrcIpPrefix(v string)`

SetOriginalSrcIpPrefix sets OriginalSrcIpPrefix field to given value.

### HasOriginalSrcIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) HasOriginalSrcIpPrefix() bool`

HasOriginalSrcIpPrefix returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2NATPolicyRulesetRule) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2NATPolicyRulesetRule) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2NATPolicyRulesetRule) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2NATPolicyRulesetRule) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

### GetTranslatedDstIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) GetTranslatedDstIpPrefix() string`

GetTranslatedDstIpPrefix returns the TranslatedDstIpPrefix field if non-nil, zero value otherwise.

### GetTranslatedDstIpPrefixOk

`func (o *ManaV2NATPolicyRulesetRule) GetTranslatedDstIpPrefixOk() (*string, bool)`

GetTranslatedDstIpPrefixOk returns a tuple with the TranslatedDstIpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranslatedDstIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) SetTranslatedDstIpPrefix(v string)`

SetTranslatedDstIpPrefix sets TranslatedDstIpPrefix field to given value.

### HasTranslatedDstIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) HasTranslatedDstIpPrefix() bool`

HasTranslatedDstIpPrefix returns a boolean if a field has been set.

### GetTranslatedSrcIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) GetTranslatedSrcIpPrefix() string`

GetTranslatedSrcIpPrefix returns the TranslatedSrcIpPrefix field if non-nil, zero value otherwise.

### GetTranslatedSrcIpPrefixOk

`func (o *ManaV2NATPolicyRulesetRule) GetTranslatedSrcIpPrefixOk() (*string, bool)`

GetTranslatedSrcIpPrefixOk returns a tuple with the TranslatedSrcIpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranslatedSrcIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) SetTranslatedSrcIpPrefix(v string)`

SetTranslatedSrcIpPrefix sets TranslatedSrcIpPrefix field to given value.

### HasTranslatedSrcIpPrefix

`func (o *ManaV2NATPolicyRulesetRule) HasTranslatedSrcIpPrefix() bool`

HasTranslatedSrcIpPrefix returns a boolean if a field has been set.

### GetType

`func (o *ManaV2NATPolicyRulesetRule) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2NATPolicyRulesetRule) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2NATPolicyRulesetRule) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2NATPolicyRulesetRule) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



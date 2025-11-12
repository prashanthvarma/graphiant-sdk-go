# AssuranceBucketSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssuranceBucket** | Pointer to **string** |  | [optional] 
**BucketColor** | Pointer to **string** |  | [optional] 
**BucketNameToDisplay** | Pointer to **string** |  | [optional] 
**BucketStats** | Pointer to [**AssuranceBucketStats**](AssuranceBucketStats.md) |  | [optional] 
**ChildBucketList** | Pointer to **[]string** |  | [optional] 
**ChildBucketStatsList** | Pointer to [**[]AssuranceBucketStatsWithId**](AssuranceBucketStatsWithId.md) |  | [optional] 
**IsRoot** | Pointer to **bool** |  | [optional] 
**IsTerminal** | Pointer to **bool** |  | [optional] 
**ParentBucketList** | Pointer to **[]string** |  | [optional] 

## Methods

### NewAssuranceBucketSummary

`func NewAssuranceBucketSummary() *AssuranceBucketSummary`

NewAssuranceBucketSummary instantiates a new AssuranceBucketSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceBucketSummaryWithDefaults

`func NewAssuranceBucketSummaryWithDefaults() *AssuranceBucketSummary`

NewAssuranceBucketSummaryWithDefaults instantiates a new AssuranceBucketSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssuranceBucket

`func (o *AssuranceBucketSummary) GetAssuranceBucket() string`

GetAssuranceBucket returns the AssuranceBucket field if non-nil, zero value otherwise.

### GetAssuranceBucketOk

`func (o *AssuranceBucketSummary) GetAssuranceBucketOk() (*string, bool)`

GetAssuranceBucketOk returns a tuple with the AssuranceBucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssuranceBucket

`func (o *AssuranceBucketSummary) SetAssuranceBucket(v string)`

SetAssuranceBucket sets AssuranceBucket field to given value.

### HasAssuranceBucket

`func (o *AssuranceBucketSummary) HasAssuranceBucket() bool`

HasAssuranceBucket returns a boolean if a field has been set.

### GetBucketColor

`func (o *AssuranceBucketSummary) GetBucketColor() string`

GetBucketColor returns the BucketColor field if non-nil, zero value otherwise.

### GetBucketColorOk

`func (o *AssuranceBucketSummary) GetBucketColorOk() (*string, bool)`

GetBucketColorOk returns a tuple with the BucketColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketColor

`func (o *AssuranceBucketSummary) SetBucketColor(v string)`

SetBucketColor sets BucketColor field to given value.

### HasBucketColor

`func (o *AssuranceBucketSummary) HasBucketColor() bool`

HasBucketColor returns a boolean if a field has been set.

### GetBucketNameToDisplay

`func (o *AssuranceBucketSummary) GetBucketNameToDisplay() string`

GetBucketNameToDisplay returns the BucketNameToDisplay field if non-nil, zero value otherwise.

### GetBucketNameToDisplayOk

`func (o *AssuranceBucketSummary) GetBucketNameToDisplayOk() (*string, bool)`

GetBucketNameToDisplayOk returns a tuple with the BucketNameToDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketNameToDisplay

`func (o *AssuranceBucketSummary) SetBucketNameToDisplay(v string)`

SetBucketNameToDisplay sets BucketNameToDisplay field to given value.

### HasBucketNameToDisplay

`func (o *AssuranceBucketSummary) HasBucketNameToDisplay() bool`

HasBucketNameToDisplay returns a boolean if a field has been set.

### GetBucketStats

`func (o *AssuranceBucketSummary) GetBucketStats() AssuranceBucketStats`

GetBucketStats returns the BucketStats field if non-nil, zero value otherwise.

### GetBucketStatsOk

`func (o *AssuranceBucketSummary) GetBucketStatsOk() (*AssuranceBucketStats, bool)`

GetBucketStatsOk returns a tuple with the BucketStats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketStats

`func (o *AssuranceBucketSummary) SetBucketStats(v AssuranceBucketStats)`

SetBucketStats sets BucketStats field to given value.

### HasBucketStats

`func (o *AssuranceBucketSummary) HasBucketStats() bool`

HasBucketStats returns a boolean if a field has been set.

### GetChildBucketList

`func (o *AssuranceBucketSummary) GetChildBucketList() []string`

GetChildBucketList returns the ChildBucketList field if non-nil, zero value otherwise.

### GetChildBucketListOk

`func (o *AssuranceBucketSummary) GetChildBucketListOk() (*[]string, bool)`

GetChildBucketListOk returns a tuple with the ChildBucketList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildBucketList

`func (o *AssuranceBucketSummary) SetChildBucketList(v []string)`

SetChildBucketList sets ChildBucketList field to given value.

### HasChildBucketList

`func (o *AssuranceBucketSummary) HasChildBucketList() bool`

HasChildBucketList returns a boolean if a field has been set.

### GetChildBucketStatsList

`func (o *AssuranceBucketSummary) GetChildBucketStatsList() []AssuranceBucketStatsWithId`

GetChildBucketStatsList returns the ChildBucketStatsList field if non-nil, zero value otherwise.

### GetChildBucketStatsListOk

`func (o *AssuranceBucketSummary) GetChildBucketStatsListOk() (*[]AssuranceBucketStatsWithId, bool)`

GetChildBucketStatsListOk returns a tuple with the ChildBucketStatsList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildBucketStatsList

`func (o *AssuranceBucketSummary) SetChildBucketStatsList(v []AssuranceBucketStatsWithId)`

SetChildBucketStatsList sets ChildBucketStatsList field to given value.

### HasChildBucketStatsList

`func (o *AssuranceBucketSummary) HasChildBucketStatsList() bool`

HasChildBucketStatsList returns a boolean if a field has been set.

### GetIsRoot

`func (o *AssuranceBucketSummary) GetIsRoot() bool`

GetIsRoot returns the IsRoot field if non-nil, zero value otherwise.

### GetIsRootOk

`func (o *AssuranceBucketSummary) GetIsRootOk() (*bool, bool)`

GetIsRootOk returns a tuple with the IsRoot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRoot

`func (o *AssuranceBucketSummary) SetIsRoot(v bool)`

SetIsRoot sets IsRoot field to given value.

### HasIsRoot

`func (o *AssuranceBucketSummary) HasIsRoot() bool`

HasIsRoot returns a boolean if a field has been set.

### GetIsTerminal

`func (o *AssuranceBucketSummary) GetIsTerminal() bool`

GetIsTerminal returns the IsTerminal field if non-nil, zero value otherwise.

### GetIsTerminalOk

`func (o *AssuranceBucketSummary) GetIsTerminalOk() (*bool, bool)`

GetIsTerminalOk returns a tuple with the IsTerminal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTerminal

`func (o *AssuranceBucketSummary) SetIsTerminal(v bool)`

SetIsTerminal sets IsTerminal field to given value.

### HasIsTerminal

`func (o *AssuranceBucketSummary) HasIsTerminal() bool`

HasIsTerminal returns a boolean if a field has been set.

### GetParentBucketList

`func (o *AssuranceBucketSummary) GetParentBucketList() []string`

GetParentBucketList returns the ParentBucketList field if non-nil, zero value otherwise.

### GetParentBucketListOk

`func (o *AssuranceBucketSummary) GetParentBucketListOk() (*[]string, bool)`

GetParentBucketListOk returns a tuple with the ParentBucketList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentBucketList

`func (o *AssuranceBucketSummary) SetParentBucketList(v []string)`

SetParentBucketList sets ParentBucketList field to given value.

### HasParentBucketList

`func (o *AssuranceBucketSummary) HasParentBucketList() bool`

HasParentBucketList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



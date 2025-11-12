# AssuranceBucketDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppCountThreatHigh** | Pointer to **int64** |  | [optional] 
**AppCountThreatLow** | Pointer to **int64** |  | [optional] 
**AppCountThreatMedium** | Pointer to **int64** |  | [optional] 
**AppIdRecords** | Pointer to [**[]AssuranceAppIdRecord**](AssuranceAppIdRecord.md) |  | [optional] 
**AppNameRecords** | Pointer to [**[]AssuranceAppNameRecord**](AssuranceAppNameRecord.md) |  | [optional] 
**BucketNameToDisplay** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DisplayIpPort** | Pointer to **bool** |  | [optional] 
**FlowCount** | Pointer to **int64** |  | [optional] 
**NewIpHint** | Pointer to **bool** |  | [optional] 
**Recommendation** | Pointer to **string** |  | [optional] 
**TrendValueList** | Pointer to [**[]AssuranceTrendValue**](AssuranceTrendValue.md) |  | [optional] 
**UniqueAppCount** | Pointer to **int64** |  | [optional] 

## Methods

### NewAssuranceBucketDetails

`func NewAssuranceBucketDetails() *AssuranceBucketDetails`

NewAssuranceBucketDetails instantiates a new AssuranceBucketDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceBucketDetailsWithDefaults

`func NewAssuranceBucketDetailsWithDefaults() *AssuranceBucketDetails`

NewAssuranceBucketDetailsWithDefaults instantiates a new AssuranceBucketDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppCountThreatHigh

`func (o *AssuranceBucketDetails) GetAppCountThreatHigh() int64`

GetAppCountThreatHigh returns the AppCountThreatHigh field if non-nil, zero value otherwise.

### GetAppCountThreatHighOk

`func (o *AssuranceBucketDetails) GetAppCountThreatHighOk() (*int64, bool)`

GetAppCountThreatHighOk returns a tuple with the AppCountThreatHigh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppCountThreatHigh

`func (o *AssuranceBucketDetails) SetAppCountThreatHigh(v int64)`

SetAppCountThreatHigh sets AppCountThreatHigh field to given value.

### HasAppCountThreatHigh

`func (o *AssuranceBucketDetails) HasAppCountThreatHigh() bool`

HasAppCountThreatHigh returns a boolean if a field has been set.

### GetAppCountThreatLow

`func (o *AssuranceBucketDetails) GetAppCountThreatLow() int64`

GetAppCountThreatLow returns the AppCountThreatLow field if non-nil, zero value otherwise.

### GetAppCountThreatLowOk

`func (o *AssuranceBucketDetails) GetAppCountThreatLowOk() (*int64, bool)`

GetAppCountThreatLowOk returns a tuple with the AppCountThreatLow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppCountThreatLow

`func (o *AssuranceBucketDetails) SetAppCountThreatLow(v int64)`

SetAppCountThreatLow sets AppCountThreatLow field to given value.

### HasAppCountThreatLow

`func (o *AssuranceBucketDetails) HasAppCountThreatLow() bool`

HasAppCountThreatLow returns a boolean if a field has been set.

### GetAppCountThreatMedium

`func (o *AssuranceBucketDetails) GetAppCountThreatMedium() int64`

GetAppCountThreatMedium returns the AppCountThreatMedium field if non-nil, zero value otherwise.

### GetAppCountThreatMediumOk

`func (o *AssuranceBucketDetails) GetAppCountThreatMediumOk() (*int64, bool)`

GetAppCountThreatMediumOk returns a tuple with the AppCountThreatMedium field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppCountThreatMedium

`func (o *AssuranceBucketDetails) SetAppCountThreatMedium(v int64)`

SetAppCountThreatMedium sets AppCountThreatMedium field to given value.

### HasAppCountThreatMedium

`func (o *AssuranceBucketDetails) HasAppCountThreatMedium() bool`

HasAppCountThreatMedium returns a boolean if a field has been set.

### GetAppIdRecords

`func (o *AssuranceBucketDetails) GetAppIdRecords() []AssuranceAppIdRecord`

GetAppIdRecords returns the AppIdRecords field if non-nil, zero value otherwise.

### GetAppIdRecordsOk

`func (o *AssuranceBucketDetails) GetAppIdRecordsOk() (*[]AssuranceAppIdRecord, bool)`

GetAppIdRecordsOk returns a tuple with the AppIdRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppIdRecords

`func (o *AssuranceBucketDetails) SetAppIdRecords(v []AssuranceAppIdRecord)`

SetAppIdRecords sets AppIdRecords field to given value.

### HasAppIdRecords

`func (o *AssuranceBucketDetails) HasAppIdRecords() bool`

HasAppIdRecords returns a boolean if a field has been set.

### GetAppNameRecords

`func (o *AssuranceBucketDetails) GetAppNameRecords() []AssuranceAppNameRecord`

GetAppNameRecords returns the AppNameRecords field if non-nil, zero value otherwise.

### GetAppNameRecordsOk

`func (o *AssuranceBucketDetails) GetAppNameRecordsOk() (*[]AssuranceAppNameRecord, bool)`

GetAppNameRecordsOk returns a tuple with the AppNameRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppNameRecords

`func (o *AssuranceBucketDetails) SetAppNameRecords(v []AssuranceAppNameRecord)`

SetAppNameRecords sets AppNameRecords field to given value.

### HasAppNameRecords

`func (o *AssuranceBucketDetails) HasAppNameRecords() bool`

HasAppNameRecords returns a boolean if a field has been set.

### GetBucketNameToDisplay

`func (o *AssuranceBucketDetails) GetBucketNameToDisplay() string`

GetBucketNameToDisplay returns the BucketNameToDisplay field if non-nil, zero value otherwise.

### GetBucketNameToDisplayOk

`func (o *AssuranceBucketDetails) GetBucketNameToDisplayOk() (*string, bool)`

GetBucketNameToDisplayOk returns a tuple with the BucketNameToDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketNameToDisplay

`func (o *AssuranceBucketDetails) SetBucketNameToDisplay(v string)`

SetBucketNameToDisplay sets BucketNameToDisplay field to given value.

### HasBucketNameToDisplay

`func (o *AssuranceBucketDetails) HasBucketNameToDisplay() bool`

HasBucketNameToDisplay returns a boolean if a field has been set.

### GetDescription

`func (o *AssuranceBucketDetails) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AssuranceBucketDetails) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AssuranceBucketDetails) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AssuranceBucketDetails) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDisplayIpPort

`func (o *AssuranceBucketDetails) GetDisplayIpPort() bool`

GetDisplayIpPort returns the DisplayIpPort field if non-nil, zero value otherwise.

### GetDisplayIpPortOk

`func (o *AssuranceBucketDetails) GetDisplayIpPortOk() (*bool, bool)`

GetDisplayIpPortOk returns a tuple with the DisplayIpPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayIpPort

`func (o *AssuranceBucketDetails) SetDisplayIpPort(v bool)`

SetDisplayIpPort sets DisplayIpPort field to given value.

### HasDisplayIpPort

`func (o *AssuranceBucketDetails) HasDisplayIpPort() bool`

HasDisplayIpPort returns a boolean if a field has been set.

### GetFlowCount

`func (o *AssuranceBucketDetails) GetFlowCount() int64`

GetFlowCount returns the FlowCount field if non-nil, zero value otherwise.

### GetFlowCountOk

`func (o *AssuranceBucketDetails) GetFlowCountOk() (*int64, bool)`

GetFlowCountOk returns a tuple with the FlowCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlowCount

`func (o *AssuranceBucketDetails) SetFlowCount(v int64)`

SetFlowCount sets FlowCount field to given value.

### HasFlowCount

`func (o *AssuranceBucketDetails) HasFlowCount() bool`

HasFlowCount returns a boolean if a field has been set.

### GetNewIpHint

`func (o *AssuranceBucketDetails) GetNewIpHint() bool`

GetNewIpHint returns the NewIpHint field if non-nil, zero value otherwise.

### GetNewIpHintOk

`func (o *AssuranceBucketDetails) GetNewIpHintOk() (*bool, bool)`

GetNewIpHintOk returns a tuple with the NewIpHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewIpHint

`func (o *AssuranceBucketDetails) SetNewIpHint(v bool)`

SetNewIpHint sets NewIpHint field to given value.

### HasNewIpHint

`func (o *AssuranceBucketDetails) HasNewIpHint() bool`

HasNewIpHint returns a boolean if a field has been set.

### GetRecommendation

`func (o *AssuranceBucketDetails) GetRecommendation() string`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *AssuranceBucketDetails) GetRecommendationOk() (*string, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *AssuranceBucketDetails) SetRecommendation(v string)`

SetRecommendation sets Recommendation field to given value.

### HasRecommendation

`func (o *AssuranceBucketDetails) HasRecommendation() bool`

HasRecommendation returns a boolean if a field has been set.

### GetTrendValueList

`func (o *AssuranceBucketDetails) GetTrendValueList() []AssuranceTrendValue`

GetTrendValueList returns the TrendValueList field if non-nil, zero value otherwise.

### GetTrendValueListOk

`func (o *AssuranceBucketDetails) GetTrendValueListOk() (*[]AssuranceTrendValue, bool)`

GetTrendValueListOk returns a tuple with the TrendValueList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrendValueList

`func (o *AssuranceBucketDetails) SetTrendValueList(v []AssuranceTrendValue)`

SetTrendValueList sets TrendValueList field to given value.

### HasTrendValueList

`func (o *AssuranceBucketDetails) HasTrendValueList() bool`

HasTrendValueList returns a boolean if a field has been set.

### GetUniqueAppCount

`func (o *AssuranceBucketDetails) GetUniqueAppCount() int64`

GetUniqueAppCount returns the UniqueAppCount field if non-nil, zero value otherwise.

### GetUniqueAppCountOk

`func (o *AssuranceBucketDetails) GetUniqueAppCountOk() (*int64, bool)`

GetUniqueAppCountOk returns a tuple with the UniqueAppCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueAppCount

`func (o *AssuranceBucketDetails) SetUniqueAppCount(v int64)`

SetUniqueAppCount sets UniqueAppCount field to given value.

### HasUniqueAppCount

`func (o *AssuranceBucketDetails) HasUniqueAppCount() bool`

HasUniqueAppCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



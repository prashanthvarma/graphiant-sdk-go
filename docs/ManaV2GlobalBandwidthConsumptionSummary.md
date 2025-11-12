# ManaV2GlobalBandwidthConsumptionSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllocatedMonthlyCredits** | Pointer to **float32** | Credits allocated for the current month | [optional] 
**ConsumedMonthlyCredits** | Pointer to **float32** | Credits billed for the current month. It equals the the higher value between the credits allocated and used for the month | [optional] 
**PriorAllocatedMonthlyCredits** | Pointer to **float32** | Credits allocated for the prior month | [optional] 
**PriorConsumedMonthlyCredits** | Pointer to **float32** | Credits billed for the prior month. | [optional] 
**RecommendedMonthlyCredits** | Pointer to **float32** | Expected amount of credits to allocate for the month to match the overall contracted amount. For monthly-contracted enterprises, this is equivalent to the monthly number of credits being billed while for term-based-contracted enterprises, this is equivalent to the number of credits to use up in this and the following months to use up exactly the number of credits remaining in the contract. | [optional] 

## Methods

### NewManaV2GlobalBandwidthConsumptionSummary

`func NewManaV2GlobalBandwidthConsumptionSummary() *ManaV2GlobalBandwidthConsumptionSummary`

NewManaV2GlobalBandwidthConsumptionSummary instantiates a new ManaV2GlobalBandwidthConsumptionSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2GlobalBandwidthConsumptionSummaryWithDefaults

`func NewManaV2GlobalBandwidthConsumptionSummaryWithDefaults() *ManaV2GlobalBandwidthConsumptionSummary`

NewManaV2GlobalBandwidthConsumptionSummaryWithDefaults instantiates a new ManaV2GlobalBandwidthConsumptionSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllocatedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetAllocatedMonthlyCredits() float32`

GetAllocatedMonthlyCredits returns the AllocatedMonthlyCredits field if non-nil, zero value otherwise.

### GetAllocatedMonthlyCreditsOk

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetAllocatedMonthlyCreditsOk() (*float32, bool)`

GetAllocatedMonthlyCreditsOk returns a tuple with the AllocatedMonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocatedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) SetAllocatedMonthlyCredits(v float32)`

SetAllocatedMonthlyCredits sets AllocatedMonthlyCredits field to given value.

### HasAllocatedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) HasAllocatedMonthlyCredits() bool`

HasAllocatedMonthlyCredits returns a boolean if a field has been set.

### GetConsumedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetConsumedMonthlyCredits() float32`

GetConsumedMonthlyCredits returns the ConsumedMonthlyCredits field if non-nil, zero value otherwise.

### GetConsumedMonthlyCreditsOk

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetConsumedMonthlyCreditsOk() (*float32, bool)`

GetConsumedMonthlyCreditsOk returns a tuple with the ConsumedMonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) SetConsumedMonthlyCredits(v float32)`

SetConsumedMonthlyCredits sets ConsumedMonthlyCredits field to given value.

### HasConsumedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) HasConsumedMonthlyCredits() bool`

HasConsumedMonthlyCredits returns a boolean if a field has been set.

### GetPriorAllocatedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetPriorAllocatedMonthlyCredits() float32`

GetPriorAllocatedMonthlyCredits returns the PriorAllocatedMonthlyCredits field if non-nil, zero value otherwise.

### GetPriorAllocatedMonthlyCreditsOk

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetPriorAllocatedMonthlyCreditsOk() (*float32, bool)`

GetPriorAllocatedMonthlyCreditsOk returns a tuple with the PriorAllocatedMonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorAllocatedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) SetPriorAllocatedMonthlyCredits(v float32)`

SetPriorAllocatedMonthlyCredits sets PriorAllocatedMonthlyCredits field to given value.

### HasPriorAllocatedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) HasPriorAllocatedMonthlyCredits() bool`

HasPriorAllocatedMonthlyCredits returns a boolean if a field has been set.

### GetPriorConsumedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetPriorConsumedMonthlyCredits() float32`

GetPriorConsumedMonthlyCredits returns the PriorConsumedMonthlyCredits field if non-nil, zero value otherwise.

### GetPriorConsumedMonthlyCreditsOk

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetPriorConsumedMonthlyCreditsOk() (*float32, bool)`

GetPriorConsumedMonthlyCreditsOk returns a tuple with the PriorConsumedMonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorConsumedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) SetPriorConsumedMonthlyCredits(v float32)`

SetPriorConsumedMonthlyCredits sets PriorConsumedMonthlyCredits field to given value.

### HasPriorConsumedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) HasPriorConsumedMonthlyCredits() bool`

HasPriorConsumedMonthlyCredits returns a boolean if a field has been set.

### GetRecommendedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetRecommendedMonthlyCredits() float32`

GetRecommendedMonthlyCredits returns the RecommendedMonthlyCredits field if non-nil, zero value otherwise.

### GetRecommendedMonthlyCreditsOk

`func (o *ManaV2GlobalBandwidthConsumptionSummary) GetRecommendedMonthlyCreditsOk() (*float32, bool)`

GetRecommendedMonthlyCreditsOk returns a tuple with the RecommendedMonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) SetRecommendedMonthlyCredits(v float32)`

SetRecommendedMonthlyCredits sets RecommendedMonthlyCredits field to given value.

### HasRecommendedMonthlyCredits

`func (o *ManaV2GlobalBandwidthConsumptionSummary) HasRecommendedMonthlyCredits() bool`

HasRecommendedMonthlyCredits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2RegionalBandwidthConsumptionSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Allocation** | Pointer to [**ManaV2BandwidthInfo**](ManaV2BandwidthInfo.md) |  | [optional] 
**ConsumedCredits** | Pointer to **float32** | Credits billed for the region. It equals the higher value between total credits allocated and used plus any additional dia consumption | [optional] 
**CoreConversionFactor** | Pointer to **float32** | Conversion rate from gigabytes per second to Graphiant credits used for calculating credits on core networks for this region | [optional] 
**GwConversionFactor** | Pointer to **float32** | Conversion rate from gigabytes per second to Graphiant credits used for calculating credits on core networks for this region | [optional] 
**InternetConsumption** | Pointer to [**ManaV2InternetAccessBandwidthInfo**](ManaV2InternetAccessBandwidthInfo.md) |  | [optional] 
**Usage** | Pointer to [**ManaV2BandwidthInfo**](ManaV2BandwidthInfo.md) |  | [optional] 

## Methods

### NewManaV2RegionalBandwidthConsumptionSummary

`func NewManaV2RegionalBandwidthConsumptionSummary() *ManaV2RegionalBandwidthConsumptionSummary`

NewManaV2RegionalBandwidthConsumptionSummary instantiates a new ManaV2RegionalBandwidthConsumptionSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2RegionalBandwidthConsumptionSummaryWithDefaults

`func NewManaV2RegionalBandwidthConsumptionSummaryWithDefaults() *ManaV2RegionalBandwidthConsumptionSummary`

NewManaV2RegionalBandwidthConsumptionSummaryWithDefaults instantiates a new ManaV2RegionalBandwidthConsumptionSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllocation

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetAllocation() ManaV2BandwidthInfo`

GetAllocation returns the Allocation field if non-nil, zero value otherwise.

### GetAllocationOk

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetAllocationOk() (*ManaV2BandwidthInfo, bool)`

GetAllocationOk returns a tuple with the Allocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocation

`func (o *ManaV2RegionalBandwidthConsumptionSummary) SetAllocation(v ManaV2BandwidthInfo)`

SetAllocation sets Allocation field to given value.

### HasAllocation

`func (o *ManaV2RegionalBandwidthConsumptionSummary) HasAllocation() bool`

HasAllocation returns a boolean if a field has been set.

### GetConsumedCredits

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetConsumedCredits() float32`

GetConsumedCredits returns the ConsumedCredits field if non-nil, zero value otherwise.

### GetConsumedCreditsOk

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetConsumedCreditsOk() (*float32, bool)`

GetConsumedCreditsOk returns a tuple with the ConsumedCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumedCredits

`func (o *ManaV2RegionalBandwidthConsumptionSummary) SetConsumedCredits(v float32)`

SetConsumedCredits sets ConsumedCredits field to given value.

### HasConsumedCredits

`func (o *ManaV2RegionalBandwidthConsumptionSummary) HasConsumedCredits() bool`

HasConsumedCredits returns a boolean if a field has been set.

### GetCoreConversionFactor

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetCoreConversionFactor() float32`

GetCoreConversionFactor returns the CoreConversionFactor field if non-nil, zero value otherwise.

### GetCoreConversionFactorOk

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetCoreConversionFactorOk() (*float32, bool)`

GetCoreConversionFactorOk returns a tuple with the CoreConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreConversionFactor

`func (o *ManaV2RegionalBandwidthConsumptionSummary) SetCoreConversionFactor(v float32)`

SetCoreConversionFactor sets CoreConversionFactor field to given value.

### HasCoreConversionFactor

`func (o *ManaV2RegionalBandwidthConsumptionSummary) HasCoreConversionFactor() bool`

HasCoreConversionFactor returns a boolean if a field has been set.

### GetGwConversionFactor

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetGwConversionFactor() float32`

GetGwConversionFactor returns the GwConversionFactor field if non-nil, zero value otherwise.

### GetGwConversionFactorOk

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetGwConversionFactorOk() (*float32, bool)`

GetGwConversionFactorOk returns a tuple with the GwConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGwConversionFactor

`func (o *ManaV2RegionalBandwidthConsumptionSummary) SetGwConversionFactor(v float32)`

SetGwConversionFactor sets GwConversionFactor field to given value.

### HasGwConversionFactor

`func (o *ManaV2RegionalBandwidthConsumptionSummary) HasGwConversionFactor() bool`

HasGwConversionFactor returns a boolean if a field has been set.

### GetInternetConsumption

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetInternetConsumption() ManaV2InternetAccessBandwidthInfo`

GetInternetConsumption returns the InternetConsumption field if non-nil, zero value otherwise.

### GetInternetConsumptionOk

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetInternetConsumptionOk() (*ManaV2InternetAccessBandwidthInfo, bool)`

GetInternetConsumptionOk returns a tuple with the InternetConsumption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternetConsumption

`func (o *ManaV2RegionalBandwidthConsumptionSummary) SetInternetConsumption(v ManaV2InternetAccessBandwidthInfo)`

SetInternetConsumption sets InternetConsumption field to given value.

### HasInternetConsumption

`func (o *ManaV2RegionalBandwidthConsumptionSummary) HasInternetConsumption() bool`

HasInternetConsumption returns a boolean if a field has been set.

### GetUsage

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetUsage() ManaV2BandwidthInfo`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *ManaV2RegionalBandwidthConsumptionSummary) GetUsageOk() (*ManaV2BandwidthInfo, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *ManaV2RegionalBandwidthConsumptionSummary) SetUsage(v ManaV2BandwidthInfo)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *ManaV2RegionalBandwidthConsumptionSummary) HasUsage() bool`

HasUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



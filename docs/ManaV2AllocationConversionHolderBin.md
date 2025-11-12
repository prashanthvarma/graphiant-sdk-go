# ManaV2AllocationConversionHolderBin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllocationUpperBound** | Pointer to **float32** | Int32 value indicating the conversion rates apply from the prior highest upper bound to this upper bound | [optional] 
**CoreConversionFactor** | Pointer to **float32** | Conversion rate from gigabytes per second to Graphiant credits for connections to core devices | [optional] 
**CoreConversionRate** | Pointer to **int32** |  | [optional] 
**GwConversionFactor** | Pointer to **float32** | Conversion rate from gigabytes per second to Graphiant credits for connections to gateway devices | [optional] 
**GwConversionRate** | Pointer to **int32** |  | [optional] 
**IsPrivate** | Pointer to **bool** | True-only flag indicating the conversion rates apply within a private context such as in-country | [optional] 

## Methods

### NewManaV2AllocationConversionHolderBin

`func NewManaV2AllocationConversionHolderBin() *ManaV2AllocationConversionHolderBin`

NewManaV2AllocationConversionHolderBin instantiates a new ManaV2AllocationConversionHolderBin object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AllocationConversionHolderBinWithDefaults

`func NewManaV2AllocationConversionHolderBinWithDefaults() *ManaV2AllocationConversionHolderBin`

NewManaV2AllocationConversionHolderBinWithDefaults instantiates a new ManaV2AllocationConversionHolderBin object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllocationUpperBound

`func (o *ManaV2AllocationConversionHolderBin) GetAllocationUpperBound() float32`

GetAllocationUpperBound returns the AllocationUpperBound field if non-nil, zero value otherwise.

### GetAllocationUpperBoundOk

`func (o *ManaV2AllocationConversionHolderBin) GetAllocationUpperBoundOk() (*float32, bool)`

GetAllocationUpperBoundOk returns a tuple with the AllocationUpperBound field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocationUpperBound

`func (o *ManaV2AllocationConversionHolderBin) SetAllocationUpperBound(v float32)`

SetAllocationUpperBound sets AllocationUpperBound field to given value.

### HasAllocationUpperBound

`func (o *ManaV2AllocationConversionHolderBin) HasAllocationUpperBound() bool`

HasAllocationUpperBound returns a boolean if a field has been set.

### GetCoreConversionFactor

`func (o *ManaV2AllocationConversionHolderBin) GetCoreConversionFactor() float32`

GetCoreConversionFactor returns the CoreConversionFactor field if non-nil, zero value otherwise.

### GetCoreConversionFactorOk

`func (o *ManaV2AllocationConversionHolderBin) GetCoreConversionFactorOk() (*float32, bool)`

GetCoreConversionFactorOk returns a tuple with the CoreConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreConversionFactor

`func (o *ManaV2AllocationConversionHolderBin) SetCoreConversionFactor(v float32)`

SetCoreConversionFactor sets CoreConversionFactor field to given value.

### HasCoreConversionFactor

`func (o *ManaV2AllocationConversionHolderBin) HasCoreConversionFactor() bool`

HasCoreConversionFactor returns a boolean if a field has been set.

### GetCoreConversionRate

`func (o *ManaV2AllocationConversionHolderBin) GetCoreConversionRate() int32`

GetCoreConversionRate returns the CoreConversionRate field if non-nil, zero value otherwise.

### GetCoreConversionRateOk

`func (o *ManaV2AllocationConversionHolderBin) GetCoreConversionRateOk() (*int32, bool)`

GetCoreConversionRateOk returns a tuple with the CoreConversionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreConversionRate

`func (o *ManaV2AllocationConversionHolderBin) SetCoreConversionRate(v int32)`

SetCoreConversionRate sets CoreConversionRate field to given value.

### HasCoreConversionRate

`func (o *ManaV2AllocationConversionHolderBin) HasCoreConversionRate() bool`

HasCoreConversionRate returns a boolean if a field has been set.

### GetGwConversionFactor

`func (o *ManaV2AllocationConversionHolderBin) GetGwConversionFactor() float32`

GetGwConversionFactor returns the GwConversionFactor field if non-nil, zero value otherwise.

### GetGwConversionFactorOk

`func (o *ManaV2AllocationConversionHolderBin) GetGwConversionFactorOk() (*float32, bool)`

GetGwConversionFactorOk returns a tuple with the GwConversionFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGwConversionFactor

`func (o *ManaV2AllocationConversionHolderBin) SetGwConversionFactor(v float32)`

SetGwConversionFactor sets GwConversionFactor field to given value.

### HasGwConversionFactor

`func (o *ManaV2AllocationConversionHolderBin) HasGwConversionFactor() bool`

HasGwConversionFactor returns a boolean if a field has been set.

### GetGwConversionRate

`func (o *ManaV2AllocationConversionHolderBin) GetGwConversionRate() int32`

GetGwConversionRate returns the GwConversionRate field if non-nil, zero value otherwise.

### GetGwConversionRateOk

`func (o *ManaV2AllocationConversionHolderBin) GetGwConversionRateOk() (*int32, bool)`

GetGwConversionRateOk returns a tuple with the GwConversionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGwConversionRate

`func (o *ManaV2AllocationConversionHolderBin) SetGwConversionRate(v int32)`

SetGwConversionRate sets GwConversionRate field to given value.

### HasGwConversionRate

`func (o *ManaV2AllocationConversionHolderBin) HasGwConversionRate() bool`

HasGwConversionRate returns a boolean if a field has been set.

### GetIsPrivate

`func (o *ManaV2AllocationConversionHolderBin) GetIsPrivate() bool`

GetIsPrivate returns the IsPrivate field if non-nil, zero value otherwise.

### GetIsPrivateOk

`func (o *ManaV2AllocationConversionHolderBin) GetIsPrivateOk() (*bool, bool)`

GetIsPrivateOk returns a tuple with the IsPrivate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPrivate

`func (o *ManaV2AllocationConversionHolderBin) SetIsPrivate(v bool)`

SetIsPrivate sets IsPrivate field to given value.

### HasIsPrivate

`func (o *ManaV2AllocationConversionHolderBin) HasIsPrivate() bool`

HasIsPrivate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2BandwidthConsumptionSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContractualSummary** | Pointer to [**ManaV2ContractualBandwidthConsumptionSummary**](ManaV2ContractualBandwidthConsumptionSummary.md) |  | [optional] 
**GlobalSummary** | Pointer to [**ManaV2GlobalBandwidthConsumptionSummary**](ManaV2GlobalBandwidthConsumptionSummary.md) |  | [optional] 
**RegionalSummaries** | Pointer to [**map[string]ManaV2RegionalBandwidthConsumptionSummary**](ManaV2RegionalBandwidthConsumptionSummary.md) |  | [optional] 

## Methods

### NewManaV2BandwidthConsumptionSummary

`func NewManaV2BandwidthConsumptionSummary() *ManaV2BandwidthConsumptionSummary`

NewManaV2BandwidthConsumptionSummary instantiates a new ManaV2BandwidthConsumptionSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BandwidthConsumptionSummaryWithDefaults

`func NewManaV2BandwidthConsumptionSummaryWithDefaults() *ManaV2BandwidthConsumptionSummary`

NewManaV2BandwidthConsumptionSummaryWithDefaults instantiates a new ManaV2BandwidthConsumptionSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContractualSummary

`func (o *ManaV2BandwidthConsumptionSummary) GetContractualSummary() ManaV2ContractualBandwidthConsumptionSummary`

GetContractualSummary returns the ContractualSummary field if non-nil, zero value otherwise.

### GetContractualSummaryOk

`func (o *ManaV2BandwidthConsumptionSummary) GetContractualSummaryOk() (*ManaV2ContractualBandwidthConsumptionSummary, bool)`

GetContractualSummaryOk returns a tuple with the ContractualSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractualSummary

`func (o *ManaV2BandwidthConsumptionSummary) SetContractualSummary(v ManaV2ContractualBandwidthConsumptionSummary)`

SetContractualSummary sets ContractualSummary field to given value.

### HasContractualSummary

`func (o *ManaV2BandwidthConsumptionSummary) HasContractualSummary() bool`

HasContractualSummary returns a boolean if a field has been set.

### GetGlobalSummary

`func (o *ManaV2BandwidthConsumptionSummary) GetGlobalSummary() ManaV2GlobalBandwidthConsumptionSummary`

GetGlobalSummary returns the GlobalSummary field if non-nil, zero value otherwise.

### GetGlobalSummaryOk

`func (o *ManaV2BandwidthConsumptionSummary) GetGlobalSummaryOk() (*ManaV2GlobalBandwidthConsumptionSummary, bool)`

GetGlobalSummaryOk returns a tuple with the GlobalSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalSummary

`func (o *ManaV2BandwidthConsumptionSummary) SetGlobalSummary(v ManaV2GlobalBandwidthConsumptionSummary)`

SetGlobalSummary sets GlobalSummary field to given value.

### HasGlobalSummary

`func (o *ManaV2BandwidthConsumptionSummary) HasGlobalSummary() bool`

HasGlobalSummary returns a boolean if a field has been set.

### GetRegionalSummaries

`func (o *ManaV2BandwidthConsumptionSummary) GetRegionalSummaries() map[string]ManaV2RegionalBandwidthConsumptionSummary`

GetRegionalSummaries returns the RegionalSummaries field if non-nil, zero value otherwise.

### GetRegionalSummariesOk

`func (o *ManaV2BandwidthConsumptionSummary) GetRegionalSummariesOk() (*map[string]ManaV2RegionalBandwidthConsumptionSummary, bool)`

GetRegionalSummariesOk returns a tuple with the RegionalSummaries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionalSummaries

`func (o *ManaV2BandwidthConsumptionSummary) SetRegionalSummaries(v map[string]ManaV2RegionalBandwidthConsumptionSummary)`

SetRegionalSummaries sets RegionalSummaries field to given value.

### HasRegionalSummaries

`func (o *ManaV2BandwidthConsumptionSummary) HasRegionalSummaries() bool`

HasRegionalSummaries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



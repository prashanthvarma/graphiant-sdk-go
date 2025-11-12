# ManaV2RegionalAllocation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllocationCore** | Pointer to **float32** | Gigabytes per second allowed for core network connections on this region | [optional] 
**AllocationGw** | Pointer to **float32** | Gigabytes per second allowed for gateway connections on this region | [optional] 
**AllocationInternet** | Pointer to **float32** | Gigabytes per second allowed for dia gateway internet access on this region. Must be 0, 10, or 100 | [optional] 
**CreditCore** | Pointer to **float32** |  | [optional] 
**CreditGw** | Pointer to **float32** |  | [optional] 
**RegionId** | Pointer to **int32** |  | [optional] 
**RegionName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2RegionalAllocation

`func NewManaV2RegionalAllocation() *ManaV2RegionalAllocation`

NewManaV2RegionalAllocation instantiates a new ManaV2RegionalAllocation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2RegionalAllocationWithDefaults

`func NewManaV2RegionalAllocationWithDefaults() *ManaV2RegionalAllocation`

NewManaV2RegionalAllocationWithDefaults instantiates a new ManaV2RegionalAllocation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllocationCore

`func (o *ManaV2RegionalAllocation) GetAllocationCore() float32`

GetAllocationCore returns the AllocationCore field if non-nil, zero value otherwise.

### GetAllocationCoreOk

`func (o *ManaV2RegionalAllocation) GetAllocationCoreOk() (*float32, bool)`

GetAllocationCoreOk returns a tuple with the AllocationCore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocationCore

`func (o *ManaV2RegionalAllocation) SetAllocationCore(v float32)`

SetAllocationCore sets AllocationCore field to given value.

### HasAllocationCore

`func (o *ManaV2RegionalAllocation) HasAllocationCore() bool`

HasAllocationCore returns a boolean if a field has been set.

### GetAllocationGw

`func (o *ManaV2RegionalAllocation) GetAllocationGw() float32`

GetAllocationGw returns the AllocationGw field if non-nil, zero value otherwise.

### GetAllocationGwOk

`func (o *ManaV2RegionalAllocation) GetAllocationGwOk() (*float32, bool)`

GetAllocationGwOk returns a tuple with the AllocationGw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocationGw

`func (o *ManaV2RegionalAllocation) SetAllocationGw(v float32)`

SetAllocationGw sets AllocationGw field to given value.

### HasAllocationGw

`func (o *ManaV2RegionalAllocation) HasAllocationGw() bool`

HasAllocationGw returns a boolean if a field has been set.

### GetAllocationInternet

`func (o *ManaV2RegionalAllocation) GetAllocationInternet() float32`

GetAllocationInternet returns the AllocationInternet field if non-nil, zero value otherwise.

### GetAllocationInternetOk

`func (o *ManaV2RegionalAllocation) GetAllocationInternetOk() (*float32, bool)`

GetAllocationInternetOk returns a tuple with the AllocationInternet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocationInternet

`func (o *ManaV2RegionalAllocation) SetAllocationInternet(v float32)`

SetAllocationInternet sets AllocationInternet field to given value.

### HasAllocationInternet

`func (o *ManaV2RegionalAllocation) HasAllocationInternet() bool`

HasAllocationInternet returns a boolean if a field has been set.

### GetCreditCore

`func (o *ManaV2RegionalAllocation) GetCreditCore() float32`

GetCreditCore returns the CreditCore field if non-nil, zero value otherwise.

### GetCreditCoreOk

`func (o *ManaV2RegionalAllocation) GetCreditCoreOk() (*float32, bool)`

GetCreditCoreOk returns a tuple with the CreditCore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditCore

`func (o *ManaV2RegionalAllocation) SetCreditCore(v float32)`

SetCreditCore sets CreditCore field to given value.

### HasCreditCore

`func (o *ManaV2RegionalAllocation) HasCreditCore() bool`

HasCreditCore returns a boolean if a field has been set.

### GetCreditGw

`func (o *ManaV2RegionalAllocation) GetCreditGw() float32`

GetCreditGw returns the CreditGw field if non-nil, zero value otherwise.

### GetCreditGwOk

`func (o *ManaV2RegionalAllocation) GetCreditGwOk() (*float32, bool)`

GetCreditGwOk returns a tuple with the CreditGw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditGw

`func (o *ManaV2RegionalAllocation) SetCreditGw(v float32)`

SetCreditGw sets CreditGw field to given value.

### HasCreditGw

`func (o *ManaV2RegionalAllocation) HasCreditGw() bool`

HasCreditGw returns a boolean if a field has been set.

### GetRegionId

`func (o *ManaV2RegionalAllocation) GetRegionId() int32`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *ManaV2RegionalAllocation) GetRegionIdOk() (*int32, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *ManaV2RegionalAllocation) SetRegionId(v int32)`

SetRegionId sets RegionId field to given value.

### HasRegionId

`func (o *ManaV2RegionalAllocation) HasRegionId() bool`

HasRegionId returns a boolean if a field has been set.

### GetRegionName

`func (o *ManaV2RegionalAllocation) GetRegionName() string`

GetRegionName returns the RegionName field if non-nil, zero value otherwise.

### GetRegionNameOk

`func (o *ManaV2RegionalAllocation) GetRegionNameOk() (*string, bool)`

GetRegionNameOk returns a tuple with the RegionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionName

`func (o *ManaV2RegionalAllocation) SetRegionName(v string)`

SetRegionName sets RegionName field to given value.

### HasRegionName

`func (o *ManaV2RegionalAllocation) HasRegionName() bool`

HasRegionName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



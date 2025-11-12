# V1EdgesHardwareUnassignedGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Inventory** | Pointer to [**[]OnboardingHardwareInventory**](OnboardingHardwareInventory.md) |  | [optional] 
**IsNewCount** | Pointer to **int32** |  | [optional] 

## Methods

### NewV1EdgesHardwareUnassignedGetResponse

`func NewV1EdgesHardwareUnassignedGetResponse() *V1EdgesHardwareUnassignedGetResponse`

NewV1EdgesHardwareUnassignedGetResponse instantiates a new V1EdgesHardwareUnassignedGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EdgesHardwareUnassignedGetResponseWithDefaults

`func NewV1EdgesHardwareUnassignedGetResponseWithDefaults() *V1EdgesHardwareUnassignedGetResponse`

NewV1EdgesHardwareUnassignedGetResponseWithDefaults instantiates a new V1EdgesHardwareUnassignedGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInventory

`func (o *V1EdgesHardwareUnassignedGetResponse) GetInventory() []OnboardingHardwareInventory`

GetInventory returns the Inventory field if non-nil, zero value otherwise.

### GetInventoryOk

`func (o *V1EdgesHardwareUnassignedGetResponse) GetInventoryOk() (*[]OnboardingHardwareInventory, bool)`

GetInventoryOk returns a tuple with the Inventory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventory

`func (o *V1EdgesHardwareUnassignedGetResponse) SetInventory(v []OnboardingHardwareInventory)`

SetInventory sets Inventory field to given value.

### HasInventory

`func (o *V1EdgesHardwareUnassignedGetResponse) HasInventory() bool`

HasInventory returns a boolean if a field has been set.

### GetIsNewCount

`func (o *V1EdgesHardwareUnassignedGetResponse) GetIsNewCount() int32`

GetIsNewCount returns the IsNewCount field if non-nil, zero value otherwise.

### GetIsNewCountOk

`func (o *V1EdgesHardwareUnassignedGetResponse) GetIsNewCountOk() (*int32, bool)`

GetIsNewCountOk returns a tuple with the IsNewCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNewCount

`func (o *V1EdgesHardwareUnassignedGetResponse) SetIsNewCount(v int32)`

SetIsNewCount sets IsNewCount field to given value.

### HasIsNewCount

`func (o *V1EdgesHardwareUnassignedGetResponse) HasIsNewCount() bool`

HasIsNewCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesInventoryGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Inventory** | Pointer to [**[]OnboardingHardwareInventory**](OnboardingHardwareInventory.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Methods

### NewV1DevicesInventoryGetResponse

`func NewV1DevicesInventoryGetResponse() *V1DevicesInventoryGetResponse`

NewV1DevicesInventoryGetResponse instantiates a new V1DevicesInventoryGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesInventoryGetResponseWithDefaults

`func NewV1DevicesInventoryGetResponseWithDefaults() *V1DevicesInventoryGetResponse`

NewV1DevicesInventoryGetResponseWithDefaults instantiates a new V1DevicesInventoryGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInventory

`func (o *V1DevicesInventoryGetResponse) GetInventory() []OnboardingHardwareInventory`

GetInventory returns the Inventory field if non-nil, zero value otherwise.

### GetInventoryOk

`func (o *V1DevicesInventoryGetResponse) GetInventoryOk() (*[]OnboardingHardwareInventory, bool)`

GetInventoryOk returns a tuple with the Inventory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventory

`func (o *V1DevicesInventoryGetResponse) SetInventory(v []OnboardingHardwareInventory)`

SetInventory sets Inventory field to given value.

### HasInventory

`func (o *V1DevicesInventoryGetResponse) HasInventory() bool`

HasInventory returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DevicesInventoryGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DevicesInventoryGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DevicesInventoryGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DevicesInventoryGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



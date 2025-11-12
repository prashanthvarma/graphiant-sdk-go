# V1DevicesInventoryGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotAssigned** | Pointer to **bool** |  | [optional] 
**PageRequest** | Pointer to [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Methods

### NewV1DevicesInventoryGetRequest

`func NewV1DevicesInventoryGetRequest() *V1DevicesInventoryGetRequest`

NewV1DevicesInventoryGetRequest instantiates a new V1DevicesInventoryGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesInventoryGetRequestWithDefaults

`func NewV1DevicesInventoryGetRequestWithDefaults() *V1DevicesInventoryGetRequest`

NewV1DevicesInventoryGetRequestWithDefaults instantiates a new V1DevicesInventoryGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotAssigned

`func (o *V1DevicesInventoryGetRequest) GetNotAssigned() bool`

GetNotAssigned returns the NotAssigned field if non-nil, zero value otherwise.

### GetNotAssignedOk

`func (o *V1DevicesInventoryGetRequest) GetNotAssignedOk() (*bool, bool)`

GetNotAssignedOk returns a tuple with the NotAssigned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotAssigned

`func (o *V1DevicesInventoryGetRequest) SetNotAssigned(v bool)`

SetNotAssigned sets NotAssigned field to given value.

### HasNotAssigned

`func (o *V1DevicesInventoryGetRequest) HasNotAssigned() bool`

HasNotAssigned returns a boolean if a field has been set.

### GetPageRequest

`func (o *V1DevicesInventoryGetRequest) GetPageRequest() CommonPageRequest`

GetPageRequest returns the PageRequest field if non-nil, zero value otherwise.

### GetPageRequestOk

`func (o *V1DevicesInventoryGetRequest) GetPageRequestOk() (*CommonPageRequest, bool)`

GetPageRequestOk returns a tuple with the PageRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRequest

`func (o *V1DevicesInventoryGetRequest) SetPageRequest(v CommonPageRequest)`

SetPageRequest sets PageRequest field to given value.

### HasPageRequest

`func (o *V1DevicesInventoryGetRequest) HasPageRequest() bool`

HasPageRequest returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



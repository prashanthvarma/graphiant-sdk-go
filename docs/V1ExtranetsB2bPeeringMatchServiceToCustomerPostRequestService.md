# V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** |  | [optional] 
**LanSegment** | Pointer to **int64** |  | [optional] 
**Nat** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner.md) |  | [optional] 
**NumCustomers** | Pointer to **int32** |  | [optional] 
**ServicePrefixes** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner.md) |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService

`func NewV1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService() *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService`

NewV1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService instantiates a new V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceWithDefaults

`func NewV1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceWithDefaults() *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService`

NewV1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceWithDefaults instantiates a new V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLanSegment

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetLanSegment() int64`

GetLanSegment returns the LanSegment field if non-nil, zero value otherwise.

### GetLanSegmentOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetLanSegmentOk() (*int64, bool)`

GetLanSegmentOk returns a tuple with the LanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegment

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) SetLanSegment(v int64)`

SetLanSegment sets LanSegment field to given value.

### HasLanSegment

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) HasLanSegment() bool`

HasLanSegment returns a boolean if a field has been set.

### GetNat

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetNat() []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner`

GetNat returns the Nat field if non-nil, zero value otherwise.

### GetNatOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetNatOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner, bool)`

GetNatOk returns a tuple with the Nat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNat

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) SetNat(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner)`

SetNat sets Nat field to given value.

### HasNat

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) HasNat() bool`

HasNat returns a boolean if a field has been set.

### GetNumCustomers

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetNumCustomers() int32`

GetNumCustomers returns the NumCustomers field if non-nil, zero value otherwise.

### GetNumCustomersOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetNumCustomersOk() (*int32, bool)`

GetNumCustomersOk returns a tuple with the NumCustomers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumCustomers

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) SetNumCustomers(v int32)`

SetNumCustomers sets NumCustomers field to given value.

### HasNumCustomers

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) HasNumCustomers() bool`

HasNumCustomers returns a boolean if a field has been set.

### GetServicePrefixes

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetServicePrefixes() []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner`

GetServicePrefixes returns the ServicePrefixes field if non-nil, zero value otherwise.

### GetServicePrefixesOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) GetServicePrefixesOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner, bool)`

GetServicePrefixesOk returns a tuple with the ServicePrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePrefixes

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) SetServicePrefixes(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner)`

SetServicePrefixes sets ServicePrefixes field to given value.

### HasServicePrefixes

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestService) HasServicePrefixes() bool`

HasServicePrefixes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



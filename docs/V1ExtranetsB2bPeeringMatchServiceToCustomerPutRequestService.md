# V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** |  | [optional] 
**LanSegment** | Pointer to **int64** |  | [optional] 
**Nat** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner.md) |  | [optional] 
**NumCustomers** | Pointer to **int32** |  | [optional] 
**ServicePrefixes** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner.md) |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService

`func NewV1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService() *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService`

NewV1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService instantiates a new V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceWithDefaults

`func NewV1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceWithDefaults() *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService`

NewV1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceWithDefaults instantiates a new V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLanSegment

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetLanSegment() int64`

GetLanSegment returns the LanSegment field if non-nil, zero value otherwise.

### GetLanSegmentOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetLanSegmentOk() (*int64, bool)`

GetLanSegmentOk returns a tuple with the LanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegment

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) SetLanSegment(v int64)`

SetLanSegment sets LanSegment field to given value.

### HasLanSegment

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) HasLanSegment() bool`

HasLanSegment returns a boolean if a field has been set.

### GetNat

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetNat() []V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner`

GetNat returns the Nat field if non-nil, zero value otherwise.

### GetNatOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetNatOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner, bool)`

GetNatOk returns a tuple with the Nat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNat

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) SetNat(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner)`

SetNat sets Nat field to given value.

### HasNat

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) HasNat() bool`

HasNat returns a boolean if a field has been set.

### GetNumCustomers

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetNumCustomers() int32`

GetNumCustomers returns the NumCustomers field if non-nil, zero value otherwise.

### GetNumCustomersOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetNumCustomersOk() (*int32, bool)`

GetNumCustomersOk returns a tuple with the NumCustomers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumCustomers

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) SetNumCustomers(v int32)`

SetNumCustomers sets NumCustomers field to given value.

### HasNumCustomers

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) HasNumCustomers() bool`

HasNumCustomers returns a boolean if a field has been set.

### GetServicePrefixes

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetServicePrefixes() []V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner`

GetServicePrefixes returns the ServicePrefixes field if non-nil, zero value otherwise.

### GetServicePrefixesOk

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) GetServicePrefixesOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner, bool)`

GetServicePrefixesOk returns a tuple with the ServicePrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePrefixes

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) SetServicePrefixes(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner)`

SetServicePrefixes sets ServicePrefixes field to given value.

### HasServicePrefixes

`func (o *V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService) HasServicePrefixes() bool`

HasServicePrefixes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



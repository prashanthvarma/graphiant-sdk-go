# V1ExtranetsB2bPeeringConsumerIdPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **int64** |  | [optional] 
**Nat** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner.md) |  | [optional] 
**Policy** | Pointer to [**[]V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner**](V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner.md) |  | [optional] 
**SiteInformation** | Pointer to [**[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**SiteToSiteVpn** | Pointer to [**V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn**](V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn.md) |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringConsumerIdPostRequest

`func NewV1ExtranetsB2bPeeringConsumerIdPostRequest() *V1ExtranetsB2bPeeringConsumerIdPostRequest`

NewV1ExtranetsB2bPeeringConsumerIdPostRequest instantiates a new V1ExtranetsB2bPeeringConsumerIdPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringConsumerIdPostRequestWithDefaults

`func NewV1ExtranetsB2bPeeringConsumerIdPostRequestWithDefaults() *V1ExtranetsB2bPeeringConsumerIdPostRequest`

NewV1ExtranetsB2bPeeringConsumerIdPostRequestWithDefaults instantiates a new V1ExtranetsB2bPeeringConsumerIdPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetCustomerId() int64`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetCustomerIdOk() (*int64, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) SetCustomerId(v int64)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetNat

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetNat() []V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner`

GetNat returns the Nat field if non-nil, zero value otherwise.

### GetNatOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetNatOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner, bool)`

GetNatOk returns a tuple with the Nat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNat

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) SetNat(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner)`

SetNat sets Nat field to given value.

### HasNat

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) HasNat() bool`

HasNat returns a boolean if a field has been set.

### GetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetPolicy() []V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetPolicyOk() (*[]V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) SetPolicy(v []V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### GetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetSiteInformation() []V1ExtranetsB2bConsumerPostRequestSiteInformationInner`

GetSiteInformation returns the SiteInformation field if non-nil, zero value otherwise.

### GetSiteInformationOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetSiteInformationOk() (*[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner, bool)`

GetSiteInformationOk returns a tuple with the SiteInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) SetSiteInformation(v []V1ExtranetsB2bConsumerPostRequestSiteInformationInner)`

SetSiteInformation sets SiteInformation field to given value.

### HasSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) HasSiteInformation() bool`

HasSiteInformation returns a boolean if a field has been set.

### GetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetSiteToSiteVpn() V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn`

GetSiteToSiteVpn returns the SiteToSiteVpn field if non-nil, zero value otherwise.

### GetSiteToSiteVpnOk

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) GetSiteToSiteVpnOk() (*V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn, bool)`

GetSiteToSiteVpnOk returns a tuple with the SiteToSiteVpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) SetSiteToSiteVpn(v V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn)`

SetSiteToSiteVpn sets SiteToSiteVpn field to given value.

### HasSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerIdPostRequest) HasSiteToSiteVpn() bool`

HasSiteToSiteVpn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



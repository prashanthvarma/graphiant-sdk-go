# V1ExtranetsB2bPeeringConsumerMatchIdPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **int64** |  | [optional] 
**GlobalObjectOps** | Pointer to [**map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Nat** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner.md) |  | [optional] 
**Policy** | Pointer to [**[]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner.md) |  | [optional] 
**SiteInformation** | Pointer to [**[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**SiteToSiteVpn** | Pointer to [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.md) |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequest

`func NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequest() *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest`

NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequest instantiates a new V1ExtranetsB2bPeeringConsumerMatchIdPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestWithDefaults

`func NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestWithDefaults() *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest`

NewV1ExtranetsB2bPeeringConsumerMatchIdPostRequestWithDefaults instantiates a new V1ExtranetsB2bPeeringConsumerMatchIdPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetCustomerId() int64`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetCustomerIdOk() (*int64, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetCustomerId(v int64)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetGlobalObjectOps

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetGlobalObjectOps() map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue`

GetGlobalObjectOps returns the GlobalObjectOps field if non-nil, zero value otherwise.

### GetGlobalObjectOpsOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetGlobalObjectOpsOk() (*map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue, bool)`

GetGlobalObjectOpsOk returns a tuple with the GlobalObjectOps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalObjectOps

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetGlobalObjectOps(v map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue)`

SetGlobalObjectOps sets GlobalObjectOps field to given value.

### HasGlobalObjectOps

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasGlobalObjectOps() bool`

HasGlobalObjectOps returns a boolean if a field has been set.

### GetId

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetNat

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetNat() []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner`

GetNat returns the Nat field if non-nil, zero value otherwise.

### GetNatOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetNatOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner, bool)`

GetNatOk returns a tuple with the Nat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNat

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetNat(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner)`

SetNat sets Nat field to given value.

### HasNat

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasNat() bool`

HasNat returns a boolean if a field has been set.

### GetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetPolicy() []V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetPolicyOk() (*[]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetPolicy(v []V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### GetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetSiteInformation() []V1ExtranetsB2bConsumerPostRequestSiteInformationInner`

GetSiteInformation returns the SiteInformation field if non-nil, zero value otherwise.

### GetSiteInformationOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetSiteInformationOk() (*[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner, bool)`

GetSiteInformationOk returns a tuple with the SiteInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetSiteInformation(v []V1ExtranetsB2bConsumerPostRequestSiteInformationInner)`

SetSiteInformation sets SiteInformation field to given value.

### HasSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasSiteInformation() bool`

HasSiteInformation returns a boolean if a field has been set.

### GetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetSiteToSiteVpn() V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn`

GetSiteToSiteVpn returns the SiteToSiteVpn field if non-nil, zero value otherwise.

### GetSiteToSiteVpnOk

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) GetSiteToSiteVpnOk() (*V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn, bool)`

GetSiteToSiteVpnOk returns a tuple with the SiteToSiteVpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) SetSiteToSiteVpn(v V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn)`

SetSiteToSiteVpn sets SiteToSiteVpn field to given value.

### HasSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerMatchIdPostRequest) HasSiteToSiteVpn() bool`

HasSiteToSiteVpn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2ForwardingPolicyMatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Application** | Pointer to **string** |  | [optional] 
**DestinationNetwork** | Pointer to **string** |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**DestinationPortRange** | Pointer to [**ManaV2PortRange**](ManaV2PortRange.md) |  | [optional] 
**DomainCategoryIds** | Pointer to **[]int64** |  | [optional] 
**DomainWildcards** | Pointer to **[]string** |  | [optional] 
**Dscp** | Pointer to [**ManaV2Dscp**](ManaV2Dscp.md) |  | [optional] 
**IcmpType** | Pointer to **int32** |  | [optional] 
**IpProtocol** | Pointer to **string** |  | [optional] 
**Protocol** | Pointer to **string** |  | [optional] 
**SourceNetwork** | Pointer to **string** |  | [optional] 
**SourcePort** | Pointer to **int32** |  | [optional] 
**SourcePortRange** | Pointer to [**ManaV2PortRange**](ManaV2PortRange.md) |  | [optional] 

## Methods

### NewManaV2ForwardingPolicyMatch

`func NewManaV2ForwardingPolicyMatch() *ManaV2ForwardingPolicyMatch`

NewManaV2ForwardingPolicyMatch instantiates a new ManaV2ForwardingPolicyMatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ForwardingPolicyMatchWithDefaults

`func NewManaV2ForwardingPolicyMatchWithDefaults() *ManaV2ForwardingPolicyMatch`

NewManaV2ForwardingPolicyMatchWithDefaults instantiates a new ManaV2ForwardingPolicyMatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplication

`func (o *ManaV2ForwardingPolicyMatch) GetApplication() string`

GetApplication returns the Application field if non-nil, zero value otherwise.

### GetApplicationOk

`func (o *ManaV2ForwardingPolicyMatch) GetApplicationOk() (*string, bool)`

GetApplicationOk returns a tuple with the Application field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplication

`func (o *ManaV2ForwardingPolicyMatch) SetApplication(v string)`

SetApplication sets Application field to given value.

### HasApplication

`func (o *ManaV2ForwardingPolicyMatch) HasApplication() bool`

HasApplication returns a boolean if a field has been set.

### GetDestinationNetwork

`func (o *ManaV2ForwardingPolicyMatch) GetDestinationNetwork() string`

GetDestinationNetwork returns the DestinationNetwork field if non-nil, zero value otherwise.

### GetDestinationNetworkOk

`func (o *ManaV2ForwardingPolicyMatch) GetDestinationNetworkOk() (*string, bool)`

GetDestinationNetworkOk returns a tuple with the DestinationNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationNetwork

`func (o *ManaV2ForwardingPolicyMatch) SetDestinationNetwork(v string)`

SetDestinationNetwork sets DestinationNetwork field to given value.

### HasDestinationNetwork

`func (o *ManaV2ForwardingPolicyMatch) HasDestinationNetwork() bool`

HasDestinationNetwork returns a boolean if a field has been set.

### GetDestinationPort

`func (o *ManaV2ForwardingPolicyMatch) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *ManaV2ForwardingPolicyMatch) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *ManaV2ForwardingPolicyMatch) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *ManaV2ForwardingPolicyMatch) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetDestinationPortRange

`func (o *ManaV2ForwardingPolicyMatch) GetDestinationPortRange() ManaV2PortRange`

GetDestinationPortRange returns the DestinationPortRange field if non-nil, zero value otherwise.

### GetDestinationPortRangeOk

`func (o *ManaV2ForwardingPolicyMatch) GetDestinationPortRangeOk() (*ManaV2PortRange, bool)`

GetDestinationPortRangeOk returns a tuple with the DestinationPortRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPortRange

`func (o *ManaV2ForwardingPolicyMatch) SetDestinationPortRange(v ManaV2PortRange)`

SetDestinationPortRange sets DestinationPortRange field to given value.

### HasDestinationPortRange

`func (o *ManaV2ForwardingPolicyMatch) HasDestinationPortRange() bool`

HasDestinationPortRange returns a boolean if a field has been set.

### GetDomainCategoryIds

`func (o *ManaV2ForwardingPolicyMatch) GetDomainCategoryIds() []int64`

GetDomainCategoryIds returns the DomainCategoryIds field if non-nil, zero value otherwise.

### GetDomainCategoryIdsOk

`func (o *ManaV2ForwardingPolicyMatch) GetDomainCategoryIdsOk() (*[]int64, bool)`

GetDomainCategoryIdsOk returns a tuple with the DomainCategoryIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainCategoryIds

`func (o *ManaV2ForwardingPolicyMatch) SetDomainCategoryIds(v []int64)`

SetDomainCategoryIds sets DomainCategoryIds field to given value.

### HasDomainCategoryIds

`func (o *ManaV2ForwardingPolicyMatch) HasDomainCategoryIds() bool`

HasDomainCategoryIds returns a boolean if a field has been set.

### GetDomainWildcards

`func (o *ManaV2ForwardingPolicyMatch) GetDomainWildcards() []string`

GetDomainWildcards returns the DomainWildcards field if non-nil, zero value otherwise.

### GetDomainWildcardsOk

`func (o *ManaV2ForwardingPolicyMatch) GetDomainWildcardsOk() (*[]string, bool)`

GetDomainWildcardsOk returns a tuple with the DomainWildcards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainWildcards

`func (o *ManaV2ForwardingPolicyMatch) SetDomainWildcards(v []string)`

SetDomainWildcards sets DomainWildcards field to given value.

### HasDomainWildcards

`func (o *ManaV2ForwardingPolicyMatch) HasDomainWildcards() bool`

HasDomainWildcards returns a boolean if a field has been set.

### GetDscp

`func (o *ManaV2ForwardingPolicyMatch) GetDscp() ManaV2Dscp`

GetDscp returns the Dscp field if non-nil, zero value otherwise.

### GetDscpOk

`func (o *ManaV2ForwardingPolicyMatch) GetDscpOk() (*ManaV2Dscp, bool)`

GetDscpOk returns a tuple with the Dscp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDscp

`func (o *ManaV2ForwardingPolicyMatch) SetDscp(v ManaV2Dscp)`

SetDscp sets Dscp field to given value.

### HasDscp

`func (o *ManaV2ForwardingPolicyMatch) HasDscp() bool`

HasDscp returns a boolean if a field has been set.

### GetIcmpType

`func (o *ManaV2ForwardingPolicyMatch) GetIcmpType() int32`

GetIcmpType returns the IcmpType field if non-nil, zero value otherwise.

### GetIcmpTypeOk

`func (o *ManaV2ForwardingPolicyMatch) GetIcmpTypeOk() (*int32, bool)`

GetIcmpTypeOk returns a tuple with the IcmpType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcmpType

`func (o *ManaV2ForwardingPolicyMatch) SetIcmpType(v int32)`

SetIcmpType sets IcmpType field to given value.

### HasIcmpType

`func (o *ManaV2ForwardingPolicyMatch) HasIcmpType() bool`

HasIcmpType returns a boolean if a field has been set.

### GetIpProtocol

`func (o *ManaV2ForwardingPolicyMatch) GetIpProtocol() string`

GetIpProtocol returns the IpProtocol field if non-nil, zero value otherwise.

### GetIpProtocolOk

`func (o *ManaV2ForwardingPolicyMatch) GetIpProtocolOk() (*string, bool)`

GetIpProtocolOk returns a tuple with the IpProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpProtocol

`func (o *ManaV2ForwardingPolicyMatch) SetIpProtocol(v string)`

SetIpProtocol sets IpProtocol field to given value.

### HasIpProtocol

`func (o *ManaV2ForwardingPolicyMatch) HasIpProtocol() bool`

HasIpProtocol returns a boolean if a field has been set.

### GetProtocol

`func (o *ManaV2ForwardingPolicyMatch) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *ManaV2ForwardingPolicyMatch) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *ManaV2ForwardingPolicyMatch) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *ManaV2ForwardingPolicyMatch) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetSourceNetwork

`func (o *ManaV2ForwardingPolicyMatch) GetSourceNetwork() string`

GetSourceNetwork returns the SourceNetwork field if non-nil, zero value otherwise.

### GetSourceNetworkOk

`func (o *ManaV2ForwardingPolicyMatch) GetSourceNetworkOk() (*string, bool)`

GetSourceNetworkOk returns a tuple with the SourceNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNetwork

`func (o *ManaV2ForwardingPolicyMatch) SetSourceNetwork(v string)`

SetSourceNetwork sets SourceNetwork field to given value.

### HasSourceNetwork

`func (o *ManaV2ForwardingPolicyMatch) HasSourceNetwork() bool`

HasSourceNetwork returns a boolean if a field has been set.

### GetSourcePort

`func (o *ManaV2ForwardingPolicyMatch) GetSourcePort() int32`

GetSourcePort returns the SourcePort field if non-nil, zero value otherwise.

### GetSourcePortOk

`func (o *ManaV2ForwardingPolicyMatch) GetSourcePortOk() (*int32, bool)`

GetSourcePortOk returns a tuple with the SourcePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePort

`func (o *ManaV2ForwardingPolicyMatch) SetSourcePort(v int32)`

SetSourcePort sets SourcePort field to given value.

### HasSourcePort

`func (o *ManaV2ForwardingPolicyMatch) HasSourcePort() bool`

HasSourcePort returns a boolean if a field has been set.

### GetSourcePortRange

`func (o *ManaV2ForwardingPolicyMatch) GetSourcePortRange() ManaV2PortRange`

GetSourcePortRange returns the SourcePortRange field if non-nil, zero value otherwise.

### GetSourcePortRangeOk

`func (o *ManaV2ForwardingPolicyMatch) GetSourcePortRangeOk() (*ManaV2PortRange, bool)`

GetSourcePortRangeOk returns a tuple with the SourcePortRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePortRange

`func (o *ManaV2ForwardingPolicyMatch) SetSourcePortRange(v ManaV2PortRange)`

SetSourcePortRange sets SourcePortRange field to given value.

### HasSourcePortRange

`func (o *ManaV2ForwardingPolicyMatch) HasSourcePortRange() bool`

HasSourcePortRange returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



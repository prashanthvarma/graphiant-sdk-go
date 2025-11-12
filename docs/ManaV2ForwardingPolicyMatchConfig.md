# ManaV2ForwardingPolicyMatchConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Application** | Pointer to [**ManaV2NullableApplicationMatchConfig**](ManaV2NullableApplicationMatchConfig.md) |  | [optional] 
**ContentFilter** | Pointer to [**ManaV2NullableContentFilterMatchConfig**](ManaV2NullableContentFilterMatchConfig.md) |  | [optional] 
**DestinationNetwork** | Pointer to [**ManaV2NullableDestinationNetworkMatchConfig**](ManaV2NullableDestinationNetworkMatchConfig.md) |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**DestinationPortRange** | Pointer to [**ManaV2PortRangeConfig**](ManaV2PortRangeConfig.md) |  | [optional] 
**DomainList** | Pointer to [**ManaV2NullableDomainListMatchConfig**](ManaV2NullableDomainListMatchConfig.md) |  | [optional] 
**Dscp** | Pointer to [**ManaV2NullableDscpMatchConfig**](ManaV2NullableDscpMatchConfig.md) |  | [optional] 
**IcmpType** | Pointer to **int32** |  | [optional] 
**IpProtocol** | Pointer to **string** |  | [optional] 
**Protocol** | Pointer to [**ManaV2NullableIpProtocol**](ManaV2NullableIpProtocol.md) |  | [optional] 
**SourceNetwork** | Pointer to [**ManaV2NullableSourceNetworkMatchConfig**](ManaV2NullableSourceNetworkMatchConfig.md) |  | [optional] 
**SourcePort** | Pointer to **int32** |  | [optional] 
**SourcePortRange** | Pointer to [**ManaV2PortRangeConfig**](ManaV2PortRangeConfig.md) |  | [optional] 

## Methods

### NewManaV2ForwardingPolicyMatchConfig

`func NewManaV2ForwardingPolicyMatchConfig() *ManaV2ForwardingPolicyMatchConfig`

NewManaV2ForwardingPolicyMatchConfig instantiates a new ManaV2ForwardingPolicyMatchConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ForwardingPolicyMatchConfigWithDefaults

`func NewManaV2ForwardingPolicyMatchConfigWithDefaults() *ManaV2ForwardingPolicyMatchConfig`

NewManaV2ForwardingPolicyMatchConfigWithDefaults instantiates a new ManaV2ForwardingPolicyMatchConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplication

`func (o *ManaV2ForwardingPolicyMatchConfig) GetApplication() ManaV2NullableApplicationMatchConfig`

GetApplication returns the Application field if non-nil, zero value otherwise.

### GetApplicationOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetApplicationOk() (*ManaV2NullableApplicationMatchConfig, bool)`

GetApplicationOk returns a tuple with the Application field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplication

`func (o *ManaV2ForwardingPolicyMatchConfig) SetApplication(v ManaV2NullableApplicationMatchConfig)`

SetApplication sets Application field to given value.

### HasApplication

`func (o *ManaV2ForwardingPolicyMatchConfig) HasApplication() bool`

HasApplication returns a boolean if a field has been set.

### GetContentFilter

`func (o *ManaV2ForwardingPolicyMatchConfig) GetContentFilter() ManaV2NullableContentFilterMatchConfig`

GetContentFilter returns the ContentFilter field if non-nil, zero value otherwise.

### GetContentFilterOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetContentFilterOk() (*ManaV2NullableContentFilterMatchConfig, bool)`

GetContentFilterOk returns a tuple with the ContentFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentFilter

`func (o *ManaV2ForwardingPolicyMatchConfig) SetContentFilter(v ManaV2NullableContentFilterMatchConfig)`

SetContentFilter sets ContentFilter field to given value.

### HasContentFilter

`func (o *ManaV2ForwardingPolicyMatchConfig) HasContentFilter() bool`

HasContentFilter returns a boolean if a field has been set.

### GetDestinationNetwork

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDestinationNetwork() ManaV2NullableDestinationNetworkMatchConfig`

GetDestinationNetwork returns the DestinationNetwork field if non-nil, zero value otherwise.

### GetDestinationNetworkOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDestinationNetworkOk() (*ManaV2NullableDestinationNetworkMatchConfig, bool)`

GetDestinationNetworkOk returns a tuple with the DestinationNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationNetwork

`func (o *ManaV2ForwardingPolicyMatchConfig) SetDestinationNetwork(v ManaV2NullableDestinationNetworkMatchConfig)`

SetDestinationNetwork sets DestinationNetwork field to given value.

### HasDestinationNetwork

`func (o *ManaV2ForwardingPolicyMatchConfig) HasDestinationNetwork() bool`

HasDestinationNetwork returns a boolean if a field has been set.

### GetDestinationPort

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *ManaV2ForwardingPolicyMatchConfig) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *ManaV2ForwardingPolicyMatchConfig) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetDestinationPortRange

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDestinationPortRange() ManaV2PortRangeConfig`

GetDestinationPortRange returns the DestinationPortRange field if non-nil, zero value otherwise.

### GetDestinationPortRangeOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDestinationPortRangeOk() (*ManaV2PortRangeConfig, bool)`

GetDestinationPortRangeOk returns a tuple with the DestinationPortRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPortRange

`func (o *ManaV2ForwardingPolicyMatchConfig) SetDestinationPortRange(v ManaV2PortRangeConfig)`

SetDestinationPortRange sets DestinationPortRange field to given value.

### HasDestinationPortRange

`func (o *ManaV2ForwardingPolicyMatchConfig) HasDestinationPortRange() bool`

HasDestinationPortRange returns a boolean if a field has been set.

### GetDomainList

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDomainList() ManaV2NullableDomainListMatchConfig`

GetDomainList returns the DomainList field if non-nil, zero value otherwise.

### GetDomainListOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDomainListOk() (*ManaV2NullableDomainListMatchConfig, bool)`

GetDomainListOk returns a tuple with the DomainList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainList

`func (o *ManaV2ForwardingPolicyMatchConfig) SetDomainList(v ManaV2NullableDomainListMatchConfig)`

SetDomainList sets DomainList field to given value.

### HasDomainList

`func (o *ManaV2ForwardingPolicyMatchConfig) HasDomainList() bool`

HasDomainList returns a boolean if a field has been set.

### GetDscp

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDscp() ManaV2NullableDscpMatchConfig`

GetDscp returns the Dscp field if non-nil, zero value otherwise.

### GetDscpOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetDscpOk() (*ManaV2NullableDscpMatchConfig, bool)`

GetDscpOk returns a tuple with the Dscp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDscp

`func (o *ManaV2ForwardingPolicyMatchConfig) SetDscp(v ManaV2NullableDscpMatchConfig)`

SetDscp sets Dscp field to given value.

### HasDscp

`func (o *ManaV2ForwardingPolicyMatchConfig) HasDscp() bool`

HasDscp returns a boolean if a field has been set.

### GetIcmpType

`func (o *ManaV2ForwardingPolicyMatchConfig) GetIcmpType() int32`

GetIcmpType returns the IcmpType field if non-nil, zero value otherwise.

### GetIcmpTypeOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetIcmpTypeOk() (*int32, bool)`

GetIcmpTypeOk returns a tuple with the IcmpType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcmpType

`func (o *ManaV2ForwardingPolicyMatchConfig) SetIcmpType(v int32)`

SetIcmpType sets IcmpType field to given value.

### HasIcmpType

`func (o *ManaV2ForwardingPolicyMatchConfig) HasIcmpType() bool`

HasIcmpType returns a boolean if a field has been set.

### GetIpProtocol

`func (o *ManaV2ForwardingPolicyMatchConfig) GetIpProtocol() string`

GetIpProtocol returns the IpProtocol field if non-nil, zero value otherwise.

### GetIpProtocolOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetIpProtocolOk() (*string, bool)`

GetIpProtocolOk returns a tuple with the IpProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpProtocol

`func (o *ManaV2ForwardingPolicyMatchConfig) SetIpProtocol(v string)`

SetIpProtocol sets IpProtocol field to given value.

### HasIpProtocol

`func (o *ManaV2ForwardingPolicyMatchConfig) HasIpProtocol() bool`

HasIpProtocol returns a boolean if a field has been set.

### GetProtocol

`func (o *ManaV2ForwardingPolicyMatchConfig) GetProtocol() ManaV2NullableIpProtocol`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetProtocolOk() (*ManaV2NullableIpProtocol, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *ManaV2ForwardingPolicyMatchConfig) SetProtocol(v ManaV2NullableIpProtocol)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *ManaV2ForwardingPolicyMatchConfig) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetSourceNetwork

`func (o *ManaV2ForwardingPolicyMatchConfig) GetSourceNetwork() ManaV2NullableSourceNetworkMatchConfig`

GetSourceNetwork returns the SourceNetwork field if non-nil, zero value otherwise.

### GetSourceNetworkOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetSourceNetworkOk() (*ManaV2NullableSourceNetworkMatchConfig, bool)`

GetSourceNetworkOk returns a tuple with the SourceNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNetwork

`func (o *ManaV2ForwardingPolicyMatchConfig) SetSourceNetwork(v ManaV2NullableSourceNetworkMatchConfig)`

SetSourceNetwork sets SourceNetwork field to given value.

### HasSourceNetwork

`func (o *ManaV2ForwardingPolicyMatchConfig) HasSourceNetwork() bool`

HasSourceNetwork returns a boolean if a field has been set.

### GetSourcePort

`func (o *ManaV2ForwardingPolicyMatchConfig) GetSourcePort() int32`

GetSourcePort returns the SourcePort field if non-nil, zero value otherwise.

### GetSourcePortOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetSourcePortOk() (*int32, bool)`

GetSourcePortOk returns a tuple with the SourcePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePort

`func (o *ManaV2ForwardingPolicyMatchConfig) SetSourcePort(v int32)`

SetSourcePort sets SourcePort field to given value.

### HasSourcePort

`func (o *ManaV2ForwardingPolicyMatchConfig) HasSourcePort() bool`

HasSourcePort returns a boolean if a field has been set.

### GetSourcePortRange

`func (o *ManaV2ForwardingPolicyMatchConfig) GetSourcePortRange() ManaV2PortRangeConfig`

GetSourcePortRange returns the SourcePortRange field if non-nil, zero value otherwise.

### GetSourcePortRangeOk

`func (o *ManaV2ForwardingPolicyMatchConfig) GetSourcePortRangeOk() (*ManaV2PortRangeConfig, bool)`

GetSourcePortRangeOk returns a tuple with the SourcePortRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePortRange

`func (o *ManaV2ForwardingPolicyMatchConfig) SetSourcePortRange(v ManaV2PortRangeConfig)`

SetSourcePortRange sets SourcePortRange field to given value.

### HasSourcePortRange

`func (o *ManaV2ForwardingPolicyMatchConfig) HasSourcePortRange() bool`

HasSourcePortRange returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



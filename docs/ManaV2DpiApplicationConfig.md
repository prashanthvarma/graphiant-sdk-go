# ManaV2DpiApplicationConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**DestinationNetwork** | Pointer to **string** |  | [optional] 
**DestinationNetworkList** | Pointer to **string** |  | [optional] 
**DestinationNetworks** | Pointer to [**ManaV2IpNetworkListConfig**](ManaV2IpNetworkListConfig.md) |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**DestinationPortList** | Pointer to **string** |  | [optional] 
**DestinationPorts** | Pointer to [**ManaV2L4PortListConfig**](ManaV2L4PortListConfig.md) |  | [optional] 
**IcmpType** | Pointer to **int32** |  | [optional] 
**IpProtocol** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**SourceNetwork** | Pointer to **string** |  | [optional] 
**SourceNetworkList** | Pointer to **string** |  | [optional] 
**SourceNetworks** | Pointer to [**ManaV2IpNetworkListConfig**](ManaV2IpNetworkListConfig.md) |  | [optional] 
**SourcePort** | Pointer to **int32** |  | [optional] 
**SourcePortList** | Pointer to **string** |  | [optional] 
**SourcePorts** | Pointer to [**ManaV2L4PortListConfig**](ManaV2L4PortListConfig.md) |  | [optional] 

## Methods

### NewManaV2DpiApplicationConfig

`func NewManaV2DpiApplicationConfig() *ManaV2DpiApplicationConfig`

NewManaV2DpiApplicationConfig instantiates a new ManaV2DpiApplicationConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DpiApplicationConfigWithDefaults

`func NewManaV2DpiApplicationConfigWithDefaults() *ManaV2DpiApplicationConfig`

NewManaV2DpiApplicationConfigWithDefaults instantiates a new ManaV2DpiApplicationConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2DpiApplicationConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2DpiApplicationConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2DpiApplicationConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2DpiApplicationConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDestinationNetwork

`func (o *ManaV2DpiApplicationConfig) GetDestinationNetwork() string`

GetDestinationNetwork returns the DestinationNetwork field if non-nil, zero value otherwise.

### GetDestinationNetworkOk

`func (o *ManaV2DpiApplicationConfig) GetDestinationNetworkOk() (*string, bool)`

GetDestinationNetworkOk returns a tuple with the DestinationNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationNetwork

`func (o *ManaV2DpiApplicationConfig) SetDestinationNetwork(v string)`

SetDestinationNetwork sets DestinationNetwork field to given value.

### HasDestinationNetwork

`func (o *ManaV2DpiApplicationConfig) HasDestinationNetwork() bool`

HasDestinationNetwork returns a boolean if a field has been set.

### GetDestinationNetworkList

`func (o *ManaV2DpiApplicationConfig) GetDestinationNetworkList() string`

GetDestinationNetworkList returns the DestinationNetworkList field if non-nil, zero value otherwise.

### GetDestinationNetworkListOk

`func (o *ManaV2DpiApplicationConfig) GetDestinationNetworkListOk() (*string, bool)`

GetDestinationNetworkListOk returns a tuple with the DestinationNetworkList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationNetworkList

`func (o *ManaV2DpiApplicationConfig) SetDestinationNetworkList(v string)`

SetDestinationNetworkList sets DestinationNetworkList field to given value.

### HasDestinationNetworkList

`func (o *ManaV2DpiApplicationConfig) HasDestinationNetworkList() bool`

HasDestinationNetworkList returns a boolean if a field has been set.

### GetDestinationNetworks

`func (o *ManaV2DpiApplicationConfig) GetDestinationNetworks() ManaV2IpNetworkListConfig`

GetDestinationNetworks returns the DestinationNetworks field if non-nil, zero value otherwise.

### GetDestinationNetworksOk

`func (o *ManaV2DpiApplicationConfig) GetDestinationNetworksOk() (*ManaV2IpNetworkListConfig, bool)`

GetDestinationNetworksOk returns a tuple with the DestinationNetworks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationNetworks

`func (o *ManaV2DpiApplicationConfig) SetDestinationNetworks(v ManaV2IpNetworkListConfig)`

SetDestinationNetworks sets DestinationNetworks field to given value.

### HasDestinationNetworks

`func (o *ManaV2DpiApplicationConfig) HasDestinationNetworks() bool`

HasDestinationNetworks returns a boolean if a field has been set.

### GetDestinationPort

`func (o *ManaV2DpiApplicationConfig) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *ManaV2DpiApplicationConfig) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *ManaV2DpiApplicationConfig) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *ManaV2DpiApplicationConfig) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetDestinationPortList

`func (o *ManaV2DpiApplicationConfig) GetDestinationPortList() string`

GetDestinationPortList returns the DestinationPortList field if non-nil, zero value otherwise.

### GetDestinationPortListOk

`func (o *ManaV2DpiApplicationConfig) GetDestinationPortListOk() (*string, bool)`

GetDestinationPortListOk returns a tuple with the DestinationPortList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPortList

`func (o *ManaV2DpiApplicationConfig) SetDestinationPortList(v string)`

SetDestinationPortList sets DestinationPortList field to given value.

### HasDestinationPortList

`func (o *ManaV2DpiApplicationConfig) HasDestinationPortList() bool`

HasDestinationPortList returns a boolean if a field has been set.

### GetDestinationPorts

`func (o *ManaV2DpiApplicationConfig) GetDestinationPorts() ManaV2L4PortListConfig`

GetDestinationPorts returns the DestinationPorts field if non-nil, zero value otherwise.

### GetDestinationPortsOk

`func (o *ManaV2DpiApplicationConfig) GetDestinationPortsOk() (*ManaV2L4PortListConfig, bool)`

GetDestinationPortsOk returns a tuple with the DestinationPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPorts

`func (o *ManaV2DpiApplicationConfig) SetDestinationPorts(v ManaV2L4PortListConfig)`

SetDestinationPorts sets DestinationPorts field to given value.

### HasDestinationPorts

`func (o *ManaV2DpiApplicationConfig) HasDestinationPorts() bool`

HasDestinationPorts returns a boolean if a field has been set.

### GetIcmpType

`func (o *ManaV2DpiApplicationConfig) GetIcmpType() int32`

GetIcmpType returns the IcmpType field if non-nil, zero value otherwise.

### GetIcmpTypeOk

`func (o *ManaV2DpiApplicationConfig) GetIcmpTypeOk() (*int32, bool)`

GetIcmpTypeOk returns a tuple with the IcmpType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcmpType

`func (o *ManaV2DpiApplicationConfig) SetIcmpType(v int32)`

SetIcmpType sets IcmpType field to given value.

### HasIcmpType

`func (o *ManaV2DpiApplicationConfig) HasIcmpType() bool`

HasIcmpType returns a boolean if a field has been set.

### GetIpProtocol

`func (o *ManaV2DpiApplicationConfig) GetIpProtocol() string`

GetIpProtocol returns the IpProtocol field if non-nil, zero value otherwise.

### GetIpProtocolOk

`func (o *ManaV2DpiApplicationConfig) GetIpProtocolOk() (*string, bool)`

GetIpProtocolOk returns a tuple with the IpProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpProtocol

`func (o *ManaV2DpiApplicationConfig) SetIpProtocol(v string)`

SetIpProtocol sets IpProtocol field to given value.

### HasIpProtocol

`func (o *ManaV2DpiApplicationConfig) HasIpProtocol() bool`

HasIpProtocol returns a boolean if a field has been set.

### GetName

`func (o *ManaV2DpiApplicationConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2DpiApplicationConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2DpiApplicationConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2DpiApplicationConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSourceNetwork

`func (o *ManaV2DpiApplicationConfig) GetSourceNetwork() string`

GetSourceNetwork returns the SourceNetwork field if non-nil, zero value otherwise.

### GetSourceNetworkOk

`func (o *ManaV2DpiApplicationConfig) GetSourceNetworkOk() (*string, bool)`

GetSourceNetworkOk returns a tuple with the SourceNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNetwork

`func (o *ManaV2DpiApplicationConfig) SetSourceNetwork(v string)`

SetSourceNetwork sets SourceNetwork field to given value.

### HasSourceNetwork

`func (o *ManaV2DpiApplicationConfig) HasSourceNetwork() bool`

HasSourceNetwork returns a boolean if a field has been set.

### GetSourceNetworkList

`func (o *ManaV2DpiApplicationConfig) GetSourceNetworkList() string`

GetSourceNetworkList returns the SourceNetworkList field if non-nil, zero value otherwise.

### GetSourceNetworkListOk

`func (o *ManaV2DpiApplicationConfig) GetSourceNetworkListOk() (*string, bool)`

GetSourceNetworkListOk returns a tuple with the SourceNetworkList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNetworkList

`func (o *ManaV2DpiApplicationConfig) SetSourceNetworkList(v string)`

SetSourceNetworkList sets SourceNetworkList field to given value.

### HasSourceNetworkList

`func (o *ManaV2DpiApplicationConfig) HasSourceNetworkList() bool`

HasSourceNetworkList returns a boolean if a field has been set.

### GetSourceNetworks

`func (o *ManaV2DpiApplicationConfig) GetSourceNetworks() ManaV2IpNetworkListConfig`

GetSourceNetworks returns the SourceNetworks field if non-nil, zero value otherwise.

### GetSourceNetworksOk

`func (o *ManaV2DpiApplicationConfig) GetSourceNetworksOk() (*ManaV2IpNetworkListConfig, bool)`

GetSourceNetworksOk returns a tuple with the SourceNetworks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNetworks

`func (o *ManaV2DpiApplicationConfig) SetSourceNetworks(v ManaV2IpNetworkListConfig)`

SetSourceNetworks sets SourceNetworks field to given value.

### HasSourceNetworks

`func (o *ManaV2DpiApplicationConfig) HasSourceNetworks() bool`

HasSourceNetworks returns a boolean if a field has been set.

### GetSourcePort

`func (o *ManaV2DpiApplicationConfig) GetSourcePort() int32`

GetSourcePort returns the SourcePort field if non-nil, zero value otherwise.

### GetSourcePortOk

`func (o *ManaV2DpiApplicationConfig) GetSourcePortOk() (*int32, bool)`

GetSourcePortOk returns a tuple with the SourcePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePort

`func (o *ManaV2DpiApplicationConfig) SetSourcePort(v int32)`

SetSourcePort sets SourcePort field to given value.

### HasSourcePort

`func (o *ManaV2DpiApplicationConfig) HasSourcePort() bool`

HasSourcePort returns a boolean if a field has been set.

### GetSourcePortList

`func (o *ManaV2DpiApplicationConfig) GetSourcePortList() string`

GetSourcePortList returns the SourcePortList field if non-nil, zero value otherwise.

### GetSourcePortListOk

`func (o *ManaV2DpiApplicationConfig) GetSourcePortListOk() (*string, bool)`

GetSourcePortListOk returns a tuple with the SourcePortList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePortList

`func (o *ManaV2DpiApplicationConfig) SetSourcePortList(v string)`

SetSourcePortList sets SourcePortList field to given value.

### HasSourcePortList

`func (o *ManaV2DpiApplicationConfig) HasSourcePortList() bool`

HasSourcePortList returns a boolean if a field has been set.

### GetSourcePorts

`func (o *ManaV2DpiApplicationConfig) GetSourcePorts() ManaV2L4PortListConfig`

GetSourcePorts returns the SourcePorts field if non-nil, zero value otherwise.

### GetSourcePortsOk

`func (o *ManaV2DpiApplicationConfig) GetSourcePortsOk() (*ManaV2L4PortListConfig, bool)`

GetSourcePortsOk returns a tuple with the SourcePorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePorts

`func (o *ManaV2DpiApplicationConfig) SetSourcePorts(v ManaV2L4PortListConfig)`

SetSourcePorts sets SourcePorts field to given value.

### HasSourcePorts

`func (o *ManaV2DpiApplicationConfig) HasSourcePorts() bool`

HasSourcePorts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



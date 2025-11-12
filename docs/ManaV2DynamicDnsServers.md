# ManaV2DynamicDnsServers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuit** | Pointer to **string** |  | [optional] 
**Servers** | Pointer to [**map[string]ManaV2DnsipAddresses**](ManaV2DnsipAddresses.md) |  | [optional] 

## Methods

### NewManaV2DynamicDnsServers

`func NewManaV2DynamicDnsServers() *ManaV2DynamicDnsServers`

NewManaV2DynamicDnsServers instantiates a new ManaV2DynamicDnsServers object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2DynamicDnsServersWithDefaults

`func NewManaV2DynamicDnsServersWithDefaults() *ManaV2DynamicDnsServers`

NewManaV2DynamicDnsServersWithDefaults instantiates a new ManaV2DynamicDnsServers object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuit

`func (o *ManaV2DynamicDnsServers) GetCircuit() string`

GetCircuit returns the Circuit field if non-nil, zero value otherwise.

### GetCircuitOk

`func (o *ManaV2DynamicDnsServers) GetCircuitOk() (*string, bool)`

GetCircuitOk returns a tuple with the Circuit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuit

`func (o *ManaV2DynamicDnsServers) SetCircuit(v string)`

SetCircuit sets Circuit field to given value.

### HasCircuit

`func (o *ManaV2DynamicDnsServers) HasCircuit() bool`

HasCircuit returns a boolean if a field has been set.

### GetServers

`func (o *ManaV2DynamicDnsServers) GetServers() map[string]ManaV2DnsipAddresses`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *ManaV2DynamicDnsServers) GetServersOk() (*map[string]ManaV2DnsipAddresses, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *ManaV2DynamicDnsServers) SetServers(v map[string]ManaV2DnsipAddresses)`

SetServers sets Servers field to given value.

### HasServers

`func (o *ManaV2DynamicDnsServers) HasServers() bool`

HasServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



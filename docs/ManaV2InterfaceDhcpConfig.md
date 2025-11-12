# ManaV2InterfaceDhcpConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DhcpClient** | Pointer to **bool** |  | [optional] 
**DhcpRelay** | Pointer to [**ManaV2DhcpRelayConfig**](ManaV2DhcpRelayConfig.md) |  | [optional] 

## Methods

### NewManaV2InterfaceDhcpConfig

`func NewManaV2InterfaceDhcpConfig() *ManaV2InterfaceDhcpConfig`

NewManaV2InterfaceDhcpConfig instantiates a new ManaV2InterfaceDhcpConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2InterfaceDhcpConfigWithDefaults

`func NewManaV2InterfaceDhcpConfigWithDefaults() *ManaV2InterfaceDhcpConfig`

NewManaV2InterfaceDhcpConfigWithDefaults instantiates a new ManaV2InterfaceDhcpConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDhcpClient

`func (o *ManaV2InterfaceDhcpConfig) GetDhcpClient() bool`

GetDhcpClient returns the DhcpClient field if non-nil, zero value otherwise.

### GetDhcpClientOk

`func (o *ManaV2InterfaceDhcpConfig) GetDhcpClientOk() (*bool, bool)`

GetDhcpClientOk returns a tuple with the DhcpClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpClient

`func (o *ManaV2InterfaceDhcpConfig) SetDhcpClient(v bool)`

SetDhcpClient sets DhcpClient field to given value.

### HasDhcpClient

`func (o *ManaV2InterfaceDhcpConfig) HasDhcpClient() bool`

HasDhcpClient returns a boolean if a field has been set.

### GetDhcpRelay

`func (o *ManaV2InterfaceDhcpConfig) GetDhcpRelay() ManaV2DhcpRelayConfig`

GetDhcpRelay returns the DhcpRelay field if non-nil, zero value otherwise.

### GetDhcpRelayOk

`func (o *ManaV2InterfaceDhcpConfig) GetDhcpRelayOk() (*ManaV2DhcpRelayConfig, bool)`

GetDhcpRelayOk returns a tuple with the DhcpRelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpRelay

`func (o *ManaV2InterfaceDhcpConfig) SetDhcpRelay(v ManaV2DhcpRelayConfig)`

SetDhcpRelay sets DhcpRelay field to given value.

### HasDhcpRelay

`func (o *ManaV2InterfaceDhcpConfig) HasDhcpRelay() bool`

HasDhcpRelay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2InterfaceAddress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** |  | [optional] 
**DhcpClient** | Pointer to **bool** |  | [optional] 
**DhcpRelay** | Pointer to [**ManaV2DhcpRelay**](ManaV2DhcpRelay.md) |  | [optional] 
**DhcpServer** | Pointer to **bool** |  | [optional] 
**Origin** | Pointer to **string** |  | [optional] 
**VrrpGroup** | Pointer to [**ManaV2VrrpGroup**](ManaV2VrrpGroup.md) |  | [optional] 

## Methods

### NewManaV2InterfaceAddress

`func NewManaV2InterfaceAddress() *ManaV2InterfaceAddress`

NewManaV2InterfaceAddress instantiates a new ManaV2InterfaceAddress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2InterfaceAddressWithDefaults

`func NewManaV2InterfaceAddressWithDefaults() *ManaV2InterfaceAddress`

NewManaV2InterfaceAddressWithDefaults instantiates a new ManaV2InterfaceAddress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ManaV2InterfaceAddress) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ManaV2InterfaceAddress) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ManaV2InterfaceAddress) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ManaV2InterfaceAddress) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetDhcpClient

`func (o *ManaV2InterfaceAddress) GetDhcpClient() bool`

GetDhcpClient returns the DhcpClient field if non-nil, zero value otherwise.

### GetDhcpClientOk

`func (o *ManaV2InterfaceAddress) GetDhcpClientOk() (*bool, bool)`

GetDhcpClientOk returns a tuple with the DhcpClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpClient

`func (o *ManaV2InterfaceAddress) SetDhcpClient(v bool)`

SetDhcpClient sets DhcpClient field to given value.

### HasDhcpClient

`func (o *ManaV2InterfaceAddress) HasDhcpClient() bool`

HasDhcpClient returns a boolean if a field has been set.

### GetDhcpRelay

`func (o *ManaV2InterfaceAddress) GetDhcpRelay() ManaV2DhcpRelay`

GetDhcpRelay returns the DhcpRelay field if non-nil, zero value otherwise.

### GetDhcpRelayOk

`func (o *ManaV2InterfaceAddress) GetDhcpRelayOk() (*ManaV2DhcpRelay, bool)`

GetDhcpRelayOk returns a tuple with the DhcpRelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpRelay

`func (o *ManaV2InterfaceAddress) SetDhcpRelay(v ManaV2DhcpRelay)`

SetDhcpRelay sets DhcpRelay field to given value.

### HasDhcpRelay

`func (o *ManaV2InterfaceAddress) HasDhcpRelay() bool`

HasDhcpRelay returns a boolean if a field has been set.

### GetDhcpServer

`func (o *ManaV2InterfaceAddress) GetDhcpServer() bool`

GetDhcpServer returns the DhcpServer field if non-nil, zero value otherwise.

### GetDhcpServerOk

`func (o *ManaV2InterfaceAddress) GetDhcpServerOk() (*bool, bool)`

GetDhcpServerOk returns a tuple with the DhcpServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpServer

`func (o *ManaV2InterfaceAddress) SetDhcpServer(v bool)`

SetDhcpServer sets DhcpServer field to given value.

### HasDhcpServer

`func (o *ManaV2InterfaceAddress) HasDhcpServer() bool`

HasDhcpServer returns a boolean if a field has been set.

### GetOrigin

`func (o *ManaV2InterfaceAddress) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *ManaV2InterfaceAddress) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *ManaV2InterfaceAddress) SetOrigin(v string)`

SetOrigin sets Origin field to given value.

### HasOrigin

`func (o *ManaV2InterfaceAddress) HasOrigin() bool`

HasOrigin returns a boolean if a field has been set.

### GetVrrpGroup

`func (o *ManaV2InterfaceAddress) GetVrrpGroup() ManaV2VrrpGroup`

GetVrrpGroup returns the VrrpGroup field if non-nil, zero value otherwise.

### GetVrrpGroupOk

`func (o *ManaV2InterfaceAddress) GetVrrpGroupOk() (*ManaV2VrrpGroup, bool)`

GetVrrpGroupOk returns a tuple with the VrrpGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrrpGroup

`func (o *ManaV2InterfaceAddress) SetVrrpGroup(v ManaV2VrrpGroup)`

SetVrrpGroup sets VrrpGroup field to given value.

### HasVrrpGroup

`func (o *ManaV2InterfaceAddress) HasVrrpGroup() bool`

HasVrrpGroup returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



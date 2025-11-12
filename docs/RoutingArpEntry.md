# RoutingArpEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InterfaceName** | Pointer to **string** |  | [optional] 
**Ipv4Address** | Pointer to **string** |  | [optional] 
**MacAddress** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** | Circuit or VRF name | [optional] 

## Methods

### NewRoutingArpEntry

`func NewRoutingArpEntry() *RoutingArpEntry`

NewRoutingArpEntry instantiates a new RoutingArpEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingArpEntryWithDefaults

`func NewRoutingArpEntryWithDefaults() *RoutingArpEntry`

NewRoutingArpEntryWithDefaults instantiates a new RoutingArpEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaceName

`func (o *RoutingArpEntry) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *RoutingArpEntry) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *RoutingArpEntry) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *RoutingArpEntry) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.

### GetIpv4Address

`func (o *RoutingArpEntry) GetIpv4Address() string`

GetIpv4Address returns the Ipv4Address field if non-nil, zero value otherwise.

### GetIpv4AddressOk

`func (o *RoutingArpEntry) GetIpv4AddressOk() (*string, bool)`

GetIpv4AddressOk returns a tuple with the Ipv4Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4Address

`func (o *RoutingArpEntry) SetIpv4Address(v string)`

SetIpv4Address sets Ipv4Address field to given value.

### HasIpv4Address

`func (o *RoutingArpEntry) HasIpv4Address() bool`

HasIpv4Address returns a boolean if a field has been set.

### GetMacAddress

`func (o *RoutingArpEntry) GetMacAddress() string`

GetMacAddress returns the MacAddress field if non-nil, zero value otherwise.

### GetMacAddressOk

`func (o *RoutingArpEntry) GetMacAddressOk() (*string, bool)`

GetMacAddressOk returns a tuple with the MacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMacAddress

`func (o *RoutingArpEntry) SetMacAddress(v string)`

SetMacAddress sets MacAddress field to given value.

### HasMacAddress

`func (o *RoutingArpEntry) HasMacAddress() bool`

HasMacAddress returns a boolean if a field has been set.

### GetName

`func (o *RoutingArpEntry) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoutingArpEntry) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoutingArpEntry) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RoutingArpEntry) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# RoutingNdEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InterfaceName** | Pointer to **string** |  | [optional] 
**Ipv6Address** | Pointer to **string** |  | [optional] 
**MacAddress** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** | Circuit or VRF name | [optional] 

## Methods

### NewRoutingNdEntry

`func NewRoutingNdEntry() *RoutingNdEntry`

NewRoutingNdEntry instantiates a new RoutingNdEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingNdEntryWithDefaults

`func NewRoutingNdEntryWithDefaults() *RoutingNdEntry`

NewRoutingNdEntryWithDefaults instantiates a new RoutingNdEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaceName

`func (o *RoutingNdEntry) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *RoutingNdEntry) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *RoutingNdEntry) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *RoutingNdEntry) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.

### GetIpv6Address

`func (o *RoutingNdEntry) GetIpv6Address() string`

GetIpv6Address returns the Ipv6Address field if non-nil, zero value otherwise.

### GetIpv6AddressOk

`func (o *RoutingNdEntry) GetIpv6AddressOk() (*string, bool)`

GetIpv6AddressOk returns a tuple with the Ipv6Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6Address

`func (o *RoutingNdEntry) SetIpv6Address(v string)`

SetIpv6Address sets Ipv6Address field to given value.

### HasIpv6Address

`func (o *RoutingNdEntry) HasIpv6Address() bool`

HasIpv6Address returns a boolean if a field has been set.

### GetMacAddress

`func (o *RoutingNdEntry) GetMacAddress() string`

GetMacAddress returns the MacAddress field if non-nil, zero value otherwise.

### GetMacAddressOk

`func (o *RoutingNdEntry) GetMacAddressOk() (*string, bool)`

GetMacAddressOk returns a tuple with the MacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMacAddress

`func (o *RoutingNdEntry) SetMacAddress(v string)`

SetMacAddress sets MacAddress field to given value.

### HasMacAddress

`func (o *RoutingNdEntry) HasMacAddress() bool`

HasMacAddress returns a boolean if a field has been set.

### GetName

`func (o *RoutingNdEntry) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoutingNdEntry) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoutingNdEntry) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RoutingNdEntry) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



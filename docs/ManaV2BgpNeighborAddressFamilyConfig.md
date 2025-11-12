# ManaV2BgpNeighborAddressFamilyConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamily** | Pointer to **string** |  | [optional] 
**InboundPolicy** | Pointer to [**ManaV2NullablePolicyName**](ManaV2NullablePolicyName.md) |  | [optional] 
**OutboundPolicy** | Pointer to [**ManaV2NullablePolicyName**](ManaV2NullablePolicyName.md) |  | [optional] 

## Methods

### NewManaV2BgpNeighborAddressFamilyConfig

`func NewManaV2BgpNeighborAddressFamilyConfig() *ManaV2BgpNeighborAddressFamilyConfig`

NewManaV2BgpNeighborAddressFamilyConfig instantiates a new ManaV2BgpNeighborAddressFamilyConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BgpNeighborAddressFamilyConfigWithDefaults

`func NewManaV2BgpNeighborAddressFamilyConfigWithDefaults() *ManaV2BgpNeighborAddressFamilyConfig`

NewManaV2BgpNeighborAddressFamilyConfigWithDefaults instantiates a new ManaV2BgpNeighborAddressFamilyConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamily

`func (o *ManaV2BgpNeighborAddressFamilyConfig) GetAddressFamily() string`

GetAddressFamily returns the AddressFamily field if non-nil, zero value otherwise.

### GetAddressFamilyOk

`func (o *ManaV2BgpNeighborAddressFamilyConfig) GetAddressFamilyOk() (*string, bool)`

GetAddressFamilyOk returns a tuple with the AddressFamily field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamily

`func (o *ManaV2BgpNeighborAddressFamilyConfig) SetAddressFamily(v string)`

SetAddressFamily sets AddressFamily field to given value.

### HasAddressFamily

`func (o *ManaV2BgpNeighborAddressFamilyConfig) HasAddressFamily() bool`

HasAddressFamily returns a boolean if a field has been set.

### GetInboundPolicy

`func (o *ManaV2BgpNeighborAddressFamilyConfig) GetInboundPolicy() ManaV2NullablePolicyName`

GetInboundPolicy returns the InboundPolicy field if non-nil, zero value otherwise.

### GetInboundPolicyOk

`func (o *ManaV2BgpNeighborAddressFamilyConfig) GetInboundPolicyOk() (*ManaV2NullablePolicyName, bool)`

GetInboundPolicyOk returns a tuple with the InboundPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundPolicy

`func (o *ManaV2BgpNeighborAddressFamilyConfig) SetInboundPolicy(v ManaV2NullablePolicyName)`

SetInboundPolicy sets InboundPolicy field to given value.

### HasInboundPolicy

`func (o *ManaV2BgpNeighborAddressFamilyConfig) HasInboundPolicy() bool`

HasInboundPolicy returns a boolean if a field has been set.

### GetOutboundPolicy

`func (o *ManaV2BgpNeighborAddressFamilyConfig) GetOutboundPolicy() ManaV2NullablePolicyName`

GetOutboundPolicy returns the OutboundPolicy field if non-nil, zero value otherwise.

### GetOutboundPolicyOk

`func (o *ManaV2BgpNeighborAddressFamilyConfig) GetOutboundPolicyOk() (*ManaV2NullablePolicyName, bool)`

GetOutboundPolicyOk returns a tuple with the OutboundPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundPolicy

`func (o *ManaV2BgpNeighborAddressFamilyConfig) SetOutboundPolicy(v ManaV2NullablePolicyName)`

SetOutboundPolicy sets OutboundPolicy field to given value.

### HasOutboundPolicy

`func (o *ManaV2BgpNeighborAddressFamilyConfig) HasOutboundPolicy() bool`

HasOutboundPolicy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



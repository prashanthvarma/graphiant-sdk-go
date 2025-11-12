# V1GatewaysGuestConsumerMatchIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationPrefixes** | Pointer to **[]string** |  | [optional] 
**IpsecTunnelConfig** | Pointer to [**[]V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig**](V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig.md) |  | [optional] 
**SiteToSiteVpn** | Pointer to [**ManaV2GuestConsumerSiteToSiteVpnConfig**](ManaV2GuestConsumerSiteToSiteVpnConfig.md) |  | [optional] 

## Methods

### NewV1GatewaysGuestConsumerMatchIdGetResponse

`func NewV1GatewaysGuestConsumerMatchIdGetResponse() *V1GatewaysGuestConsumerMatchIdGetResponse`

NewV1GatewaysGuestConsumerMatchIdGetResponse instantiates a new V1GatewaysGuestConsumerMatchIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GatewaysGuestConsumerMatchIdGetResponseWithDefaults

`func NewV1GatewaysGuestConsumerMatchIdGetResponseWithDefaults() *V1GatewaysGuestConsumerMatchIdGetResponse`

NewV1GatewaysGuestConsumerMatchIdGetResponseWithDefaults instantiates a new V1GatewaysGuestConsumerMatchIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationPrefixes

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) GetDestinationPrefixes() []string`

GetDestinationPrefixes returns the DestinationPrefixes field if non-nil, zero value otherwise.

### GetDestinationPrefixesOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) GetDestinationPrefixesOk() (*[]string, bool)`

GetDestinationPrefixesOk returns a tuple with the DestinationPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPrefixes

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) SetDestinationPrefixes(v []string)`

SetDestinationPrefixes sets DestinationPrefixes field to given value.

### HasDestinationPrefixes

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) HasDestinationPrefixes() bool`

HasDestinationPrefixes returns a boolean if a field has been set.

### GetIpsecTunnelConfig

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) GetIpsecTunnelConfig() []V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig`

GetIpsecTunnelConfig returns the IpsecTunnelConfig field if non-nil, zero value otherwise.

### GetIpsecTunnelConfigOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) GetIpsecTunnelConfigOk() (*[]V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig, bool)`

GetIpsecTunnelConfigOk returns a tuple with the IpsecTunnelConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecTunnelConfig

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) SetIpsecTunnelConfig(v []V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig)`

SetIpsecTunnelConfig sets IpsecTunnelConfig field to given value.

### HasIpsecTunnelConfig

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) HasIpsecTunnelConfig() bool`

HasIpsecTunnelConfig returns a boolean if a field has been set.

### GetSiteToSiteVpn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) GetSiteToSiteVpn() ManaV2GuestConsumerSiteToSiteVpnConfig`

GetSiteToSiteVpn returns the SiteToSiteVpn field if non-nil, zero value otherwise.

### GetSiteToSiteVpnOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) GetSiteToSiteVpnOk() (*ManaV2GuestConsumerSiteToSiteVpnConfig, bool)`

GetSiteToSiteVpnOk returns a tuple with the SiteToSiteVpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteToSiteVpn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) SetSiteToSiteVpn(v ManaV2GuestConsumerSiteToSiteVpnConfig)`

SetSiteToSiteVpn sets SiteToSiteVpn field to given value.

### HasSiteToSiteVpn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponse) HasSiteToSiteVpn() bool`

HasSiteToSiteVpn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | Pointer to **int64** |  | [optional] 
**ConsumerName** | Pointer to **string** |  | [optional] 
**Emails** | Pointer to **[]string** |  | [optional] 
**GlobalObjectDeviceSummaries** | Pointer to [**map[string]ManaV2GlobalObjectServiceSummaries**](ManaV2GlobalObjectServiceSummaries.md) |  | [optional] 
**GlobalObjectSummaries** | Pointer to [**map[string]ManaV2GlobalObjectServiceSummaries**](ManaV2GlobalObjectServiceSummaries.md) |  | [optional] 
**IpsecTunnelConfig** | Pointer to [**[]V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig.md) |  | [optional] 
**MatchDetails** | Pointer to [**ManaV2B2bExtranetServiceCustomerMatchDetails**](ManaV2B2bExtranetServiceCustomerMatchDetails.md) |  | [optional] 
**PeerType** | Pointer to **string** |  | [optional] 
**Policy** | Pointer to [**[]ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy**](ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy.md) |  | [optional] 
**SiteInformation** | Pointer to [**[]ManaV2B2bSiteInformation**](ManaV2B2bSiteInformation.md) |  | [optional] 
**SiteToSiteVpn** | Pointer to [**ManaV2GuestConsumerSiteToSiteVpnConfig**](ManaV2GuestConsumerSiteToSiteVpnConfig.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse

`func NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse() *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse`

NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse instantiates a new V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseWithDefaults

`func NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseWithDefaults() *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse`

NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseWithDefaults instantiates a new V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetConsumerId() int64`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetConsumerIdOk() (*int64, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetConsumerId(v int64)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### GetConsumerName

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetConsumerName() string`

GetConsumerName returns the ConsumerName field if non-nil, zero value otherwise.

### GetConsumerNameOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetConsumerNameOk() (*string, bool)`

GetConsumerNameOk returns a tuple with the ConsumerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerName

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetConsumerName(v string)`

SetConsumerName sets ConsumerName field to given value.

### HasConsumerName

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasConsumerName() bool`

HasConsumerName returns a boolean if a field has been set.

### GetEmails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasEmails() bool`

HasEmails returns a boolean if a field has been set.

### GetGlobalObjectDeviceSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetGlobalObjectDeviceSummaries() map[string]ManaV2GlobalObjectServiceSummaries`

GetGlobalObjectDeviceSummaries returns the GlobalObjectDeviceSummaries field if non-nil, zero value otherwise.

### GetGlobalObjectDeviceSummariesOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetGlobalObjectDeviceSummariesOk() (*map[string]ManaV2GlobalObjectServiceSummaries, bool)`

GetGlobalObjectDeviceSummariesOk returns a tuple with the GlobalObjectDeviceSummaries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalObjectDeviceSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetGlobalObjectDeviceSummaries(v map[string]ManaV2GlobalObjectServiceSummaries)`

SetGlobalObjectDeviceSummaries sets GlobalObjectDeviceSummaries field to given value.

### HasGlobalObjectDeviceSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasGlobalObjectDeviceSummaries() bool`

HasGlobalObjectDeviceSummaries returns a boolean if a field has been set.

### GetGlobalObjectSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetGlobalObjectSummaries() map[string]ManaV2GlobalObjectServiceSummaries`

GetGlobalObjectSummaries returns the GlobalObjectSummaries field if non-nil, zero value otherwise.

### GetGlobalObjectSummariesOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetGlobalObjectSummariesOk() (*map[string]ManaV2GlobalObjectServiceSummaries, bool)`

GetGlobalObjectSummariesOk returns a tuple with the GlobalObjectSummaries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalObjectSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetGlobalObjectSummaries(v map[string]ManaV2GlobalObjectServiceSummaries)`

SetGlobalObjectSummaries sets GlobalObjectSummaries field to given value.

### HasGlobalObjectSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasGlobalObjectSummaries() bool`

HasGlobalObjectSummaries returns a boolean if a field has been set.

### GetIpsecTunnelConfig

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetIpsecTunnelConfig() []V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig`

GetIpsecTunnelConfig returns the IpsecTunnelConfig field if non-nil, zero value otherwise.

### GetIpsecTunnelConfigOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetIpsecTunnelConfigOk() (*[]V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig, bool)`

GetIpsecTunnelConfigOk returns a tuple with the IpsecTunnelConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecTunnelConfig

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetIpsecTunnelConfig(v []V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponseIpsecVpnTunnelConfig)`

SetIpsecTunnelConfig sets IpsecTunnelConfig field to given value.

### HasIpsecTunnelConfig

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasIpsecTunnelConfig() bool`

HasIpsecTunnelConfig returns a boolean if a field has been set.

### GetMatchDetails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetMatchDetails() ManaV2B2bExtranetServiceCustomerMatchDetails`

GetMatchDetails returns the MatchDetails field if non-nil, zero value otherwise.

### GetMatchDetailsOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetMatchDetailsOk() (*ManaV2B2bExtranetServiceCustomerMatchDetails, bool)`

GetMatchDetailsOk returns a tuple with the MatchDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchDetails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetMatchDetails(v ManaV2B2bExtranetServiceCustomerMatchDetails)`

SetMatchDetails sets MatchDetails field to given value.

### HasMatchDetails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasMatchDetails() bool`

HasMatchDetails returns a boolean if a field has been set.

### GetPeerType

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetPeerType() string`

GetPeerType returns the PeerType field if non-nil, zero value otherwise.

### GetPeerTypeOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetPeerTypeOk() (*string, bool)`

GetPeerTypeOk returns a tuple with the PeerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerType

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetPeerType(v string)`

SetPeerType sets PeerType field to given value.

### HasPeerType

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasPeerType() bool`

HasPeerType returns a boolean if a field has been set.

### GetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetPolicy() []ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetPolicyOk() (*[]ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetPolicy(v []ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### GetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetSiteInformation() []ManaV2B2bSiteInformation`

GetSiteInformation returns the SiteInformation field if non-nil, zero value otherwise.

### GetSiteInformationOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetSiteInformationOk() (*[]ManaV2B2bSiteInformation, bool)`

GetSiteInformationOk returns a tuple with the SiteInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetSiteInformation(v []ManaV2B2bSiteInformation)`

SetSiteInformation sets SiteInformation field to given value.

### HasSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasSiteInformation() bool`

HasSiteInformation returns a boolean if a field has been set.

### GetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetSiteToSiteVpn() ManaV2GuestConsumerSiteToSiteVpnConfig`

GetSiteToSiteVpn returns the SiteToSiteVpn field if non-nil, zero value otherwise.

### GetSiteToSiteVpnOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetSiteToSiteVpnOk() (*ManaV2GuestConsumerSiteToSiteVpnConfig, bool)`

GetSiteToSiteVpnOk returns a tuple with the SiteToSiteVpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetSiteToSiteVpn(v ManaV2GuestConsumerSiteToSiteVpnConfig)`

SetSiteToSiteVpn sets SiteToSiteVpn field to given value.

### HasSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasSiteToSiteVpn() bool`

HasSiteToSiteVpn returns a boolean if a field has been set.

### GetStatus

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGetResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



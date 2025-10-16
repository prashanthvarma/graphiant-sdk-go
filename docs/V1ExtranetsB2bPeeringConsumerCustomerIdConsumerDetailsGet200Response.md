# V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | Pointer to **int64** |  | [optional] 
**ConsumerName** | Pointer to **string** |  | [optional] 
**Emails** | Pointer to **[]string** |  | [optional] 
**GlobalObjectDeviceSummaries** | Pointer to [**map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue**](V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue.md) |  | [optional] 
**GlobalObjectSummaries** | Pointer to [**map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue**](V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue.md) |  | [optional] 
**IpsecTunnelConfig** | Pointer to [**[]V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner.md) |  | [optional] 
**MatchDetails** | Pointer to [**V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails.md) |  | [optional] 
**PeerType** | Pointer to **string** |  | [optional] 
**Policy** | Pointer to [**[]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner.md) |  | [optional] 
**SiteInformation** | Pointer to [**[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**SiteToSiteVpn** | Pointer to [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response

`func NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response() *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response`

NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response instantiates a new V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseWithDefaults

`func NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseWithDefaults() *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response`

NewV1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseWithDefaults instantiates a new V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetConsumerId() int64`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetConsumerIdOk() (*int64, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetConsumerId(v int64)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### GetConsumerName

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetConsumerName() string`

GetConsumerName returns the ConsumerName field if non-nil, zero value otherwise.

### GetConsumerNameOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetConsumerNameOk() (*string, bool)`

GetConsumerNameOk returns a tuple with the ConsumerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerName

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetConsumerName(v string)`

SetConsumerName sets ConsumerName field to given value.

### HasConsumerName

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasConsumerName() bool`

HasConsumerName returns a boolean if a field has been set.

### GetEmails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasEmails() bool`

HasEmails returns a boolean if a field has been set.

### GetGlobalObjectDeviceSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetGlobalObjectDeviceSummaries() map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue`

GetGlobalObjectDeviceSummaries returns the GlobalObjectDeviceSummaries field if non-nil, zero value otherwise.

### GetGlobalObjectDeviceSummariesOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetGlobalObjectDeviceSummariesOk() (*map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue, bool)`

GetGlobalObjectDeviceSummariesOk returns a tuple with the GlobalObjectDeviceSummaries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalObjectDeviceSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetGlobalObjectDeviceSummaries(v map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue)`

SetGlobalObjectDeviceSummaries sets GlobalObjectDeviceSummaries field to given value.

### HasGlobalObjectDeviceSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasGlobalObjectDeviceSummaries() bool`

HasGlobalObjectDeviceSummaries returns a boolean if a field has been set.

### GetGlobalObjectSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetGlobalObjectSummaries() map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue`

GetGlobalObjectSummaries returns the GlobalObjectSummaries field if non-nil, zero value otherwise.

### GetGlobalObjectSummariesOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetGlobalObjectSummariesOk() (*map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue, bool)`

GetGlobalObjectSummariesOk returns a tuple with the GlobalObjectSummaries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalObjectSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetGlobalObjectSummaries(v map[string]V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue)`

SetGlobalObjectSummaries sets GlobalObjectSummaries field to given value.

### HasGlobalObjectSummaries

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasGlobalObjectSummaries() bool`

HasGlobalObjectSummaries returns a boolean if a field has been set.

### GetIpsecTunnelConfig

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetIpsecTunnelConfig() []V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner`

GetIpsecTunnelConfig returns the IpsecTunnelConfig field if non-nil, zero value otherwise.

### GetIpsecTunnelConfigOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetIpsecTunnelConfigOk() (*[]V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner, bool)`

GetIpsecTunnelConfigOk returns a tuple with the IpsecTunnelConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecTunnelConfig

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetIpsecTunnelConfig(v []V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner)`

SetIpsecTunnelConfig sets IpsecTunnelConfig field to given value.

### HasIpsecTunnelConfig

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasIpsecTunnelConfig() bool`

HasIpsecTunnelConfig returns a boolean if a field has been set.

### GetMatchDetails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetMatchDetails() V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails`

GetMatchDetails returns the MatchDetails field if non-nil, zero value otherwise.

### GetMatchDetailsOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetMatchDetailsOk() (*V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails, bool)`

GetMatchDetailsOk returns a tuple with the MatchDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchDetails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetMatchDetails(v V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails)`

SetMatchDetails sets MatchDetails field to given value.

### HasMatchDetails

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasMatchDetails() bool`

HasMatchDetails returns a boolean if a field has been set.

### GetPeerType

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetPeerType() string`

GetPeerType returns the PeerType field if non-nil, zero value otherwise.

### GetPeerTypeOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetPeerTypeOk() (*string, bool)`

GetPeerTypeOk returns a tuple with the PeerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerType

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetPeerType(v string)`

SetPeerType sets PeerType field to given value.

### HasPeerType

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasPeerType() bool`

HasPeerType returns a boolean if a field has been set.

### GetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetPolicy() []V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetPolicyOk() (*[]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetPolicy(v []V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### GetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetSiteInformation() []V1ExtranetsB2bConsumerPostRequestSiteInformationInner`

GetSiteInformation returns the SiteInformation field if non-nil, zero value otherwise.

### GetSiteInformationOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetSiteInformationOk() (*[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner, bool)`

GetSiteInformationOk returns a tuple with the SiteInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetSiteInformation(v []V1ExtranetsB2bConsumerPostRequestSiteInformationInner)`

SetSiteInformation sets SiteInformation field to given value.

### HasSiteInformation

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasSiteInformation() bool`

HasSiteInformation returns a boolean if a field has been set.

### GetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetSiteToSiteVpn() V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn`

GetSiteToSiteVpn returns the SiteToSiteVpn field if non-nil, zero value otherwise.

### GetSiteToSiteVpnOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetSiteToSiteVpnOk() (*V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn, bool)`

GetSiteToSiteVpnOk returns a tuple with the SiteToSiteVpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetSiteToSiteVpn(v V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn)`

SetSiteToSiteVpn sets SiteToSiteVpn field to given value.

### HasSiteToSiteVpn

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasSiteToSiteVpn() bool`

HasSiteToSiteVpn returns a boolean if a field has been set.

### GetStatus

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



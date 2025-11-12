# V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpGraphiantAsn** | Pointer to **int32** |  | [optional] 
**BgpLocalAsn** | Pointer to **int32** |  | [optional] 
**BgpNeighborHoldTime** | Pointer to **int32** |  | [optional] 
**BgpNeighborIpv4** | Pointer to **string** |  | [optional] 
**BgpNeighborIpv6** | Pointer to **string** |  | [optional] 
**DpdInterval** | Pointer to **int32** |  | [optional] 
**DpdRetries** | Pointer to **int32** |  | [optional] 
**GraphiantDestinationIp** | Pointer to **string** |  | [optional] 
**GraphiantIkeId** | Pointer to **string** |  | [optional] 
**GraphiantOuterTunnelIp** | Pointer to **string** |  | [optional] 
**GraphiantTunnelIp** | Pointer to **string** |  | [optional] 
**GraphiantTunnelIpv6** | Pointer to **string** |  | [optional] 
**IkeAuthenticationAlgorithm** | Pointer to **string** |  | [optional] 
**IkeAuthenticationMethod** | Pointer to **string** |  | [optional] 
**IkeDhAlgorithm** | Pointer to **string** |  | [optional] 
**IkeEncryptionAlgorithm** | Pointer to **string** |  | [optional] 
**IkeLifetime** | Pointer to **string** |  | [optional] 
**IkePresharedKey** | Pointer to **string** |  | [optional] 
**IkeVersion** | Pointer to **int32** |  | [optional] 
**IpsecAuthenticationAlgorithm** | Pointer to **string** |  | [optional] 
**IpsecEncryptionAlgorithm** | Pointer to **string** |  | [optional] 
**IpsecExtendedSequenceNumber** | Pointer to **bool** |  | [optional] 
**IpsecLifetime** | Pointer to **string** |  | [optional] 
**IpsecMode** | Pointer to **string** |  | [optional] 
**IpsecPfsAlgorithm** | Pointer to **string** |  | [optional] 
**IpsecProtocol** | Pointer to **string** |  | [optional] 
**LocalIkeId** | Pointer to **string** |  | [optional] 
**LocalOuterTunnelIp** | Pointer to **string** |  | [optional] 
**LocalTunnelIp** | Pointer to **string** |  | [optional] 
**LocalTunnelIpv6** | Pointer to **string** |  | [optional] 
**TcpMss** | Pointer to **int32** |  | [optional] 
**TunnelMtu** | Pointer to **int32** |  | [optional] 

## Methods

### NewV1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig

`func NewV1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig() *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig`

NewV1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig instantiates a new V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfigWithDefaults

`func NewV1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfigWithDefaults() *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig`

NewV1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfigWithDefaults instantiates a new V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpGraphiantAsn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpGraphiantAsn() int32`

GetBgpGraphiantAsn returns the BgpGraphiantAsn field if non-nil, zero value otherwise.

### GetBgpGraphiantAsnOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpGraphiantAsnOk() (*int32, bool)`

GetBgpGraphiantAsnOk returns a tuple with the BgpGraphiantAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpGraphiantAsn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetBgpGraphiantAsn(v int32)`

SetBgpGraphiantAsn sets BgpGraphiantAsn field to given value.

### HasBgpGraphiantAsn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasBgpGraphiantAsn() bool`

HasBgpGraphiantAsn returns a boolean if a field has been set.

### GetBgpLocalAsn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpLocalAsn() int32`

GetBgpLocalAsn returns the BgpLocalAsn field if non-nil, zero value otherwise.

### GetBgpLocalAsnOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpLocalAsnOk() (*int32, bool)`

GetBgpLocalAsnOk returns a tuple with the BgpLocalAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpLocalAsn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetBgpLocalAsn(v int32)`

SetBgpLocalAsn sets BgpLocalAsn field to given value.

### HasBgpLocalAsn

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasBgpLocalAsn() bool`

HasBgpLocalAsn returns a boolean if a field has been set.

### GetBgpNeighborHoldTime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpNeighborHoldTime() int32`

GetBgpNeighborHoldTime returns the BgpNeighborHoldTime field if non-nil, zero value otherwise.

### GetBgpNeighborHoldTimeOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpNeighborHoldTimeOk() (*int32, bool)`

GetBgpNeighborHoldTimeOk returns a tuple with the BgpNeighborHoldTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighborHoldTime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetBgpNeighborHoldTime(v int32)`

SetBgpNeighborHoldTime sets BgpNeighborHoldTime field to given value.

### HasBgpNeighborHoldTime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasBgpNeighborHoldTime() bool`

HasBgpNeighborHoldTime returns a boolean if a field has been set.

### GetBgpNeighborIpv4

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpNeighborIpv4() string`

GetBgpNeighborIpv4 returns the BgpNeighborIpv4 field if non-nil, zero value otherwise.

### GetBgpNeighborIpv4Ok

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpNeighborIpv4Ok() (*string, bool)`

GetBgpNeighborIpv4Ok returns a tuple with the BgpNeighborIpv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighborIpv4

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetBgpNeighborIpv4(v string)`

SetBgpNeighborIpv4 sets BgpNeighborIpv4 field to given value.

### HasBgpNeighborIpv4

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasBgpNeighborIpv4() bool`

HasBgpNeighborIpv4 returns a boolean if a field has been set.

### GetBgpNeighborIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpNeighborIpv6() string`

GetBgpNeighborIpv6 returns the BgpNeighborIpv6 field if non-nil, zero value otherwise.

### GetBgpNeighborIpv6Ok

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetBgpNeighborIpv6Ok() (*string, bool)`

GetBgpNeighborIpv6Ok returns a tuple with the BgpNeighborIpv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpNeighborIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetBgpNeighborIpv6(v string)`

SetBgpNeighborIpv6 sets BgpNeighborIpv6 field to given value.

### HasBgpNeighborIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasBgpNeighborIpv6() bool`

HasBgpNeighborIpv6 returns a boolean if a field has been set.

### GetDpdInterval

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetDpdInterval() int32`

GetDpdInterval returns the DpdInterval field if non-nil, zero value otherwise.

### GetDpdIntervalOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetDpdIntervalOk() (*int32, bool)`

GetDpdIntervalOk returns a tuple with the DpdInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpdInterval

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetDpdInterval(v int32)`

SetDpdInterval sets DpdInterval field to given value.

### HasDpdInterval

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasDpdInterval() bool`

HasDpdInterval returns a boolean if a field has been set.

### GetDpdRetries

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetDpdRetries() int32`

GetDpdRetries returns the DpdRetries field if non-nil, zero value otherwise.

### GetDpdRetriesOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetDpdRetriesOk() (*int32, bool)`

GetDpdRetriesOk returns a tuple with the DpdRetries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDpdRetries

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetDpdRetries(v int32)`

SetDpdRetries sets DpdRetries field to given value.

### HasDpdRetries

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasDpdRetries() bool`

HasDpdRetries returns a boolean if a field has been set.

### GetGraphiantDestinationIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantDestinationIp() string`

GetGraphiantDestinationIp returns the GraphiantDestinationIp field if non-nil, zero value otherwise.

### GetGraphiantDestinationIpOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantDestinationIpOk() (*string, bool)`

GetGraphiantDestinationIpOk returns a tuple with the GraphiantDestinationIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantDestinationIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetGraphiantDestinationIp(v string)`

SetGraphiantDestinationIp sets GraphiantDestinationIp field to given value.

### HasGraphiantDestinationIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasGraphiantDestinationIp() bool`

HasGraphiantDestinationIp returns a boolean if a field has been set.

### GetGraphiantIkeId

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantIkeId() string`

GetGraphiantIkeId returns the GraphiantIkeId field if non-nil, zero value otherwise.

### GetGraphiantIkeIdOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantIkeIdOk() (*string, bool)`

GetGraphiantIkeIdOk returns a tuple with the GraphiantIkeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantIkeId

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetGraphiantIkeId(v string)`

SetGraphiantIkeId sets GraphiantIkeId field to given value.

### HasGraphiantIkeId

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasGraphiantIkeId() bool`

HasGraphiantIkeId returns a boolean if a field has been set.

### GetGraphiantOuterTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantOuterTunnelIp() string`

GetGraphiantOuterTunnelIp returns the GraphiantOuterTunnelIp field if non-nil, zero value otherwise.

### GetGraphiantOuterTunnelIpOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantOuterTunnelIpOk() (*string, bool)`

GetGraphiantOuterTunnelIpOk returns a tuple with the GraphiantOuterTunnelIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantOuterTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetGraphiantOuterTunnelIp(v string)`

SetGraphiantOuterTunnelIp sets GraphiantOuterTunnelIp field to given value.

### HasGraphiantOuterTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasGraphiantOuterTunnelIp() bool`

HasGraphiantOuterTunnelIp returns a boolean if a field has been set.

### GetGraphiantTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantTunnelIp() string`

GetGraphiantTunnelIp returns the GraphiantTunnelIp field if non-nil, zero value otherwise.

### GetGraphiantTunnelIpOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantTunnelIpOk() (*string, bool)`

GetGraphiantTunnelIpOk returns a tuple with the GraphiantTunnelIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetGraphiantTunnelIp(v string)`

SetGraphiantTunnelIp sets GraphiantTunnelIp field to given value.

### HasGraphiantTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasGraphiantTunnelIp() bool`

HasGraphiantTunnelIp returns a boolean if a field has been set.

### GetGraphiantTunnelIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantTunnelIpv6() string`

GetGraphiantTunnelIpv6 returns the GraphiantTunnelIpv6 field if non-nil, zero value otherwise.

### GetGraphiantTunnelIpv6Ok

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetGraphiantTunnelIpv6Ok() (*string, bool)`

GetGraphiantTunnelIpv6Ok returns a tuple with the GraphiantTunnelIpv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantTunnelIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetGraphiantTunnelIpv6(v string)`

SetGraphiantTunnelIpv6 sets GraphiantTunnelIpv6 field to given value.

### HasGraphiantTunnelIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasGraphiantTunnelIpv6() bool`

HasGraphiantTunnelIpv6 returns a boolean if a field has been set.

### GetIkeAuthenticationAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeAuthenticationAlgorithm() string`

GetIkeAuthenticationAlgorithm returns the IkeAuthenticationAlgorithm field if non-nil, zero value otherwise.

### GetIkeAuthenticationAlgorithmOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeAuthenticationAlgorithmOk() (*string, bool)`

GetIkeAuthenticationAlgorithmOk returns a tuple with the IkeAuthenticationAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeAuthenticationAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkeAuthenticationAlgorithm(v string)`

SetIkeAuthenticationAlgorithm sets IkeAuthenticationAlgorithm field to given value.

### HasIkeAuthenticationAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkeAuthenticationAlgorithm() bool`

HasIkeAuthenticationAlgorithm returns a boolean if a field has been set.

### GetIkeAuthenticationMethod

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeAuthenticationMethod() string`

GetIkeAuthenticationMethod returns the IkeAuthenticationMethod field if non-nil, zero value otherwise.

### GetIkeAuthenticationMethodOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeAuthenticationMethodOk() (*string, bool)`

GetIkeAuthenticationMethodOk returns a tuple with the IkeAuthenticationMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeAuthenticationMethod

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkeAuthenticationMethod(v string)`

SetIkeAuthenticationMethod sets IkeAuthenticationMethod field to given value.

### HasIkeAuthenticationMethod

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkeAuthenticationMethod() bool`

HasIkeAuthenticationMethod returns a boolean if a field has been set.

### GetIkeDhAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeDhAlgorithm() string`

GetIkeDhAlgorithm returns the IkeDhAlgorithm field if non-nil, zero value otherwise.

### GetIkeDhAlgorithmOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeDhAlgorithmOk() (*string, bool)`

GetIkeDhAlgorithmOk returns a tuple with the IkeDhAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeDhAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkeDhAlgorithm(v string)`

SetIkeDhAlgorithm sets IkeDhAlgorithm field to given value.

### HasIkeDhAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkeDhAlgorithm() bool`

HasIkeDhAlgorithm returns a boolean if a field has been set.

### GetIkeEncryptionAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeEncryptionAlgorithm() string`

GetIkeEncryptionAlgorithm returns the IkeEncryptionAlgorithm field if non-nil, zero value otherwise.

### GetIkeEncryptionAlgorithmOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeEncryptionAlgorithmOk() (*string, bool)`

GetIkeEncryptionAlgorithmOk returns a tuple with the IkeEncryptionAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeEncryptionAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkeEncryptionAlgorithm(v string)`

SetIkeEncryptionAlgorithm sets IkeEncryptionAlgorithm field to given value.

### HasIkeEncryptionAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkeEncryptionAlgorithm() bool`

HasIkeEncryptionAlgorithm returns a boolean if a field has been set.

### GetIkeLifetime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeLifetime() string`

GetIkeLifetime returns the IkeLifetime field if non-nil, zero value otherwise.

### GetIkeLifetimeOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeLifetimeOk() (*string, bool)`

GetIkeLifetimeOk returns a tuple with the IkeLifetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeLifetime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkeLifetime(v string)`

SetIkeLifetime sets IkeLifetime field to given value.

### HasIkeLifetime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkeLifetime() bool`

HasIkeLifetime returns a boolean if a field has been set.

### GetIkePresharedKey

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkePresharedKey() string`

GetIkePresharedKey returns the IkePresharedKey field if non-nil, zero value otherwise.

### GetIkePresharedKeyOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkePresharedKeyOk() (*string, bool)`

GetIkePresharedKeyOk returns a tuple with the IkePresharedKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkePresharedKey

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkePresharedKey(v string)`

SetIkePresharedKey sets IkePresharedKey field to given value.

### HasIkePresharedKey

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkePresharedKey() bool`

HasIkePresharedKey returns a boolean if a field has been set.

### GetIkeVersion

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeVersion() int32`

GetIkeVersion returns the IkeVersion field if non-nil, zero value otherwise.

### GetIkeVersionOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIkeVersionOk() (*int32, bool)`

GetIkeVersionOk returns a tuple with the IkeVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIkeVersion

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIkeVersion(v int32)`

SetIkeVersion sets IkeVersion field to given value.

### HasIkeVersion

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIkeVersion() bool`

HasIkeVersion returns a boolean if a field has been set.

### GetIpsecAuthenticationAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecAuthenticationAlgorithm() string`

GetIpsecAuthenticationAlgorithm returns the IpsecAuthenticationAlgorithm field if non-nil, zero value otherwise.

### GetIpsecAuthenticationAlgorithmOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecAuthenticationAlgorithmOk() (*string, bool)`

GetIpsecAuthenticationAlgorithmOk returns a tuple with the IpsecAuthenticationAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecAuthenticationAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecAuthenticationAlgorithm(v string)`

SetIpsecAuthenticationAlgorithm sets IpsecAuthenticationAlgorithm field to given value.

### HasIpsecAuthenticationAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecAuthenticationAlgorithm() bool`

HasIpsecAuthenticationAlgorithm returns a boolean if a field has been set.

### GetIpsecEncryptionAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecEncryptionAlgorithm() string`

GetIpsecEncryptionAlgorithm returns the IpsecEncryptionAlgorithm field if non-nil, zero value otherwise.

### GetIpsecEncryptionAlgorithmOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecEncryptionAlgorithmOk() (*string, bool)`

GetIpsecEncryptionAlgorithmOk returns a tuple with the IpsecEncryptionAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecEncryptionAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecEncryptionAlgorithm(v string)`

SetIpsecEncryptionAlgorithm sets IpsecEncryptionAlgorithm field to given value.

### HasIpsecEncryptionAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecEncryptionAlgorithm() bool`

HasIpsecEncryptionAlgorithm returns a boolean if a field has been set.

### GetIpsecExtendedSequenceNumber

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecExtendedSequenceNumber() bool`

GetIpsecExtendedSequenceNumber returns the IpsecExtendedSequenceNumber field if non-nil, zero value otherwise.

### GetIpsecExtendedSequenceNumberOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecExtendedSequenceNumberOk() (*bool, bool)`

GetIpsecExtendedSequenceNumberOk returns a tuple with the IpsecExtendedSequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecExtendedSequenceNumber

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecExtendedSequenceNumber(v bool)`

SetIpsecExtendedSequenceNumber sets IpsecExtendedSequenceNumber field to given value.

### HasIpsecExtendedSequenceNumber

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecExtendedSequenceNumber() bool`

HasIpsecExtendedSequenceNumber returns a boolean if a field has been set.

### GetIpsecLifetime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecLifetime() string`

GetIpsecLifetime returns the IpsecLifetime field if non-nil, zero value otherwise.

### GetIpsecLifetimeOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecLifetimeOk() (*string, bool)`

GetIpsecLifetimeOk returns a tuple with the IpsecLifetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecLifetime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecLifetime(v string)`

SetIpsecLifetime sets IpsecLifetime field to given value.

### HasIpsecLifetime

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecLifetime() bool`

HasIpsecLifetime returns a boolean if a field has been set.

### GetIpsecMode

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecMode() string`

GetIpsecMode returns the IpsecMode field if non-nil, zero value otherwise.

### GetIpsecModeOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecModeOk() (*string, bool)`

GetIpsecModeOk returns a tuple with the IpsecMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecMode

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecMode(v string)`

SetIpsecMode sets IpsecMode field to given value.

### HasIpsecMode

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecMode() bool`

HasIpsecMode returns a boolean if a field has been set.

### GetIpsecPfsAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecPfsAlgorithm() string`

GetIpsecPfsAlgorithm returns the IpsecPfsAlgorithm field if non-nil, zero value otherwise.

### GetIpsecPfsAlgorithmOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecPfsAlgorithmOk() (*string, bool)`

GetIpsecPfsAlgorithmOk returns a tuple with the IpsecPfsAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecPfsAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecPfsAlgorithm(v string)`

SetIpsecPfsAlgorithm sets IpsecPfsAlgorithm field to given value.

### HasIpsecPfsAlgorithm

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecPfsAlgorithm() bool`

HasIpsecPfsAlgorithm returns a boolean if a field has been set.

### GetIpsecProtocol

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecProtocol() string`

GetIpsecProtocol returns the IpsecProtocol field if non-nil, zero value otherwise.

### GetIpsecProtocolOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetIpsecProtocolOk() (*string, bool)`

GetIpsecProtocolOk returns a tuple with the IpsecProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecProtocol

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetIpsecProtocol(v string)`

SetIpsecProtocol sets IpsecProtocol field to given value.

### HasIpsecProtocol

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasIpsecProtocol() bool`

HasIpsecProtocol returns a boolean if a field has been set.

### GetLocalIkeId

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalIkeId() string`

GetLocalIkeId returns the LocalIkeId field if non-nil, zero value otherwise.

### GetLocalIkeIdOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalIkeIdOk() (*string, bool)`

GetLocalIkeIdOk returns a tuple with the LocalIkeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIkeId

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetLocalIkeId(v string)`

SetLocalIkeId sets LocalIkeId field to given value.

### HasLocalIkeId

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasLocalIkeId() bool`

HasLocalIkeId returns a boolean if a field has been set.

### GetLocalOuterTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalOuterTunnelIp() string`

GetLocalOuterTunnelIp returns the LocalOuterTunnelIp field if non-nil, zero value otherwise.

### GetLocalOuterTunnelIpOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalOuterTunnelIpOk() (*string, bool)`

GetLocalOuterTunnelIpOk returns a tuple with the LocalOuterTunnelIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalOuterTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetLocalOuterTunnelIp(v string)`

SetLocalOuterTunnelIp sets LocalOuterTunnelIp field to given value.

### HasLocalOuterTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasLocalOuterTunnelIp() bool`

HasLocalOuterTunnelIp returns a boolean if a field has been set.

### GetLocalTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalTunnelIp() string`

GetLocalTunnelIp returns the LocalTunnelIp field if non-nil, zero value otherwise.

### GetLocalTunnelIpOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalTunnelIpOk() (*string, bool)`

GetLocalTunnelIpOk returns a tuple with the LocalTunnelIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetLocalTunnelIp(v string)`

SetLocalTunnelIp sets LocalTunnelIp field to given value.

### HasLocalTunnelIp

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasLocalTunnelIp() bool`

HasLocalTunnelIp returns a boolean if a field has been set.

### GetLocalTunnelIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalTunnelIpv6() string`

GetLocalTunnelIpv6 returns the LocalTunnelIpv6 field if non-nil, zero value otherwise.

### GetLocalTunnelIpv6Ok

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetLocalTunnelIpv6Ok() (*string, bool)`

GetLocalTunnelIpv6Ok returns a tuple with the LocalTunnelIpv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalTunnelIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetLocalTunnelIpv6(v string)`

SetLocalTunnelIpv6 sets LocalTunnelIpv6 field to given value.

### HasLocalTunnelIpv6

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasLocalTunnelIpv6() bool`

HasLocalTunnelIpv6 returns a boolean if a field has been set.

### GetTcpMss

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetTcpMss() int32`

GetTcpMss returns the TcpMss field if non-nil, zero value otherwise.

### GetTcpMssOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetTcpMssOk() (*int32, bool)`

GetTcpMssOk returns a tuple with the TcpMss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpMss

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetTcpMss(v int32)`

SetTcpMss sets TcpMss field to given value.

### HasTcpMss

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasTcpMss() bool`

HasTcpMss returns a boolean if a field has been set.

### GetTunnelMtu

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetTunnelMtu() int32`

GetTunnelMtu returns the TunnelMtu field if non-nil, zero value otherwise.

### GetTunnelMtuOk

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) GetTunnelMtuOk() (*int32, bool)`

GetTunnelMtuOk returns a tuple with the TunnelMtu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnelMtu

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) SetTunnelMtu(v int32)`

SetTunnelMtu sets TunnelMtu field to given value.

### HasTunnelMtu

`func (o *V1GatewaysGuestConsumerMatchIdGetResponseIpsecVpnTunnelConfig) HasTunnelMtu() bool`

HasTunnelMtu returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



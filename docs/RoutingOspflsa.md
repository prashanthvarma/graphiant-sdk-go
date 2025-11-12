# RoutingOspflsa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdvertisingRouter** | Pointer to **string** | IP address (required) | [optional] 
**Age** | Pointer to **int32** | How old is the LSA (required) | [optional] 
**AsexternalLsa** | Pointer to [**RoutingOspfasExternalLsa**](RoutingOspfasExternalLsa.md) |  | [optional] 
**Checksum** | Pointer to **int32** | LSA Checksum (required) | [optional] 
**Length** | Pointer to **int32** | LSA length (required) | [optional] 
**LinkId** | Pointer to **string** | IP address of link on peer (required) | [optional] 
**NetworkLsa** | Pointer to [**RoutingOspfNetworkLsa**](RoutingOspfNetworkLsa.md) |  | [optional] 
**RouterLsa** | Pointer to [**RoutingOspfRouterLsa**](RoutingOspfRouterLsa.md) |  | [optional] 
**SequenceNumber** | Pointer to **string** | LSA sequence number (required) | [optional] 
**SummaryLsa** | Pointer to [**RoutingOspfSummaryLsa**](RoutingOspfSummaryLsa.md) |  | [optional] 
**Type** | Pointer to **string** | Type of LSA (required) | [optional] 

## Methods

### NewRoutingOspflsa

`func NewRoutingOspflsa() *RoutingOspflsa`

NewRoutingOspflsa instantiates a new RoutingOspflsa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingOspflsaWithDefaults

`func NewRoutingOspflsaWithDefaults() *RoutingOspflsa`

NewRoutingOspflsaWithDefaults instantiates a new RoutingOspflsa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdvertisingRouter

`func (o *RoutingOspflsa) GetAdvertisingRouter() string`

GetAdvertisingRouter returns the AdvertisingRouter field if non-nil, zero value otherwise.

### GetAdvertisingRouterOk

`func (o *RoutingOspflsa) GetAdvertisingRouterOk() (*string, bool)`

GetAdvertisingRouterOk returns a tuple with the AdvertisingRouter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvertisingRouter

`func (o *RoutingOspflsa) SetAdvertisingRouter(v string)`

SetAdvertisingRouter sets AdvertisingRouter field to given value.

### HasAdvertisingRouter

`func (o *RoutingOspflsa) HasAdvertisingRouter() bool`

HasAdvertisingRouter returns a boolean if a field has been set.

### GetAge

`func (o *RoutingOspflsa) GetAge() int32`

GetAge returns the Age field if non-nil, zero value otherwise.

### GetAgeOk

`func (o *RoutingOspflsa) GetAgeOk() (*int32, bool)`

GetAgeOk returns a tuple with the Age field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAge

`func (o *RoutingOspflsa) SetAge(v int32)`

SetAge sets Age field to given value.

### HasAge

`func (o *RoutingOspflsa) HasAge() bool`

HasAge returns a boolean if a field has been set.

### GetAsexternalLsa

`func (o *RoutingOspflsa) GetAsexternalLsa() RoutingOspfasExternalLsa`

GetAsexternalLsa returns the AsexternalLsa field if non-nil, zero value otherwise.

### GetAsexternalLsaOk

`func (o *RoutingOspflsa) GetAsexternalLsaOk() (*RoutingOspfasExternalLsa, bool)`

GetAsexternalLsaOk returns a tuple with the AsexternalLsa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsexternalLsa

`func (o *RoutingOspflsa) SetAsexternalLsa(v RoutingOspfasExternalLsa)`

SetAsexternalLsa sets AsexternalLsa field to given value.

### HasAsexternalLsa

`func (o *RoutingOspflsa) HasAsexternalLsa() bool`

HasAsexternalLsa returns a boolean if a field has been set.

### GetChecksum

`func (o *RoutingOspflsa) GetChecksum() int32`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *RoutingOspflsa) GetChecksumOk() (*int32, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *RoutingOspflsa) SetChecksum(v int32)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *RoutingOspflsa) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### GetLength

`func (o *RoutingOspflsa) GetLength() int32`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *RoutingOspflsa) GetLengthOk() (*int32, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *RoutingOspflsa) SetLength(v int32)`

SetLength sets Length field to given value.

### HasLength

`func (o *RoutingOspflsa) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetLinkId

`func (o *RoutingOspflsa) GetLinkId() string`

GetLinkId returns the LinkId field if non-nil, zero value otherwise.

### GetLinkIdOk

`func (o *RoutingOspflsa) GetLinkIdOk() (*string, bool)`

GetLinkIdOk returns a tuple with the LinkId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkId

`func (o *RoutingOspflsa) SetLinkId(v string)`

SetLinkId sets LinkId field to given value.

### HasLinkId

`func (o *RoutingOspflsa) HasLinkId() bool`

HasLinkId returns a boolean if a field has been set.

### GetNetworkLsa

`func (o *RoutingOspflsa) GetNetworkLsa() RoutingOspfNetworkLsa`

GetNetworkLsa returns the NetworkLsa field if non-nil, zero value otherwise.

### GetNetworkLsaOk

`func (o *RoutingOspflsa) GetNetworkLsaOk() (*RoutingOspfNetworkLsa, bool)`

GetNetworkLsaOk returns a tuple with the NetworkLsa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkLsa

`func (o *RoutingOspflsa) SetNetworkLsa(v RoutingOspfNetworkLsa)`

SetNetworkLsa sets NetworkLsa field to given value.

### HasNetworkLsa

`func (o *RoutingOspflsa) HasNetworkLsa() bool`

HasNetworkLsa returns a boolean if a field has been set.

### GetRouterLsa

`func (o *RoutingOspflsa) GetRouterLsa() RoutingOspfRouterLsa`

GetRouterLsa returns the RouterLsa field if non-nil, zero value otherwise.

### GetRouterLsaOk

`func (o *RoutingOspflsa) GetRouterLsaOk() (*RoutingOspfRouterLsa, bool)`

GetRouterLsaOk returns a tuple with the RouterLsa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterLsa

`func (o *RoutingOspflsa) SetRouterLsa(v RoutingOspfRouterLsa)`

SetRouterLsa sets RouterLsa field to given value.

### HasRouterLsa

`func (o *RoutingOspflsa) HasRouterLsa() bool`

HasRouterLsa returns a boolean if a field has been set.

### GetSequenceNumber

`func (o *RoutingOspflsa) GetSequenceNumber() string`

GetSequenceNumber returns the SequenceNumber field if non-nil, zero value otherwise.

### GetSequenceNumberOk

`func (o *RoutingOspflsa) GetSequenceNumberOk() (*string, bool)`

GetSequenceNumberOk returns a tuple with the SequenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequenceNumber

`func (o *RoutingOspflsa) SetSequenceNumber(v string)`

SetSequenceNumber sets SequenceNumber field to given value.

### HasSequenceNumber

`func (o *RoutingOspflsa) HasSequenceNumber() bool`

HasSequenceNumber returns a boolean if a field has been set.

### GetSummaryLsa

`func (o *RoutingOspflsa) GetSummaryLsa() RoutingOspfSummaryLsa`

GetSummaryLsa returns the SummaryLsa field if non-nil, zero value otherwise.

### GetSummaryLsaOk

`func (o *RoutingOspflsa) GetSummaryLsaOk() (*RoutingOspfSummaryLsa, bool)`

GetSummaryLsaOk returns a tuple with the SummaryLsa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummaryLsa

`func (o *RoutingOspflsa) SetSummaryLsa(v RoutingOspfSummaryLsa)`

SetSummaryLsa sets SummaryLsa field to given value.

### HasSummaryLsa

`func (o *RoutingOspflsa) HasSummaryLsa() bool`

HasSummaryLsa returns a boolean if a field has been set.

### GetType

`func (o *RoutingOspflsa) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RoutingOspflsa) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RoutingOspflsa) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RoutingOspflsa) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



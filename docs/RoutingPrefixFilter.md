# RoutingPrefixFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AsPath** | Pointer to **[]string** |  | [optional] 
**ExtCommunity** | Pointer to **string** |  | [optional] 
**InterfaceName** | Pointer to **string** | Interface name | [optional] 
**NextHop** | Pointer to **string** | IPv4 or IPv6 Nexthop | [optional] 
**Prefix** | Pointer to **string** |  | [optional] 
**Rd** | Pointer to **string** | Route RD. Must for BGPAddrFamilyVpnIpv4Unicast/BGPAddrFamilyVpnIpv6Unicast | [optional] 
**SrcProto** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** | route type | [optional] 

## Methods

### NewRoutingPrefixFilter

`func NewRoutingPrefixFilter() *RoutingPrefixFilter`

NewRoutingPrefixFilter instantiates a new RoutingPrefixFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingPrefixFilterWithDefaults

`func NewRoutingPrefixFilterWithDefaults() *RoutingPrefixFilter`

NewRoutingPrefixFilterWithDefaults instantiates a new RoutingPrefixFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAsPath

`func (o *RoutingPrefixFilter) GetAsPath() []string`

GetAsPath returns the AsPath field if non-nil, zero value otherwise.

### GetAsPathOk

`func (o *RoutingPrefixFilter) GetAsPathOk() (*[]string, bool)`

GetAsPathOk returns a tuple with the AsPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsPath

`func (o *RoutingPrefixFilter) SetAsPath(v []string)`

SetAsPath sets AsPath field to given value.

### HasAsPath

`func (o *RoutingPrefixFilter) HasAsPath() bool`

HasAsPath returns a boolean if a field has been set.

### GetExtCommunity

`func (o *RoutingPrefixFilter) GetExtCommunity() string`

GetExtCommunity returns the ExtCommunity field if non-nil, zero value otherwise.

### GetExtCommunityOk

`func (o *RoutingPrefixFilter) GetExtCommunityOk() (*string, bool)`

GetExtCommunityOk returns a tuple with the ExtCommunity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtCommunity

`func (o *RoutingPrefixFilter) SetExtCommunity(v string)`

SetExtCommunity sets ExtCommunity field to given value.

### HasExtCommunity

`func (o *RoutingPrefixFilter) HasExtCommunity() bool`

HasExtCommunity returns a boolean if a field has been set.

### GetInterfaceName

`func (o *RoutingPrefixFilter) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *RoutingPrefixFilter) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *RoutingPrefixFilter) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *RoutingPrefixFilter) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.

### GetNextHop

`func (o *RoutingPrefixFilter) GetNextHop() string`

GetNextHop returns the NextHop field if non-nil, zero value otherwise.

### GetNextHopOk

`func (o *RoutingPrefixFilter) GetNextHopOk() (*string, bool)`

GetNextHopOk returns a tuple with the NextHop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextHop

`func (o *RoutingPrefixFilter) SetNextHop(v string)`

SetNextHop sets NextHop field to given value.

### HasNextHop

`func (o *RoutingPrefixFilter) HasNextHop() bool`

HasNextHop returns a boolean if a field has been set.

### GetPrefix

`func (o *RoutingPrefixFilter) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *RoutingPrefixFilter) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *RoutingPrefixFilter) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.

### HasPrefix

`func (o *RoutingPrefixFilter) HasPrefix() bool`

HasPrefix returns a boolean if a field has been set.

### GetRd

`func (o *RoutingPrefixFilter) GetRd() string`

GetRd returns the Rd field if non-nil, zero value otherwise.

### GetRdOk

`func (o *RoutingPrefixFilter) GetRdOk() (*string, bool)`

GetRdOk returns a tuple with the Rd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRd

`func (o *RoutingPrefixFilter) SetRd(v string)`

SetRd sets Rd field to given value.

### HasRd

`func (o *RoutingPrefixFilter) HasRd() bool`

HasRd returns a boolean if a field has been set.

### GetSrcProto

`func (o *RoutingPrefixFilter) GetSrcProto() string`

GetSrcProto returns the SrcProto field if non-nil, zero value otherwise.

### GetSrcProtoOk

`func (o *RoutingPrefixFilter) GetSrcProtoOk() (*string, bool)`

GetSrcProtoOk returns a tuple with the SrcProto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSrcProto

`func (o *RoutingPrefixFilter) SetSrcProto(v string)`

SetSrcProto sets SrcProto field to given value.

### HasSrcProto

`func (o *RoutingPrefixFilter) HasSrcProto() bool`

HasSrcProto returns a boolean if a field has been set.

### GetType

`func (o *RoutingPrefixFilter) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RoutingPrefixFilter) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RoutingPrefixFilter) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RoutingPrefixFilter) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



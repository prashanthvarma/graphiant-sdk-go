# ManaV2RoutingPolicyStatementMatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Community** | Pointer to **[]string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**PrefixSet** | Pointer to **string** |  | [optional] 
**ProtocolRouteType** | Pointer to **string** |  | [optional] 
**RouteTag** | Pointer to [**ManaV2RouteTag**](ManaV2RouteTag.md) |  | [optional] 
**Seq** | Pointer to **int32** |  | [optional] 
**SourceInterface** | Pointer to **string** |  | [optional] 
**SourceProtocol** | Pointer to **string** |  | [optional] 
**StalePurge** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2RoutingPolicyStatementMatch

`func NewManaV2RoutingPolicyStatementMatch() *ManaV2RoutingPolicyStatementMatch`

NewManaV2RoutingPolicyStatementMatch instantiates a new ManaV2RoutingPolicyStatementMatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2RoutingPolicyStatementMatchWithDefaults

`func NewManaV2RoutingPolicyStatementMatchWithDefaults() *ManaV2RoutingPolicyStatementMatch`

NewManaV2RoutingPolicyStatementMatchWithDefaults instantiates a new ManaV2RoutingPolicyStatementMatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommunity

`func (o *ManaV2RoutingPolicyStatementMatch) GetCommunity() []string`

GetCommunity returns the Community field if non-nil, zero value otherwise.

### GetCommunityOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetCommunityOk() (*[]string, bool)`

GetCommunityOk returns a tuple with the Community field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunity

`func (o *ManaV2RoutingPolicyStatementMatch) SetCommunity(v []string)`

SetCommunity sets Community field to given value.

### HasCommunity

`func (o *ManaV2RoutingPolicyStatementMatch) HasCommunity() bool`

HasCommunity returns a boolean if a field has been set.

### GetId

`func (o *ManaV2RoutingPolicyStatementMatch) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2RoutingPolicyStatementMatch) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2RoutingPolicyStatementMatch) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPrefixSet

`func (o *ManaV2RoutingPolicyStatementMatch) GetPrefixSet() string`

GetPrefixSet returns the PrefixSet field if non-nil, zero value otherwise.

### GetPrefixSetOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetPrefixSetOk() (*string, bool)`

GetPrefixSetOk returns a tuple with the PrefixSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixSet

`func (o *ManaV2RoutingPolicyStatementMatch) SetPrefixSet(v string)`

SetPrefixSet sets PrefixSet field to given value.

### HasPrefixSet

`func (o *ManaV2RoutingPolicyStatementMatch) HasPrefixSet() bool`

HasPrefixSet returns a boolean if a field has been set.

### GetProtocolRouteType

`func (o *ManaV2RoutingPolicyStatementMatch) GetProtocolRouteType() string`

GetProtocolRouteType returns the ProtocolRouteType field if non-nil, zero value otherwise.

### GetProtocolRouteTypeOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetProtocolRouteTypeOk() (*string, bool)`

GetProtocolRouteTypeOk returns a tuple with the ProtocolRouteType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocolRouteType

`func (o *ManaV2RoutingPolicyStatementMatch) SetProtocolRouteType(v string)`

SetProtocolRouteType sets ProtocolRouteType field to given value.

### HasProtocolRouteType

`func (o *ManaV2RoutingPolicyStatementMatch) HasProtocolRouteType() bool`

HasProtocolRouteType returns a boolean if a field has been set.

### GetRouteTag

`func (o *ManaV2RoutingPolicyStatementMatch) GetRouteTag() ManaV2RouteTag`

GetRouteTag returns the RouteTag field if non-nil, zero value otherwise.

### GetRouteTagOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetRouteTagOk() (*ManaV2RouteTag, bool)`

GetRouteTagOk returns a tuple with the RouteTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteTag

`func (o *ManaV2RoutingPolicyStatementMatch) SetRouteTag(v ManaV2RouteTag)`

SetRouteTag sets RouteTag field to given value.

### HasRouteTag

`func (o *ManaV2RoutingPolicyStatementMatch) HasRouteTag() bool`

HasRouteTag returns a boolean if a field has been set.

### GetSeq

`func (o *ManaV2RoutingPolicyStatementMatch) GetSeq() int32`

GetSeq returns the Seq field if non-nil, zero value otherwise.

### GetSeqOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetSeqOk() (*int32, bool)`

GetSeqOk returns a tuple with the Seq field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeq

`func (o *ManaV2RoutingPolicyStatementMatch) SetSeq(v int32)`

SetSeq sets Seq field to given value.

### HasSeq

`func (o *ManaV2RoutingPolicyStatementMatch) HasSeq() bool`

HasSeq returns a boolean if a field has been set.

### GetSourceInterface

`func (o *ManaV2RoutingPolicyStatementMatch) GetSourceInterface() string`

GetSourceInterface returns the SourceInterface field if non-nil, zero value otherwise.

### GetSourceInterfaceOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetSourceInterfaceOk() (*string, bool)`

GetSourceInterfaceOk returns a tuple with the SourceInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceInterface

`func (o *ManaV2RoutingPolicyStatementMatch) SetSourceInterface(v string)`

SetSourceInterface sets SourceInterface field to given value.

### HasSourceInterface

`func (o *ManaV2RoutingPolicyStatementMatch) HasSourceInterface() bool`

HasSourceInterface returns a boolean if a field has been set.

### GetSourceProtocol

`func (o *ManaV2RoutingPolicyStatementMatch) GetSourceProtocol() string`

GetSourceProtocol returns the SourceProtocol field if non-nil, zero value otherwise.

### GetSourceProtocolOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetSourceProtocolOk() (*string, bool)`

GetSourceProtocolOk returns a tuple with the SourceProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceProtocol

`func (o *ManaV2RoutingPolicyStatementMatch) SetSourceProtocol(v string)`

SetSourceProtocol sets SourceProtocol field to given value.

### HasSourceProtocol

`func (o *ManaV2RoutingPolicyStatementMatch) HasSourceProtocol() bool`

HasSourceProtocol returns a boolean if a field has been set.

### GetStalePurge

`func (o *ManaV2RoutingPolicyStatementMatch) GetStalePurge() bool`

GetStalePurge returns the StalePurge field if non-nil, zero value otherwise.

### GetStalePurgeOk

`func (o *ManaV2RoutingPolicyStatementMatch) GetStalePurgeOk() (*bool, bool)`

GetStalePurgeOk returns a tuple with the StalePurge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStalePurge

`func (o *ManaV2RoutingPolicyStatementMatch) SetStalePurge(v bool)`

SetStalePurge sets StalePurge field to given value.

### HasStalePurge

`func (o *ManaV2RoutingPolicyStatementMatch) HasStalePurge() bool`

HasStalePurge returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



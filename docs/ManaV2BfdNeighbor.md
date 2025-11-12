# ManaV2BfdNeighbor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DesiredMinimumTxInterval** | Pointer to **int32** |  | [optional] 
**IfIndex** | Pointer to **int32** |  | [optional] 
**Interface** | Pointer to **string** |  | [optional] 
**LastUpdated** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**LocalDiag** | Pointer to **string** |  | [optional] 
**PeerAddress** | Pointer to **string** |  | [optional] 
**RemoteDiag** | Pointer to **string** |  | [optional] 
**RequiredMinimumRxInterval** | Pointer to **int32** |  | [optional] 
**SegmentName** | Pointer to **string** |  | [optional] 
**SourceAddress** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**TimeInState** | Pointer to [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**Up** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2BfdNeighbor

`func NewManaV2BfdNeighbor() *ManaV2BfdNeighbor`

NewManaV2BfdNeighbor instantiates a new ManaV2BfdNeighbor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BfdNeighborWithDefaults

`func NewManaV2BfdNeighborWithDefaults() *ManaV2BfdNeighbor`

NewManaV2BfdNeighborWithDefaults instantiates a new ManaV2BfdNeighbor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDesiredMinimumTxInterval

`func (o *ManaV2BfdNeighbor) GetDesiredMinimumTxInterval() int32`

GetDesiredMinimumTxInterval returns the DesiredMinimumTxInterval field if non-nil, zero value otherwise.

### GetDesiredMinimumTxIntervalOk

`func (o *ManaV2BfdNeighbor) GetDesiredMinimumTxIntervalOk() (*int32, bool)`

GetDesiredMinimumTxIntervalOk returns a tuple with the DesiredMinimumTxInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredMinimumTxInterval

`func (o *ManaV2BfdNeighbor) SetDesiredMinimumTxInterval(v int32)`

SetDesiredMinimumTxInterval sets DesiredMinimumTxInterval field to given value.

### HasDesiredMinimumTxInterval

`func (o *ManaV2BfdNeighbor) HasDesiredMinimumTxInterval() bool`

HasDesiredMinimumTxInterval returns a boolean if a field has been set.

### GetIfIndex

`func (o *ManaV2BfdNeighbor) GetIfIndex() int32`

GetIfIndex returns the IfIndex field if non-nil, zero value otherwise.

### GetIfIndexOk

`func (o *ManaV2BfdNeighbor) GetIfIndexOk() (*int32, bool)`

GetIfIndexOk returns a tuple with the IfIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIfIndex

`func (o *ManaV2BfdNeighbor) SetIfIndex(v int32)`

SetIfIndex sets IfIndex field to given value.

### HasIfIndex

`func (o *ManaV2BfdNeighbor) HasIfIndex() bool`

HasIfIndex returns a boolean if a field has been set.

### GetInterface

`func (o *ManaV2BfdNeighbor) GetInterface() string`

GetInterface returns the Interface field if non-nil, zero value otherwise.

### GetInterfaceOk

`func (o *ManaV2BfdNeighbor) GetInterfaceOk() (*string, bool)`

GetInterfaceOk returns a tuple with the Interface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterface

`func (o *ManaV2BfdNeighbor) SetInterface(v string)`

SetInterface sets Interface field to given value.

### HasInterface

`func (o *ManaV2BfdNeighbor) HasInterface() bool`

HasInterface returns a boolean if a field has been set.

### GetLastUpdated

`func (o *ManaV2BfdNeighbor) GetLastUpdated() GoogleProtobufTimestamp`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *ManaV2BfdNeighbor) GetLastUpdatedOk() (*GoogleProtobufTimestamp, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *ManaV2BfdNeighbor) SetLastUpdated(v GoogleProtobufTimestamp)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *ManaV2BfdNeighbor) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### GetLocalDiag

`func (o *ManaV2BfdNeighbor) GetLocalDiag() string`

GetLocalDiag returns the LocalDiag field if non-nil, zero value otherwise.

### GetLocalDiagOk

`func (o *ManaV2BfdNeighbor) GetLocalDiagOk() (*string, bool)`

GetLocalDiagOk returns a tuple with the LocalDiag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalDiag

`func (o *ManaV2BfdNeighbor) SetLocalDiag(v string)`

SetLocalDiag sets LocalDiag field to given value.

### HasLocalDiag

`func (o *ManaV2BfdNeighbor) HasLocalDiag() bool`

HasLocalDiag returns a boolean if a field has been set.

### GetPeerAddress

`func (o *ManaV2BfdNeighbor) GetPeerAddress() string`

GetPeerAddress returns the PeerAddress field if non-nil, zero value otherwise.

### GetPeerAddressOk

`func (o *ManaV2BfdNeighbor) GetPeerAddressOk() (*string, bool)`

GetPeerAddressOk returns a tuple with the PeerAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerAddress

`func (o *ManaV2BfdNeighbor) SetPeerAddress(v string)`

SetPeerAddress sets PeerAddress field to given value.

### HasPeerAddress

`func (o *ManaV2BfdNeighbor) HasPeerAddress() bool`

HasPeerAddress returns a boolean if a field has been set.

### GetRemoteDiag

`func (o *ManaV2BfdNeighbor) GetRemoteDiag() string`

GetRemoteDiag returns the RemoteDiag field if non-nil, zero value otherwise.

### GetRemoteDiagOk

`func (o *ManaV2BfdNeighbor) GetRemoteDiagOk() (*string, bool)`

GetRemoteDiagOk returns a tuple with the RemoteDiag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteDiag

`func (o *ManaV2BfdNeighbor) SetRemoteDiag(v string)`

SetRemoteDiag sets RemoteDiag field to given value.

### HasRemoteDiag

`func (o *ManaV2BfdNeighbor) HasRemoteDiag() bool`

HasRemoteDiag returns a boolean if a field has been set.

### GetRequiredMinimumRxInterval

`func (o *ManaV2BfdNeighbor) GetRequiredMinimumRxInterval() int32`

GetRequiredMinimumRxInterval returns the RequiredMinimumRxInterval field if non-nil, zero value otherwise.

### GetRequiredMinimumRxIntervalOk

`func (o *ManaV2BfdNeighbor) GetRequiredMinimumRxIntervalOk() (*int32, bool)`

GetRequiredMinimumRxIntervalOk returns a tuple with the RequiredMinimumRxInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredMinimumRxInterval

`func (o *ManaV2BfdNeighbor) SetRequiredMinimumRxInterval(v int32)`

SetRequiredMinimumRxInterval sets RequiredMinimumRxInterval field to given value.

### HasRequiredMinimumRxInterval

`func (o *ManaV2BfdNeighbor) HasRequiredMinimumRxInterval() bool`

HasRequiredMinimumRxInterval returns a boolean if a field has been set.

### GetSegmentName

`func (o *ManaV2BfdNeighbor) GetSegmentName() string`

GetSegmentName returns the SegmentName field if non-nil, zero value otherwise.

### GetSegmentNameOk

`func (o *ManaV2BfdNeighbor) GetSegmentNameOk() (*string, bool)`

GetSegmentNameOk returns a tuple with the SegmentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentName

`func (o *ManaV2BfdNeighbor) SetSegmentName(v string)`

SetSegmentName sets SegmentName field to given value.

### HasSegmentName

`func (o *ManaV2BfdNeighbor) HasSegmentName() bool`

HasSegmentName returns a boolean if a field has been set.

### GetSourceAddress

`func (o *ManaV2BfdNeighbor) GetSourceAddress() string`

GetSourceAddress returns the SourceAddress field if non-nil, zero value otherwise.

### GetSourceAddressOk

`func (o *ManaV2BfdNeighbor) GetSourceAddressOk() (*string, bool)`

GetSourceAddressOk returns a tuple with the SourceAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAddress

`func (o *ManaV2BfdNeighbor) SetSourceAddress(v string)`

SetSourceAddress sets SourceAddress field to given value.

### HasSourceAddress

`func (o *ManaV2BfdNeighbor) HasSourceAddress() bool`

HasSourceAddress returns a boolean if a field has been set.

### GetState

`func (o *ManaV2BfdNeighbor) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ManaV2BfdNeighbor) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ManaV2BfdNeighbor) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ManaV2BfdNeighbor) HasState() bool`

HasState returns a boolean if a field has been set.

### GetTimeInState

`func (o *ManaV2BfdNeighbor) GetTimeInState() GoogleProtobufDuration`

GetTimeInState returns the TimeInState field if non-nil, zero value otherwise.

### GetTimeInStateOk

`func (o *ManaV2BfdNeighbor) GetTimeInStateOk() (*GoogleProtobufDuration, bool)`

GetTimeInStateOk returns a tuple with the TimeInState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInState

`func (o *ManaV2BfdNeighbor) SetTimeInState(v GoogleProtobufDuration)`

SetTimeInState sets TimeInState field to given value.

### HasTimeInState

`func (o *ManaV2BfdNeighbor) HasTimeInState() bool`

HasTimeInState returns a boolean if a field has been set.

### GetUp

`func (o *ManaV2BfdNeighbor) GetUp() bool`

GetUp returns the Up field if non-nil, zero value otherwise.

### GetUpOk

`func (o *ManaV2BfdNeighbor) GetUpOk() (*bool, bool)`

GetUpOk returns a tuple with the Up field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUp

`func (o *ManaV2BfdNeighbor) SetUp(v bool)`

SetUp sets Up field to given value.

### HasUp

`func (o *ManaV2BfdNeighbor) HasUp() bool`

HasUp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



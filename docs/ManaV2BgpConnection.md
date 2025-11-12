# ManaV2BgpConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LocalAddress** | Pointer to **string** |  | [optional] 
**OperStatus** | Pointer to **bool** |  | [optional] 
**RemoteAddress** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**TimeSinceLastOperChange** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Up** | Pointer to **bool** |  | [optional] 

## Methods

### NewManaV2BgpConnection

`func NewManaV2BgpConnection() *ManaV2BgpConnection`

NewManaV2BgpConnection instantiates a new ManaV2BgpConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BgpConnectionWithDefaults

`func NewManaV2BgpConnectionWithDefaults() *ManaV2BgpConnection`

NewManaV2BgpConnectionWithDefaults instantiates a new ManaV2BgpConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLocalAddress

`func (o *ManaV2BgpConnection) GetLocalAddress() string`

GetLocalAddress returns the LocalAddress field if non-nil, zero value otherwise.

### GetLocalAddressOk

`func (o *ManaV2BgpConnection) GetLocalAddressOk() (*string, bool)`

GetLocalAddressOk returns a tuple with the LocalAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAddress

`func (o *ManaV2BgpConnection) SetLocalAddress(v string)`

SetLocalAddress sets LocalAddress field to given value.

### HasLocalAddress

`func (o *ManaV2BgpConnection) HasLocalAddress() bool`

HasLocalAddress returns a boolean if a field has been set.

### GetOperStatus

`func (o *ManaV2BgpConnection) GetOperStatus() bool`

GetOperStatus returns the OperStatus field if non-nil, zero value otherwise.

### GetOperStatusOk

`func (o *ManaV2BgpConnection) GetOperStatusOk() (*bool, bool)`

GetOperStatusOk returns a tuple with the OperStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperStatus

`func (o *ManaV2BgpConnection) SetOperStatus(v bool)`

SetOperStatus sets OperStatus field to given value.

### HasOperStatus

`func (o *ManaV2BgpConnection) HasOperStatus() bool`

HasOperStatus returns a boolean if a field has been set.

### GetRemoteAddress

`func (o *ManaV2BgpConnection) GetRemoteAddress() string`

GetRemoteAddress returns the RemoteAddress field if non-nil, zero value otherwise.

### GetRemoteAddressOk

`func (o *ManaV2BgpConnection) GetRemoteAddressOk() (*string, bool)`

GetRemoteAddressOk returns a tuple with the RemoteAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteAddress

`func (o *ManaV2BgpConnection) SetRemoteAddress(v string)`

SetRemoteAddress sets RemoteAddress field to given value.

### HasRemoteAddress

`func (o *ManaV2BgpConnection) HasRemoteAddress() bool`

HasRemoteAddress returns a boolean if a field has been set.

### GetState

`func (o *ManaV2BgpConnection) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ManaV2BgpConnection) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ManaV2BgpConnection) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ManaV2BgpConnection) HasState() bool`

HasState returns a boolean if a field has been set.

### GetTimeSinceLastOperChange

`func (o *ManaV2BgpConnection) GetTimeSinceLastOperChange() GoogleProtobufTimestamp`

GetTimeSinceLastOperChange returns the TimeSinceLastOperChange field if non-nil, zero value otherwise.

### GetTimeSinceLastOperChangeOk

`func (o *ManaV2BgpConnection) GetTimeSinceLastOperChangeOk() (*GoogleProtobufTimestamp, bool)`

GetTimeSinceLastOperChangeOk returns a tuple with the TimeSinceLastOperChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSinceLastOperChange

`func (o *ManaV2BgpConnection) SetTimeSinceLastOperChange(v GoogleProtobufTimestamp)`

SetTimeSinceLastOperChange sets TimeSinceLastOperChange field to given value.

### HasTimeSinceLastOperChange

`func (o *ManaV2BgpConnection) HasTimeSinceLastOperChange() bool`

HasTimeSinceLastOperChange returns a boolean if a field has been set.

### GetUp

`func (o *ManaV2BgpConnection) GetUp() bool`

GetUp returns the Up field if non-nil, zero value otherwise.

### GetUpOk

`func (o *ManaV2BgpConnection) GetUpOk() (*bool, bool)`

GetUpOk returns a tuple with the Up field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUp

`func (o *ManaV2BgpConnection) SetUp(v bool)`

SetUp sets Up field to given value.

### HasUp

`func (o *ManaV2BgpConnection) HasUp() bool`

HasUp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



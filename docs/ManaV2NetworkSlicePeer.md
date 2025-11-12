# ManaV2NetworkSlicePeer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpConnection** | Pointer to [**ManaV2BgpConnection**](ManaV2BgpConnection.md) |  | [optional] 
**ConnectionQuality** | Pointer to **string** |  | [optional] 
**DeviceId** | Pointer to **int64** |  | [optional] 
**Gdi** | Pointer to **int32** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**IpsecConnection** | Pointer to [**ManaV2InterfaceTunnel**](ManaV2InterfaceTunnel.md) |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**WanAddresses** | Pointer to **[]string** |  | [optional] 

## Methods

### NewManaV2NetworkSlicePeer

`func NewManaV2NetworkSlicePeer() *ManaV2NetworkSlicePeer`

NewManaV2NetworkSlicePeer instantiates a new ManaV2NetworkSlicePeer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2NetworkSlicePeerWithDefaults

`func NewManaV2NetworkSlicePeerWithDefaults() *ManaV2NetworkSlicePeer`

NewManaV2NetworkSlicePeerWithDefaults instantiates a new ManaV2NetworkSlicePeer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpConnection

`func (o *ManaV2NetworkSlicePeer) GetBgpConnection() ManaV2BgpConnection`

GetBgpConnection returns the BgpConnection field if non-nil, zero value otherwise.

### GetBgpConnectionOk

`func (o *ManaV2NetworkSlicePeer) GetBgpConnectionOk() (*ManaV2BgpConnection, bool)`

GetBgpConnectionOk returns a tuple with the BgpConnection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpConnection

`func (o *ManaV2NetworkSlicePeer) SetBgpConnection(v ManaV2BgpConnection)`

SetBgpConnection sets BgpConnection field to given value.

### HasBgpConnection

`func (o *ManaV2NetworkSlicePeer) HasBgpConnection() bool`

HasBgpConnection returns a boolean if a field has been set.

### GetConnectionQuality

`func (o *ManaV2NetworkSlicePeer) GetConnectionQuality() string`

GetConnectionQuality returns the ConnectionQuality field if non-nil, zero value otherwise.

### GetConnectionQualityOk

`func (o *ManaV2NetworkSlicePeer) GetConnectionQualityOk() (*string, bool)`

GetConnectionQualityOk returns a tuple with the ConnectionQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionQuality

`func (o *ManaV2NetworkSlicePeer) SetConnectionQuality(v string)`

SetConnectionQuality sets ConnectionQuality field to given value.

### HasConnectionQuality

`func (o *ManaV2NetworkSlicePeer) HasConnectionQuality() bool`

HasConnectionQuality returns a boolean if a field has been set.

### GetDeviceId

`func (o *ManaV2NetworkSlicePeer) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *ManaV2NetworkSlicePeer) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *ManaV2NetworkSlicePeer) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *ManaV2NetworkSlicePeer) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetGdi

`func (o *ManaV2NetworkSlicePeer) GetGdi() int32`

GetGdi returns the Gdi field if non-nil, zero value otherwise.

### GetGdiOk

`func (o *ManaV2NetworkSlicePeer) GetGdiOk() (*int32, bool)`

GetGdiOk returns a tuple with the Gdi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdi

`func (o *ManaV2NetworkSlicePeer) SetGdi(v int32)`

SetGdi sets Gdi field to given value.

### HasGdi

`func (o *ManaV2NetworkSlicePeer) HasGdi() bool`

HasGdi returns a boolean if a field has been set.

### GetHostname

`func (o *ManaV2NetworkSlicePeer) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *ManaV2NetworkSlicePeer) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *ManaV2NetworkSlicePeer) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *ManaV2NetworkSlicePeer) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetIpsecConnection

`func (o *ManaV2NetworkSlicePeer) GetIpsecConnection() ManaV2InterfaceTunnel`

GetIpsecConnection returns the IpsecConnection field if non-nil, zero value otherwise.

### GetIpsecConnectionOk

`func (o *ManaV2NetworkSlicePeer) GetIpsecConnectionOk() (*ManaV2InterfaceTunnel, bool)`

GetIpsecConnectionOk returns a tuple with the IpsecConnection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecConnection

`func (o *ManaV2NetworkSlicePeer) SetIpsecConnection(v ManaV2InterfaceTunnel)`

SetIpsecConnection sets IpsecConnection field to given value.

### HasIpsecConnection

`func (o *ManaV2NetworkSlicePeer) HasIpsecConnection() bool`

HasIpsecConnection returns a boolean if a field has been set.

### GetState

`func (o *ManaV2NetworkSlicePeer) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ManaV2NetworkSlicePeer) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ManaV2NetworkSlicePeer) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ManaV2NetworkSlicePeer) HasState() bool`

HasState returns a boolean if a field has been set.

### GetWanAddresses

`func (o *ManaV2NetworkSlicePeer) GetWanAddresses() []string`

GetWanAddresses returns the WanAddresses field if non-nil, zero value otherwise.

### GetWanAddressesOk

`func (o *ManaV2NetworkSlicePeer) GetWanAddressesOk() (*[]string, bool)`

GetWanAddressesOk returns a tuple with the WanAddresses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanAddresses

`func (o *ManaV2NetworkSlicePeer) SetWanAddresses(v []string)`

SetWanAddresses sets WanAddresses field to given value.

### HasWanAddresses

`func (o *ManaV2NetworkSlicePeer) HasWanAddresses() bool`

HasWanAddresses returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2ZoneFirewallPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ip** | Pointer to [**ManaV2IpFirewallPolicy**](ManaV2IpFirewallPolicy.md) |  | [optional] 
**Udp** | Pointer to [**ManaV2UdpFlowTable**](ManaV2UdpFlowTable.md) |  | [optional] 
**ZoneName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2ZoneFirewallPolicy

`func NewManaV2ZoneFirewallPolicy() *ManaV2ZoneFirewallPolicy`

NewManaV2ZoneFirewallPolicy instantiates a new ManaV2ZoneFirewallPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2ZoneFirewallPolicyWithDefaults

`func NewManaV2ZoneFirewallPolicyWithDefaults() *ManaV2ZoneFirewallPolicy`

NewManaV2ZoneFirewallPolicyWithDefaults instantiates a new ManaV2ZoneFirewallPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIp

`func (o *ManaV2ZoneFirewallPolicy) GetIp() ManaV2IpFirewallPolicy`

GetIp returns the Ip field if non-nil, zero value otherwise.

### GetIpOk

`func (o *ManaV2ZoneFirewallPolicy) GetIpOk() (*ManaV2IpFirewallPolicy, bool)`

GetIpOk returns a tuple with the Ip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIp

`func (o *ManaV2ZoneFirewallPolicy) SetIp(v ManaV2IpFirewallPolicy)`

SetIp sets Ip field to given value.

### HasIp

`func (o *ManaV2ZoneFirewallPolicy) HasIp() bool`

HasIp returns a boolean if a field has been set.

### GetUdp

`func (o *ManaV2ZoneFirewallPolicy) GetUdp() ManaV2UdpFlowTable`

GetUdp returns the Udp field if non-nil, zero value otherwise.

### GetUdpOk

`func (o *ManaV2ZoneFirewallPolicy) GetUdpOk() (*ManaV2UdpFlowTable, bool)`

GetUdpOk returns a tuple with the Udp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUdp

`func (o *ManaV2ZoneFirewallPolicy) SetUdp(v ManaV2UdpFlowTable)`

SetUdp sets Udp field to given value.

### HasUdp

`func (o *ManaV2ZoneFirewallPolicy) HasUdp() bool`

HasUdp returns a boolean if a field has been set.

### GetZoneName

`func (o *ManaV2ZoneFirewallPolicy) GetZoneName() string`

GetZoneName returns the ZoneName field if non-nil, zero value otherwise.

### GetZoneNameOk

`func (o *ManaV2ZoneFirewallPolicy) GetZoneNameOk() (*string, bool)`

GetZoneNameOk returns a tuple with the ZoneName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZoneName

`func (o *ManaV2ZoneFirewallPolicy) SetZoneName(v string)`

SetZoneName sets ZoneName field to given value.

### HasZoneName

`func (o *ManaV2ZoneFirewallPolicy) HasZoneName() bool`

HasZoneName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



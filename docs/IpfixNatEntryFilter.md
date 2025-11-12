# IpfixNatEntryFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationIp** | Pointer to **string** |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**InsideLocalIp** | Pointer to **string** |  | [optional] 
**InsideLocalPort** | Pointer to **int32** |  | [optional] 
**NatType** | Pointer to **string** |  | [optional] 
**OutsideGlobalIp** | Pointer to **string** |  | [optional] 
**OutsideGlobalPort** | Pointer to **int32** |  | [optional] 
**VrfIds** | Pointer to **[]int64** |  | [optional] 

## Methods

### NewIpfixNatEntryFilter

`func NewIpfixNatEntryFilter() *IpfixNatEntryFilter`

NewIpfixNatEntryFilter instantiates a new IpfixNatEntryFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixNatEntryFilterWithDefaults

`func NewIpfixNatEntryFilterWithDefaults() *IpfixNatEntryFilter`

NewIpfixNatEntryFilterWithDefaults instantiates a new IpfixNatEntryFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationIp

`func (o *IpfixNatEntryFilter) GetDestinationIp() string`

GetDestinationIp returns the DestinationIp field if non-nil, zero value otherwise.

### GetDestinationIpOk

`func (o *IpfixNatEntryFilter) GetDestinationIpOk() (*string, bool)`

GetDestinationIpOk returns a tuple with the DestinationIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationIp

`func (o *IpfixNatEntryFilter) SetDestinationIp(v string)`

SetDestinationIp sets DestinationIp field to given value.

### HasDestinationIp

`func (o *IpfixNatEntryFilter) HasDestinationIp() bool`

HasDestinationIp returns a boolean if a field has been set.

### GetDestinationPort

`func (o *IpfixNatEntryFilter) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *IpfixNatEntryFilter) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *IpfixNatEntryFilter) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *IpfixNatEntryFilter) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetInsideLocalIp

`func (o *IpfixNatEntryFilter) GetInsideLocalIp() string`

GetInsideLocalIp returns the InsideLocalIp field if non-nil, zero value otherwise.

### GetInsideLocalIpOk

`func (o *IpfixNatEntryFilter) GetInsideLocalIpOk() (*string, bool)`

GetInsideLocalIpOk returns a tuple with the InsideLocalIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideLocalIp

`func (o *IpfixNatEntryFilter) SetInsideLocalIp(v string)`

SetInsideLocalIp sets InsideLocalIp field to given value.

### HasInsideLocalIp

`func (o *IpfixNatEntryFilter) HasInsideLocalIp() bool`

HasInsideLocalIp returns a boolean if a field has been set.

### GetInsideLocalPort

`func (o *IpfixNatEntryFilter) GetInsideLocalPort() int32`

GetInsideLocalPort returns the InsideLocalPort field if non-nil, zero value otherwise.

### GetInsideLocalPortOk

`func (o *IpfixNatEntryFilter) GetInsideLocalPortOk() (*int32, bool)`

GetInsideLocalPortOk returns a tuple with the InsideLocalPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsideLocalPort

`func (o *IpfixNatEntryFilter) SetInsideLocalPort(v int32)`

SetInsideLocalPort sets InsideLocalPort field to given value.

### HasInsideLocalPort

`func (o *IpfixNatEntryFilter) HasInsideLocalPort() bool`

HasInsideLocalPort returns a boolean if a field has been set.

### GetNatType

`func (o *IpfixNatEntryFilter) GetNatType() string`

GetNatType returns the NatType field if non-nil, zero value otherwise.

### GetNatTypeOk

`func (o *IpfixNatEntryFilter) GetNatTypeOk() (*string, bool)`

GetNatTypeOk returns a tuple with the NatType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNatType

`func (o *IpfixNatEntryFilter) SetNatType(v string)`

SetNatType sets NatType field to given value.

### HasNatType

`func (o *IpfixNatEntryFilter) HasNatType() bool`

HasNatType returns a boolean if a field has been set.

### GetOutsideGlobalIp

`func (o *IpfixNatEntryFilter) GetOutsideGlobalIp() string`

GetOutsideGlobalIp returns the OutsideGlobalIp field if non-nil, zero value otherwise.

### GetOutsideGlobalIpOk

`func (o *IpfixNatEntryFilter) GetOutsideGlobalIpOk() (*string, bool)`

GetOutsideGlobalIpOk returns a tuple with the OutsideGlobalIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutsideGlobalIp

`func (o *IpfixNatEntryFilter) SetOutsideGlobalIp(v string)`

SetOutsideGlobalIp sets OutsideGlobalIp field to given value.

### HasOutsideGlobalIp

`func (o *IpfixNatEntryFilter) HasOutsideGlobalIp() bool`

HasOutsideGlobalIp returns a boolean if a field has been set.

### GetOutsideGlobalPort

`func (o *IpfixNatEntryFilter) GetOutsideGlobalPort() int32`

GetOutsideGlobalPort returns the OutsideGlobalPort field if non-nil, zero value otherwise.

### GetOutsideGlobalPortOk

`func (o *IpfixNatEntryFilter) GetOutsideGlobalPortOk() (*int32, bool)`

GetOutsideGlobalPortOk returns a tuple with the OutsideGlobalPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutsideGlobalPort

`func (o *IpfixNatEntryFilter) SetOutsideGlobalPort(v int32)`

SetOutsideGlobalPort sets OutsideGlobalPort field to given value.

### HasOutsideGlobalPort

`func (o *IpfixNatEntryFilter) HasOutsideGlobalPort() bool`

HasOutsideGlobalPort returns a boolean if a field has been set.

### GetVrfIds

`func (o *IpfixNatEntryFilter) GetVrfIds() []int64`

GetVrfIds returns the VrfIds field if non-nil, zero value otherwise.

### GetVrfIdsOk

`func (o *IpfixNatEntryFilter) GetVrfIdsOk() (*[]int64, bool)`

GetVrfIdsOk returns a tuple with the VrfIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfIds

`func (o *IpfixNatEntryFilter) SetVrfIds(v []int64)`

SetVrfIds sets VrfIds field to given value.

### HasVrfIds

`func (o *IpfixNatEntryFilter) HasVrfIds() bool`

HasVrfIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



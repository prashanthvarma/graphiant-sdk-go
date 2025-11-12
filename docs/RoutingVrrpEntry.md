# RoutingVrrpEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressFamily** | Pointer to **string** | type of IP address | [optional] 
**AdvertisementRcvd** | Pointer to **int64** |  | [optional] 
**AdvertisementSent** | Pointer to **int64** |  | [optional] 
**EffectivePriority** | Pointer to **int32** |  | [optional] 
**GroupId** | Pointer to **int32** |  | [optional] 
**IsOwner** | Pointer to **bool** |  | [optional] 
**MasterTransition** | Pointer to **int32** |  | [optional] 
**NewMasterReason** | Pointer to **string** |  | [optional] 
**PriorityZeroPktsRcvd** | Pointer to **int64** |  | [optional] 
**PriorityZeroPktsSent** | Pointer to **int64** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 

## Methods

### NewRoutingVrrpEntry

`func NewRoutingVrrpEntry() *RoutingVrrpEntry`

NewRoutingVrrpEntry instantiates a new RoutingVrrpEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingVrrpEntryWithDefaults

`func NewRoutingVrrpEntryWithDefaults() *RoutingVrrpEntry`

NewRoutingVrrpEntryWithDefaults instantiates a new RoutingVrrpEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressFamily

`func (o *RoutingVrrpEntry) GetAddressFamily() string`

GetAddressFamily returns the AddressFamily field if non-nil, zero value otherwise.

### GetAddressFamilyOk

`func (o *RoutingVrrpEntry) GetAddressFamilyOk() (*string, bool)`

GetAddressFamilyOk returns a tuple with the AddressFamily field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressFamily

`func (o *RoutingVrrpEntry) SetAddressFamily(v string)`

SetAddressFamily sets AddressFamily field to given value.

### HasAddressFamily

`func (o *RoutingVrrpEntry) HasAddressFamily() bool`

HasAddressFamily returns a boolean if a field has been set.

### GetAdvertisementRcvd

`func (o *RoutingVrrpEntry) GetAdvertisementRcvd() int64`

GetAdvertisementRcvd returns the AdvertisementRcvd field if non-nil, zero value otherwise.

### GetAdvertisementRcvdOk

`func (o *RoutingVrrpEntry) GetAdvertisementRcvdOk() (*int64, bool)`

GetAdvertisementRcvdOk returns a tuple with the AdvertisementRcvd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvertisementRcvd

`func (o *RoutingVrrpEntry) SetAdvertisementRcvd(v int64)`

SetAdvertisementRcvd sets AdvertisementRcvd field to given value.

### HasAdvertisementRcvd

`func (o *RoutingVrrpEntry) HasAdvertisementRcvd() bool`

HasAdvertisementRcvd returns a boolean if a field has been set.

### GetAdvertisementSent

`func (o *RoutingVrrpEntry) GetAdvertisementSent() int64`

GetAdvertisementSent returns the AdvertisementSent field if non-nil, zero value otherwise.

### GetAdvertisementSentOk

`func (o *RoutingVrrpEntry) GetAdvertisementSentOk() (*int64, bool)`

GetAdvertisementSentOk returns a tuple with the AdvertisementSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvertisementSent

`func (o *RoutingVrrpEntry) SetAdvertisementSent(v int64)`

SetAdvertisementSent sets AdvertisementSent field to given value.

### HasAdvertisementSent

`func (o *RoutingVrrpEntry) HasAdvertisementSent() bool`

HasAdvertisementSent returns a boolean if a field has been set.

### GetEffectivePriority

`func (o *RoutingVrrpEntry) GetEffectivePriority() int32`

GetEffectivePriority returns the EffectivePriority field if non-nil, zero value otherwise.

### GetEffectivePriorityOk

`func (o *RoutingVrrpEntry) GetEffectivePriorityOk() (*int32, bool)`

GetEffectivePriorityOk returns a tuple with the EffectivePriority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectivePriority

`func (o *RoutingVrrpEntry) SetEffectivePriority(v int32)`

SetEffectivePriority sets EffectivePriority field to given value.

### HasEffectivePriority

`func (o *RoutingVrrpEntry) HasEffectivePriority() bool`

HasEffectivePriority returns a boolean if a field has been set.

### GetGroupId

`func (o *RoutingVrrpEntry) GetGroupId() int32`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *RoutingVrrpEntry) GetGroupIdOk() (*int32, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *RoutingVrrpEntry) SetGroupId(v int32)`

SetGroupId sets GroupId field to given value.

### HasGroupId

`func (o *RoutingVrrpEntry) HasGroupId() bool`

HasGroupId returns a boolean if a field has been set.

### GetIsOwner

`func (o *RoutingVrrpEntry) GetIsOwner() bool`

GetIsOwner returns the IsOwner field if non-nil, zero value otherwise.

### GetIsOwnerOk

`func (o *RoutingVrrpEntry) GetIsOwnerOk() (*bool, bool)`

GetIsOwnerOk returns a tuple with the IsOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOwner

`func (o *RoutingVrrpEntry) SetIsOwner(v bool)`

SetIsOwner sets IsOwner field to given value.

### HasIsOwner

`func (o *RoutingVrrpEntry) HasIsOwner() bool`

HasIsOwner returns a boolean if a field has been set.

### GetMasterTransition

`func (o *RoutingVrrpEntry) GetMasterTransition() int32`

GetMasterTransition returns the MasterTransition field if non-nil, zero value otherwise.

### GetMasterTransitionOk

`func (o *RoutingVrrpEntry) GetMasterTransitionOk() (*int32, bool)`

GetMasterTransitionOk returns a tuple with the MasterTransition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMasterTransition

`func (o *RoutingVrrpEntry) SetMasterTransition(v int32)`

SetMasterTransition sets MasterTransition field to given value.

### HasMasterTransition

`func (o *RoutingVrrpEntry) HasMasterTransition() bool`

HasMasterTransition returns a boolean if a field has been set.

### GetNewMasterReason

`func (o *RoutingVrrpEntry) GetNewMasterReason() string`

GetNewMasterReason returns the NewMasterReason field if non-nil, zero value otherwise.

### GetNewMasterReasonOk

`func (o *RoutingVrrpEntry) GetNewMasterReasonOk() (*string, bool)`

GetNewMasterReasonOk returns a tuple with the NewMasterReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewMasterReason

`func (o *RoutingVrrpEntry) SetNewMasterReason(v string)`

SetNewMasterReason sets NewMasterReason field to given value.

### HasNewMasterReason

`func (o *RoutingVrrpEntry) HasNewMasterReason() bool`

HasNewMasterReason returns a boolean if a field has been set.

### GetPriorityZeroPktsRcvd

`func (o *RoutingVrrpEntry) GetPriorityZeroPktsRcvd() int64`

GetPriorityZeroPktsRcvd returns the PriorityZeroPktsRcvd field if non-nil, zero value otherwise.

### GetPriorityZeroPktsRcvdOk

`func (o *RoutingVrrpEntry) GetPriorityZeroPktsRcvdOk() (*int64, bool)`

GetPriorityZeroPktsRcvdOk returns a tuple with the PriorityZeroPktsRcvd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorityZeroPktsRcvd

`func (o *RoutingVrrpEntry) SetPriorityZeroPktsRcvd(v int64)`

SetPriorityZeroPktsRcvd sets PriorityZeroPktsRcvd field to given value.

### HasPriorityZeroPktsRcvd

`func (o *RoutingVrrpEntry) HasPriorityZeroPktsRcvd() bool`

HasPriorityZeroPktsRcvd returns a boolean if a field has been set.

### GetPriorityZeroPktsSent

`func (o *RoutingVrrpEntry) GetPriorityZeroPktsSent() int64`

GetPriorityZeroPktsSent returns the PriorityZeroPktsSent field if non-nil, zero value otherwise.

### GetPriorityZeroPktsSentOk

`func (o *RoutingVrrpEntry) GetPriorityZeroPktsSentOk() (*int64, bool)`

GetPriorityZeroPktsSentOk returns a tuple with the PriorityZeroPktsSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorityZeroPktsSent

`func (o *RoutingVrrpEntry) SetPriorityZeroPktsSent(v int64)`

SetPriorityZeroPktsSent sets PriorityZeroPktsSent field to given value.

### HasPriorityZeroPktsSent

`func (o *RoutingVrrpEntry) HasPriorityZeroPktsSent() bool`

HasPriorityZeroPktsSent returns a boolean if a field has been set.

### GetState

`func (o *RoutingVrrpEntry) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *RoutingVrrpEntry) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *RoutingVrrpEntry) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *RoutingVrrpEntry) HasState() bool`

HasState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



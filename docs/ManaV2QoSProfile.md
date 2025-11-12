# ManaV2QoSProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | Pointer to **string** |  | [optional] 
**Profile** | Pointer to **string** |  | [optional] 
**Queues** | Pointer to [**[]ManaV2QoSProfileQueue**](ManaV2QoSProfileQueue.md) |  | [optional] 

## Methods

### NewManaV2QoSProfile

`func NewManaV2QoSProfile() *ManaV2QoSProfile`

NewManaV2QoSProfile instantiates a new ManaV2QoSProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2QoSProfileWithDefaults

`func NewManaV2QoSProfileWithDefaults() *ManaV2QoSProfile`

NewManaV2QoSProfileWithDefaults instantiates a new ManaV2QoSProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *ManaV2QoSProfile) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ManaV2QoSProfile) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ManaV2QoSProfile) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *ManaV2QoSProfile) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetProfile

`func (o *ManaV2QoSProfile) GetProfile() string`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *ManaV2QoSProfile) GetProfileOk() (*string, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *ManaV2QoSProfile) SetProfile(v string)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *ManaV2QoSProfile) HasProfile() bool`

HasProfile returns a boolean if a field has been set.

### GetQueues

`func (o *ManaV2QoSProfile) GetQueues() []ManaV2QoSProfileQueue`

GetQueues returns the Queues field if non-nil, zero value otherwise.

### GetQueuesOk

`func (o *ManaV2QoSProfile) GetQueuesOk() (*[]ManaV2QoSProfileQueue, bool)`

GetQueuesOk returns a tuple with the Queues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueues

`func (o *ManaV2QoSProfile) SetQueues(v []ManaV2QoSProfileQueue)`

SetQueues sets Queues field to given value.

### HasQueues

`func (o *ManaV2QoSProfile) HasQueues() bool`

HasQueues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



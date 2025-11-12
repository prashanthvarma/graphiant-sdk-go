# ManaV2GraphiantConnections

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlConnection** | Pointer to [**[]ManaV2IpsecConnection**](ManaV2IpsecConnection.md) |  | [optional] 
**CoreConnection** | Pointer to [**[]ManaV2IpsecConnection**](ManaV2IpsecConnection.md) |  | [optional] 
**ManagementConnection** | Pointer to [**[]ManaV2IpsecConnection**](ManaV2IpsecConnection.md) |  | [optional] 

## Methods

### NewManaV2GraphiantConnections

`func NewManaV2GraphiantConnections() *ManaV2GraphiantConnections`

NewManaV2GraphiantConnections instantiates a new ManaV2GraphiantConnections object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2GraphiantConnectionsWithDefaults

`func NewManaV2GraphiantConnectionsWithDefaults() *ManaV2GraphiantConnections`

NewManaV2GraphiantConnectionsWithDefaults instantiates a new ManaV2GraphiantConnections object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlConnection

`func (o *ManaV2GraphiantConnections) GetControlConnection() []ManaV2IpsecConnection`

GetControlConnection returns the ControlConnection field if non-nil, zero value otherwise.

### GetControlConnectionOk

`func (o *ManaV2GraphiantConnections) GetControlConnectionOk() (*[]ManaV2IpsecConnection, bool)`

GetControlConnectionOk returns a tuple with the ControlConnection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlConnection

`func (o *ManaV2GraphiantConnections) SetControlConnection(v []ManaV2IpsecConnection)`

SetControlConnection sets ControlConnection field to given value.

### HasControlConnection

`func (o *ManaV2GraphiantConnections) HasControlConnection() bool`

HasControlConnection returns a boolean if a field has been set.

### GetCoreConnection

`func (o *ManaV2GraphiantConnections) GetCoreConnection() []ManaV2IpsecConnection`

GetCoreConnection returns the CoreConnection field if non-nil, zero value otherwise.

### GetCoreConnectionOk

`func (o *ManaV2GraphiantConnections) GetCoreConnectionOk() (*[]ManaV2IpsecConnection, bool)`

GetCoreConnectionOk returns a tuple with the CoreConnection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreConnection

`func (o *ManaV2GraphiantConnections) SetCoreConnection(v []ManaV2IpsecConnection)`

SetCoreConnection sets CoreConnection field to given value.

### HasCoreConnection

`func (o *ManaV2GraphiantConnections) HasCoreConnection() bool`

HasCoreConnection returns a boolean if a field has been set.

### GetManagementConnection

`func (o *ManaV2GraphiantConnections) GetManagementConnection() []ManaV2IpsecConnection`

GetManagementConnection returns the ManagementConnection field if non-nil, zero value otherwise.

### GetManagementConnectionOk

`func (o *ManaV2GraphiantConnections) GetManagementConnectionOk() (*[]ManaV2IpsecConnection, bool)`

GetManagementConnectionOk returns a tuple with the ManagementConnection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagementConnection

`func (o *ManaV2GraphiantConnections) SetManagementConnection(v []ManaV2IpsecConnection)`

SetManagementConnection sets ManagementConnection field to given value.

### HasManagementConnection

`func (o *ManaV2GraphiantConnections) HasManagementConnection() bool`

HasManagementConnection returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



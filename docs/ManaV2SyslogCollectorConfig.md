# ManaV2SyslogCollectorConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Host** | Pointer to **string** |  | [optional] 
**InterfaceName** | Pointer to **string** |  | [optional] 
**IsGlobalSync** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Port** | Pointer to **int32** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**Transport** | Pointer to **string** |  | [optional] 
**VrfId** | Pointer to **int64** |  | [optional] 

## Methods

### NewManaV2SyslogCollectorConfig

`func NewManaV2SyslogCollectorConfig() *ManaV2SyslogCollectorConfig`

NewManaV2SyslogCollectorConfig instantiates a new ManaV2SyslogCollectorConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SyslogCollectorConfigWithDefaults

`func NewManaV2SyslogCollectorConfigWithDefaults() *ManaV2SyslogCollectorConfig`

NewManaV2SyslogCollectorConfigWithDefaults instantiates a new ManaV2SyslogCollectorConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *ManaV2SyslogCollectorConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManaV2SyslogCollectorConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManaV2SyslogCollectorConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManaV2SyslogCollectorConfig) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2SyslogCollectorConfig) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2SyslogCollectorConfig) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2SyslogCollectorConfig) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2SyslogCollectorConfig) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetHost

`func (o *ManaV2SyslogCollectorConfig) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *ManaV2SyslogCollectorConfig) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *ManaV2SyslogCollectorConfig) SetHost(v string)`

SetHost sets Host field to given value.

### HasHost

`func (o *ManaV2SyslogCollectorConfig) HasHost() bool`

HasHost returns a boolean if a field has been set.

### GetInterfaceName

`func (o *ManaV2SyslogCollectorConfig) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *ManaV2SyslogCollectorConfig) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *ManaV2SyslogCollectorConfig) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *ManaV2SyslogCollectorConfig) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.

### GetIsGlobalSync

`func (o *ManaV2SyslogCollectorConfig) GetIsGlobalSync() bool`

GetIsGlobalSync returns the IsGlobalSync field if non-nil, zero value otherwise.

### GetIsGlobalSyncOk

`func (o *ManaV2SyslogCollectorConfig) GetIsGlobalSyncOk() (*bool, bool)`

GetIsGlobalSyncOk returns a tuple with the IsGlobalSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobalSync

`func (o *ManaV2SyslogCollectorConfig) SetIsGlobalSync(v bool)`

SetIsGlobalSync sets IsGlobalSync field to given value.

### HasIsGlobalSync

`func (o *ManaV2SyslogCollectorConfig) HasIsGlobalSync() bool`

HasIsGlobalSync returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SyslogCollectorConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SyslogCollectorConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SyslogCollectorConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SyslogCollectorConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPort

`func (o *ManaV2SyslogCollectorConfig) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ManaV2SyslogCollectorConfig) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ManaV2SyslogCollectorConfig) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *ManaV2SyslogCollectorConfig) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetSeverity

`func (o *ManaV2SyslogCollectorConfig) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *ManaV2SyslogCollectorConfig) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *ManaV2SyslogCollectorConfig) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *ManaV2SyslogCollectorConfig) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetTransport

`func (o *ManaV2SyslogCollectorConfig) GetTransport() string`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *ManaV2SyslogCollectorConfig) GetTransportOk() (*string, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *ManaV2SyslogCollectorConfig) SetTransport(v string)`

SetTransport sets Transport field to given value.

### HasTransport

`func (o *ManaV2SyslogCollectorConfig) HasTransport() bool`

HasTransport returns a boolean if a field has been set.

### GetVrfId

`func (o *ManaV2SyslogCollectorConfig) GetVrfId() int64`

GetVrfId returns the VrfId field if non-nil, zero value otherwise.

### GetVrfIdOk

`func (o *ManaV2SyslogCollectorConfig) GetVrfIdOk() (*int64, bool)`

GetVrfIdOk returns a tuple with the VrfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfId

`func (o *ManaV2SyslogCollectorConfig) SetVrfId(v int64)`

SetVrfId sets VrfId field to given value.

### HasVrfId

`func (o *ManaV2SyslogCollectorConfig) HasVrfId() bool`

HasVrfId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



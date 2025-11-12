# ManaV2SyslogCollector

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationHost** | Pointer to **string** |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**SourceInterface** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Transport** | Pointer to **string** |  | [optional] 
**VrfId** | Pointer to **int64** |  | [optional] 
**VrfName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SyslogCollector

`func NewManaV2SyslogCollector() *ManaV2SyslogCollector`

NewManaV2SyslogCollector instantiates a new ManaV2SyslogCollector object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SyslogCollectorWithDefaults

`func NewManaV2SyslogCollectorWithDefaults() *ManaV2SyslogCollector`

NewManaV2SyslogCollectorWithDefaults instantiates a new ManaV2SyslogCollector object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationHost

`func (o *ManaV2SyslogCollector) GetDestinationHost() string`

GetDestinationHost returns the DestinationHost field if non-nil, zero value otherwise.

### GetDestinationHostOk

`func (o *ManaV2SyslogCollector) GetDestinationHostOk() (*string, bool)`

GetDestinationHostOk returns a tuple with the DestinationHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationHost

`func (o *ManaV2SyslogCollector) SetDestinationHost(v string)`

SetDestinationHost sets DestinationHost field to given value.

### HasDestinationHost

`func (o *ManaV2SyslogCollector) HasDestinationHost() bool`

HasDestinationHost returns a boolean if a field has been set.

### GetDestinationPort

`func (o *ManaV2SyslogCollector) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *ManaV2SyslogCollector) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *ManaV2SyslogCollector) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *ManaV2SyslogCollector) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetEnabled

`func (o *ManaV2SyslogCollector) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManaV2SyslogCollector) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManaV2SyslogCollector) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManaV2SyslogCollector) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ManaV2SyslogCollector) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ManaV2SyslogCollector) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ManaV2SyslogCollector) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ManaV2SyslogCollector) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2SyslogCollector) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2SyslogCollector) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2SyslogCollector) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2SyslogCollector) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetId

`func (o *ManaV2SyslogCollector) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2SyslogCollector) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2SyslogCollector) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2SyslogCollector) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2SyslogCollector) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2SyslogCollector) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2SyslogCollector) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2SyslogCollector) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSeverity

`func (o *ManaV2SyslogCollector) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *ManaV2SyslogCollector) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *ManaV2SyslogCollector) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *ManaV2SyslogCollector) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetSourceInterface

`func (o *ManaV2SyslogCollector) GetSourceInterface() string`

GetSourceInterface returns the SourceInterface field if non-nil, zero value otherwise.

### GetSourceInterfaceOk

`func (o *ManaV2SyslogCollector) GetSourceInterfaceOk() (*string, bool)`

GetSourceInterfaceOk returns a tuple with the SourceInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceInterface

`func (o *ManaV2SyslogCollector) SetSourceInterface(v string)`

SetSourceInterface sets SourceInterface field to given value.

### HasSourceInterface

`func (o *ManaV2SyslogCollector) HasSourceInterface() bool`

HasSourceInterface returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2SyslogCollector) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2SyslogCollector) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2SyslogCollector) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2SyslogCollector) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTransport

`func (o *ManaV2SyslogCollector) GetTransport() string`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *ManaV2SyslogCollector) GetTransportOk() (*string, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *ManaV2SyslogCollector) SetTransport(v string)`

SetTransport sets Transport field to given value.

### HasTransport

`func (o *ManaV2SyslogCollector) HasTransport() bool`

HasTransport returns a boolean if a field has been set.

### GetVrfId

`func (o *ManaV2SyslogCollector) GetVrfId() int64`

GetVrfId returns the VrfId field if non-nil, zero value otherwise.

### GetVrfIdOk

`func (o *ManaV2SyslogCollector) GetVrfIdOk() (*int64, bool)`

GetVrfIdOk returns a tuple with the VrfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfId

`func (o *ManaV2SyslogCollector) SetVrfId(v int64)`

SetVrfId sets VrfId field to given value.

### HasVrfId

`func (o *ManaV2SyslogCollector) HasVrfId() bool`

HasVrfId returns a boolean if a field has been set.

### GetVrfName

`func (o *ManaV2SyslogCollector) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *ManaV2SyslogCollector) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *ManaV2SyslogCollector) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *ManaV2SyslogCollector) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



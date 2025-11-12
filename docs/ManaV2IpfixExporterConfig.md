# ManaV2IpfixExporterConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationAddress** | Pointer to **string** |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**IsGlobalSync** | Pointer to **bool** |  | [optional] 
**MonitoredSegments** | Pointer to **[]string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**SampleMode** | Pointer to **string** |  | [optional] 
**SampleRate** | Pointer to **int32** |  | [optional] 
**SourceInterfaceName** | Pointer to **string** |  | [optional] 
**VrfId** | Pointer to **int64** |  | [optional] 

## Methods

### NewManaV2IpfixExporterConfig

`func NewManaV2IpfixExporterConfig() *ManaV2IpfixExporterConfig`

NewManaV2IpfixExporterConfig instantiates a new ManaV2IpfixExporterConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IpfixExporterConfigWithDefaults

`func NewManaV2IpfixExporterConfigWithDefaults() *ManaV2IpfixExporterConfig`

NewManaV2IpfixExporterConfigWithDefaults instantiates a new ManaV2IpfixExporterConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationAddress

`func (o *ManaV2IpfixExporterConfig) GetDestinationAddress() string`

GetDestinationAddress returns the DestinationAddress field if non-nil, zero value otherwise.

### GetDestinationAddressOk

`func (o *ManaV2IpfixExporterConfig) GetDestinationAddressOk() (*string, bool)`

GetDestinationAddressOk returns a tuple with the DestinationAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationAddress

`func (o *ManaV2IpfixExporterConfig) SetDestinationAddress(v string)`

SetDestinationAddress sets DestinationAddress field to given value.

### HasDestinationAddress

`func (o *ManaV2IpfixExporterConfig) HasDestinationAddress() bool`

HasDestinationAddress returns a boolean if a field has been set.

### GetDestinationPort

`func (o *ManaV2IpfixExporterConfig) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *ManaV2IpfixExporterConfig) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *ManaV2IpfixExporterConfig) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *ManaV2IpfixExporterConfig) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2IpfixExporterConfig) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2IpfixExporterConfig) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2IpfixExporterConfig) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2IpfixExporterConfig) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetIsGlobalSync

`func (o *ManaV2IpfixExporterConfig) GetIsGlobalSync() bool`

GetIsGlobalSync returns the IsGlobalSync field if non-nil, zero value otherwise.

### GetIsGlobalSyncOk

`func (o *ManaV2IpfixExporterConfig) GetIsGlobalSyncOk() (*bool, bool)`

GetIsGlobalSyncOk returns a tuple with the IsGlobalSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobalSync

`func (o *ManaV2IpfixExporterConfig) SetIsGlobalSync(v bool)`

SetIsGlobalSync sets IsGlobalSync field to given value.

### HasIsGlobalSync

`func (o *ManaV2IpfixExporterConfig) HasIsGlobalSync() bool`

HasIsGlobalSync returns a boolean if a field has been set.

### GetMonitoredSegments

`func (o *ManaV2IpfixExporterConfig) GetMonitoredSegments() []string`

GetMonitoredSegments returns the MonitoredSegments field if non-nil, zero value otherwise.

### GetMonitoredSegmentsOk

`func (o *ManaV2IpfixExporterConfig) GetMonitoredSegmentsOk() (*[]string, bool)`

GetMonitoredSegmentsOk returns a tuple with the MonitoredSegments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitoredSegments

`func (o *ManaV2IpfixExporterConfig) SetMonitoredSegments(v []string)`

SetMonitoredSegments sets MonitoredSegments field to given value.

### HasMonitoredSegments

`func (o *ManaV2IpfixExporterConfig) HasMonitoredSegments() bool`

HasMonitoredSegments returns a boolean if a field has been set.

### GetName

`func (o *ManaV2IpfixExporterConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2IpfixExporterConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2IpfixExporterConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2IpfixExporterConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSampleMode

`func (o *ManaV2IpfixExporterConfig) GetSampleMode() string`

GetSampleMode returns the SampleMode field if non-nil, zero value otherwise.

### GetSampleModeOk

`func (o *ManaV2IpfixExporterConfig) GetSampleModeOk() (*string, bool)`

GetSampleModeOk returns a tuple with the SampleMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleMode

`func (o *ManaV2IpfixExporterConfig) SetSampleMode(v string)`

SetSampleMode sets SampleMode field to given value.

### HasSampleMode

`func (o *ManaV2IpfixExporterConfig) HasSampleMode() bool`

HasSampleMode returns a boolean if a field has been set.

### GetSampleRate

`func (o *ManaV2IpfixExporterConfig) GetSampleRate() int32`

GetSampleRate returns the SampleRate field if non-nil, zero value otherwise.

### GetSampleRateOk

`func (o *ManaV2IpfixExporterConfig) GetSampleRateOk() (*int32, bool)`

GetSampleRateOk returns a tuple with the SampleRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleRate

`func (o *ManaV2IpfixExporterConfig) SetSampleRate(v int32)`

SetSampleRate sets SampleRate field to given value.

### HasSampleRate

`func (o *ManaV2IpfixExporterConfig) HasSampleRate() bool`

HasSampleRate returns a boolean if a field has been set.

### GetSourceInterfaceName

`func (o *ManaV2IpfixExporterConfig) GetSourceInterfaceName() string`

GetSourceInterfaceName returns the SourceInterfaceName field if non-nil, zero value otherwise.

### GetSourceInterfaceNameOk

`func (o *ManaV2IpfixExporterConfig) GetSourceInterfaceNameOk() (*string, bool)`

GetSourceInterfaceNameOk returns a tuple with the SourceInterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceInterfaceName

`func (o *ManaV2IpfixExporterConfig) SetSourceInterfaceName(v string)`

SetSourceInterfaceName sets SourceInterfaceName field to given value.

### HasSourceInterfaceName

`func (o *ManaV2IpfixExporterConfig) HasSourceInterfaceName() bool`

HasSourceInterfaceName returns a boolean if a field has been set.

### GetVrfId

`func (o *ManaV2IpfixExporterConfig) GetVrfId() int64`

GetVrfId returns the VrfId field if non-nil, zero value otherwise.

### GetVrfIdOk

`func (o *ManaV2IpfixExporterConfig) GetVrfIdOk() (*int64, bool)`

GetVrfIdOk returns a tuple with the VrfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfId

`func (o *ManaV2IpfixExporterConfig) SetVrfId(v int64)`

SetVrfId sets VrfId field to given value.

### HasVrfId

`func (o *ManaV2IpfixExporterConfig) HasVrfId() bool`

HasVrfId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



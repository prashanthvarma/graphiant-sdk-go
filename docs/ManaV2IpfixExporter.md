# ManaV2IpfixExporter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestinationAddress** | Pointer to **string** |  | [optional] 
**DestinationPort** | Pointer to **int32** |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**GlobalId** | Pointer to **int64** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**MonitoredSegments** | Pointer to **[]string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**SampleMode** | Pointer to **string** |  | [optional] 
**SampleRate** | Pointer to **int64** |  | [optional] 
**SourceAddress** | Pointer to **string** |  | [optional] 
**SourceInterface** | Pointer to **string** |  | [optional] 
**SourceSegment** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**VrfId** | Pointer to **int64** |  | [optional] 
**VrfName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2IpfixExporter

`func NewManaV2IpfixExporter() *ManaV2IpfixExporter`

NewManaV2IpfixExporter instantiates a new ManaV2IpfixExporter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2IpfixExporterWithDefaults

`func NewManaV2IpfixExporterWithDefaults() *ManaV2IpfixExporter`

NewManaV2IpfixExporterWithDefaults instantiates a new ManaV2IpfixExporter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestinationAddress

`func (o *ManaV2IpfixExporter) GetDestinationAddress() string`

GetDestinationAddress returns the DestinationAddress field if non-nil, zero value otherwise.

### GetDestinationAddressOk

`func (o *ManaV2IpfixExporter) GetDestinationAddressOk() (*string, bool)`

GetDestinationAddressOk returns a tuple with the DestinationAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationAddress

`func (o *ManaV2IpfixExporter) SetDestinationAddress(v string)`

SetDestinationAddress sets DestinationAddress field to given value.

### HasDestinationAddress

`func (o *ManaV2IpfixExporter) HasDestinationAddress() bool`

HasDestinationAddress returns a boolean if a field has been set.

### GetDestinationPort

`func (o *ManaV2IpfixExporter) GetDestinationPort() int32`

GetDestinationPort returns the DestinationPort field if non-nil, zero value otherwise.

### GetDestinationPortOk

`func (o *ManaV2IpfixExporter) GetDestinationPortOk() (*int32, bool)`

GetDestinationPortOk returns a tuple with the DestinationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationPort

`func (o *ManaV2IpfixExporter) SetDestinationPort(v int32)`

SetDestinationPort sets DestinationPort field to given value.

### HasDestinationPort

`func (o *ManaV2IpfixExporter) HasDestinationPort() bool`

HasDestinationPort returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ManaV2IpfixExporter) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ManaV2IpfixExporter) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ManaV2IpfixExporter) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ManaV2IpfixExporter) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetGlobalId

`func (o *ManaV2IpfixExporter) GetGlobalId() int64`

GetGlobalId returns the GlobalId field if non-nil, zero value otherwise.

### GetGlobalIdOk

`func (o *ManaV2IpfixExporter) GetGlobalIdOk() (*int64, bool)`

GetGlobalIdOk returns a tuple with the GlobalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalId

`func (o *ManaV2IpfixExporter) SetGlobalId(v int64)`

SetGlobalId sets GlobalId field to given value.

### HasGlobalId

`func (o *ManaV2IpfixExporter) HasGlobalId() bool`

HasGlobalId returns a boolean if a field has been set.

### GetId

`func (o *ManaV2IpfixExporter) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2IpfixExporter) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2IpfixExporter) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2IpfixExporter) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMonitoredSegments

`func (o *ManaV2IpfixExporter) GetMonitoredSegments() []string`

GetMonitoredSegments returns the MonitoredSegments field if non-nil, zero value otherwise.

### GetMonitoredSegmentsOk

`func (o *ManaV2IpfixExporter) GetMonitoredSegmentsOk() (*[]string, bool)`

GetMonitoredSegmentsOk returns a tuple with the MonitoredSegments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitoredSegments

`func (o *ManaV2IpfixExporter) SetMonitoredSegments(v []string)`

SetMonitoredSegments sets MonitoredSegments field to given value.

### HasMonitoredSegments

`func (o *ManaV2IpfixExporter) HasMonitoredSegments() bool`

HasMonitoredSegments returns a boolean if a field has been set.

### GetName

`func (o *ManaV2IpfixExporter) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2IpfixExporter) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2IpfixExporter) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2IpfixExporter) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSampleMode

`func (o *ManaV2IpfixExporter) GetSampleMode() string`

GetSampleMode returns the SampleMode field if non-nil, zero value otherwise.

### GetSampleModeOk

`func (o *ManaV2IpfixExporter) GetSampleModeOk() (*string, bool)`

GetSampleModeOk returns a tuple with the SampleMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleMode

`func (o *ManaV2IpfixExporter) SetSampleMode(v string)`

SetSampleMode sets SampleMode field to given value.

### HasSampleMode

`func (o *ManaV2IpfixExporter) HasSampleMode() bool`

HasSampleMode returns a boolean if a field has been set.

### GetSampleRate

`func (o *ManaV2IpfixExporter) GetSampleRate() int64`

GetSampleRate returns the SampleRate field if non-nil, zero value otherwise.

### GetSampleRateOk

`func (o *ManaV2IpfixExporter) GetSampleRateOk() (*int64, bool)`

GetSampleRateOk returns a tuple with the SampleRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleRate

`func (o *ManaV2IpfixExporter) SetSampleRate(v int64)`

SetSampleRate sets SampleRate field to given value.

### HasSampleRate

`func (o *ManaV2IpfixExporter) HasSampleRate() bool`

HasSampleRate returns a boolean if a field has been set.

### GetSourceAddress

`func (o *ManaV2IpfixExporter) GetSourceAddress() string`

GetSourceAddress returns the SourceAddress field if non-nil, zero value otherwise.

### GetSourceAddressOk

`func (o *ManaV2IpfixExporter) GetSourceAddressOk() (*string, bool)`

GetSourceAddressOk returns a tuple with the SourceAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAddress

`func (o *ManaV2IpfixExporter) SetSourceAddress(v string)`

SetSourceAddress sets SourceAddress field to given value.

### HasSourceAddress

`func (o *ManaV2IpfixExporter) HasSourceAddress() bool`

HasSourceAddress returns a boolean if a field has been set.

### GetSourceInterface

`func (o *ManaV2IpfixExporter) GetSourceInterface() string`

GetSourceInterface returns the SourceInterface field if non-nil, zero value otherwise.

### GetSourceInterfaceOk

`func (o *ManaV2IpfixExporter) GetSourceInterfaceOk() (*string, bool)`

GetSourceInterfaceOk returns a tuple with the SourceInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceInterface

`func (o *ManaV2IpfixExporter) SetSourceInterface(v string)`

SetSourceInterface sets SourceInterface field to given value.

### HasSourceInterface

`func (o *ManaV2IpfixExporter) HasSourceInterface() bool`

HasSourceInterface returns a boolean if a field has been set.

### GetSourceSegment

`func (o *ManaV2IpfixExporter) GetSourceSegment() string`

GetSourceSegment returns the SourceSegment field if non-nil, zero value otherwise.

### GetSourceSegmentOk

`func (o *ManaV2IpfixExporter) GetSourceSegmentOk() (*string, bool)`

GetSourceSegmentOk returns a tuple with the SourceSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceSegment

`func (o *ManaV2IpfixExporter) SetSourceSegment(v string)`

SetSourceSegment sets SourceSegment field to given value.

### HasSourceSegment

`func (o *ManaV2IpfixExporter) HasSourceSegment() bool`

HasSourceSegment returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2IpfixExporter) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2IpfixExporter) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2IpfixExporter) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2IpfixExporter) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetVrfId

`func (o *ManaV2IpfixExporter) GetVrfId() int64`

GetVrfId returns the VrfId field if non-nil, zero value otherwise.

### GetVrfIdOk

`func (o *ManaV2IpfixExporter) GetVrfIdOk() (*int64, bool)`

GetVrfIdOk returns a tuple with the VrfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfId

`func (o *ManaV2IpfixExporter) SetVrfId(v int64)`

SetVrfId sets VrfId field to given value.

### HasVrfId

`func (o *ManaV2IpfixExporter) HasVrfId() bool`

HasVrfId returns a boolean if a field has been set.

### GetVrfName

`func (o *ManaV2IpfixExporter) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *ManaV2IpfixExporter) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *ManaV2IpfixExporter) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *ManaV2IpfixExporter) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



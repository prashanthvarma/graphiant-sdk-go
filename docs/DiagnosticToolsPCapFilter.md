# DiagnosticToolsPCapFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | Pointer to [**DiagnosticToolsPrefixPort**](DiagnosticToolsPrefixPort.md) |  | [optional] 
**Dscp** | Pointer to **int32** | Filters the packet capture for the specified DSCP field | [optional] 
**Protocol** | Pointer to **string** | Filters the packet capture for the specified protocol | [optional] 
**Source** | Pointer to [**DiagnosticToolsPrefixPort**](DiagnosticToolsPrefixPort.md) |  | [optional] 

## Methods

### NewDiagnosticToolsPCapFilter

`func NewDiagnosticToolsPCapFilter() *DiagnosticToolsPCapFilter`

NewDiagnosticToolsPCapFilter instantiates a new DiagnosticToolsPCapFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsPCapFilterWithDefaults

`func NewDiagnosticToolsPCapFilterWithDefaults() *DiagnosticToolsPCapFilter`

NewDiagnosticToolsPCapFilterWithDefaults instantiates a new DiagnosticToolsPCapFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *DiagnosticToolsPCapFilter) GetDestination() DiagnosticToolsPrefixPort`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *DiagnosticToolsPCapFilter) GetDestinationOk() (*DiagnosticToolsPrefixPort, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *DiagnosticToolsPCapFilter) SetDestination(v DiagnosticToolsPrefixPort)`

SetDestination sets Destination field to given value.

### HasDestination

`func (o *DiagnosticToolsPCapFilter) HasDestination() bool`

HasDestination returns a boolean if a field has been set.

### GetDscp

`func (o *DiagnosticToolsPCapFilter) GetDscp() int32`

GetDscp returns the Dscp field if non-nil, zero value otherwise.

### GetDscpOk

`func (o *DiagnosticToolsPCapFilter) GetDscpOk() (*int32, bool)`

GetDscpOk returns a tuple with the Dscp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDscp

`func (o *DiagnosticToolsPCapFilter) SetDscp(v int32)`

SetDscp sets Dscp field to given value.

### HasDscp

`func (o *DiagnosticToolsPCapFilter) HasDscp() bool`

HasDscp returns a boolean if a field has been set.

### GetProtocol

`func (o *DiagnosticToolsPCapFilter) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *DiagnosticToolsPCapFilter) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *DiagnosticToolsPCapFilter) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *DiagnosticToolsPCapFilter) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetSource

`func (o *DiagnosticToolsPCapFilter) GetSource() DiagnosticToolsPrefixPort`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *DiagnosticToolsPCapFilter) GetSourceOk() (*DiagnosticToolsPrefixPort, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *DiagnosticToolsPCapFilter) SetSource(v DiagnosticToolsPrefixPort)`

SetSource sets Source field to given value.

### HasSource

`func (o *DiagnosticToolsPCapFilter) HasSource() bool`

HasSource returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



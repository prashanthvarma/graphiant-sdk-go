# DiagnosticToolsRouteLookupResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NexthopAddress** | Pointer to **string** | IPv4 or IPv6 gateway address (required) | [optional] 
**OutgoingInterface** | Pointer to **string** | Interface name (required) | [optional] 
**Prefix** | Pointer to **string** | IPv4 or IPv6 longest matching prefix (required) | [optional] 

## Methods

### NewDiagnosticToolsRouteLookupResult

`func NewDiagnosticToolsRouteLookupResult() *DiagnosticToolsRouteLookupResult`

NewDiagnosticToolsRouteLookupResult instantiates a new DiagnosticToolsRouteLookupResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsRouteLookupResultWithDefaults

`func NewDiagnosticToolsRouteLookupResultWithDefaults() *DiagnosticToolsRouteLookupResult`

NewDiagnosticToolsRouteLookupResultWithDefaults instantiates a new DiagnosticToolsRouteLookupResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNexthopAddress

`func (o *DiagnosticToolsRouteLookupResult) GetNexthopAddress() string`

GetNexthopAddress returns the NexthopAddress field if non-nil, zero value otherwise.

### GetNexthopAddressOk

`func (o *DiagnosticToolsRouteLookupResult) GetNexthopAddressOk() (*string, bool)`

GetNexthopAddressOk returns a tuple with the NexthopAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNexthopAddress

`func (o *DiagnosticToolsRouteLookupResult) SetNexthopAddress(v string)`

SetNexthopAddress sets NexthopAddress field to given value.

### HasNexthopAddress

`func (o *DiagnosticToolsRouteLookupResult) HasNexthopAddress() bool`

HasNexthopAddress returns a boolean if a field has been set.

### GetOutgoingInterface

`func (o *DiagnosticToolsRouteLookupResult) GetOutgoingInterface() string`

GetOutgoingInterface returns the OutgoingInterface field if non-nil, zero value otherwise.

### GetOutgoingInterfaceOk

`func (o *DiagnosticToolsRouteLookupResult) GetOutgoingInterfaceOk() (*string, bool)`

GetOutgoingInterfaceOk returns a tuple with the OutgoingInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutgoingInterface

`func (o *DiagnosticToolsRouteLookupResult) SetOutgoingInterface(v string)`

SetOutgoingInterface sets OutgoingInterface field to given value.

### HasOutgoingInterface

`func (o *DiagnosticToolsRouteLookupResult) HasOutgoingInterface() bool`

HasOutgoingInterface returns a boolean if a field has been set.

### GetPrefix

`func (o *DiagnosticToolsRouteLookupResult) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *DiagnosticToolsRouteLookupResult) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *DiagnosticToolsRouteLookupResult) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.

### HasPrefix

`func (o *DiagnosticToolsRouteLookupResult) HasPrefix() bool`

HasPrefix returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



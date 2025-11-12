# DiagnosticToolsArpEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to [**DiagnosticToolsArpEntryAddress**](DiagnosticToolsArpEntryAddress.md) |  | [optional] 
**AllEntry** | Pointer to **bool** | All IPv4 addresses | [optional] 
**InterfaceName** | Pointer to **string** | Interface Name | [optional] 

## Methods

### NewDiagnosticToolsArpEntry

`func NewDiagnosticToolsArpEntry() *DiagnosticToolsArpEntry`

NewDiagnosticToolsArpEntry instantiates a new DiagnosticToolsArpEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsArpEntryWithDefaults

`func NewDiagnosticToolsArpEntryWithDefaults() *DiagnosticToolsArpEntry`

NewDiagnosticToolsArpEntryWithDefaults instantiates a new DiagnosticToolsArpEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *DiagnosticToolsArpEntry) GetAddress() DiagnosticToolsArpEntryAddress`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *DiagnosticToolsArpEntry) GetAddressOk() (*DiagnosticToolsArpEntryAddress, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *DiagnosticToolsArpEntry) SetAddress(v DiagnosticToolsArpEntryAddress)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *DiagnosticToolsArpEntry) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetAllEntry

`func (o *DiagnosticToolsArpEntry) GetAllEntry() bool`

GetAllEntry returns the AllEntry field if non-nil, zero value otherwise.

### GetAllEntryOk

`func (o *DiagnosticToolsArpEntry) GetAllEntryOk() (*bool, bool)`

GetAllEntryOk returns a tuple with the AllEntry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllEntry

`func (o *DiagnosticToolsArpEntry) SetAllEntry(v bool)`

SetAllEntry sets AllEntry field to given value.

### HasAllEntry

`func (o *DiagnosticToolsArpEntry) HasAllEntry() bool`

HasAllEntry returns a boolean if a field has been set.

### GetInterfaceName

`func (o *DiagnosticToolsArpEntry) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *DiagnosticToolsArpEntry) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *DiagnosticToolsArpEntry) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *DiagnosticToolsArpEntry) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



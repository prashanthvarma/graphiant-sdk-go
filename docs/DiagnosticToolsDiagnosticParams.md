# DiagnosticToolsDiagnosticParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestAddress** | **string** | IPv4 or IPv6 Destination address (required) | 
**HopStatsCount** | Pointer to **int32** | Per hop probes needed for traceroute hop stats | [optional] 
**Interface** | Pointer to **string** | Source Interface name | [optional] 
**PayloadSize** | Pointer to **int32** | Size of  packet to be sent | [optional] 
**Port** | **int32** | Valid in case of TCP ping (required) | 
**ProbeCount** | Pointer to **int32** | Number of probes to send | [optional] 
**SrcAddress** | **string** | IPv4 or IPv6 address (required) | 
**Tos** | Pointer to **int32** | Type of service | [optional] 
**VrfName** | **string** | configure VRF Name (required) | 

## Methods

### NewDiagnosticToolsDiagnosticParams

`func NewDiagnosticToolsDiagnosticParams(destAddress string, port int32, srcAddress string, vrfName string, ) *DiagnosticToolsDiagnosticParams`

NewDiagnosticToolsDiagnosticParams instantiates a new DiagnosticToolsDiagnosticParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsDiagnosticParamsWithDefaults

`func NewDiagnosticToolsDiagnosticParamsWithDefaults() *DiagnosticToolsDiagnosticParams`

NewDiagnosticToolsDiagnosticParamsWithDefaults instantiates a new DiagnosticToolsDiagnosticParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestAddress

`func (o *DiagnosticToolsDiagnosticParams) GetDestAddress() string`

GetDestAddress returns the DestAddress field if non-nil, zero value otherwise.

### GetDestAddressOk

`func (o *DiagnosticToolsDiagnosticParams) GetDestAddressOk() (*string, bool)`

GetDestAddressOk returns a tuple with the DestAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestAddress

`func (o *DiagnosticToolsDiagnosticParams) SetDestAddress(v string)`

SetDestAddress sets DestAddress field to given value.


### GetHopStatsCount

`func (o *DiagnosticToolsDiagnosticParams) GetHopStatsCount() int32`

GetHopStatsCount returns the HopStatsCount field if non-nil, zero value otherwise.

### GetHopStatsCountOk

`func (o *DiagnosticToolsDiagnosticParams) GetHopStatsCountOk() (*int32, bool)`

GetHopStatsCountOk returns a tuple with the HopStatsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHopStatsCount

`func (o *DiagnosticToolsDiagnosticParams) SetHopStatsCount(v int32)`

SetHopStatsCount sets HopStatsCount field to given value.

### HasHopStatsCount

`func (o *DiagnosticToolsDiagnosticParams) HasHopStatsCount() bool`

HasHopStatsCount returns a boolean if a field has been set.

### GetInterface

`func (o *DiagnosticToolsDiagnosticParams) GetInterface() string`

GetInterface returns the Interface field if non-nil, zero value otherwise.

### GetInterfaceOk

`func (o *DiagnosticToolsDiagnosticParams) GetInterfaceOk() (*string, bool)`

GetInterfaceOk returns a tuple with the Interface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterface

`func (o *DiagnosticToolsDiagnosticParams) SetInterface(v string)`

SetInterface sets Interface field to given value.

### HasInterface

`func (o *DiagnosticToolsDiagnosticParams) HasInterface() bool`

HasInterface returns a boolean if a field has been set.

### GetPayloadSize

`func (o *DiagnosticToolsDiagnosticParams) GetPayloadSize() int32`

GetPayloadSize returns the PayloadSize field if non-nil, zero value otherwise.

### GetPayloadSizeOk

`func (o *DiagnosticToolsDiagnosticParams) GetPayloadSizeOk() (*int32, bool)`

GetPayloadSizeOk returns a tuple with the PayloadSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayloadSize

`func (o *DiagnosticToolsDiagnosticParams) SetPayloadSize(v int32)`

SetPayloadSize sets PayloadSize field to given value.

### HasPayloadSize

`func (o *DiagnosticToolsDiagnosticParams) HasPayloadSize() bool`

HasPayloadSize returns a boolean if a field has been set.

### GetPort

`func (o *DiagnosticToolsDiagnosticParams) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *DiagnosticToolsDiagnosticParams) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *DiagnosticToolsDiagnosticParams) SetPort(v int32)`

SetPort sets Port field to given value.


### GetProbeCount

`func (o *DiagnosticToolsDiagnosticParams) GetProbeCount() int32`

GetProbeCount returns the ProbeCount field if non-nil, zero value otherwise.

### GetProbeCountOk

`func (o *DiagnosticToolsDiagnosticParams) GetProbeCountOk() (*int32, bool)`

GetProbeCountOk returns a tuple with the ProbeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProbeCount

`func (o *DiagnosticToolsDiagnosticParams) SetProbeCount(v int32)`

SetProbeCount sets ProbeCount field to given value.

### HasProbeCount

`func (o *DiagnosticToolsDiagnosticParams) HasProbeCount() bool`

HasProbeCount returns a boolean if a field has been set.

### GetSrcAddress

`func (o *DiagnosticToolsDiagnosticParams) GetSrcAddress() string`

GetSrcAddress returns the SrcAddress field if non-nil, zero value otherwise.

### GetSrcAddressOk

`func (o *DiagnosticToolsDiagnosticParams) GetSrcAddressOk() (*string, bool)`

GetSrcAddressOk returns a tuple with the SrcAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSrcAddress

`func (o *DiagnosticToolsDiagnosticParams) SetSrcAddress(v string)`

SetSrcAddress sets SrcAddress field to given value.


### GetTos

`func (o *DiagnosticToolsDiagnosticParams) GetTos() int32`

GetTos returns the Tos field if non-nil, zero value otherwise.

### GetTosOk

`func (o *DiagnosticToolsDiagnosticParams) GetTosOk() (*int32, bool)`

GetTosOk returns a tuple with the Tos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTos

`func (o *DiagnosticToolsDiagnosticParams) SetTos(v int32)`

SetTos sets Tos field to given value.

### HasTos

`func (o *DiagnosticToolsDiagnosticParams) HasTos() bool`

HasTos returns a boolean if a field has been set.

### GetVrfName

`func (o *DiagnosticToolsDiagnosticParams) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *DiagnosticToolsDiagnosticParams) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *DiagnosticToolsDiagnosticParams) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



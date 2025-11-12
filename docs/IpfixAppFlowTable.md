# IpfixAppFlowTable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DestIp** | Pointer to **string** |  | [optional] 
**DestPort** | Pointer to **int32** |  | [optional] 
**DlCircuitName** | Pointer to **string** |  | [optional] 
**DlUsage** | Pointer to **float64** | Down link application usage in MB | [optional] 
**EgressLocalCoreRegion** | Pointer to **string** |  | [optional] 
**IngressLocalCoreRegion** | Pointer to **string** |  | [optional] 
**LanSegment** | Pointer to **string** |  | [optional] 
**Protocol** | Pointer to **string** |  | [optional] 
**RemoteCoreRegion** | Pointer to **string** |  | [optional] 
**SlaClass** | Pointer to **string** |  | [optional] 
**SrcIp** | Pointer to **string** |  | [optional] 
**SrcPort** | Pointer to **int32** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**UlCircuitName** | Pointer to **string** |  | [optional] 
**UlUsage** | Pointer to **float64** | Up link application usage in MB | [optional] 

## Methods

### NewIpfixAppFlowTable

`func NewIpfixAppFlowTable() *IpfixAppFlowTable`

NewIpfixAppFlowTable instantiates a new IpfixAppFlowTable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppFlowTableWithDefaults

`func NewIpfixAppFlowTableWithDefaults() *IpfixAppFlowTable`

NewIpfixAppFlowTableWithDefaults instantiates a new IpfixAppFlowTable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestIp

`func (o *IpfixAppFlowTable) GetDestIp() string`

GetDestIp returns the DestIp field if non-nil, zero value otherwise.

### GetDestIpOk

`func (o *IpfixAppFlowTable) GetDestIpOk() (*string, bool)`

GetDestIpOk returns a tuple with the DestIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestIp

`func (o *IpfixAppFlowTable) SetDestIp(v string)`

SetDestIp sets DestIp field to given value.

### HasDestIp

`func (o *IpfixAppFlowTable) HasDestIp() bool`

HasDestIp returns a boolean if a field has been set.

### GetDestPort

`func (o *IpfixAppFlowTable) GetDestPort() int32`

GetDestPort returns the DestPort field if non-nil, zero value otherwise.

### GetDestPortOk

`func (o *IpfixAppFlowTable) GetDestPortOk() (*int32, bool)`

GetDestPortOk returns a tuple with the DestPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestPort

`func (o *IpfixAppFlowTable) SetDestPort(v int32)`

SetDestPort sets DestPort field to given value.

### HasDestPort

`func (o *IpfixAppFlowTable) HasDestPort() bool`

HasDestPort returns a boolean if a field has been set.

### GetDlCircuitName

`func (o *IpfixAppFlowTable) GetDlCircuitName() string`

GetDlCircuitName returns the DlCircuitName field if non-nil, zero value otherwise.

### GetDlCircuitNameOk

`func (o *IpfixAppFlowTable) GetDlCircuitNameOk() (*string, bool)`

GetDlCircuitNameOk returns a tuple with the DlCircuitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDlCircuitName

`func (o *IpfixAppFlowTable) SetDlCircuitName(v string)`

SetDlCircuitName sets DlCircuitName field to given value.

### HasDlCircuitName

`func (o *IpfixAppFlowTable) HasDlCircuitName() bool`

HasDlCircuitName returns a boolean if a field has been set.

### GetDlUsage

`func (o *IpfixAppFlowTable) GetDlUsage() float64`

GetDlUsage returns the DlUsage field if non-nil, zero value otherwise.

### GetDlUsageOk

`func (o *IpfixAppFlowTable) GetDlUsageOk() (*float64, bool)`

GetDlUsageOk returns a tuple with the DlUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDlUsage

`func (o *IpfixAppFlowTable) SetDlUsage(v float64)`

SetDlUsage sets DlUsage field to given value.

### HasDlUsage

`func (o *IpfixAppFlowTable) HasDlUsage() bool`

HasDlUsage returns a boolean if a field has been set.

### GetEgressLocalCoreRegion

`func (o *IpfixAppFlowTable) GetEgressLocalCoreRegion() string`

GetEgressLocalCoreRegion returns the EgressLocalCoreRegion field if non-nil, zero value otherwise.

### GetEgressLocalCoreRegionOk

`func (o *IpfixAppFlowTable) GetEgressLocalCoreRegionOk() (*string, bool)`

GetEgressLocalCoreRegionOk returns a tuple with the EgressLocalCoreRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEgressLocalCoreRegion

`func (o *IpfixAppFlowTable) SetEgressLocalCoreRegion(v string)`

SetEgressLocalCoreRegion sets EgressLocalCoreRegion field to given value.

### HasEgressLocalCoreRegion

`func (o *IpfixAppFlowTable) HasEgressLocalCoreRegion() bool`

HasEgressLocalCoreRegion returns a boolean if a field has been set.

### GetIngressLocalCoreRegion

`func (o *IpfixAppFlowTable) GetIngressLocalCoreRegion() string`

GetIngressLocalCoreRegion returns the IngressLocalCoreRegion field if non-nil, zero value otherwise.

### GetIngressLocalCoreRegionOk

`func (o *IpfixAppFlowTable) GetIngressLocalCoreRegionOk() (*string, bool)`

GetIngressLocalCoreRegionOk returns a tuple with the IngressLocalCoreRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIngressLocalCoreRegion

`func (o *IpfixAppFlowTable) SetIngressLocalCoreRegion(v string)`

SetIngressLocalCoreRegion sets IngressLocalCoreRegion field to given value.

### HasIngressLocalCoreRegion

`func (o *IpfixAppFlowTable) HasIngressLocalCoreRegion() bool`

HasIngressLocalCoreRegion returns a boolean if a field has been set.

### GetLanSegment

`func (o *IpfixAppFlowTable) GetLanSegment() string`

GetLanSegment returns the LanSegment field if non-nil, zero value otherwise.

### GetLanSegmentOk

`func (o *IpfixAppFlowTable) GetLanSegmentOk() (*string, bool)`

GetLanSegmentOk returns a tuple with the LanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegment

`func (o *IpfixAppFlowTable) SetLanSegment(v string)`

SetLanSegment sets LanSegment field to given value.

### HasLanSegment

`func (o *IpfixAppFlowTable) HasLanSegment() bool`

HasLanSegment returns a boolean if a field has been set.

### GetProtocol

`func (o *IpfixAppFlowTable) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *IpfixAppFlowTable) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *IpfixAppFlowTable) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *IpfixAppFlowTable) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### GetRemoteCoreRegion

`func (o *IpfixAppFlowTable) GetRemoteCoreRegion() string`

GetRemoteCoreRegion returns the RemoteCoreRegion field if non-nil, zero value otherwise.

### GetRemoteCoreRegionOk

`func (o *IpfixAppFlowTable) GetRemoteCoreRegionOk() (*string, bool)`

GetRemoteCoreRegionOk returns a tuple with the RemoteCoreRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteCoreRegion

`func (o *IpfixAppFlowTable) SetRemoteCoreRegion(v string)`

SetRemoteCoreRegion sets RemoteCoreRegion field to given value.

### HasRemoteCoreRegion

`func (o *IpfixAppFlowTable) HasRemoteCoreRegion() bool`

HasRemoteCoreRegion returns a boolean if a field has been set.

### GetSlaClass

`func (o *IpfixAppFlowTable) GetSlaClass() string`

GetSlaClass returns the SlaClass field if non-nil, zero value otherwise.

### GetSlaClassOk

`func (o *IpfixAppFlowTable) GetSlaClassOk() (*string, bool)`

GetSlaClassOk returns a tuple with the SlaClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlaClass

`func (o *IpfixAppFlowTable) SetSlaClass(v string)`

SetSlaClass sets SlaClass field to given value.

### HasSlaClass

`func (o *IpfixAppFlowTable) HasSlaClass() bool`

HasSlaClass returns a boolean if a field has been set.

### GetSrcIp

`func (o *IpfixAppFlowTable) GetSrcIp() string`

GetSrcIp returns the SrcIp field if non-nil, zero value otherwise.

### GetSrcIpOk

`func (o *IpfixAppFlowTable) GetSrcIpOk() (*string, bool)`

GetSrcIpOk returns a tuple with the SrcIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSrcIp

`func (o *IpfixAppFlowTable) SetSrcIp(v string)`

SetSrcIp sets SrcIp field to given value.

### HasSrcIp

`func (o *IpfixAppFlowTable) HasSrcIp() bool`

HasSrcIp returns a boolean if a field has been set.

### GetSrcPort

`func (o *IpfixAppFlowTable) GetSrcPort() int32`

GetSrcPort returns the SrcPort field if non-nil, zero value otherwise.

### GetSrcPortOk

`func (o *IpfixAppFlowTable) GetSrcPortOk() (*int32, bool)`

GetSrcPortOk returns a tuple with the SrcPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSrcPort

`func (o *IpfixAppFlowTable) SetSrcPort(v int32)`

SetSrcPort sets SrcPort field to given value.

### HasSrcPort

`func (o *IpfixAppFlowTable) HasSrcPort() bool`

HasSrcPort returns a boolean if a field has been set.

### GetTs

`func (o *IpfixAppFlowTable) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *IpfixAppFlowTable) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *IpfixAppFlowTable) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *IpfixAppFlowTable) HasTs() bool`

HasTs returns a boolean if a field has been set.

### GetUlCircuitName

`func (o *IpfixAppFlowTable) GetUlCircuitName() string`

GetUlCircuitName returns the UlCircuitName field if non-nil, zero value otherwise.

### GetUlCircuitNameOk

`func (o *IpfixAppFlowTable) GetUlCircuitNameOk() (*string, bool)`

GetUlCircuitNameOk returns a tuple with the UlCircuitName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUlCircuitName

`func (o *IpfixAppFlowTable) SetUlCircuitName(v string)`

SetUlCircuitName sets UlCircuitName field to given value.

### HasUlCircuitName

`func (o *IpfixAppFlowTable) HasUlCircuitName() bool`

HasUlCircuitName returns a boolean if a field has been set.

### GetUlUsage

`func (o *IpfixAppFlowTable) GetUlUsage() float64`

GetUlUsage returns the UlUsage field if non-nil, zero value otherwise.

### GetUlUsageOk

`func (o *IpfixAppFlowTable) GetUlUsageOk() (*float64, bool)`

GetUlUsageOk returns a tuple with the UlUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUlUsage

`func (o *IpfixAppFlowTable) SetUlUsage(v float64)`

SetUlUsage sets UlUsage field to given value.

### HasUlUsage

`func (o *IpfixAppFlowTable) HasUlUsage() bool`

HasUlUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



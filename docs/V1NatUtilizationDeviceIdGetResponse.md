# V1NatUtilizationDeviceIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NatUsage** | Pointer to [**IpfixNatUsage**](IpfixNatUsage.md) |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1NatUtilizationDeviceIdGetResponse

`func NewV1NatUtilizationDeviceIdGetResponse() *V1NatUtilizationDeviceIdGetResponse`

NewV1NatUtilizationDeviceIdGetResponse instantiates a new V1NatUtilizationDeviceIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1NatUtilizationDeviceIdGetResponseWithDefaults

`func NewV1NatUtilizationDeviceIdGetResponseWithDefaults() *V1NatUtilizationDeviceIdGetResponse`

NewV1NatUtilizationDeviceIdGetResponseWithDefaults instantiates a new V1NatUtilizationDeviceIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNatUsage

`func (o *V1NatUtilizationDeviceIdGetResponse) GetNatUsage() IpfixNatUsage`

GetNatUsage returns the NatUsage field if non-nil, zero value otherwise.

### GetNatUsageOk

`func (o *V1NatUtilizationDeviceIdGetResponse) GetNatUsageOk() (*IpfixNatUsage, bool)`

GetNatUsageOk returns a tuple with the NatUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNatUsage

`func (o *V1NatUtilizationDeviceIdGetResponse) SetNatUsage(v IpfixNatUsage)`

SetNatUsage sets NatUsage field to given value.

### HasNatUsage

`func (o *V1NatUtilizationDeviceIdGetResponse) HasNatUsage() bool`

HasNatUsage returns a boolean if a field has been set.

### GetTs

`func (o *V1NatUtilizationDeviceIdGetResponse) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *V1NatUtilizationDeviceIdGetResponse) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *V1NatUtilizationDeviceIdGetResponse) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *V1NatUtilizationDeviceIdGetResponse) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



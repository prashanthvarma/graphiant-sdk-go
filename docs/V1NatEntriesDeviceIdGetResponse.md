# V1NatEntriesDeviceIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NatEntries** | Pointer to [**[]IpfixNatEntry**](IpfixNatEntry.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1NatEntriesDeviceIdGetResponse

`func NewV1NatEntriesDeviceIdGetResponse() *V1NatEntriesDeviceIdGetResponse`

NewV1NatEntriesDeviceIdGetResponse instantiates a new V1NatEntriesDeviceIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1NatEntriesDeviceIdGetResponseWithDefaults

`func NewV1NatEntriesDeviceIdGetResponseWithDefaults() *V1NatEntriesDeviceIdGetResponse`

NewV1NatEntriesDeviceIdGetResponseWithDefaults instantiates a new V1NatEntriesDeviceIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNatEntries

`func (o *V1NatEntriesDeviceIdGetResponse) GetNatEntries() []IpfixNatEntry`

GetNatEntries returns the NatEntries field if non-nil, zero value otherwise.

### GetNatEntriesOk

`func (o *V1NatEntriesDeviceIdGetResponse) GetNatEntriesOk() (*[]IpfixNatEntry, bool)`

GetNatEntriesOk returns a tuple with the NatEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNatEntries

`func (o *V1NatEntriesDeviceIdGetResponse) SetNatEntries(v []IpfixNatEntry)`

SetNatEntries sets NatEntries field to given value.

### HasNatEntries

`func (o *V1NatEntriesDeviceIdGetResponse) HasNatEntries() bool`

HasNatEntries returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1NatEntriesDeviceIdGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1NatEntriesDeviceIdGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1NatEntriesDeviceIdGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1NatEntriesDeviceIdGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetTs

`func (o *V1NatEntriesDeviceIdGetResponse) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *V1NatEntriesDeviceIdGetResponse) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *V1NatEntriesDeviceIdGetResponse) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *V1NatEntriesDeviceIdGetResponse) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



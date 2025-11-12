# V1NatEntriesDeviceIdGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NatFilter** | Pointer to [**IpfixNatEntryFilter**](IpfixNatEntryFilter.md) |  | [optional] 
**PageRequest** | Pointer to [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1NatEntriesDeviceIdGetRequest

`func NewV1NatEntriesDeviceIdGetRequest() *V1NatEntriesDeviceIdGetRequest`

NewV1NatEntriesDeviceIdGetRequest instantiates a new V1NatEntriesDeviceIdGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1NatEntriesDeviceIdGetRequestWithDefaults

`func NewV1NatEntriesDeviceIdGetRequestWithDefaults() *V1NatEntriesDeviceIdGetRequest`

NewV1NatEntriesDeviceIdGetRequestWithDefaults instantiates a new V1NatEntriesDeviceIdGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNatFilter

`func (o *V1NatEntriesDeviceIdGetRequest) GetNatFilter() IpfixNatEntryFilter`

GetNatFilter returns the NatFilter field if non-nil, zero value otherwise.

### GetNatFilterOk

`func (o *V1NatEntriesDeviceIdGetRequest) GetNatFilterOk() (*IpfixNatEntryFilter, bool)`

GetNatFilterOk returns a tuple with the NatFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNatFilter

`func (o *V1NatEntriesDeviceIdGetRequest) SetNatFilter(v IpfixNatEntryFilter)`

SetNatFilter sets NatFilter field to given value.

### HasNatFilter

`func (o *V1NatEntriesDeviceIdGetRequest) HasNatFilter() bool`

HasNatFilter returns a boolean if a field has been set.

### GetPageRequest

`func (o *V1NatEntriesDeviceIdGetRequest) GetPageRequest() CommonPageRequest`

GetPageRequest returns the PageRequest field if non-nil, zero value otherwise.

### GetPageRequestOk

`func (o *V1NatEntriesDeviceIdGetRequest) GetPageRequestOk() (*CommonPageRequest, bool)`

GetPageRequestOk returns a tuple with the PageRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRequest

`func (o *V1NatEntriesDeviceIdGetRequest) SetPageRequest(v CommonPageRequest)`

SetPageRequest sets PageRequest field to given value.

### HasPageRequest

`func (o *V1NatEntriesDeviceIdGetRequest) HasPageRequest() bool`

HasPageRequest returns a boolean if a field has been set.

### GetTs

`func (o *V1NatEntriesDeviceIdGetRequest) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *V1NatEntriesDeviceIdGetRequest) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *V1NatEntriesDeviceIdGetRequest) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *V1NatEntriesDeviceIdGetRequest) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



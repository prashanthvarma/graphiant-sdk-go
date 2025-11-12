# IpfixAppIncidentsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppCount** | Pointer to **int32** | number of apps running in this time bucket | [optional] 
**AppStatus** | Pointer to **string** |  | [optional] 
**Ts** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewIpfixAppIncidentsData

`func NewIpfixAppIncidentsData() *IpfixAppIncidentsData`

NewIpfixAppIncidentsData instantiates a new IpfixAppIncidentsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppIncidentsDataWithDefaults

`func NewIpfixAppIncidentsDataWithDefaults() *IpfixAppIncidentsData`

NewIpfixAppIncidentsDataWithDefaults instantiates a new IpfixAppIncidentsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppCount

`func (o *IpfixAppIncidentsData) GetAppCount() int32`

GetAppCount returns the AppCount field if non-nil, zero value otherwise.

### GetAppCountOk

`func (o *IpfixAppIncidentsData) GetAppCountOk() (*int32, bool)`

GetAppCountOk returns a tuple with the AppCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppCount

`func (o *IpfixAppIncidentsData) SetAppCount(v int32)`

SetAppCount sets AppCount field to given value.

### HasAppCount

`func (o *IpfixAppIncidentsData) HasAppCount() bool`

HasAppCount returns a boolean if a field has been set.

### GetAppStatus

`func (o *IpfixAppIncidentsData) GetAppStatus() string`

GetAppStatus returns the AppStatus field if non-nil, zero value otherwise.

### GetAppStatusOk

`func (o *IpfixAppIncidentsData) GetAppStatusOk() (*string, bool)`

GetAppStatusOk returns a tuple with the AppStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppStatus

`func (o *IpfixAppIncidentsData) SetAppStatus(v string)`

SetAppStatus sets AppStatus field to given value.

### HasAppStatus

`func (o *IpfixAppIncidentsData) HasAppStatus() bool`

HasAppStatus returns a boolean if a field has been set.

### GetTs

`func (o *IpfixAppIncidentsData) GetTs() GoogleProtobufTimestamp`

GetTs returns the Ts field if non-nil, zero value otherwise.

### GetTsOk

`func (o *IpfixAppIncidentsData) GetTsOk() (*GoogleProtobufTimestamp, bool)`

GetTsOk returns a tuple with the Ts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTs

`func (o *IpfixAppIncidentsData) SetTs(v GoogleProtobufTimestamp)`

SetTs sets Ts field to given value.

### HasTs

`func (o *IpfixAppIncidentsData) HasTs() bool`

HasTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



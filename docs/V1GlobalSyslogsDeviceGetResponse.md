# V1GlobalSyslogsDeviceGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Collectors** | Pointer to [**[]ManaV2SyslogCollector**](ManaV2SyslogCollector.md) |  | [optional] 

## Methods

### NewV1GlobalSyslogsDeviceGetResponse

`func NewV1GlobalSyslogsDeviceGetResponse() *V1GlobalSyslogsDeviceGetResponse`

NewV1GlobalSyslogsDeviceGetResponse instantiates a new V1GlobalSyslogsDeviceGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GlobalSyslogsDeviceGetResponseWithDefaults

`func NewV1GlobalSyslogsDeviceGetResponseWithDefaults() *V1GlobalSyslogsDeviceGetResponse`

NewV1GlobalSyslogsDeviceGetResponseWithDefaults instantiates a new V1GlobalSyslogsDeviceGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCollectors

`func (o *V1GlobalSyslogsDeviceGetResponse) GetCollectors() []ManaV2SyslogCollector`

GetCollectors returns the Collectors field if non-nil, zero value otherwise.

### GetCollectorsOk

`func (o *V1GlobalSyslogsDeviceGetResponse) GetCollectorsOk() (*[]ManaV2SyslogCollector, bool)`

GetCollectorsOk returns a tuple with the Collectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectors

`func (o *V1GlobalSyslogsDeviceGetResponse) SetCollectors(v []ManaV2SyslogCollector)`

SetCollectors sets Collectors field to given value.

### HasCollectors

`func (o *V1GlobalSyslogsDeviceGetResponse) HasCollectors() bool`

HasCollectors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



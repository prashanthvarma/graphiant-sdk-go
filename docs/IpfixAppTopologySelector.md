# IpfixAppTopologySelector

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **int32** | Filter by app ID | [optional] 
**AppName** | Pointer to **string** | Filter by application name | [optional] 
**SlaClass** | Pointer to **string** | Filter by SLA class | [optional] 

## Methods

### NewIpfixAppTopologySelector

`func NewIpfixAppTopologySelector() *IpfixAppTopologySelector`

NewIpfixAppTopologySelector instantiates a new IpfixAppTopologySelector object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppTopologySelectorWithDefaults

`func NewIpfixAppTopologySelectorWithDefaults() *IpfixAppTopologySelector`

NewIpfixAppTopologySelectorWithDefaults instantiates a new IpfixAppTopologySelector object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *IpfixAppTopologySelector) GetAppId() int32`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *IpfixAppTopologySelector) GetAppIdOk() (*int32, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *IpfixAppTopologySelector) SetAppId(v int32)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *IpfixAppTopologySelector) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *IpfixAppTopologySelector) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *IpfixAppTopologySelector) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *IpfixAppTopologySelector) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *IpfixAppTopologySelector) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### GetSlaClass

`func (o *IpfixAppTopologySelector) GetSlaClass() string`

GetSlaClass returns the SlaClass field if non-nil, zero value otherwise.

### GetSlaClassOk

`func (o *IpfixAppTopologySelector) GetSlaClassOk() (*string, bool)`

GetSlaClassOk returns a tuple with the SlaClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlaClass

`func (o *IpfixAppTopologySelector) SetSlaClass(v string)`

SetSlaClass sets SlaClass field to given value.

### HasSlaClass

`func (o *IpfixAppTopologySelector) HasSlaClass() bool`

HasSlaClass returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



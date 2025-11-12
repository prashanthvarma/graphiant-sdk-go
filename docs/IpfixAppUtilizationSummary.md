# IpfixAppUtilizationSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **int32** |  | [optional] 
**AppName** | Pointer to **string** |  | [optional] 
**Usage** | Pointer to **int64** | application usage in kilo bytes | [optional] 

## Methods

### NewIpfixAppUtilizationSummary

`func NewIpfixAppUtilizationSummary() *IpfixAppUtilizationSummary`

NewIpfixAppUtilizationSummary instantiates a new IpfixAppUtilizationSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppUtilizationSummaryWithDefaults

`func NewIpfixAppUtilizationSummaryWithDefaults() *IpfixAppUtilizationSummary`

NewIpfixAppUtilizationSummaryWithDefaults instantiates a new IpfixAppUtilizationSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *IpfixAppUtilizationSummary) GetAppId() int32`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *IpfixAppUtilizationSummary) GetAppIdOk() (*int32, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *IpfixAppUtilizationSummary) SetAppId(v int32)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *IpfixAppUtilizationSummary) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *IpfixAppUtilizationSummary) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *IpfixAppUtilizationSummary) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *IpfixAppUtilizationSummary) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *IpfixAppUtilizationSummary) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### GetUsage

`func (o *IpfixAppUtilizationSummary) GetUsage() int64`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *IpfixAppUtilizationSummary) GetUsageOk() (*int64, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *IpfixAppUtilizationSummary) SetUsage(v int64)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *IpfixAppUtilizationSummary) HasUsage() bool`

HasUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



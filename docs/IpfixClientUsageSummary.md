# IpfixClientUsageSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientIpAddress** | Pointer to **string** |  | [optional] 
**Usage** | Pointer to **int64** | data used in kilo bytes | [optional] 

## Methods

### NewIpfixClientUsageSummary

`func NewIpfixClientUsageSummary() *IpfixClientUsageSummary`

NewIpfixClientUsageSummary instantiates a new IpfixClientUsageSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixClientUsageSummaryWithDefaults

`func NewIpfixClientUsageSummaryWithDefaults() *IpfixClientUsageSummary`

NewIpfixClientUsageSummaryWithDefaults instantiates a new IpfixClientUsageSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientIpAddress

`func (o *IpfixClientUsageSummary) GetClientIpAddress() string`

GetClientIpAddress returns the ClientIpAddress field if non-nil, zero value otherwise.

### GetClientIpAddressOk

`func (o *IpfixClientUsageSummary) GetClientIpAddressOk() (*string, bool)`

GetClientIpAddressOk returns a tuple with the ClientIpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIpAddress

`func (o *IpfixClientUsageSummary) SetClientIpAddress(v string)`

SetClientIpAddress sets ClientIpAddress field to given value.

### HasClientIpAddress

`func (o *IpfixClientUsageSummary) HasClientIpAddress() bool`

HasClientIpAddress returns a boolean if a field has been set.

### GetUsage

`func (o *IpfixClientUsageSummary) GetUsage() int64`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *IpfixClientUsageSummary) GetUsageOk() (*int64, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *IpfixClientUsageSummary) SetUsage(v int64)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *IpfixClientUsageSummary) HasUsage() bool`

HasUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



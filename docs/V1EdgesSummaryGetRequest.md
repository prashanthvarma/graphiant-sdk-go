# V1EdgesSummaryGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**Filter** | Pointer to [**SearchSearchFilter**](SearchSearchFilter.md) |  | [optional] 
**IsRequested** | Pointer to **bool** |  | [optional] 
**UpgradeSummary** | Pointer to **bool** |  | [optional] 

## Methods

### NewV1EdgesSummaryGetRequest

`func NewV1EdgesSummaryGetRequest() *V1EdgesSummaryGetRequest`

NewV1EdgesSummaryGetRequest instantiates a new V1EdgesSummaryGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EdgesSummaryGetRequestWithDefaults

`func NewV1EdgesSummaryGetRequestWithDefaults() *V1EdgesSummaryGetRequest`

NewV1EdgesSummaryGetRequestWithDefaults instantiates a new V1EdgesSummaryGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnterpriseId

`func (o *V1EdgesSummaryGetRequest) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *V1EdgesSummaryGetRequest) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *V1EdgesSummaryGetRequest) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *V1EdgesSummaryGetRequest) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetFilter

`func (o *V1EdgesSummaryGetRequest) GetFilter() SearchSearchFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *V1EdgesSummaryGetRequest) GetFilterOk() (*SearchSearchFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *V1EdgesSummaryGetRequest) SetFilter(v SearchSearchFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *V1EdgesSummaryGetRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### GetIsRequested

`func (o *V1EdgesSummaryGetRequest) GetIsRequested() bool`

GetIsRequested returns the IsRequested field if non-nil, zero value otherwise.

### GetIsRequestedOk

`func (o *V1EdgesSummaryGetRequest) GetIsRequestedOk() (*bool, bool)`

GetIsRequestedOk returns a tuple with the IsRequested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRequested

`func (o *V1EdgesSummaryGetRequest) SetIsRequested(v bool)`

SetIsRequested sets IsRequested field to given value.

### HasIsRequested

`func (o *V1EdgesSummaryGetRequest) HasIsRequested() bool`

HasIsRequested returns a boolean if a field has been set.

### GetUpgradeSummary

`func (o *V1EdgesSummaryGetRequest) GetUpgradeSummary() bool`

GetUpgradeSummary returns the UpgradeSummary field if non-nil, zero value otherwise.

### GetUpgradeSummaryOk

`func (o *V1EdgesSummaryGetRequest) GetUpgradeSummaryOk() (*bool, bool)`

GetUpgradeSummaryOk returns a tuple with the UpgradeSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpgradeSummary

`func (o *V1EdgesSummaryGetRequest) SetUpgradeSummary(v bool)`

SetUpgradeSummary sets UpgradeSummary field to given value.

### HasUpgradeSummary

`func (o *V1EdgesSummaryGetRequest) HasUpgradeSummary() bool`

HasUpgradeSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



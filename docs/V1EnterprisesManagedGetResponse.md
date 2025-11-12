# V1EnterprisesManagedGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Counts** | Pointer to [**IamCounts**](IamCounts.md) |  | [optional] 
**Enterprises** | Pointer to [**[]IamEnterprise**](IamEnterprise.md) |  | [optional] 

## Methods

### NewV1EnterprisesManagedGetResponse

`func NewV1EnterprisesManagedGetResponse() *V1EnterprisesManagedGetResponse`

NewV1EnterprisesManagedGetResponse instantiates a new V1EnterprisesManagedGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EnterprisesManagedGetResponseWithDefaults

`func NewV1EnterprisesManagedGetResponseWithDefaults() *V1EnterprisesManagedGetResponse`

NewV1EnterprisesManagedGetResponseWithDefaults instantiates a new V1EnterprisesManagedGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCounts

`func (o *V1EnterprisesManagedGetResponse) GetCounts() IamCounts`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *V1EnterprisesManagedGetResponse) GetCountsOk() (*IamCounts, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *V1EnterprisesManagedGetResponse) SetCounts(v IamCounts)`

SetCounts sets Counts field to given value.

### HasCounts

`func (o *V1EnterprisesManagedGetResponse) HasCounts() bool`

HasCounts returns a boolean if a field has been set.

### GetEnterprises

`func (o *V1EnterprisesManagedGetResponse) GetEnterprises() []IamEnterprise`

GetEnterprises returns the Enterprises field if non-nil, zero value otherwise.

### GetEnterprisesOk

`func (o *V1EnterprisesManagedGetResponse) GetEnterprisesOk() (*[]IamEnterprise, bool)`

GetEnterprisesOk returns a tuple with the Enterprises field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterprises

`func (o *V1EnterprisesManagedGetResponse) SetEnterprises(v []IamEnterprise)`

SetEnterprises sets Enterprises field to given value.

### HasEnterprises

`func (o *V1EnterprisesManagedGetResponse) HasEnterprises() bool`

HasEnterprises returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



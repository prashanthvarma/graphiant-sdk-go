# IamCustomer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminEmail** | Pointer to **string** |  | [optional] 
**CompanyName** | Pointer to **string** |  | [optional] 
**Counts** | Pointer to [**IamCounts**](IamCounts.md) |  | [optional] 
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**ImpersonationEnabled** | Pointer to **bool** |  | [optional] 

## Methods

### NewIamCustomer

`func NewIamCustomer() *IamCustomer`

NewIamCustomer instantiates a new IamCustomer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIamCustomerWithDefaults

`func NewIamCustomerWithDefaults() *IamCustomer`

NewIamCustomerWithDefaults instantiates a new IamCustomer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminEmail

`func (o *IamCustomer) GetAdminEmail() string`

GetAdminEmail returns the AdminEmail field if non-nil, zero value otherwise.

### GetAdminEmailOk

`func (o *IamCustomer) GetAdminEmailOk() (*string, bool)`

GetAdminEmailOk returns a tuple with the AdminEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminEmail

`func (o *IamCustomer) SetAdminEmail(v string)`

SetAdminEmail sets AdminEmail field to given value.

### HasAdminEmail

`func (o *IamCustomer) HasAdminEmail() bool`

HasAdminEmail returns a boolean if a field has been set.

### GetCompanyName

`func (o *IamCustomer) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *IamCustomer) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *IamCustomer) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *IamCustomer) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetCounts

`func (o *IamCustomer) GetCounts() IamCounts`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *IamCustomer) GetCountsOk() (*IamCounts, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *IamCustomer) SetCounts(v IamCounts)`

SetCounts sets Counts field to given value.

### HasCounts

`func (o *IamCustomer) HasCounts() bool`

HasCounts returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *IamCustomer) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *IamCustomer) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *IamCustomer) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *IamCustomer) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetImpersonationEnabled

`func (o *IamCustomer) GetImpersonationEnabled() bool`

GetImpersonationEnabled returns the ImpersonationEnabled field if non-nil, zero value otherwise.

### GetImpersonationEnabledOk

`func (o *IamCustomer) GetImpersonationEnabledOk() (*bool, bool)`

GetImpersonationEnabledOk returns a tuple with the ImpersonationEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpersonationEnabled

`func (o *IamCustomer) SetImpersonationEnabled(v bool)`

SetImpersonationEnabled sets ImpersonationEnabled field to given value.

### HasImpersonationEnabled

`func (o *IamCustomer) HasImpersonationEnabled() bool`

HasImpersonationEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



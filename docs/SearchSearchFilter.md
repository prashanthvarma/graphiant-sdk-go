# SearchSearchFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | Pointer to **string** |  | [optional] 
**SiteName** | Pointer to **string** |  | [optional] 
**Status** | **string** | Status of the device, valid values are staging, active, inactive (required) | 

## Methods

### NewSearchSearchFilter

`func NewSearchSearchFilter(status string, ) *SearchSearchFilter`

NewSearchSearchFilter instantiates a new SearchSearchFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchSearchFilterWithDefaults

`func NewSearchSearchFilterWithDefaults() *SearchSearchFilter`

NewSearchSearchFilterWithDefaults instantiates a new SearchSearchFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *SearchSearchFilter) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *SearchSearchFilter) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *SearchSearchFilter) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *SearchSearchFilter) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetSiteName

`func (o *SearchSearchFilter) GetSiteName() string`

GetSiteName returns the SiteName field if non-nil, zero value otherwise.

### GetSiteNameOk

`func (o *SearchSearchFilter) GetSiteNameOk() (*string, bool)`

GetSiteNameOk returns a tuple with the SiteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteName

`func (o *SearchSearchFilter) SetSiteName(v string)`

SetSiteName sets SiteName field to given value.

### HasSiteName

`func (o *SearchSearchFilter) HasSiteName() bool`

HasSiteName returns a boolean if a field has been set.

### GetStatus

`func (o *SearchSearchFilter) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SearchSearchFilter) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SearchSearchFilter) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



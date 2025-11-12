# V1PolicyApplicationsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Applications** | Pointer to [**[]V1PolicyApplicationsGetResponseApplication**](V1PolicyApplicationsGetResponseApplication.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Methods

### NewV1PolicyApplicationsGetResponse

`func NewV1PolicyApplicationsGetResponse() *V1PolicyApplicationsGetResponse`

NewV1PolicyApplicationsGetResponse instantiates a new V1PolicyApplicationsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1PolicyApplicationsGetResponseWithDefaults

`func NewV1PolicyApplicationsGetResponseWithDefaults() *V1PolicyApplicationsGetResponse`

NewV1PolicyApplicationsGetResponseWithDefaults instantiates a new V1PolicyApplicationsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplications

`func (o *V1PolicyApplicationsGetResponse) GetApplications() []V1PolicyApplicationsGetResponseApplication`

GetApplications returns the Applications field if non-nil, zero value otherwise.

### GetApplicationsOk

`func (o *V1PolicyApplicationsGetResponse) GetApplicationsOk() (*[]V1PolicyApplicationsGetResponseApplication, bool)`

GetApplicationsOk returns a tuple with the Applications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplications

`func (o *V1PolicyApplicationsGetResponse) SetApplications(v []V1PolicyApplicationsGetResponseApplication)`

SetApplications sets Applications field to given value.

### HasApplications

`func (o *V1PolicyApplicationsGetResponse) HasApplications() bool`

HasApplications returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1PolicyApplicationsGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1PolicyApplicationsGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1PolicyApplicationsGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1PolicyApplicationsGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



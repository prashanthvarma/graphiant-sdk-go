# V1DevicesDeviceIdPolicyApplicationsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Applications** | Pointer to [**[]V1DevicesDeviceIdPolicyApplicationsGetResponseApplication**](V1DevicesDeviceIdPolicyApplicationsGetResponseApplication.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Methods

### NewV1DevicesDeviceIdPolicyApplicationsGetResponse

`func NewV1DevicesDeviceIdPolicyApplicationsGetResponse() *V1DevicesDeviceIdPolicyApplicationsGetResponse`

NewV1DevicesDeviceIdPolicyApplicationsGetResponse instantiates a new V1DevicesDeviceIdPolicyApplicationsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdPolicyApplicationsGetResponseWithDefaults

`func NewV1DevicesDeviceIdPolicyApplicationsGetResponseWithDefaults() *V1DevicesDeviceIdPolicyApplicationsGetResponse`

NewV1DevicesDeviceIdPolicyApplicationsGetResponseWithDefaults instantiates a new V1DevicesDeviceIdPolicyApplicationsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplications

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) GetApplications() []V1DevicesDeviceIdPolicyApplicationsGetResponseApplication`

GetApplications returns the Applications field if non-nil, zero value otherwise.

### GetApplicationsOk

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) GetApplicationsOk() (*[]V1DevicesDeviceIdPolicyApplicationsGetResponseApplication, bool)`

GetApplicationsOk returns a tuple with the Applications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplications

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) SetApplications(v []V1DevicesDeviceIdPolicyApplicationsGetResponseApplication)`

SetApplications sets Applications field to given value.

### HasApplications

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) HasApplications() bool`

HasApplications returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DevicesDeviceIdPolicyApplicationsGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



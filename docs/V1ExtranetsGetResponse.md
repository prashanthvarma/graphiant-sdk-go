# V1ExtranetsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Policies** | Pointer to [**[]ManaV2ExtranetPolicy**](ManaV2ExtranetPolicy.md) |  | [optional] 

## Methods

### NewV1ExtranetsGetResponse

`func NewV1ExtranetsGetResponse() *V1ExtranetsGetResponse`

NewV1ExtranetsGetResponse instantiates a new V1ExtranetsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsGetResponseWithDefaults

`func NewV1ExtranetsGetResponseWithDefaults() *V1ExtranetsGetResponse`

NewV1ExtranetsGetResponseWithDefaults instantiates a new V1ExtranetsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageInfo

`func (o *V1ExtranetsGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1ExtranetsGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1ExtranetsGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1ExtranetsGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetPolicies

`func (o *V1ExtranetsGetResponse) GetPolicies() []ManaV2ExtranetPolicy`

GetPolicies returns the Policies field if non-nil, zero value otherwise.

### GetPoliciesOk

`func (o *V1ExtranetsGetResponse) GetPoliciesOk() (*[]ManaV2ExtranetPolicy, bool)`

GetPoliciesOk returns a tuple with the Policies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicies

`func (o *V1ExtranetsGetResponse) SetPolicies(v []ManaV2ExtranetPolicy)`

SetPolicies sets Policies field to given value.

### HasPolicies

`func (o *V1ExtranetsGetResponse) HasPolicies() bool`

HasPolicies returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



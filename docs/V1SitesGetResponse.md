# V1SitesGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Sites** | Pointer to [**[]ManaV2Site**](ManaV2Site.md) |  | [optional] 

## Methods

### NewV1SitesGetResponse

`func NewV1SitesGetResponse() *V1SitesGetResponse`

NewV1SitesGetResponse instantiates a new V1SitesGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1SitesGetResponseWithDefaults

`func NewV1SitesGetResponseWithDefaults() *V1SitesGetResponse`

NewV1SitesGetResponseWithDefaults instantiates a new V1SitesGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageInfo

`func (o *V1SitesGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1SitesGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1SitesGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1SitesGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetSites

`func (o *V1SitesGetResponse) GetSites() []ManaV2Site`

GetSites returns the Sites field if non-nil, zero value otherwise.

### GetSitesOk

`func (o *V1SitesGetResponse) GetSitesOk() (*[]ManaV2Site, bool)`

GetSitesOk returns a tuple with the Sites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSites

`func (o *V1SitesGetResponse) SetSites(v []ManaV2Site)`

SetSites sets Sites field to given value.

### HasSites

`func (o *V1SitesGetResponse) HasSites() bool`

HasSites returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



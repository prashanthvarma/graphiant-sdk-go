# V1LanSegmentsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Segments** | Pointer to [**[]ManaV2Vrf**](ManaV2Vrf.md) |  | [optional] 

## Methods

### NewV1LanSegmentsGetResponse

`func NewV1LanSegmentsGetResponse() *V1LanSegmentsGetResponse`

NewV1LanSegmentsGetResponse instantiates a new V1LanSegmentsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1LanSegmentsGetResponseWithDefaults

`func NewV1LanSegmentsGetResponseWithDefaults() *V1LanSegmentsGetResponse`

NewV1LanSegmentsGetResponseWithDefaults instantiates a new V1LanSegmentsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageInfo

`func (o *V1LanSegmentsGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1LanSegmentsGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1LanSegmentsGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1LanSegmentsGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetSegments

`func (o *V1LanSegmentsGetResponse) GetSegments() []ManaV2Vrf`

GetSegments returns the Segments field if non-nil, zero value otherwise.

### GetSegmentsOk

`func (o *V1LanSegmentsGetResponse) GetSegmentsOk() (*[]ManaV2Vrf, bool)`

GetSegmentsOk returns a tuple with the Segments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegments

`func (o *V1LanSegmentsGetResponse) SetSegments(v []ManaV2Vrf)`

SetSegments sets Segments field to given value.

### HasSegments

`func (o *V1LanSegmentsGetResponse) HasSegments() bool`

HasSegments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



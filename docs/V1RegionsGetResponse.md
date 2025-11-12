# V1RegionsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Regions** | Pointer to [**[]ManaV2Region**](ManaV2Region.md) |  | [optional] 

## Methods

### NewV1RegionsGetResponse

`func NewV1RegionsGetResponse() *V1RegionsGetResponse`

NewV1RegionsGetResponse instantiates a new V1RegionsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1RegionsGetResponseWithDefaults

`func NewV1RegionsGetResponseWithDefaults() *V1RegionsGetResponse`

NewV1RegionsGetResponseWithDefaults instantiates a new V1RegionsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegions

`func (o *V1RegionsGetResponse) GetRegions() []ManaV2Region`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *V1RegionsGetResponse) GetRegionsOk() (*[]ManaV2Region, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *V1RegionsGetResponse) SetRegions(v []ManaV2Region)`

SetRegions sets Regions field to given value.

### HasRegions

`func (o *V1RegionsGetResponse) HasRegions() bool`

HasRegions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1ZonesGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Zones** | Pointer to [**[]ManaV2Zone**](ManaV2Zone.md) |  | [optional] 

## Methods

### NewV1ZonesGetResponse

`func NewV1ZonesGetResponse() *V1ZonesGetResponse`

NewV1ZonesGetResponse instantiates a new V1ZonesGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ZonesGetResponseWithDefaults

`func NewV1ZonesGetResponseWithDefaults() *V1ZonesGetResponse`

NewV1ZonesGetResponseWithDefaults instantiates a new V1ZonesGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageInfo

`func (o *V1ZonesGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1ZonesGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1ZonesGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1ZonesGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetZones

`func (o *V1ZonesGetResponse) GetZones() []ManaV2Zone`

GetZones returns the Zones field if non-nil, zero value otherwise.

### GetZonesOk

`func (o *V1ZonesGetResponse) GetZonesOk() (*[]ManaV2Zone, bool)`

GetZonesOk returns a tuple with the Zones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZones

`func (o *V1ZonesGetResponse) SetZones(v []ManaV2Zone)`

SetZones sets Zones field to given value.

### HasZones

`func (o *V1ZonesGetResponse) HasZones() bool`

HasZones returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DeviceRoutingBgpNbrStatsGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Stats** | Pointer to [**RoutingNbrStats**](RoutingNbrStats.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried,this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingBgpNbrStatsGetResponse

`func NewV1DeviceRoutingBgpNbrStatsGetResponse() *V1DeviceRoutingBgpNbrStatsGetResponse`

NewV1DeviceRoutingBgpNbrStatsGetResponse instantiates a new V1DeviceRoutingBgpNbrStatsGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingBgpNbrStatsGetResponseWithDefaults

`func NewV1DeviceRoutingBgpNbrStatsGetResponseWithDefaults() *V1DeviceRoutingBgpNbrStatsGetResponse`

NewV1DeviceRoutingBgpNbrStatsGetResponseWithDefaults instantiates a new V1DeviceRoutingBgpNbrStatsGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageInfo

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetStats

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) GetStats() RoutingNbrStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) GetStatsOk() (*RoutingNbrStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) SetStats(v RoutingNbrStats)`

SetStats sets Stats field to given value.

### HasStats

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) HasStats() bool`

HasStats returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingBgpNbrStatsGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



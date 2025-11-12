# V1DeviceRoutingOspfv2AreaLsdbGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Lsas** | Pointer to [**[]RoutingOspflsa**](RoutingOspflsa.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingOspfv2AreaLsdbGetResponse

`func NewV1DeviceRoutingOspfv2AreaLsdbGetResponse() *V1DeviceRoutingOspfv2AreaLsdbGetResponse`

NewV1DeviceRoutingOspfv2AreaLsdbGetResponse instantiates a new V1DeviceRoutingOspfv2AreaLsdbGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv2AreaLsdbGetResponseWithDefaults

`func NewV1DeviceRoutingOspfv2AreaLsdbGetResponseWithDefaults() *V1DeviceRoutingOspfv2AreaLsdbGetResponse`

NewV1DeviceRoutingOspfv2AreaLsdbGetResponseWithDefaults instantiates a new V1DeviceRoutingOspfv2AreaLsdbGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLsas

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) GetLsas() []RoutingOspflsa`

GetLsas returns the Lsas field if non-nil, zero value otherwise.

### GetLsasOk

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) GetLsasOk() (*[]RoutingOspflsa, bool)`

GetLsasOk returns a tuple with the Lsas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLsas

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) SetLsas(v []RoutingOspflsa)`

SetLsas sets Lsas field to given value.

### HasLsas

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) HasLsas() bool`

HasLsas returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingOspfv2AreaLsdbGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



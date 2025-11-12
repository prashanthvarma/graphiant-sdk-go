# V1DeviceRoutingOspfv2RibGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Routes** | Pointer to [**[]RoutingOspfRoute**](RoutingOspfRoute.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingOspfv2RibGetResponse

`func NewV1DeviceRoutingOspfv2RibGetResponse() *V1DeviceRoutingOspfv2RibGetResponse`

NewV1DeviceRoutingOspfv2RibGetResponse instantiates a new V1DeviceRoutingOspfv2RibGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv2RibGetResponseWithDefaults

`func NewV1DeviceRoutingOspfv2RibGetResponseWithDefaults() *V1DeviceRoutingOspfv2RibGetResponse`

NewV1DeviceRoutingOspfv2RibGetResponseWithDefaults instantiates a new V1DeviceRoutingOspfv2RibGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPageInfo

`func (o *V1DeviceRoutingOspfv2RibGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingOspfv2RibGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingOspfv2RibGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingOspfv2RibGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetRoutes

`func (o *V1DeviceRoutingOspfv2RibGetResponse) GetRoutes() []RoutingOspfRoute`

GetRoutes returns the Routes field if non-nil, zero value otherwise.

### GetRoutesOk

`func (o *V1DeviceRoutingOspfv2RibGetResponse) GetRoutesOk() (*[]RoutingOspfRoute, bool)`

GetRoutesOk returns a tuple with the Routes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutes

`func (o *V1DeviceRoutingOspfv2RibGetResponse) SetRoutes(v []RoutingOspfRoute)`

SetRoutes sets Routes field to given value.

### HasRoutes

`func (o *V1DeviceRoutingOspfv2RibGetResponse) HasRoutes() bool`

HasRoutes returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingOspfv2RibGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingOspfv2RibGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingOspfv2RibGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingOspfv2RibGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



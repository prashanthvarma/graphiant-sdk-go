# V1DeviceRoutingOspfv2LsdbGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Lsas** | Pointer to [**[]RoutingOspflsa**](RoutingOspflsa.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingOspfv2LsdbGetResponse

`func NewV1DeviceRoutingOspfv2LsdbGetResponse() *V1DeviceRoutingOspfv2LsdbGetResponse`

NewV1DeviceRoutingOspfv2LsdbGetResponse instantiates a new V1DeviceRoutingOspfv2LsdbGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv2LsdbGetResponseWithDefaults

`func NewV1DeviceRoutingOspfv2LsdbGetResponseWithDefaults() *V1DeviceRoutingOspfv2LsdbGetResponse`

NewV1DeviceRoutingOspfv2LsdbGetResponseWithDefaults instantiates a new V1DeviceRoutingOspfv2LsdbGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLsas

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) GetLsas() []RoutingOspflsa`

GetLsas returns the Lsas field if non-nil, zero value otherwise.

### GetLsasOk

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) GetLsasOk() (*[]RoutingOspflsa, bool)`

GetLsasOk returns a tuple with the Lsas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLsas

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) SetLsas(v []RoutingOspflsa)`

SetLsas sets Lsas field to given value.

### HasLsas

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) HasLsas() bool`

HasLsas returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingOspfv2LsdbGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



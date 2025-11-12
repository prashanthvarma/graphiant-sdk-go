# V1DeviceRoutingOspfv3AreaInterfaceGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Interfaces** | Pointer to [**[]RoutingOspfInterface**](RoutingOspfInterface.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingOspfv3AreaInterfaceGetResponse

`func NewV1DeviceRoutingOspfv3AreaInterfaceGetResponse() *V1DeviceRoutingOspfv3AreaInterfaceGetResponse`

NewV1DeviceRoutingOspfv3AreaInterfaceGetResponse instantiates a new V1DeviceRoutingOspfv3AreaInterfaceGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv3AreaInterfaceGetResponseWithDefaults

`func NewV1DeviceRoutingOspfv3AreaInterfaceGetResponseWithDefaults() *V1DeviceRoutingOspfv3AreaInterfaceGetResponse`

NewV1DeviceRoutingOspfv3AreaInterfaceGetResponseWithDefaults instantiates a new V1DeviceRoutingOspfv3AreaInterfaceGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaces

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) GetInterfaces() []RoutingOspfInterface`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) GetInterfacesOk() (*[]RoutingOspfInterface, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) SetInterfaces(v []RoutingOspfInterface)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingOspfv3AreaInterfaceGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DeviceRoutingOspfv3AreaInterfaceidGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Interfaces** | Pointer to **[]string** |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingOspfv3AreaInterfaceidGetResponse

`func NewV1DeviceRoutingOspfv3AreaInterfaceidGetResponse() *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse`

NewV1DeviceRoutingOspfv3AreaInterfaceidGetResponse instantiates a new V1DeviceRoutingOspfv3AreaInterfaceidGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv3AreaInterfaceidGetResponseWithDefaults

`func NewV1DeviceRoutingOspfv3AreaInterfaceidGetResponseWithDefaults() *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse`

NewV1DeviceRoutingOspfv3AreaInterfaceidGetResponseWithDefaults instantiates a new V1DeviceRoutingOspfv3AreaInterfaceidGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaces

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) GetInterfaces() []string`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) GetInterfacesOk() (*[]string, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) SetInterfaces(v []string)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingOspfv3AreaInterfaceidGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



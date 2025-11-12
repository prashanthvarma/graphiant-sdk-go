# V1DeviceRoutingOspfv3AreaidGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Areas** | Pointer to **[]string** |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingOspfv3AreaidGetResponse

`func NewV1DeviceRoutingOspfv3AreaidGetResponse() *V1DeviceRoutingOspfv3AreaidGetResponse`

NewV1DeviceRoutingOspfv3AreaidGetResponse instantiates a new V1DeviceRoutingOspfv3AreaidGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv3AreaidGetResponseWithDefaults

`func NewV1DeviceRoutingOspfv3AreaidGetResponseWithDefaults() *V1DeviceRoutingOspfv3AreaidGetResponse`

NewV1DeviceRoutingOspfv3AreaidGetResponseWithDefaults instantiates a new V1DeviceRoutingOspfv3AreaidGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAreas

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) GetAreas() []string`

GetAreas returns the Areas field if non-nil, zero value otherwise.

### GetAreasOk

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) GetAreasOk() (*[]string, bool)`

GetAreasOk returns a tuple with the Areas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreas

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) SetAreas(v []string)`

SetAreas sets Areas field to given value.

### HasAreas

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) HasAreas() bool`

HasAreas returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingOspfv3AreaidGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



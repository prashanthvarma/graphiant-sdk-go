# V1DeviceRoutingBgpNbridGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Nbrs** | Pointer to **[]string** |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**Token** | Pointer to **string** | Reference to the resultset being queried, this should be sent by the service as part of a previous request and so can be opaque to the client. | [optional] 

## Methods

### NewV1DeviceRoutingBgpNbridGetResponse

`func NewV1DeviceRoutingBgpNbridGetResponse() *V1DeviceRoutingBgpNbridGetResponse`

NewV1DeviceRoutingBgpNbridGetResponse instantiates a new V1DeviceRoutingBgpNbridGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingBgpNbridGetResponseWithDefaults

`func NewV1DeviceRoutingBgpNbridGetResponseWithDefaults() *V1DeviceRoutingBgpNbridGetResponse`

NewV1DeviceRoutingBgpNbridGetResponseWithDefaults instantiates a new V1DeviceRoutingBgpNbridGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNbrs

`func (o *V1DeviceRoutingBgpNbridGetResponse) GetNbrs() []string`

GetNbrs returns the Nbrs field if non-nil, zero value otherwise.

### GetNbrsOk

`func (o *V1DeviceRoutingBgpNbridGetResponse) GetNbrsOk() (*[]string, bool)`

GetNbrsOk returns a tuple with the Nbrs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNbrs

`func (o *V1DeviceRoutingBgpNbridGetResponse) SetNbrs(v []string)`

SetNbrs sets Nbrs field to given value.

### HasNbrs

`func (o *V1DeviceRoutingBgpNbridGetResponse) HasNbrs() bool`

HasNbrs returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DeviceRoutingBgpNbridGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DeviceRoutingBgpNbridGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DeviceRoutingBgpNbridGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DeviceRoutingBgpNbridGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.

### GetToken

`func (o *V1DeviceRoutingBgpNbridGetResponse) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *V1DeviceRoutingBgpNbridGetResponse) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *V1DeviceRoutingBgpNbridGetResponse) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *V1DeviceRoutingBgpNbridGetResponse) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



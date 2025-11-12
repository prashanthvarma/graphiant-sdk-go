# V1DevicesDeviceIdInterfacesGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Interfaces** | Pointer to [**[]ManaV2Interface**](ManaV2Interface.md) |  | [optional] 
**PageInfo** | Pointer to [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Methods

### NewV1DevicesDeviceIdInterfacesGetResponse

`func NewV1DevicesDeviceIdInterfacesGetResponse() *V1DevicesDeviceIdInterfacesGetResponse`

NewV1DevicesDeviceIdInterfacesGetResponse instantiates a new V1DevicesDeviceIdInterfacesGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdInterfacesGetResponseWithDefaults

`func NewV1DevicesDeviceIdInterfacesGetResponseWithDefaults() *V1DevicesDeviceIdInterfacesGetResponse`

NewV1DevicesDeviceIdInterfacesGetResponseWithDefaults instantiates a new V1DevicesDeviceIdInterfacesGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaces

`func (o *V1DevicesDeviceIdInterfacesGetResponse) GetInterfaces() []ManaV2Interface`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *V1DevicesDeviceIdInterfacesGetResponse) GetInterfacesOk() (*[]ManaV2Interface, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *V1DevicesDeviceIdInterfacesGetResponse) SetInterfaces(v []ManaV2Interface)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *V1DevicesDeviceIdInterfacesGetResponse) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetPageInfo

`func (o *V1DevicesDeviceIdInterfacesGetResponse) GetPageInfo() CommonPageInfo`

GetPageInfo returns the PageInfo field if non-nil, zero value otherwise.

### GetPageInfoOk

`func (o *V1DevicesDeviceIdInterfacesGetResponse) GetPageInfoOk() (*CommonPageInfo, bool)`

GetPageInfoOk returns a tuple with the PageInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageInfo

`func (o *V1DevicesDeviceIdInterfacesGetResponse) SetPageInfo(v CommonPageInfo)`

SetPageInfo sets PageInfo field to given value.

### HasPageInfo

`func (o *V1DevicesDeviceIdInterfacesGetResponse) HasPageInfo() bool`

HasPageInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



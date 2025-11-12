# V1DeviceRoutingOspfv2RibGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filter** | Pointer to [**RoutingPrefixFilter**](RoutingPrefixFilter.md) |  | [optional] 
**PageRequest** | Pointer to [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Methods

### NewV1DeviceRoutingOspfv2RibGetRequest

`func NewV1DeviceRoutingOspfv2RibGetRequest() *V1DeviceRoutingOspfv2RibGetRequest`

NewV1DeviceRoutingOspfv2RibGetRequest instantiates a new V1DeviceRoutingOspfv2RibGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingOspfv2RibGetRequestWithDefaults

`func NewV1DeviceRoutingOspfv2RibGetRequestWithDefaults() *V1DeviceRoutingOspfv2RibGetRequest`

NewV1DeviceRoutingOspfv2RibGetRequestWithDefaults instantiates a new V1DeviceRoutingOspfv2RibGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilter

`func (o *V1DeviceRoutingOspfv2RibGetRequest) GetFilter() RoutingPrefixFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *V1DeviceRoutingOspfv2RibGetRequest) GetFilterOk() (*RoutingPrefixFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *V1DeviceRoutingOspfv2RibGetRequest) SetFilter(v RoutingPrefixFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *V1DeviceRoutingOspfv2RibGetRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### GetPageRequest

`func (o *V1DeviceRoutingOspfv2RibGetRequest) GetPageRequest() CommonPageRequest`

GetPageRequest returns the PageRequest field if non-nil, zero value otherwise.

### GetPageRequestOk

`func (o *V1DeviceRoutingOspfv2RibGetRequest) GetPageRequestOk() (*CommonPageRequest, bool)`

GetPageRequestOk returns a tuple with the PageRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRequest

`func (o *V1DeviceRoutingOspfv2RibGetRequest) SetPageRequest(v CommonPageRequest)`

SetPageRequest sets PageRequest field to given value.

### HasPageRequest

`func (o *V1DeviceRoutingOspfv2RibGetRequest) HasPageRequest() bool`

HasPageRequest returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



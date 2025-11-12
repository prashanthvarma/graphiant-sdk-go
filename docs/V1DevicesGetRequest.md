# V1DevicesGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceFilter** | Pointer to [**ManaV2DeviceFilter**](ManaV2DeviceFilter.md) |  | [optional] 
**DeviceRole** | Pointer to **string** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**List** | Pointer to **string** |  | [optional] 
**PageRequest** | Pointer to [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Methods

### NewV1DevicesGetRequest

`func NewV1DevicesGetRequest() *V1DevicesGetRequest`

NewV1DevicesGetRequest instantiates a new V1DevicesGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesGetRequestWithDefaults

`func NewV1DevicesGetRequestWithDefaults() *V1DevicesGetRequest`

NewV1DevicesGetRequestWithDefaults instantiates a new V1DevicesGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceFilter

`func (o *V1DevicesGetRequest) GetDeviceFilter() ManaV2DeviceFilter`

GetDeviceFilter returns the DeviceFilter field if non-nil, zero value otherwise.

### GetDeviceFilterOk

`func (o *V1DevicesGetRequest) GetDeviceFilterOk() (*ManaV2DeviceFilter, bool)`

GetDeviceFilterOk returns a tuple with the DeviceFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceFilter

`func (o *V1DevicesGetRequest) SetDeviceFilter(v ManaV2DeviceFilter)`

SetDeviceFilter sets DeviceFilter field to given value.

### HasDeviceFilter

`func (o *V1DevicesGetRequest) HasDeviceFilter() bool`

HasDeviceFilter returns a boolean if a field has been set.

### GetDeviceRole

`func (o *V1DevicesGetRequest) GetDeviceRole() string`

GetDeviceRole returns the DeviceRole field if non-nil, zero value otherwise.

### GetDeviceRoleOk

`func (o *V1DevicesGetRequest) GetDeviceRoleOk() (*string, bool)`

GetDeviceRoleOk returns a tuple with the DeviceRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceRole

`func (o *V1DevicesGetRequest) SetDeviceRole(v string)`

SetDeviceRole sets DeviceRole field to given value.

### HasDeviceRole

`func (o *V1DevicesGetRequest) HasDeviceRole() bool`

HasDeviceRole returns a boolean if a field has been set.

### GetHostname

`func (o *V1DevicesGetRequest) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *V1DevicesGetRequest) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *V1DevicesGetRequest) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *V1DevicesGetRequest) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetList

`func (o *V1DevicesGetRequest) GetList() string`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *V1DevicesGetRequest) GetListOk() (*string, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *V1DevicesGetRequest) SetList(v string)`

SetList sets List field to given value.

### HasList

`func (o *V1DevicesGetRequest) HasList() bool`

HasList returns a boolean if a field has been set.

### GetPageRequest

`func (o *V1DevicesGetRequest) GetPageRequest() CommonPageRequest`

GetPageRequest returns the PageRequest field if non-nil, zero value otherwise.

### GetPageRequestOk

`func (o *V1DevicesGetRequest) GetPageRequestOk() (*CommonPageRequest, bool)`

GetPageRequestOk returns a tuple with the PageRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRequest

`func (o *V1DevicesGetRequest) SetPageRequest(v CommonPageRequest)`

SetPageRequest sets PageRequest field to given value.

### HasPageRequest

`func (o *V1DevicesGetRequest) HasPageRequest() bool`

HasPageRequest returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



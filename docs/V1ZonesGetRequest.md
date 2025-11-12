# V1ZonesGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Filter** | Pointer to **string** |  | [optional] 
**PageRequest** | Pointer to [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Methods

### NewV1ZonesGetRequest

`func NewV1ZonesGetRequest() *V1ZonesGetRequest`

NewV1ZonesGetRequest instantiates a new V1ZonesGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ZonesGetRequestWithDefaults

`func NewV1ZonesGetRequestWithDefaults() *V1ZonesGetRequest`

NewV1ZonesGetRequestWithDefaults instantiates a new V1ZonesGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V1ZonesGetRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1ZonesGetRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1ZonesGetRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V1ZonesGetRequest) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetFilter

`func (o *V1ZonesGetRequest) GetFilter() string`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *V1ZonesGetRequest) GetFilterOk() (*string, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *V1ZonesGetRequest) SetFilter(v string)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *V1ZonesGetRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### GetPageRequest

`func (o *V1ZonesGetRequest) GetPageRequest() CommonPageRequest`

GetPageRequest returns the PageRequest field if non-nil, zero value otherwise.

### GetPageRequestOk

`func (o *V1ZonesGetRequest) GetPageRequestOk() (*CommonPageRequest, bool)`

GetPageRequestOk returns a tuple with the PageRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRequest

`func (o *V1ZonesGetRequest) SetPageRequest(v CommonPageRequest)`

SetPageRequest sets PageRequest field to given value.

### HasPageRequest

`func (o *V1ZonesGetRequest) HasPageRequest() bool`

HasPageRequest returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesDeviceIdVersionsCompareGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromVersion** | **int32** | 8 bytes (base32 encoded) version number to compare from. (required) | 
**ToVersion** | Pointer to **int32** | 8 bytes (base32 encoded) version number to compare to. If not set, compare with the latest version. | [optional] 

## Methods

### NewV1DevicesDeviceIdVersionsCompareGetRequest

`func NewV1DevicesDeviceIdVersionsCompareGetRequest(fromVersion int32, ) *V1DevicesDeviceIdVersionsCompareGetRequest`

NewV1DevicesDeviceIdVersionsCompareGetRequest instantiates a new V1DevicesDeviceIdVersionsCompareGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesDeviceIdVersionsCompareGetRequestWithDefaults

`func NewV1DevicesDeviceIdVersionsCompareGetRequestWithDefaults() *V1DevicesDeviceIdVersionsCompareGetRequest`

NewV1DevicesDeviceIdVersionsCompareGetRequestWithDefaults instantiates a new V1DevicesDeviceIdVersionsCompareGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromVersion

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) GetFromVersion() int32`

GetFromVersion returns the FromVersion field if non-nil, zero value otherwise.

### GetFromVersionOk

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) GetFromVersionOk() (*int32, bool)`

GetFromVersionOk returns a tuple with the FromVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromVersion

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) SetFromVersion(v int32)`

SetFromVersion sets FromVersion field to given value.


### GetToVersion

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) GetToVersion() int32`

GetToVersion returns the ToVersion field if non-nil, zero value otherwise.

### GetToVersionOk

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) GetToVersionOk() (*int32, bool)`

GetToVersionOk returns a tuple with the ToVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToVersion

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) SetToVersion(v int32)`

SetToVersion sets ToVersion field to given value.

### HasToVersion

`func (o *V1DevicesDeviceIdVersionsCompareGetRequest) HasToVersion() bool`

HasToVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



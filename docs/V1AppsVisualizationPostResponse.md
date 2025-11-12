# V1AppsVisualizationPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppHealth** | Pointer to **map[string]int32** |  | [optional] 
**AppsOnDeviceCount** | Pointer to **int32** |  | [optional] 
**AppsVisualization** | Pointer to [**[]IpfixAppVisualization**](IpfixAppVisualization.md) |  | [optional] 
**AverageQoe** | Pointer to **float64** |  | [optional] 

## Methods

### NewV1AppsVisualizationPostResponse

`func NewV1AppsVisualizationPostResponse() *V1AppsVisualizationPostResponse`

NewV1AppsVisualizationPostResponse instantiates a new V1AppsVisualizationPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AppsVisualizationPostResponseWithDefaults

`func NewV1AppsVisualizationPostResponseWithDefaults() *V1AppsVisualizationPostResponse`

NewV1AppsVisualizationPostResponseWithDefaults instantiates a new V1AppsVisualizationPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppHealth

`func (o *V1AppsVisualizationPostResponse) GetAppHealth() map[string]int32`

GetAppHealth returns the AppHealth field if non-nil, zero value otherwise.

### GetAppHealthOk

`func (o *V1AppsVisualizationPostResponse) GetAppHealthOk() (*map[string]int32, bool)`

GetAppHealthOk returns a tuple with the AppHealth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppHealth

`func (o *V1AppsVisualizationPostResponse) SetAppHealth(v map[string]int32)`

SetAppHealth sets AppHealth field to given value.

### HasAppHealth

`func (o *V1AppsVisualizationPostResponse) HasAppHealth() bool`

HasAppHealth returns a boolean if a field has been set.

### GetAppsOnDeviceCount

`func (o *V1AppsVisualizationPostResponse) GetAppsOnDeviceCount() int32`

GetAppsOnDeviceCount returns the AppsOnDeviceCount field if non-nil, zero value otherwise.

### GetAppsOnDeviceCountOk

`func (o *V1AppsVisualizationPostResponse) GetAppsOnDeviceCountOk() (*int32, bool)`

GetAppsOnDeviceCountOk returns a tuple with the AppsOnDeviceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppsOnDeviceCount

`func (o *V1AppsVisualizationPostResponse) SetAppsOnDeviceCount(v int32)`

SetAppsOnDeviceCount sets AppsOnDeviceCount field to given value.

### HasAppsOnDeviceCount

`func (o *V1AppsVisualizationPostResponse) HasAppsOnDeviceCount() bool`

HasAppsOnDeviceCount returns a boolean if a field has been set.

### GetAppsVisualization

`func (o *V1AppsVisualizationPostResponse) GetAppsVisualization() []IpfixAppVisualization`

GetAppsVisualization returns the AppsVisualization field if non-nil, zero value otherwise.

### GetAppsVisualizationOk

`func (o *V1AppsVisualizationPostResponse) GetAppsVisualizationOk() (*[]IpfixAppVisualization, bool)`

GetAppsVisualizationOk returns a tuple with the AppsVisualization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppsVisualization

`func (o *V1AppsVisualizationPostResponse) SetAppsVisualization(v []IpfixAppVisualization)`

SetAppsVisualization sets AppsVisualization field to given value.

### HasAppsVisualization

`func (o *V1AppsVisualizationPostResponse) HasAppsVisualization() bool`

HasAppsVisualization returns a boolean if a field has been set.

### GetAverageQoe

`func (o *V1AppsVisualizationPostResponse) GetAverageQoe() float64`

GetAverageQoe returns the AverageQoe field if non-nil, zero value otherwise.

### GetAverageQoeOk

`func (o *V1AppsVisualizationPostResponse) GetAverageQoeOk() (*float64, bool)`

GetAverageQoeOk returns a tuple with the AverageQoe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageQoe

`func (o *V1AppsVisualizationPostResponse) SetAverageQoe(v float64)`

SetAverageQoe sets AverageQoe field to given value.

### HasAverageQoe

`func (o *V1AppsVisualizationPostResponse) HasAverageQoe() bool`

HasAverageQoe returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# IpfixAppVisualization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **int32** |  | [optional] 
**AppName** | Pointer to **string** |  | [optional] 
**CircuitAvailability** | Pointer to **map[string]int32** |  | [optional] 
**CircuitMap** | Pointer to [**map[string]IpfixCircuitMetrics**](IpfixCircuitMetrics.md) |  | [optional] 
**CurrentStatus** | Pointer to **string** | current status of the app. | [optional] 

## Methods

### NewIpfixAppVisualization

`func NewIpfixAppVisualization() *IpfixAppVisualization`

NewIpfixAppVisualization instantiates a new IpfixAppVisualization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpfixAppVisualizationWithDefaults

`func NewIpfixAppVisualizationWithDefaults() *IpfixAppVisualization`

NewIpfixAppVisualizationWithDefaults instantiates a new IpfixAppVisualization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *IpfixAppVisualization) GetAppId() int32`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *IpfixAppVisualization) GetAppIdOk() (*int32, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *IpfixAppVisualization) SetAppId(v int32)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *IpfixAppVisualization) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *IpfixAppVisualization) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *IpfixAppVisualization) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *IpfixAppVisualization) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *IpfixAppVisualization) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### GetCircuitAvailability

`func (o *IpfixAppVisualization) GetCircuitAvailability() map[string]int32`

GetCircuitAvailability returns the CircuitAvailability field if non-nil, zero value otherwise.

### GetCircuitAvailabilityOk

`func (o *IpfixAppVisualization) GetCircuitAvailabilityOk() (*map[string]int32, bool)`

GetCircuitAvailabilityOk returns a tuple with the CircuitAvailability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitAvailability

`func (o *IpfixAppVisualization) SetCircuitAvailability(v map[string]int32)`

SetCircuitAvailability sets CircuitAvailability field to given value.

### HasCircuitAvailability

`func (o *IpfixAppVisualization) HasCircuitAvailability() bool`

HasCircuitAvailability returns a boolean if a field has been set.

### GetCircuitMap

`func (o *IpfixAppVisualization) GetCircuitMap() map[string]IpfixCircuitMetrics`

GetCircuitMap returns the CircuitMap field if non-nil, zero value otherwise.

### GetCircuitMapOk

`func (o *IpfixAppVisualization) GetCircuitMapOk() (*map[string]IpfixCircuitMetrics, bool)`

GetCircuitMapOk returns a tuple with the CircuitMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitMap

`func (o *IpfixAppVisualization) SetCircuitMap(v map[string]IpfixCircuitMetrics)`

SetCircuitMap sets CircuitMap field to given value.

### HasCircuitMap

`func (o *IpfixAppVisualization) HasCircuitMap() bool`

HasCircuitMap returns a boolean if a field has been set.

### GetCurrentStatus

`func (o *IpfixAppVisualization) GetCurrentStatus() string`

GetCurrentStatus returns the CurrentStatus field if non-nil, zero value otherwise.

### GetCurrentStatusOk

`func (o *IpfixAppVisualization) GetCurrentStatusOk() (*string, bool)`

GetCurrentStatusOk returns a tuple with the CurrentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStatus

`func (o *IpfixAppVisualization) SetCurrentStatus(v string)`

SetCurrentStatus sets CurrentStatus field to given value.

### HasCurrentStatus

`func (o *IpfixAppVisualization) HasCurrentStatus() bool`

HasCurrentStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



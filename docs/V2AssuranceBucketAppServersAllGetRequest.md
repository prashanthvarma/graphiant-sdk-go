# V2AssuranceBucketAppServersAllGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppServers** | Pointer to [**[]AssuranceBucketAppServerList**](AssuranceBucketAppServerList.md) |  | [optional] 
**TimeWindow** | Pointer to [**AssuranceTimeWindow**](AssuranceTimeWindow.md) |  | [optional] 

## Methods

### NewV2AssuranceBucketAppServersAllGetRequest

`func NewV2AssuranceBucketAppServersAllGetRequest() *V2AssuranceBucketAppServersAllGetRequest`

NewV2AssuranceBucketAppServersAllGetRequest instantiates a new V2AssuranceBucketAppServersAllGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssuranceBucketAppServersAllGetRequestWithDefaults

`func NewV2AssuranceBucketAppServersAllGetRequestWithDefaults() *V2AssuranceBucketAppServersAllGetRequest`

NewV2AssuranceBucketAppServersAllGetRequestWithDefaults instantiates a new V2AssuranceBucketAppServersAllGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppServers

`func (o *V2AssuranceBucketAppServersAllGetRequest) GetAppServers() []AssuranceBucketAppServerList`

GetAppServers returns the AppServers field if non-nil, zero value otherwise.

### GetAppServersOk

`func (o *V2AssuranceBucketAppServersAllGetRequest) GetAppServersOk() (*[]AssuranceBucketAppServerList, bool)`

GetAppServersOk returns a tuple with the AppServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppServers

`func (o *V2AssuranceBucketAppServersAllGetRequest) SetAppServers(v []AssuranceBucketAppServerList)`

SetAppServers sets AppServers field to given value.

### HasAppServers

`func (o *V2AssuranceBucketAppServersAllGetRequest) HasAppServers() bool`

HasAppServers returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V2AssuranceBucketAppServersAllGetRequest) GetTimeWindow() AssuranceTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V2AssuranceBucketAppServersAllGetRequest) GetTimeWindowOk() (*AssuranceTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V2AssuranceBucketAppServersAllGetRequest) SetTimeWindow(v AssuranceTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V2AssuranceBucketAppServersAllGetRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1AppsSiteSiteIdTopPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NumApps** | Pointer to **int32** | The maximum number of apps to return (100 if left empty) | [optional] 
**TimeWindow** | Pointer to [**IpfixTimeWindow**](IpfixTimeWindow.md) |  | [optional] 

## Methods

### NewV1AppsSiteSiteIdTopPostRequest

`func NewV1AppsSiteSiteIdTopPostRequest() *V1AppsSiteSiteIdTopPostRequest`

NewV1AppsSiteSiteIdTopPostRequest instantiates a new V1AppsSiteSiteIdTopPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AppsSiteSiteIdTopPostRequestWithDefaults

`func NewV1AppsSiteSiteIdTopPostRequestWithDefaults() *V1AppsSiteSiteIdTopPostRequest`

NewV1AppsSiteSiteIdTopPostRequestWithDefaults instantiates a new V1AppsSiteSiteIdTopPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumApps

`func (o *V1AppsSiteSiteIdTopPostRequest) GetNumApps() int32`

GetNumApps returns the NumApps field if non-nil, zero value otherwise.

### GetNumAppsOk

`func (o *V1AppsSiteSiteIdTopPostRequest) GetNumAppsOk() (*int32, bool)`

GetNumAppsOk returns a tuple with the NumApps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumApps

`func (o *V1AppsSiteSiteIdTopPostRequest) SetNumApps(v int32)`

SetNumApps sets NumApps field to given value.

### HasNumApps

`func (o *V1AppsSiteSiteIdTopPostRequest) HasNumApps() bool`

HasNumApps returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1AppsSiteSiteIdTopPostRequest) GetTimeWindow() IpfixTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1AppsSiteSiteIdTopPostRequest) GetTimeWindowOk() (*IpfixTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1AppsSiteSiteIdTopPostRequest) SetTimeWindow(v IpfixTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1AppsSiteSiteIdTopPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



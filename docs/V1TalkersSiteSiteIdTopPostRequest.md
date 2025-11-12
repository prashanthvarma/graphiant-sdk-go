# V1TalkersSiteSiteIdTopPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NumClients** | Pointer to **int32** | The maximum number of apps to return (10 if left empty) | [optional] 
**TimeWindow** | Pointer to [**IpfixTimeWindow**](IpfixTimeWindow.md) |  | [optional] 

## Methods

### NewV1TalkersSiteSiteIdTopPostRequest

`func NewV1TalkersSiteSiteIdTopPostRequest() *V1TalkersSiteSiteIdTopPostRequest`

NewV1TalkersSiteSiteIdTopPostRequest instantiates a new V1TalkersSiteSiteIdTopPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1TalkersSiteSiteIdTopPostRequestWithDefaults

`func NewV1TalkersSiteSiteIdTopPostRequestWithDefaults() *V1TalkersSiteSiteIdTopPostRequest`

NewV1TalkersSiteSiteIdTopPostRequestWithDefaults instantiates a new V1TalkersSiteSiteIdTopPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumClients

`func (o *V1TalkersSiteSiteIdTopPostRequest) GetNumClients() int32`

GetNumClients returns the NumClients field if non-nil, zero value otherwise.

### GetNumClientsOk

`func (o *V1TalkersSiteSiteIdTopPostRequest) GetNumClientsOk() (*int32, bool)`

GetNumClientsOk returns a tuple with the NumClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumClients

`func (o *V1TalkersSiteSiteIdTopPostRequest) SetNumClients(v int32)`

SetNumClients sets NumClients field to given value.

### HasNumClients

`func (o *V1TalkersSiteSiteIdTopPostRequest) HasNumClients() bool`

HasNumClients returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1TalkersSiteSiteIdTopPostRequest) GetTimeWindow() IpfixTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1TalkersSiteSiteIdTopPostRequest) GetTimeWindowOk() (*IpfixTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1TalkersSiteSiteIdTopPostRequest) SetTimeWindow(v IpfixTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1TalkersSiteSiteIdTopPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



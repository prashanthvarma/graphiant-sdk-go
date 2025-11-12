# V1EventEnterpriseGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EnterpriseId** | **int64** | Well known enterprise_id (required) | 
**Filter** | Pointer to [**EventEventFilter**](EventEventFilter.md) |  | [optional] 

## Methods

### NewV1EventEnterpriseGetRequest

`func NewV1EventEnterpriseGetRequest(enterpriseId int64, ) *V1EventEnterpriseGetRequest`

NewV1EventEnterpriseGetRequest instantiates a new V1EventEnterpriseGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1EventEnterpriseGetRequestWithDefaults

`func NewV1EventEnterpriseGetRequestWithDefaults() *V1EventEnterpriseGetRequest`

NewV1EventEnterpriseGetRequestWithDefaults instantiates a new V1EventEnterpriseGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnterpriseId

`func (o *V1EventEnterpriseGetRequest) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *V1EventEnterpriseGetRequest) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *V1EventEnterpriseGetRequest) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.


### GetFilter

`func (o *V1EventEnterpriseGetRequest) GetFilter() EventEventFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *V1EventEnterpriseGetRequest) GetFilterOk() (*EventEventFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *V1EventEnterpriseGetRequest) SetFilter(v EventEventFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *V1EventEnterpriseGetRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



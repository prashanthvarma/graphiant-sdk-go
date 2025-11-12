# V1TempPasswordPutRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerName** | Pointer to **string** |  | [optional] 
**Emails** | **[]string** |  | 
**MatchId** | Pointer to **int64** |  | [optional] 
**ServiceName** | Pointer to **string** |  | [optional] 

## Methods

### NewV1TempPasswordPutRequest

`func NewV1TempPasswordPutRequest(emails []string, ) *V1TempPasswordPutRequest`

NewV1TempPasswordPutRequest instantiates a new V1TempPasswordPutRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1TempPasswordPutRequestWithDefaults

`func NewV1TempPasswordPutRequestWithDefaults() *V1TempPasswordPutRequest`

NewV1TempPasswordPutRequestWithDefaults instantiates a new V1TempPasswordPutRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerName

`func (o *V1TempPasswordPutRequest) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *V1TempPasswordPutRequest) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *V1TempPasswordPutRequest) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *V1TempPasswordPutRequest) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetEmails

`func (o *V1TempPasswordPutRequest) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *V1TempPasswordPutRequest) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *V1TempPasswordPutRequest) SetEmails(v []string)`

SetEmails sets Emails field to given value.


### GetMatchId

`func (o *V1TempPasswordPutRequest) GetMatchId() int64`

GetMatchId returns the MatchId field if non-nil, zero value otherwise.

### GetMatchIdOk

`func (o *V1TempPasswordPutRequest) GetMatchIdOk() (*int64, bool)`

GetMatchIdOk returns a tuple with the MatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchId

`func (o *V1TempPasswordPutRequest) SetMatchId(v int64)`

SetMatchId sets MatchId field to given value.

### HasMatchId

`func (o *V1TempPasswordPutRequest) HasMatchId() bool`

HasMatchId returns a boolean if a field has been set.

### GetServiceName

`func (o *V1TempPasswordPutRequest) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *V1TempPasswordPutRequest) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *V1TempPasswordPutRequest) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *V1TempPasswordPutRequest) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1AuthLoginTempPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**TempPassword** | **string** |  | 
**MatchId** | **float32** |  | 

## Methods

### NewV1AuthLoginTempPostRequest

`func NewV1AuthLoginTempPostRequest(email string, tempPassword string, matchId float32, ) *V1AuthLoginTempPostRequest`

NewV1AuthLoginTempPostRequest instantiates a new V1AuthLoginTempPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthLoginTempPostRequestWithDefaults

`func NewV1AuthLoginTempPostRequestWithDefaults() *V1AuthLoginTempPostRequest`

NewV1AuthLoginTempPostRequestWithDefaults instantiates a new V1AuthLoginTempPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *V1AuthLoginTempPostRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *V1AuthLoginTempPostRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *V1AuthLoginTempPostRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetTempPassword

`func (o *V1AuthLoginTempPostRequest) GetTempPassword() string`

GetTempPassword returns the TempPassword field if non-nil, zero value otherwise.

### GetTempPasswordOk

`func (o *V1AuthLoginTempPostRequest) GetTempPasswordOk() (*string, bool)`

GetTempPasswordOk returns a tuple with the TempPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTempPassword

`func (o *V1AuthLoginTempPostRequest) SetTempPassword(v string)`

SetTempPassword sets TempPassword field to given value.


### GetMatchId

`func (o *V1AuthLoginTempPostRequest) GetMatchId() float32`

GetMatchId returns the MatchId field if non-nil, zero value otherwise.

### GetMatchIdOk

`func (o *V1AuthLoginTempPostRequest) GetMatchIdOk() (*float32, bool)`

GetMatchIdOk returns a tuple with the MatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchId

`func (o *V1AuthLoginTempPostRequest) SetMatchId(v float32)`

SetMatchId sets MatchId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesBringupTokenPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | Pointer to **string** |  | [optional] 
**ValidTillTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1DevicesBringupTokenPostResponse

`func NewV1DevicesBringupTokenPostResponse() *V1DevicesBringupTokenPostResponse`

NewV1DevicesBringupTokenPostResponse instantiates a new V1DevicesBringupTokenPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesBringupTokenPostResponseWithDefaults

`func NewV1DevicesBringupTokenPostResponseWithDefaults() *V1DevicesBringupTokenPostResponse`

NewV1DevicesBringupTokenPostResponseWithDefaults instantiates a new V1DevicesBringupTokenPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *V1DevicesBringupTokenPostResponse) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *V1DevicesBringupTokenPostResponse) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *V1DevicesBringupTokenPostResponse) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.

### HasAccessToken

`func (o *V1DevicesBringupTokenPostResponse) HasAccessToken() bool`

HasAccessToken returns a boolean if a field has been set.

### GetValidTillTs

`func (o *V1DevicesBringupTokenPostResponse) GetValidTillTs() GoogleProtobufTimestamp`

GetValidTillTs returns the ValidTillTs field if non-nil, zero value otherwise.

### GetValidTillTsOk

`func (o *V1DevicesBringupTokenPostResponse) GetValidTillTsOk() (*GoogleProtobufTimestamp, bool)`

GetValidTillTsOk returns a tuple with the ValidTillTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidTillTs

`func (o *V1DevicesBringupTokenPostResponse) SetValidTillTs(v GoogleProtobufTimestamp)`

SetValidTillTs sets ValidTillTs field to given value.

### HasValidTillTs

`func (o *V1DevicesBringupTokenPostResponse) HasValidTillTs() bool`

HasValidTillTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



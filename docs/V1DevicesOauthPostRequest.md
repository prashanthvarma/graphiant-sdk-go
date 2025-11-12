# V1DevicesOauthPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GrantType** | **string** | OAuth grant type | 
**Scope** | **string** | OAuth scope containing device type, UUID, and hostname | 
**State** | Pointer to **string** | OAuth state parameter | [optional] 
**CodeVerify** | Pointer to **string** | OAuth code verifier | [optional] 
**Pt** | Pointer to **string** | Platform type | [optional] 
**Bm** | Pointer to **string** | Boot mode | [optional] 

## Methods

### NewV1DevicesOauthPostRequest

`func NewV1DevicesOauthPostRequest(grantType string, scope string, ) *V1DevicesOauthPostRequest`

NewV1DevicesOauthPostRequest instantiates a new V1DevicesOauthPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesOauthPostRequestWithDefaults

`func NewV1DevicesOauthPostRequestWithDefaults() *V1DevicesOauthPostRequest`

NewV1DevicesOauthPostRequestWithDefaults instantiates a new V1DevicesOauthPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGrantType

`func (o *V1DevicesOauthPostRequest) GetGrantType() string`

GetGrantType returns the GrantType field if non-nil, zero value otherwise.

### GetGrantTypeOk

`func (o *V1DevicesOauthPostRequest) GetGrantTypeOk() (*string, bool)`

GetGrantTypeOk returns a tuple with the GrantType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantType

`func (o *V1DevicesOauthPostRequest) SetGrantType(v string)`

SetGrantType sets GrantType field to given value.


### GetScope

`func (o *V1DevicesOauthPostRequest) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *V1DevicesOauthPostRequest) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *V1DevicesOauthPostRequest) SetScope(v string)`

SetScope sets Scope field to given value.


### GetState

`func (o *V1DevicesOauthPostRequest) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *V1DevicesOauthPostRequest) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *V1DevicesOauthPostRequest) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *V1DevicesOauthPostRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetCodeVerify

`func (o *V1DevicesOauthPostRequest) GetCodeVerify() string`

GetCodeVerify returns the CodeVerify field if non-nil, zero value otherwise.

### GetCodeVerifyOk

`func (o *V1DevicesOauthPostRequest) GetCodeVerifyOk() (*string, bool)`

GetCodeVerifyOk returns a tuple with the CodeVerify field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeVerify

`func (o *V1DevicesOauthPostRequest) SetCodeVerify(v string)`

SetCodeVerify sets CodeVerify field to given value.

### HasCodeVerify

`func (o *V1DevicesOauthPostRequest) HasCodeVerify() bool`

HasCodeVerify returns a boolean if a field has been set.

### GetPt

`func (o *V1DevicesOauthPostRequest) GetPt() string`

GetPt returns the Pt field if non-nil, zero value otherwise.

### GetPtOk

`func (o *V1DevicesOauthPostRequest) GetPtOk() (*string, bool)`

GetPtOk returns a tuple with the Pt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPt

`func (o *V1DevicesOauthPostRequest) SetPt(v string)`

SetPt sets Pt field to given value.

### HasPt

`func (o *V1DevicesOauthPostRequest) HasPt() bool`

HasPt returns a boolean if a field has been set.

### GetBm

`func (o *V1DevicesOauthPostRequest) GetBm() string`

GetBm returns the Bm field if non-nil, zero value otherwise.

### GetBmOk

`func (o *V1DevicesOauthPostRequest) GetBmOk() (*string, bool)`

GetBmOk returns a tuple with the Bm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBm

`func (o *V1DevicesOauthPostRequest) SetBm(v string)`

SetBm sets Bm field to given value.

### HasBm

`func (o *V1DevicesOauthPostRequest) HasBm() bool`

HasBm returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# CommonUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | Pointer to **string** |  | [optional] 
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastActiveAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**MfaFactor** | Pointer to **string** |  | [optional] 
**PhoneNumber** | Pointer to **string** |  | [optional] 
**TimeZone** | Pointer to **string** |  | [optional] 
**UserId** | Pointer to **string** |  | [optional] 
**Verified** | Pointer to **bool** |  | [optional] 

## Methods

### NewCommonUser

`func NewCommonUser() *CommonUser`

NewCommonUser instantiates a new CommonUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCommonUserWithDefaults

`func NewCommonUserWithDefaults() *CommonUser`

NewCommonUserWithDefaults instantiates a new CommonUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *CommonUser) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CommonUser) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CommonUser) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CommonUser) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *CommonUser) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *CommonUser) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *CommonUser) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *CommonUser) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetFirstName

`func (o *CommonUser) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *CommonUser) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *CommonUser) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *CommonUser) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastActiveAt

`func (o *CommonUser) GetLastActiveAt() GoogleProtobufTimestamp`

GetLastActiveAt returns the LastActiveAt field if non-nil, zero value otherwise.

### GetLastActiveAtOk

`func (o *CommonUser) GetLastActiveAtOk() (*GoogleProtobufTimestamp, bool)`

GetLastActiveAtOk returns a tuple with the LastActiveAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActiveAt

`func (o *CommonUser) SetLastActiveAt(v GoogleProtobufTimestamp)`

SetLastActiveAt sets LastActiveAt field to given value.

### HasLastActiveAt

`func (o *CommonUser) HasLastActiveAt() bool`

HasLastActiveAt returns a boolean if a field has been set.

### GetLastName

`func (o *CommonUser) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *CommonUser) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *CommonUser) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *CommonUser) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetMfaFactor

`func (o *CommonUser) GetMfaFactor() string`

GetMfaFactor returns the MfaFactor field if non-nil, zero value otherwise.

### GetMfaFactorOk

`func (o *CommonUser) GetMfaFactorOk() (*string, bool)`

GetMfaFactorOk returns a tuple with the MfaFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMfaFactor

`func (o *CommonUser) SetMfaFactor(v string)`

SetMfaFactor sets MfaFactor field to given value.

### HasMfaFactor

`func (o *CommonUser) HasMfaFactor() bool`

HasMfaFactor returns a boolean if a field has been set.

### GetPhoneNumber

`func (o *CommonUser) GetPhoneNumber() string`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *CommonUser) GetPhoneNumberOk() (*string, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *CommonUser) SetPhoneNumber(v string)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *CommonUser) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.

### GetTimeZone

`func (o *CommonUser) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *CommonUser) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *CommonUser) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.

### HasTimeZone

`func (o *CommonUser) HasTimeZone() bool`

HasTimeZone returns a boolean if a field has been set.

### GetUserId

`func (o *CommonUser) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CommonUser) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CommonUser) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CommonUser) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetVerified

`func (o *CommonUser) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *CommonUser) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *CommonUser) SetVerified(v bool)`

SetVerified sets Verified field to given value.

### HasVerified

`func (o *CommonUser) HasVerified() bool`

HasVerified returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



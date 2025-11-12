# V1AuthUserGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | User identifier | 
**EnterpriseId** | **int64** | Enterprise identifier | 
**Permissions** | [**AuthPermissions**](AuthPermissions.md) |  | 
**TimeZone** | **string** | User timezone | 

## Methods

### NewV1AuthUserGetResponse

`func NewV1AuthUserGetResponse(userId string, enterpriseId int64, permissions AuthPermissions, timeZone string, ) *V1AuthUserGetResponse`

NewV1AuthUserGetResponse instantiates a new V1AuthUserGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthUserGetResponseWithDefaults

`func NewV1AuthUserGetResponseWithDefaults() *V1AuthUserGetResponse`

NewV1AuthUserGetResponseWithDefaults instantiates a new V1AuthUserGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *V1AuthUserGetResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *V1AuthUserGetResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *V1AuthUserGetResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetEnterpriseId

`func (o *V1AuthUserGetResponse) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *V1AuthUserGetResponse) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *V1AuthUserGetResponse) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.


### GetPermissions

`func (o *V1AuthUserGetResponse) GetPermissions() AuthPermissions`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *V1AuthUserGetResponse) GetPermissionsOk() (*AuthPermissions, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *V1AuthUserGetResponse) SetPermissions(v AuthPermissions)`

SetPermissions sets Permissions field to given value.


### GetTimeZone

`func (o *V1AuthUserGetResponse) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *V1AuthUserGetResponse) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *V1AuthUserGetResponse) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



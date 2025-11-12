# V1GlobalIpsecProfileGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IpsecProfiles** | Pointer to [**[]V1GlobalIpsecProfileGetResponseIPsecProfileCount**](V1GlobalIpsecProfileGetResponseIPsecProfileCount.md) |  | [optional] 

## Methods

### NewV1GlobalIpsecProfileGetResponse

`func NewV1GlobalIpsecProfileGetResponse() *V1GlobalIpsecProfileGetResponse`

NewV1GlobalIpsecProfileGetResponse instantiates a new V1GlobalIpsecProfileGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1GlobalIpsecProfileGetResponseWithDefaults

`func NewV1GlobalIpsecProfileGetResponseWithDefaults() *V1GlobalIpsecProfileGetResponse`

NewV1GlobalIpsecProfileGetResponseWithDefaults instantiates a new V1GlobalIpsecProfileGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIpsecProfiles

`func (o *V1GlobalIpsecProfileGetResponse) GetIpsecProfiles() []V1GlobalIpsecProfileGetResponseIPsecProfileCount`

GetIpsecProfiles returns the IpsecProfiles field if non-nil, zero value otherwise.

### GetIpsecProfilesOk

`func (o *V1GlobalIpsecProfileGetResponse) GetIpsecProfilesOk() (*[]V1GlobalIpsecProfileGetResponseIPsecProfileCount, bool)`

GetIpsecProfilesOk returns a tuple with the IpsecProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecProfiles

`func (o *V1GlobalIpsecProfileGetResponse) SetIpsecProfiles(v []V1GlobalIpsecProfileGetResponseIPsecProfileCount)`

SetIpsecProfiles sets IpsecProfiles field to given value.

### HasIpsecProfiles

`func (o *V1GlobalIpsecProfileGetResponse) HasIpsecProfiles() bool`

HasIpsecProfiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



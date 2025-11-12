# V1SoftwareAutoUpgradeDefaultGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Profile** | Pointer to [**UpgradeUpgradeCanaryProfile**](UpgradeUpgradeCanaryProfile.md) |  | [optional] 
**Release** | Pointer to **string** |  | [optional] 

## Methods

### NewV1SoftwareAutoUpgradeDefaultGetResponse

`func NewV1SoftwareAutoUpgradeDefaultGetResponse() *V1SoftwareAutoUpgradeDefaultGetResponse`

NewV1SoftwareAutoUpgradeDefaultGetResponse instantiates a new V1SoftwareAutoUpgradeDefaultGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1SoftwareAutoUpgradeDefaultGetResponseWithDefaults

`func NewV1SoftwareAutoUpgradeDefaultGetResponseWithDefaults() *V1SoftwareAutoUpgradeDefaultGetResponse`

NewV1SoftwareAutoUpgradeDefaultGetResponseWithDefaults instantiates a new V1SoftwareAutoUpgradeDefaultGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProfile

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) GetProfile() UpgradeUpgradeCanaryProfile`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) GetProfileOk() (*UpgradeUpgradeCanaryProfile, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) SetProfile(v UpgradeUpgradeCanaryProfile)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) HasProfile() bool`

HasProfile returns a boolean if a field has been set.

### GetRelease

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) GetRelease() string`

GetRelease returns the Release field if non-nil, zero value otherwise.

### GetReleaseOk

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) GetReleaseOk() (*string, bool)`

GetReleaseOk returns a tuple with the Release field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelease

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) SetRelease(v string)`

SetRelease sets Release field to given value.

### HasRelease

`func (o *V1SoftwareAutoUpgradeDefaultGetResponse) HasRelease() bool`

HasRelease returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



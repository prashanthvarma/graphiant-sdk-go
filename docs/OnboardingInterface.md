# OnboardingInterface

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ipv4** | Pointer to [**OnboardingIp**](OnboardingIp.md) |  | [optional] 
**Ipv6** | Pointer to [**OnboardingIp**](OnboardingIp.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewOnboardingInterface

`func NewOnboardingInterface() *OnboardingInterface`

NewOnboardingInterface instantiates a new OnboardingInterface object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOnboardingInterfaceWithDefaults

`func NewOnboardingInterfaceWithDefaults() *OnboardingInterface`

NewOnboardingInterfaceWithDefaults instantiates a new OnboardingInterface object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIpv4

`func (o *OnboardingInterface) GetIpv4() OnboardingIp`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *OnboardingInterface) GetIpv4Ok() (*OnboardingIp, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *OnboardingInterface) SetIpv4(v OnboardingIp)`

SetIpv4 sets Ipv4 field to given value.

### HasIpv4

`func (o *OnboardingInterface) HasIpv4() bool`

HasIpv4 returns a boolean if a field has been set.

### GetIpv6

`func (o *OnboardingInterface) GetIpv6() OnboardingIp`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *OnboardingInterface) GetIpv6Ok() (*OnboardingIp, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *OnboardingInterface) SetIpv6(v OnboardingIp)`

SetIpv6 sets Ipv6 field to given value.

### HasIpv6

`func (o *OnboardingInterface) HasIpv6() bool`

HasIpv6 returns a boolean if a field has been set.

### GetName

`func (o *OnboardingInterface) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OnboardingInterface) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OnboardingInterface) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *OnboardingInterface) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *OnboardingInterface) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *OnboardingInterface) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *OnboardingInterface) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *OnboardingInterface) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# OnboardingCloudInitConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceType** | Pointer to **string** |  | [optional] 
**DnsServers** | Pointer to **string** |  | [optional] 
**Hostname** | Pointer to **string** |  | [optional] 
**Interfaces** | Pointer to [**[]OnboardingInterface**](OnboardingInterface.md) |  | [optional] 
**LocalWebPassword** | Pointer to **string** |  | [optional] 

## Methods

### NewOnboardingCloudInitConfiguration

`func NewOnboardingCloudInitConfiguration() *OnboardingCloudInitConfiguration`

NewOnboardingCloudInitConfiguration instantiates a new OnboardingCloudInitConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOnboardingCloudInitConfigurationWithDefaults

`func NewOnboardingCloudInitConfigurationWithDefaults() *OnboardingCloudInitConfiguration`

NewOnboardingCloudInitConfigurationWithDefaults instantiates a new OnboardingCloudInitConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceType

`func (o *OnboardingCloudInitConfiguration) GetDeviceType() string`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *OnboardingCloudInitConfiguration) GetDeviceTypeOk() (*string, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *OnboardingCloudInitConfiguration) SetDeviceType(v string)`

SetDeviceType sets DeviceType field to given value.

### HasDeviceType

`func (o *OnboardingCloudInitConfiguration) HasDeviceType() bool`

HasDeviceType returns a boolean if a field has been set.

### GetDnsServers

`func (o *OnboardingCloudInitConfiguration) GetDnsServers() string`

GetDnsServers returns the DnsServers field if non-nil, zero value otherwise.

### GetDnsServersOk

`func (o *OnboardingCloudInitConfiguration) GetDnsServersOk() (*string, bool)`

GetDnsServersOk returns a tuple with the DnsServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsServers

`func (o *OnboardingCloudInitConfiguration) SetDnsServers(v string)`

SetDnsServers sets DnsServers field to given value.

### HasDnsServers

`func (o *OnboardingCloudInitConfiguration) HasDnsServers() bool`

HasDnsServers returns a boolean if a field has been set.

### GetHostname

`func (o *OnboardingCloudInitConfiguration) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *OnboardingCloudInitConfiguration) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *OnboardingCloudInitConfiguration) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *OnboardingCloudInitConfiguration) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetInterfaces

`func (o *OnboardingCloudInitConfiguration) GetInterfaces() []OnboardingInterface`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *OnboardingCloudInitConfiguration) GetInterfacesOk() (*[]OnboardingInterface, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *OnboardingCloudInitConfiguration) SetInterfaces(v []OnboardingInterface)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *OnboardingCloudInitConfiguration) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetLocalWebPassword

`func (o *OnboardingCloudInitConfiguration) GetLocalWebPassword() string`

GetLocalWebPassword returns the LocalWebPassword field if non-nil, zero value otherwise.

### GetLocalWebPasswordOk

`func (o *OnboardingCloudInitConfiguration) GetLocalWebPasswordOk() (*string, bool)`

GetLocalWebPasswordOk returns a tuple with the LocalWebPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalWebPassword

`func (o *OnboardingCloudInitConfiguration) SetLocalWebPassword(v string)`

SetLocalWebPassword sets LocalWebPassword field to given value.

### HasLocalWebPassword

`func (o *OnboardingCloudInitConfiguration) HasLocalWebPassword() bool`

HasLocalWebPassword returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



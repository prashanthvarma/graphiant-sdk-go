# ManaV2GlobalAppConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**IpLists** | Pointer to **[]string** |  | [optional] 
**IpPrefixes** | Pointer to **[]string** |  | [optional] 
**IpProtocol** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PortRanges** | Pointer to [**[]ManaV2GlobalAppPortRange**](ManaV2GlobalAppPortRange.md) |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2GlobalAppConfig

`func NewManaV2GlobalAppConfig() *ManaV2GlobalAppConfig`

NewManaV2GlobalAppConfig instantiates a new ManaV2GlobalAppConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2GlobalAppConfigWithDefaults

`func NewManaV2GlobalAppConfigWithDefaults() *ManaV2GlobalAppConfig`

NewManaV2GlobalAppConfigWithDefaults instantiates a new ManaV2GlobalAppConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ManaV2GlobalAppConfig) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ManaV2GlobalAppConfig) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ManaV2GlobalAppConfig) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ManaV2GlobalAppConfig) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIpLists

`func (o *ManaV2GlobalAppConfig) GetIpLists() []string`

GetIpLists returns the IpLists field if non-nil, zero value otherwise.

### GetIpListsOk

`func (o *ManaV2GlobalAppConfig) GetIpListsOk() (*[]string, bool)`

GetIpListsOk returns a tuple with the IpLists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpLists

`func (o *ManaV2GlobalAppConfig) SetIpLists(v []string)`

SetIpLists sets IpLists field to given value.

### HasIpLists

`func (o *ManaV2GlobalAppConfig) HasIpLists() bool`

HasIpLists returns a boolean if a field has been set.

### GetIpPrefixes

`func (o *ManaV2GlobalAppConfig) GetIpPrefixes() []string`

GetIpPrefixes returns the IpPrefixes field if non-nil, zero value otherwise.

### GetIpPrefixesOk

`func (o *ManaV2GlobalAppConfig) GetIpPrefixesOk() (*[]string, bool)`

GetIpPrefixesOk returns a tuple with the IpPrefixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpPrefixes

`func (o *ManaV2GlobalAppConfig) SetIpPrefixes(v []string)`

SetIpPrefixes sets IpPrefixes field to given value.

### HasIpPrefixes

`func (o *ManaV2GlobalAppConfig) HasIpPrefixes() bool`

HasIpPrefixes returns a boolean if a field has been set.

### GetIpProtocol

`func (o *ManaV2GlobalAppConfig) GetIpProtocol() string`

GetIpProtocol returns the IpProtocol field if non-nil, zero value otherwise.

### GetIpProtocolOk

`func (o *ManaV2GlobalAppConfig) GetIpProtocolOk() (*string, bool)`

GetIpProtocolOk returns a tuple with the IpProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpProtocol

`func (o *ManaV2GlobalAppConfig) SetIpProtocol(v string)`

SetIpProtocol sets IpProtocol field to given value.

### HasIpProtocol

`func (o *ManaV2GlobalAppConfig) HasIpProtocol() bool`

HasIpProtocol returns a boolean if a field has been set.

### GetName

`func (o *ManaV2GlobalAppConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2GlobalAppConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2GlobalAppConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2GlobalAppConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPortRanges

`func (o *ManaV2GlobalAppConfig) GetPortRanges() []ManaV2GlobalAppPortRange`

GetPortRanges returns the PortRanges field if non-nil, zero value otherwise.

### GetPortRangesOk

`func (o *ManaV2GlobalAppConfig) GetPortRangesOk() (*[]ManaV2GlobalAppPortRange, bool)`

GetPortRangesOk returns a tuple with the PortRanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortRanges

`func (o *ManaV2GlobalAppConfig) SetPortRanges(v []ManaV2GlobalAppPortRange)`

SetPortRanges sets PortRanges field to given value.

### HasPortRanges

`func (o *ManaV2GlobalAppConfig) HasPortRanges() bool`

HasPortRanges returns a boolean if a field has been set.

### GetUrl

`func (o *ManaV2GlobalAppConfig) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ManaV2GlobalAppConfig) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ManaV2GlobalAppConfig) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ManaV2GlobalAppConfig) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



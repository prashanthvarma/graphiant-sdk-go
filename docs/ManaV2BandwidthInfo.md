# ManaV2BandwidthInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CombinedCredits** | Pointer to **float32** | Sum of the credits associated with cloud and gateway networks | [optional] 
**CoreBandwidth** | Pointer to **float32** | Soft-upper-bounded max speed in gigabytes per second associated with core network connections | [optional] 
**CoreCredits** | Pointer to **float32** | Credits derived from bandwidth on core network connections | [optional] 
**GwBandwidth** | Pointer to **float32** | Soft-upper-bounded max speed in gigabytes per second associated with gateway connections | [optional] 
**GwCredits** | Pointer to **float32** | Credits derived from bandwidth on gateway network connections | [optional] 

## Methods

### NewManaV2BandwidthInfo

`func NewManaV2BandwidthInfo() *ManaV2BandwidthInfo`

NewManaV2BandwidthInfo instantiates a new ManaV2BandwidthInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2BandwidthInfoWithDefaults

`func NewManaV2BandwidthInfoWithDefaults() *ManaV2BandwidthInfo`

NewManaV2BandwidthInfoWithDefaults instantiates a new ManaV2BandwidthInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCombinedCredits

`func (o *ManaV2BandwidthInfo) GetCombinedCredits() float32`

GetCombinedCredits returns the CombinedCredits field if non-nil, zero value otherwise.

### GetCombinedCreditsOk

`func (o *ManaV2BandwidthInfo) GetCombinedCreditsOk() (*float32, bool)`

GetCombinedCreditsOk returns a tuple with the CombinedCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCombinedCredits

`func (o *ManaV2BandwidthInfo) SetCombinedCredits(v float32)`

SetCombinedCredits sets CombinedCredits field to given value.

### HasCombinedCredits

`func (o *ManaV2BandwidthInfo) HasCombinedCredits() bool`

HasCombinedCredits returns a boolean if a field has been set.

### GetCoreBandwidth

`func (o *ManaV2BandwidthInfo) GetCoreBandwidth() float32`

GetCoreBandwidth returns the CoreBandwidth field if non-nil, zero value otherwise.

### GetCoreBandwidthOk

`func (o *ManaV2BandwidthInfo) GetCoreBandwidthOk() (*float32, bool)`

GetCoreBandwidthOk returns a tuple with the CoreBandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreBandwidth

`func (o *ManaV2BandwidthInfo) SetCoreBandwidth(v float32)`

SetCoreBandwidth sets CoreBandwidth field to given value.

### HasCoreBandwidth

`func (o *ManaV2BandwidthInfo) HasCoreBandwidth() bool`

HasCoreBandwidth returns a boolean if a field has been set.

### GetCoreCredits

`func (o *ManaV2BandwidthInfo) GetCoreCredits() float32`

GetCoreCredits returns the CoreCredits field if non-nil, zero value otherwise.

### GetCoreCreditsOk

`func (o *ManaV2BandwidthInfo) GetCoreCreditsOk() (*float32, bool)`

GetCoreCreditsOk returns a tuple with the CoreCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreCredits

`func (o *ManaV2BandwidthInfo) SetCoreCredits(v float32)`

SetCoreCredits sets CoreCredits field to given value.

### HasCoreCredits

`func (o *ManaV2BandwidthInfo) HasCoreCredits() bool`

HasCoreCredits returns a boolean if a field has been set.

### GetGwBandwidth

`func (o *ManaV2BandwidthInfo) GetGwBandwidth() float32`

GetGwBandwidth returns the GwBandwidth field if non-nil, zero value otherwise.

### GetGwBandwidthOk

`func (o *ManaV2BandwidthInfo) GetGwBandwidthOk() (*float32, bool)`

GetGwBandwidthOk returns a tuple with the GwBandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGwBandwidth

`func (o *ManaV2BandwidthInfo) SetGwBandwidth(v float32)`

SetGwBandwidth sets GwBandwidth field to given value.

### HasGwBandwidth

`func (o *ManaV2BandwidthInfo) HasGwBandwidth() bool`

HasGwBandwidth returns a boolean if a field has been set.

### GetGwCredits

`func (o *ManaV2BandwidthInfo) GetGwCredits() float32`

GetGwCredits returns the GwCredits field if non-nil, zero value otherwise.

### GetGwCreditsOk

`func (o *ManaV2BandwidthInfo) GetGwCreditsOk() (*float32, bool)`

GetGwCreditsOk returns a tuple with the GwCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGwCredits

`func (o *ManaV2BandwidthInfo) SetGwCredits(v float32)`

SetGwCredits sets GwCredits field to given value.

### HasGwCredits

`func (o *ManaV2BandwidthInfo) HasGwCredits() bool`

HasGwCredits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



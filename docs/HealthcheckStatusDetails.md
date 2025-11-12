# HealthcheckStatusDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpCoreState** | Pointer to **[]bool** |  | [optional] 
**BgpOdpState** | Pointer to **[]bool** |  | [optional] 
**CoreTunnelState** | Pointer to **[]bool** |  | [optional] 
**DeviceId** | Pointer to **int64** |  | [optional] 
**EnterpriseId** | Pointer to **int64** |  | [optional] 
**GnmiState** | Pointer to **bool** |  | [optional] 
**IpsecCoreStatus** | Pointer to **string** |  | [optional] 
**IpsecOdpStatus** | Pointer to **string** |  | [optional] 
**OdpStatus** | Pointer to [**HealthcheckOdpStatusDetails**](HealthcheckOdpStatusDetails.md) |  | [optional] 
**OdpTunnelState** | Pointer to **[]bool** |  | [optional] 
**OnboardingStatus** | Pointer to [**HealthcheckOnboardingStatusDetails**](HealthcheckOnboardingStatusDetails.md) |  | [optional] 
**T2Status** | Pointer to [**HealthcheckT2StatusDetails**](HealthcheckT2StatusDetails.md) |  | [optional] 
**TopoGwState** | Pointer to **string** |  | [optional] 
**TtTunnelState** | Pointer to **[]bool** |  | [optional] 

## Methods

### NewHealthcheckStatusDetails

`func NewHealthcheckStatusDetails() *HealthcheckStatusDetails`

NewHealthcheckStatusDetails instantiates a new HealthcheckStatusDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthcheckStatusDetailsWithDefaults

`func NewHealthcheckStatusDetailsWithDefaults() *HealthcheckStatusDetails`

NewHealthcheckStatusDetailsWithDefaults instantiates a new HealthcheckStatusDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpCoreState

`func (o *HealthcheckStatusDetails) GetBgpCoreState() []bool`

GetBgpCoreState returns the BgpCoreState field if non-nil, zero value otherwise.

### GetBgpCoreStateOk

`func (o *HealthcheckStatusDetails) GetBgpCoreStateOk() (*[]bool, bool)`

GetBgpCoreStateOk returns a tuple with the BgpCoreState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpCoreState

`func (o *HealthcheckStatusDetails) SetBgpCoreState(v []bool)`

SetBgpCoreState sets BgpCoreState field to given value.

### HasBgpCoreState

`func (o *HealthcheckStatusDetails) HasBgpCoreState() bool`

HasBgpCoreState returns a boolean if a field has been set.

### GetBgpOdpState

`func (o *HealthcheckStatusDetails) GetBgpOdpState() []bool`

GetBgpOdpState returns the BgpOdpState field if non-nil, zero value otherwise.

### GetBgpOdpStateOk

`func (o *HealthcheckStatusDetails) GetBgpOdpStateOk() (*[]bool, bool)`

GetBgpOdpStateOk returns a tuple with the BgpOdpState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpOdpState

`func (o *HealthcheckStatusDetails) SetBgpOdpState(v []bool)`

SetBgpOdpState sets BgpOdpState field to given value.

### HasBgpOdpState

`func (o *HealthcheckStatusDetails) HasBgpOdpState() bool`

HasBgpOdpState returns a boolean if a field has been set.

### GetCoreTunnelState

`func (o *HealthcheckStatusDetails) GetCoreTunnelState() []bool`

GetCoreTunnelState returns the CoreTunnelState field if non-nil, zero value otherwise.

### GetCoreTunnelStateOk

`func (o *HealthcheckStatusDetails) GetCoreTunnelStateOk() (*[]bool, bool)`

GetCoreTunnelStateOk returns a tuple with the CoreTunnelState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreTunnelState

`func (o *HealthcheckStatusDetails) SetCoreTunnelState(v []bool)`

SetCoreTunnelState sets CoreTunnelState field to given value.

### HasCoreTunnelState

`func (o *HealthcheckStatusDetails) HasCoreTunnelState() bool`

HasCoreTunnelState returns a boolean if a field has been set.

### GetDeviceId

`func (o *HealthcheckStatusDetails) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *HealthcheckStatusDetails) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *HealthcheckStatusDetails) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *HealthcheckStatusDetails) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *HealthcheckStatusDetails) GetEnterpriseId() int64`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *HealthcheckStatusDetails) GetEnterpriseIdOk() (*int64, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *HealthcheckStatusDetails) SetEnterpriseId(v int64)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *HealthcheckStatusDetails) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetGnmiState

`func (o *HealthcheckStatusDetails) GetGnmiState() bool`

GetGnmiState returns the GnmiState field if non-nil, zero value otherwise.

### GetGnmiStateOk

`func (o *HealthcheckStatusDetails) GetGnmiStateOk() (*bool, bool)`

GetGnmiStateOk returns a tuple with the GnmiState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGnmiState

`func (o *HealthcheckStatusDetails) SetGnmiState(v bool)`

SetGnmiState sets GnmiState field to given value.

### HasGnmiState

`func (o *HealthcheckStatusDetails) HasGnmiState() bool`

HasGnmiState returns a boolean if a field has been set.

### GetIpsecCoreStatus

`func (o *HealthcheckStatusDetails) GetIpsecCoreStatus() string`

GetIpsecCoreStatus returns the IpsecCoreStatus field if non-nil, zero value otherwise.

### GetIpsecCoreStatusOk

`func (o *HealthcheckStatusDetails) GetIpsecCoreStatusOk() (*string, bool)`

GetIpsecCoreStatusOk returns a tuple with the IpsecCoreStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecCoreStatus

`func (o *HealthcheckStatusDetails) SetIpsecCoreStatus(v string)`

SetIpsecCoreStatus sets IpsecCoreStatus field to given value.

### HasIpsecCoreStatus

`func (o *HealthcheckStatusDetails) HasIpsecCoreStatus() bool`

HasIpsecCoreStatus returns a boolean if a field has been set.

### GetIpsecOdpStatus

`func (o *HealthcheckStatusDetails) GetIpsecOdpStatus() string`

GetIpsecOdpStatus returns the IpsecOdpStatus field if non-nil, zero value otherwise.

### GetIpsecOdpStatusOk

`func (o *HealthcheckStatusDetails) GetIpsecOdpStatusOk() (*string, bool)`

GetIpsecOdpStatusOk returns a tuple with the IpsecOdpStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpsecOdpStatus

`func (o *HealthcheckStatusDetails) SetIpsecOdpStatus(v string)`

SetIpsecOdpStatus sets IpsecOdpStatus field to given value.

### HasIpsecOdpStatus

`func (o *HealthcheckStatusDetails) HasIpsecOdpStatus() bool`

HasIpsecOdpStatus returns a boolean if a field has been set.

### GetOdpStatus

`func (o *HealthcheckStatusDetails) GetOdpStatus() HealthcheckOdpStatusDetails`

GetOdpStatus returns the OdpStatus field if non-nil, zero value otherwise.

### GetOdpStatusOk

`func (o *HealthcheckStatusDetails) GetOdpStatusOk() (*HealthcheckOdpStatusDetails, bool)`

GetOdpStatusOk returns a tuple with the OdpStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOdpStatus

`func (o *HealthcheckStatusDetails) SetOdpStatus(v HealthcheckOdpStatusDetails)`

SetOdpStatus sets OdpStatus field to given value.

### HasOdpStatus

`func (o *HealthcheckStatusDetails) HasOdpStatus() bool`

HasOdpStatus returns a boolean if a field has been set.

### GetOdpTunnelState

`func (o *HealthcheckStatusDetails) GetOdpTunnelState() []bool`

GetOdpTunnelState returns the OdpTunnelState field if non-nil, zero value otherwise.

### GetOdpTunnelStateOk

`func (o *HealthcheckStatusDetails) GetOdpTunnelStateOk() (*[]bool, bool)`

GetOdpTunnelStateOk returns a tuple with the OdpTunnelState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOdpTunnelState

`func (o *HealthcheckStatusDetails) SetOdpTunnelState(v []bool)`

SetOdpTunnelState sets OdpTunnelState field to given value.

### HasOdpTunnelState

`func (o *HealthcheckStatusDetails) HasOdpTunnelState() bool`

HasOdpTunnelState returns a boolean if a field has been set.

### GetOnboardingStatus

`func (o *HealthcheckStatusDetails) GetOnboardingStatus() HealthcheckOnboardingStatusDetails`

GetOnboardingStatus returns the OnboardingStatus field if non-nil, zero value otherwise.

### GetOnboardingStatusOk

`func (o *HealthcheckStatusDetails) GetOnboardingStatusOk() (*HealthcheckOnboardingStatusDetails, bool)`

GetOnboardingStatusOk returns a tuple with the OnboardingStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnboardingStatus

`func (o *HealthcheckStatusDetails) SetOnboardingStatus(v HealthcheckOnboardingStatusDetails)`

SetOnboardingStatus sets OnboardingStatus field to given value.

### HasOnboardingStatus

`func (o *HealthcheckStatusDetails) HasOnboardingStatus() bool`

HasOnboardingStatus returns a boolean if a field has been set.

### GetT2Status

`func (o *HealthcheckStatusDetails) GetT2Status() HealthcheckT2StatusDetails`

GetT2Status returns the T2Status field if non-nil, zero value otherwise.

### GetT2StatusOk

`func (o *HealthcheckStatusDetails) GetT2StatusOk() (*HealthcheckT2StatusDetails, bool)`

GetT2StatusOk returns a tuple with the T2Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetT2Status

`func (o *HealthcheckStatusDetails) SetT2Status(v HealthcheckT2StatusDetails)`

SetT2Status sets T2Status field to given value.

### HasT2Status

`func (o *HealthcheckStatusDetails) HasT2Status() bool`

HasT2Status returns a boolean if a field has been set.

### GetTopoGwState

`func (o *HealthcheckStatusDetails) GetTopoGwState() string`

GetTopoGwState returns the TopoGwState field if non-nil, zero value otherwise.

### GetTopoGwStateOk

`func (o *HealthcheckStatusDetails) GetTopoGwStateOk() (*string, bool)`

GetTopoGwStateOk returns a tuple with the TopoGwState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopoGwState

`func (o *HealthcheckStatusDetails) SetTopoGwState(v string)`

SetTopoGwState sets TopoGwState field to given value.

### HasTopoGwState

`func (o *HealthcheckStatusDetails) HasTopoGwState() bool`

HasTopoGwState returns a boolean if a field has been set.

### GetTtTunnelState

`func (o *HealthcheckStatusDetails) GetTtTunnelState() []bool`

GetTtTunnelState returns the TtTunnelState field if non-nil, zero value otherwise.

### GetTtTunnelStateOk

`func (o *HealthcheckStatusDetails) GetTtTunnelStateOk() (*[]bool, bool)`

GetTtTunnelStateOk returns a tuple with the TtTunnelState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtTunnelState

`func (o *HealthcheckStatusDetails) SetTtTunnelState(v []bool)`

SetTtTunnelState sets TtTunnelState field to given value.

### HasTtTunnelState

`func (o *HealthcheckStatusDetails) HasTtTunnelState() bool`

HasTtTunnelState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



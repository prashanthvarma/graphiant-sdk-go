# ManaV2TrafficPolicyRuleRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | Pointer to [**ManaV2SiteDeviceStub**](ManaV2SiteDeviceStub.md) |  | [optional] 
**TrafficPolicyRule** | Pointer to [**ManaV2TrafficPolicyRule**](ManaV2TrafficPolicyRule.md) |  | [optional] 
**VrfName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2TrafficPolicyRuleRow

`func NewManaV2TrafficPolicyRuleRow() *ManaV2TrafficPolicyRuleRow`

NewManaV2TrafficPolicyRuleRow instantiates a new ManaV2TrafficPolicyRuleRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2TrafficPolicyRuleRowWithDefaults

`func NewManaV2TrafficPolicyRuleRowWithDefaults() *ManaV2TrafficPolicyRuleRow`

NewManaV2TrafficPolicyRuleRowWithDefaults instantiates a new ManaV2TrafficPolicyRuleRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevice

`func (o *ManaV2TrafficPolicyRuleRow) GetDevice() ManaV2SiteDeviceStub`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *ManaV2TrafficPolicyRuleRow) GetDeviceOk() (*ManaV2SiteDeviceStub, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *ManaV2TrafficPolicyRuleRow) SetDevice(v ManaV2SiteDeviceStub)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *ManaV2TrafficPolicyRuleRow) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetTrafficPolicyRule

`func (o *ManaV2TrafficPolicyRuleRow) GetTrafficPolicyRule() ManaV2TrafficPolicyRule`

GetTrafficPolicyRule returns the TrafficPolicyRule field if non-nil, zero value otherwise.

### GetTrafficPolicyRuleOk

`func (o *ManaV2TrafficPolicyRuleRow) GetTrafficPolicyRuleOk() (*ManaV2TrafficPolicyRule, bool)`

GetTrafficPolicyRuleOk returns a tuple with the TrafficPolicyRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficPolicyRule

`func (o *ManaV2TrafficPolicyRuleRow) SetTrafficPolicyRule(v ManaV2TrafficPolicyRule)`

SetTrafficPolicyRule sets TrafficPolicyRule field to given value.

### HasTrafficPolicyRule

`func (o *ManaV2TrafficPolicyRuleRow) HasTrafficPolicyRule() bool`

HasTrafficPolicyRule returns a boolean if a field has been set.

### GetVrfName

`func (o *ManaV2TrafficPolicyRuleRow) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *ManaV2TrafficPolicyRuleRow) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *ManaV2TrafficPolicyRuleRow) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *ManaV2TrafficPolicyRuleRow) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



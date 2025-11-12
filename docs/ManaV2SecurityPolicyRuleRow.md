# ManaV2SecurityPolicyRuleRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | Pointer to [**ManaV2SiteDeviceStub**](ManaV2SiteDeviceStub.md) |  | [optional] 
**SecurityPolicyRule** | Pointer to [**ManaV2SecurityPolicyRule**](ManaV2SecurityPolicyRule.md) |  | [optional] 
**VrfName** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2SecurityPolicyRuleRow

`func NewManaV2SecurityPolicyRuleRow() *ManaV2SecurityPolicyRuleRow`

NewManaV2SecurityPolicyRuleRow instantiates a new ManaV2SecurityPolicyRuleRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2SecurityPolicyRuleRowWithDefaults

`func NewManaV2SecurityPolicyRuleRowWithDefaults() *ManaV2SecurityPolicyRuleRow`

NewManaV2SecurityPolicyRuleRowWithDefaults instantiates a new ManaV2SecurityPolicyRuleRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevice

`func (o *ManaV2SecurityPolicyRuleRow) GetDevice() ManaV2SiteDeviceStub`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *ManaV2SecurityPolicyRuleRow) GetDeviceOk() (*ManaV2SiteDeviceStub, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *ManaV2SecurityPolicyRuleRow) SetDevice(v ManaV2SiteDeviceStub)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *ManaV2SecurityPolicyRuleRow) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetSecurityPolicyRule

`func (o *ManaV2SecurityPolicyRuleRow) GetSecurityPolicyRule() ManaV2SecurityPolicyRule`

GetSecurityPolicyRule returns the SecurityPolicyRule field if non-nil, zero value otherwise.

### GetSecurityPolicyRuleOk

`func (o *ManaV2SecurityPolicyRuleRow) GetSecurityPolicyRuleOk() (*ManaV2SecurityPolicyRule, bool)`

GetSecurityPolicyRuleOk returns a tuple with the SecurityPolicyRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityPolicyRule

`func (o *ManaV2SecurityPolicyRuleRow) SetSecurityPolicyRule(v ManaV2SecurityPolicyRule)`

SetSecurityPolicyRule sets SecurityPolicyRule field to given value.

### HasSecurityPolicyRule

`func (o *ManaV2SecurityPolicyRuleRow) HasSecurityPolicyRule() bool`

HasSecurityPolicyRule returns a boolean if a field has been set.

### GetVrfName

`func (o *ManaV2SecurityPolicyRuleRow) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *ManaV2SecurityPolicyRuleRow) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *ManaV2SecurityPolicyRuleRow) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.

### HasVrfName

`func (o *ManaV2SecurityPolicyRuleRow) HasVrfName() bool`

HasVrfName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



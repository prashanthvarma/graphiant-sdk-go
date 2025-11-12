# AlertserviceUpdateIntegrationBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Details** | Pointer to [**AlertserviceIntegrationDetails**](AlertserviceIntegrationDetails.md) |  | [optional] 
**Enterprise** | **int64** | ID of the enterprise (required) | 
**IntegrationType** | **string** | Type of integration (required) | 
**IsActive** | Pointer to **bool** | Indicates whether the integration is active | [optional] 
**NickName** | **string** | nick name of the integration (required) | 
**UpdatedBy** | Pointer to **string** | ID of the user who updated the integration | [optional] 

## Methods

### NewAlertserviceUpdateIntegrationBody

`func NewAlertserviceUpdateIntegrationBody(enterprise int64, integrationType string, nickName string, ) *AlertserviceUpdateIntegrationBody`

NewAlertserviceUpdateIntegrationBody instantiates a new AlertserviceUpdateIntegrationBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertserviceUpdateIntegrationBodyWithDefaults

`func NewAlertserviceUpdateIntegrationBodyWithDefaults() *AlertserviceUpdateIntegrationBody`

NewAlertserviceUpdateIntegrationBodyWithDefaults instantiates a new AlertserviceUpdateIntegrationBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDetails

`func (o *AlertserviceUpdateIntegrationBody) GetDetails() AlertserviceIntegrationDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AlertserviceUpdateIntegrationBody) GetDetailsOk() (*AlertserviceIntegrationDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AlertserviceUpdateIntegrationBody) SetDetails(v AlertserviceIntegrationDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AlertserviceUpdateIntegrationBody) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetEnterprise

`func (o *AlertserviceUpdateIntegrationBody) GetEnterprise() int64`

GetEnterprise returns the Enterprise field if non-nil, zero value otherwise.

### GetEnterpriseOk

`func (o *AlertserviceUpdateIntegrationBody) GetEnterpriseOk() (*int64, bool)`

GetEnterpriseOk returns a tuple with the Enterprise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterprise

`func (o *AlertserviceUpdateIntegrationBody) SetEnterprise(v int64)`

SetEnterprise sets Enterprise field to given value.


### GetIntegrationType

`func (o *AlertserviceUpdateIntegrationBody) GetIntegrationType() string`

GetIntegrationType returns the IntegrationType field if non-nil, zero value otherwise.

### GetIntegrationTypeOk

`func (o *AlertserviceUpdateIntegrationBody) GetIntegrationTypeOk() (*string, bool)`

GetIntegrationTypeOk returns a tuple with the IntegrationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntegrationType

`func (o *AlertserviceUpdateIntegrationBody) SetIntegrationType(v string)`

SetIntegrationType sets IntegrationType field to given value.


### GetIsActive

`func (o *AlertserviceUpdateIntegrationBody) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *AlertserviceUpdateIntegrationBody) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *AlertserviceUpdateIntegrationBody) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *AlertserviceUpdateIntegrationBody) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetNickName

`func (o *AlertserviceUpdateIntegrationBody) GetNickName() string`

GetNickName returns the NickName field if non-nil, zero value otherwise.

### GetNickNameOk

`func (o *AlertserviceUpdateIntegrationBody) GetNickNameOk() (*string, bool)`

GetNickNameOk returns a tuple with the NickName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNickName

`func (o *AlertserviceUpdateIntegrationBody) SetNickName(v string)`

SetNickName sets NickName field to given value.


### GetUpdatedBy

`func (o *AlertserviceUpdateIntegrationBody) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *AlertserviceUpdateIntegrationBody) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *AlertserviceUpdateIntegrationBody) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *AlertserviceUpdateIntegrationBody) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



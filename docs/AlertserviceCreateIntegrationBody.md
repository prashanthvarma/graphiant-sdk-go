# AlertserviceCreateIntegrationBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedBy** | Pointer to **string** | ID of the user who created the integration | [optional] 
**CreatedOn** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Details** | Pointer to [**AlertserviceIntegrationDetails**](AlertserviceIntegrationDetails.md) |  | [optional] 
**Enterprise** | **int64** | ID of the enterprise (required) | 
**IntegrationType** | **string** | Type of integration (required) | 
**IsActive** | Pointer to **bool** | Indicates whether the integration is active | [optional] 
**NickName** | **string** | Name of the integration (required) | 

## Methods

### NewAlertserviceCreateIntegrationBody

`func NewAlertserviceCreateIntegrationBody(enterprise int64, integrationType string, nickName string, ) *AlertserviceCreateIntegrationBody`

NewAlertserviceCreateIntegrationBody instantiates a new AlertserviceCreateIntegrationBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertserviceCreateIntegrationBodyWithDefaults

`func NewAlertserviceCreateIntegrationBodyWithDefaults() *AlertserviceCreateIntegrationBody`

NewAlertserviceCreateIntegrationBodyWithDefaults instantiates a new AlertserviceCreateIntegrationBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedBy

`func (o *AlertserviceCreateIntegrationBody) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *AlertserviceCreateIntegrationBody) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *AlertserviceCreateIntegrationBody) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *AlertserviceCreateIntegrationBody) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedOn

`func (o *AlertserviceCreateIntegrationBody) GetCreatedOn() GoogleProtobufTimestamp`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *AlertserviceCreateIntegrationBody) GetCreatedOnOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *AlertserviceCreateIntegrationBody) SetCreatedOn(v GoogleProtobufTimestamp)`

SetCreatedOn sets CreatedOn field to given value.

### HasCreatedOn

`func (o *AlertserviceCreateIntegrationBody) HasCreatedOn() bool`

HasCreatedOn returns a boolean if a field has been set.

### GetDetails

`func (o *AlertserviceCreateIntegrationBody) GetDetails() AlertserviceIntegrationDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AlertserviceCreateIntegrationBody) GetDetailsOk() (*AlertserviceIntegrationDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AlertserviceCreateIntegrationBody) SetDetails(v AlertserviceIntegrationDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AlertserviceCreateIntegrationBody) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetEnterprise

`func (o *AlertserviceCreateIntegrationBody) GetEnterprise() int64`

GetEnterprise returns the Enterprise field if non-nil, zero value otherwise.

### GetEnterpriseOk

`func (o *AlertserviceCreateIntegrationBody) GetEnterpriseOk() (*int64, bool)`

GetEnterpriseOk returns a tuple with the Enterprise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterprise

`func (o *AlertserviceCreateIntegrationBody) SetEnterprise(v int64)`

SetEnterprise sets Enterprise field to given value.


### GetIntegrationType

`func (o *AlertserviceCreateIntegrationBody) GetIntegrationType() string`

GetIntegrationType returns the IntegrationType field if non-nil, zero value otherwise.

### GetIntegrationTypeOk

`func (o *AlertserviceCreateIntegrationBody) GetIntegrationTypeOk() (*string, bool)`

GetIntegrationTypeOk returns a tuple with the IntegrationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntegrationType

`func (o *AlertserviceCreateIntegrationBody) SetIntegrationType(v string)`

SetIntegrationType sets IntegrationType field to given value.


### GetIsActive

`func (o *AlertserviceCreateIntegrationBody) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *AlertserviceCreateIntegrationBody) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *AlertserviceCreateIntegrationBody) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *AlertserviceCreateIntegrationBody) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetNickName

`func (o *AlertserviceCreateIntegrationBody) GetNickName() string`

GetNickName returns the NickName field if non-nil, zero value otherwise.

### GetNickNameOk

`func (o *AlertserviceCreateIntegrationBody) GetNickNameOk() (*string, bool)`

GetNickNameOk returns a tuple with the NickName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNickName

`func (o *AlertserviceCreateIntegrationBody) SetNickName(v string)`

SetNickName sets NickName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



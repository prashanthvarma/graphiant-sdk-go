# ManaV2AwsGatewayDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** |  | [optional] 
**AdvanceSettings** | Pointer to [**ManaV2AwsAdvanceSettings**](ManaV2AwsAdvanceSettings.md) |  | [optional] 
**TransitConnection** | Pointer to [**ManaV2AWSGatewayDetailsTransitConnection**](ManaV2AWSGatewayDetailsTransitConnection.md) |  | [optional] 

## Methods

### NewManaV2AwsGatewayDetails

`func NewManaV2AwsGatewayDetails() *ManaV2AwsGatewayDetails`

NewManaV2AwsGatewayDetails instantiates a new ManaV2AwsGatewayDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AwsGatewayDetailsWithDefaults

`func NewManaV2AwsGatewayDetailsWithDefaults() *ManaV2AwsGatewayDetails`

NewManaV2AwsGatewayDetailsWithDefaults instantiates a new ManaV2AwsGatewayDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *ManaV2AwsGatewayDetails) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *ManaV2AwsGatewayDetails) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *ManaV2AwsGatewayDetails) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *ManaV2AwsGatewayDetails) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAdvanceSettings

`func (o *ManaV2AwsGatewayDetails) GetAdvanceSettings() ManaV2AwsAdvanceSettings`

GetAdvanceSettings returns the AdvanceSettings field if non-nil, zero value otherwise.

### GetAdvanceSettingsOk

`func (o *ManaV2AwsGatewayDetails) GetAdvanceSettingsOk() (*ManaV2AwsAdvanceSettings, bool)`

GetAdvanceSettingsOk returns a tuple with the AdvanceSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvanceSettings

`func (o *ManaV2AwsGatewayDetails) SetAdvanceSettings(v ManaV2AwsAdvanceSettings)`

SetAdvanceSettings sets AdvanceSettings field to given value.

### HasAdvanceSettings

`func (o *ManaV2AwsGatewayDetails) HasAdvanceSettings() bool`

HasAdvanceSettings returns a boolean if a field has been set.

### GetTransitConnection

`func (o *ManaV2AwsGatewayDetails) GetTransitConnection() ManaV2AWSGatewayDetailsTransitConnection`

GetTransitConnection returns the TransitConnection field if non-nil, zero value otherwise.

### GetTransitConnectionOk

`func (o *ManaV2AwsGatewayDetails) GetTransitConnectionOk() (*ManaV2AWSGatewayDetailsTransitConnection, bool)`

GetTransitConnectionOk returns a tuple with the TransitConnection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransitConnection

`func (o *ManaV2AwsGatewayDetails) SetTransitConnection(v ManaV2AWSGatewayDetailsTransitConnection)`

SetTransitConnection sets TransitConnection field to given value.

### HasTransitConnection

`func (o *ManaV2AwsGatewayDetails) HasTransitConnection() bool`

HasTransitConnection returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



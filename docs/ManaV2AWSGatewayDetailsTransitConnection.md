# ManaV2AWSGatewayDetailsTransitConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Credentials** | Pointer to [**ManaV2AwsCredentials**](ManaV2AwsCredentials.md) |  | [optional] 
**CustomerAsn** | Pointer to **int32** |  | [optional] 
**Gateway** | Pointer to [**ManaV2AwsDirectConnectGateway**](ManaV2AwsDirectConnectGateway.md) |  | [optional] 
**Region** | Pointer to **string** |  | [optional] 

## Methods

### NewManaV2AWSGatewayDetailsTransitConnection

`func NewManaV2AWSGatewayDetailsTransitConnection() *ManaV2AWSGatewayDetailsTransitConnection`

NewManaV2AWSGatewayDetailsTransitConnection instantiates a new ManaV2AWSGatewayDetailsTransitConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AWSGatewayDetailsTransitConnectionWithDefaults

`func NewManaV2AWSGatewayDetailsTransitConnectionWithDefaults() *ManaV2AWSGatewayDetailsTransitConnection`

NewManaV2AWSGatewayDetailsTransitConnectionWithDefaults instantiates a new ManaV2AWSGatewayDetailsTransitConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCredentials

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetCredentials() ManaV2AwsCredentials`

GetCredentials returns the Credentials field if non-nil, zero value otherwise.

### GetCredentialsOk

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetCredentialsOk() (*ManaV2AwsCredentials, bool)`

GetCredentialsOk returns a tuple with the Credentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentials

`func (o *ManaV2AWSGatewayDetailsTransitConnection) SetCredentials(v ManaV2AwsCredentials)`

SetCredentials sets Credentials field to given value.

### HasCredentials

`func (o *ManaV2AWSGatewayDetailsTransitConnection) HasCredentials() bool`

HasCredentials returns a boolean if a field has been set.

### GetCustomerAsn

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetCustomerAsn() int32`

GetCustomerAsn returns the CustomerAsn field if non-nil, zero value otherwise.

### GetCustomerAsnOk

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetCustomerAsnOk() (*int32, bool)`

GetCustomerAsnOk returns a tuple with the CustomerAsn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerAsn

`func (o *ManaV2AWSGatewayDetailsTransitConnection) SetCustomerAsn(v int32)`

SetCustomerAsn sets CustomerAsn field to given value.

### HasCustomerAsn

`func (o *ManaV2AWSGatewayDetailsTransitConnection) HasCustomerAsn() bool`

HasCustomerAsn returns a boolean if a field has been set.

### GetGateway

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetGateway() ManaV2AwsDirectConnectGateway`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetGatewayOk() (*ManaV2AwsDirectConnectGateway, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *ManaV2AWSGatewayDetailsTransitConnection) SetGateway(v ManaV2AwsDirectConnectGateway)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *ManaV2AWSGatewayDetailsTransitConnection) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetRegion

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *ManaV2AWSGatewayDetailsTransitConnection) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *ManaV2AWSGatewayDetailsTransitConnection) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *ManaV2AWSGatewayDetailsTransitConnection) HasRegion() bool`

HasRegion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2AwsTransitGateway

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Asn** | Pointer to **int32** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**Vpcs** | Pointer to [**[]ManaV2AWSTransitGatewayVpc**](ManaV2AWSTransitGatewayVpc.md) |  | [optional] 

## Methods

### NewManaV2AwsTransitGateway

`func NewManaV2AwsTransitGateway() *ManaV2AwsTransitGateway`

NewManaV2AwsTransitGateway instantiates a new ManaV2AwsTransitGateway object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AwsTransitGatewayWithDefaults

`func NewManaV2AwsTransitGatewayWithDefaults() *ManaV2AwsTransitGateway`

NewManaV2AwsTransitGatewayWithDefaults instantiates a new ManaV2AwsTransitGateway object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAsn

`func (o *ManaV2AwsTransitGateway) GetAsn() int32`

GetAsn returns the Asn field if non-nil, zero value otherwise.

### GetAsnOk

`func (o *ManaV2AwsTransitGateway) GetAsnOk() (*int32, bool)`

GetAsnOk returns a tuple with the Asn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsn

`func (o *ManaV2AwsTransitGateway) SetAsn(v int32)`

SetAsn sets Asn field to given value.

### HasAsn

`func (o *ManaV2AwsTransitGateway) HasAsn() bool`

HasAsn returns a boolean if a field has been set.

### GetId

`func (o *ManaV2AwsTransitGateway) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2AwsTransitGateway) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2AwsTransitGateway) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2AwsTransitGateway) HasId() bool`

HasId returns a boolean if a field has been set.

### GetVpcs

`func (o *ManaV2AwsTransitGateway) GetVpcs() []ManaV2AWSTransitGatewayVpc`

GetVpcs returns the Vpcs field if non-nil, zero value otherwise.

### GetVpcsOk

`func (o *ManaV2AwsTransitGateway) GetVpcsOk() (*[]ManaV2AWSTransitGatewayVpc, bool)`

GetVpcsOk returns a tuple with the Vpcs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpcs

`func (o *ManaV2AwsTransitGateway) SetVpcs(v []ManaV2AWSTransitGatewayVpc)`

SetVpcs sets Vpcs field to given value.

### HasVpcs

`func (o *ManaV2AwsTransitGateway) HasVpcs() bool`

HasVpcs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



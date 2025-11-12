# ManaV2AWSTransitGatewayVpc

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Subnets** | Pointer to [**[]ManaV2Subnet**](ManaV2Subnet.md) |  | [optional] 

## Methods

### NewManaV2AWSTransitGatewayVpc

`func NewManaV2AWSTransitGatewayVpc() *ManaV2AWSTransitGatewayVpc`

NewManaV2AWSTransitGatewayVpc instantiates a new ManaV2AWSTransitGatewayVpc object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2AWSTransitGatewayVpcWithDefaults

`func NewManaV2AWSTransitGatewayVpcWithDefaults() *ManaV2AWSTransitGatewayVpc`

NewManaV2AWSTransitGatewayVpcWithDefaults instantiates a new ManaV2AWSTransitGatewayVpc object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManaV2AWSTransitGatewayVpc) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2AWSTransitGatewayVpc) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2AWSTransitGatewayVpc) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2AWSTransitGatewayVpc) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSubnets

`func (o *ManaV2AWSTransitGatewayVpc) GetSubnets() []ManaV2Subnet`

GetSubnets returns the Subnets field if non-nil, zero value otherwise.

### GetSubnetsOk

`func (o *ManaV2AWSTransitGatewayVpc) GetSubnetsOk() (*[]ManaV2Subnet, bool)`

GetSubnetsOk returns a tuple with the Subnets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubnets

`func (o *ManaV2AWSTransitGatewayVpc) SetSubnets(v []ManaV2Subnet)`

SetSubnets sets Subnets field to given value.

### HasSubnets

`func (o *ManaV2AWSTransitGatewayVpc) HasSubnets() bool`

HasSubnets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



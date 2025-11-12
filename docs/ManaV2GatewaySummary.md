# ManaV2GatewaySummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**GatewayDeviceSummary** | Pointer to [**[]ManaV2GatewaySummaryGatewayDeviceSummary**](ManaV2GatewaySummaryGatewayDeviceSummary.md) |  | [optional] 
**GraphiantRegion** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Speed** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SupportStatus** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewManaV2GatewaySummary

`func NewManaV2GatewaySummary() *ManaV2GatewaySummary`

NewManaV2GatewaySummary instantiates a new ManaV2GatewaySummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2GatewaySummaryWithDefaults

`func NewManaV2GatewaySummaryWithDefaults() *ManaV2GatewaySummary`

NewManaV2GatewaySummaryWithDefaults instantiates a new ManaV2GatewaySummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *ManaV2GatewaySummary) GetCreatedAt() GoogleProtobufTimestamp`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManaV2GatewaySummary) GetCreatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManaV2GatewaySummary) SetCreatedAt(v GoogleProtobufTimestamp)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ManaV2GatewaySummary) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetGatewayDeviceSummary

`func (o *ManaV2GatewaySummary) GetGatewayDeviceSummary() []ManaV2GatewaySummaryGatewayDeviceSummary`

GetGatewayDeviceSummary returns the GatewayDeviceSummary field if non-nil, zero value otherwise.

### GetGatewayDeviceSummaryOk

`func (o *ManaV2GatewaySummary) GetGatewayDeviceSummaryOk() (*[]ManaV2GatewaySummaryGatewayDeviceSummary, bool)`

GetGatewayDeviceSummaryOk returns a tuple with the GatewayDeviceSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayDeviceSummary

`func (o *ManaV2GatewaySummary) SetGatewayDeviceSummary(v []ManaV2GatewaySummaryGatewayDeviceSummary)`

SetGatewayDeviceSummary sets GatewayDeviceSummary field to given value.

### HasGatewayDeviceSummary

`func (o *ManaV2GatewaySummary) HasGatewayDeviceSummary() bool`

HasGatewayDeviceSummary returns a boolean if a field has been set.

### GetGraphiantRegion

`func (o *ManaV2GatewaySummary) GetGraphiantRegion() string`

GetGraphiantRegion returns the GraphiantRegion field if non-nil, zero value otherwise.

### GetGraphiantRegionOk

`func (o *ManaV2GatewaySummary) GetGraphiantRegionOk() (*string, bool)`

GetGraphiantRegionOk returns a tuple with the GraphiantRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphiantRegion

`func (o *ManaV2GatewaySummary) SetGraphiantRegion(v string)`

SetGraphiantRegion sets GraphiantRegion field to given value.

### HasGraphiantRegion

`func (o *ManaV2GatewaySummary) HasGraphiantRegion() bool`

HasGraphiantRegion returns a boolean if a field has been set.

### GetId

`func (o *ManaV2GatewaySummary) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManaV2GatewaySummary) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManaV2GatewaySummary) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *ManaV2GatewaySummary) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ManaV2GatewaySummary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2GatewaySummary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2GatewaySummary) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2GatewaySummary) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSpeed

`func (o *ManaV2GatewaySummary) GetSpeed() string`

GetSpeed returns the Speed field if non-nil, zero value otherwise.

### GetSpeedOk

`func (o *ManaV2GatewaySummary) GetSpeedOk() (*string, bool)`

GetSpeedOk returns a tuple with the Speed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpeed

`func (o *ManaV2GatewaySummary) SetSpeed(v string)`

SetSpeed sets Speed field to given value.

### HasSpeed

`func (o *ManaV2GatewaySummary) HasSpeed() bool`

HasSpeed returns a boolean if a field has been set.

### GetStatus

`func (o *ManaV2GatewaySummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManaV2GatewaySummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManaV2GatewaySummary) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManaV2GatewaySummary) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSupportStatus

`func (o *ManaV2GatewaySummary) GetSupportStatus() string`

GetSupportStatus returns the SupportStatus field if non-nil, zero value otherwise.

### GetSupportStatusOk

`func (o *ManaV2GatewaySummary) GetSupportStatusOk() (*string, bool)`

GetSupportStatusOk returns a tuple with the SupportStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportStatus

`func (o *ManaV2GatewaySummary) SetSupportStatus(v string)`

SetSupportStatus sets SupportStatus field to given value.

### HasSupportStatus

`func (o *ManaV2GatewaySummary) HasSupportStatus() bool`

HasSupportStatus returns a boolean if a field has been set.

### GetType

`func (o *ManaV2GatewaySummary) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManaV2GatewaySummary) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManaV2GatewaySummary) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ManaV2GatewaySummary) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ManaV2GatewaySummary) GetUpdatedAt() GoogleProtobufTimestamp`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ManaV2GatewaySummary) GetUpdatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ManaV2GatewaySummary) SetUpdatedAt(v GoogleProtobufTimestamp)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ManaV2GatewaySummary) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



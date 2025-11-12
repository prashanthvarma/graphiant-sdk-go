# V1DevicesSummaryGetResponseSiteSummaryDeviceSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** |  | [optional] 
**IsVirtual** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**OverrideRegion** | Pointer to [**ManaV2Region**](ManaV2Region.md) |  | [optional] 
**PlatformName** | Pointer to **string** |  | [optional] 
**Region** | Pointer to [**ManaV2Region**](ManaV2Region.md) |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewV1DevicesSummaryGetResponseSiteSummaryDeviceSummary

`func NewV1DevicesSummaryGetResponseSiteSummaryDeviceSummary() *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary`

NewV1DevicesSummaryGetResponseSiteSummaryDeviceSummary instantiates a new V1DevicesSummaryGetResponseSiteSummaryDeviceSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesSummaryGetResponseSiteSummaryDeviceSummaryWithDefaults

`func NewV1DevicesSummaryGetResponseSiteSummaryDeviceSummaryWithDefaults() *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary`

NewV1DevicesSummaryGetResponseSiteSummaryDeviceSummaryWithDefaults instantiates a new V1DevicesSummaryGetResponseSiteSummaryDeviceSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIsVirtual

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetIsVirtual() bool`

GetIsVirtual returns the IsVirtual field if non-nil, zero value otherwise.

### GetIsVirtualOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetIsVirtualOk() (*bool, bool)`

GetIsVirtualOk returns a tuple with the IsVirtual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVirtual

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetIsVirtual(v bool)`

SetIsVirtual sets IsVirtual field to given value.

### HasIsVirtual

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasIsVirtual() bool`

HasIsVirtual returns a boolean if a field has been set.

### GetName

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasName() bool`

HasName returns a boolean if a field has been set.

### GetOverrideRegion

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetOverrideRegion() ManaV2Region`

GetOverrideRegion returns the OverrideRegion field if non-nil, zero value otherwise.

### GetOverrideRegionOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetOverrideRegionOk() (*ManaV2Region, bool)`

GetOverrideRegionOk returns a tuple with the OverrideRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideRegion

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetOverrideRegion(v ManaV2Region)`

SetOverrideRegion sets OverrideRegion field to given value.

### HasOverrideRegion

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasOverrideRegion() bool`

HasOverrideRegion returns a boolean if a field has been set.

### GetPlatformName

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetPlatformName() string`

GetPlatformName returns the PlatformName field if non-nil, zero value otherwise.

### GetPlatformNameOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetPlatformNameOk() (*string, bool)`

GetPlatformNameOk returns a tuple with the PlatformName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformName

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetPlatformName(v string)`

SetPlatformName sets PlatformName field to given value.

### HasPlatformName

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasPlatformName() bool`

HasPlatformName returns a boolean if a field has been set.

### GetRegion

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetRegion() ManaV2Region`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetRegionOk() (*ManaV2Region, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetRegion(v ManaV2Region)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetRole

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetStatus

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1DevicesSummaryGetResponseSiteSummaryDeviceSummary) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



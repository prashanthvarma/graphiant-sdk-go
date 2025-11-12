# V1DevicesSummaryGetResponseSiteSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Devices** | Pointer to [**[]V1DevicesSummaryGetResponseSiteSummaryDeviceSummary**](V1DevicesSummaryGetResponseSiteSummaryDeviceSummary.md) |  | [optional] 
**SiteId** | Pointer to **int64** |  | [optional] 
**SiteName** | Pointer to **string** |  | [optional] 

## Methods

### NewV1DevicesSummaryGetResponseSiteSummary

`func NewV1DevicesSummaryGetResponseSiteSummary() *V1DevicesSummaryGetResponseSiteSummary`

NewV1DevicesSummaryGetResponseSiteSummary instantiates a new V1DevicesSummaryGetResponseSiteSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DevicesSummaryGetResponseSiteSummaryWithDefaults

`func NewV1DevicesSummaryGetResponseSiteSummaryWithDefaults() *V1DevicesSummaryGetResponseSiteSummary`

NewV1DevicesSummaryGetResponseSiteSummaryWithDefaults instantiates a new V1DevicesSummaryGetResponseSiteSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevices

`func (o *V1DevicesSummaryGetResponseSiteSummary) GetDevices() []V1DevicesSummaryGetResponseSiteSummaryDeviceSummary`

GetDevices returns the Devices field if non-nil, zero value otherwise.

### GetDevicesOk

`func (o *V1DevicesSummaryGetResponseSiteSummary) GetDevicesOk() (*[]V1DevicesSummaryGetResponseSiteSummaryDeviceSummary, bool)`

GetDevicesOk returns a tuple with the Devices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevices

`func (o *V1DevicesSummaryGetResponseSiteSummary) SetDevices(v []V1DevicesSummaryGetResponseSiteSummaryDeviceSummary)`

SetDevices sets Devices field to given value.

### HasDevices

`func (o *V1DevicesSummaryGetResponseSiteSummary) HasDevices() bool`

HasDevices returns a boolean if a field has been set.

### GetSiteId

`func (o *V1DevicesSummaryGetResponseSiteSummary) GetSiteId() int64`

GetSiteId returns the SiteId field if non-nil, zero value otherwise.

### GetSiteIdOk

`func (o *V1DevicesSummaryGetResponseSiteSummary) GetSiteIdOk() (*int64, bool)`

GetSiteIdOk returns a tuple with the SiteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteId

`func (o *V1DevicesSummaryGetResponseSiteSummary) SetSiteId(v int64)`

SetSiteId sets SiteId field to given value.

### HasSiteId

`func (o *V1DevicesSummaryGetResponseSiteSummary) HasSiteId() bool`

HasSiteId returns a boolean if a field has been set.

### GetSiteName

`func (o *V1DevicesSummaryGetResponseSiteSummary) GetSiteName() string`

GetSiteName returns the SiteName field if non-nil, zero value otherwise.

### GetSiteNameOk

`func (o *V1DevicesSummaryGetResponseSiteSummary) GetSiteNameOk() (*string, bool)`

GetSiteNameOk returns a tuple with the SiteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteName

`func (o *V1DevicesSummaryGetResponseSiteSummary) SetSiteName(v string)`

SetSiteName sets SiteName field to given value.

### HasSiteName

`func (o *V1DevicesSummaryGetResponseSiteSummary) HasSiteName() bool`

HasSiteName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



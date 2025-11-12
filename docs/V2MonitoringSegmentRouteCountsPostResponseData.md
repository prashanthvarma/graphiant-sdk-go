# V2MonitoringSegmentRouteCountsPostResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | Pointer to **int64** |  | [optional] 
**Ipv4RouteCount** | Pointer to [**StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**Ipv6RouteCount** | Pointer to [**StatsmonV2StatsSample**](StatsmonV2StatsSample.md) |  | [optional] 
**SegmentName** | Pointer to **string** |  | [optional] 

## Methods

### NewV2MonitoringSegmentRouteCountsPostResponseData

`func NewV2MonitoringSegmentRouteCountsPostResponseData() *V2MonitoringSegmentRouteCountsPostResponseData`

NewV2MonitoringSegmentRouteCountsPostResponseData instantiates a new V2MonitoringSegmentRouteCountsPostResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2MonitoringSegmentRouteCountsPostResponseDataWithDefaults

`func NewV2MonitoringSegmentRouteCountsPostResponseDataWithDefaults() *V2MonitoringSegmentRouteCountsPostResponseData`

NewV2MonitoringSegmentRouteCountsPostResponseDataWithDefaults instantiates a new V2MonitoringSegmentRouteCountsPostResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetIpv4RouteCount

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetIpv4RouteCount() StatsmonV2StatsSample`

GetIpv4RouteCount returns the Ipv4RouteCount field if non-nil, zero value otherwise.

### GetIpv4RouteCountOk

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetIpv4RouteCountOk() (*StatsmonV2StatsSample, bool)`

GetIpv4RouteCountOk returns a tuple with the Ipv4RouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4RouteCount

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) SetIpv4RouteCount(v StatsmonV2StatsSample)`

SetIpv4RouteCount sets Ipv4RouteCount field to given value.

### HasIpv4RouteCount

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) HasIpv4RouteCount() bool`

HasIpv4RouteCount returns a boolean if a field has been set.

### GetIpv6RouteCount

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetIpv6RouteCount() StatsmonV2StatsSample`

GetIpv6RouteCount returns the Ipv6RouteCount field if non-nil, zero value otherwise.

### GetIpv6RouteCountOk

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetIpv6RouteCountOk() (*StatsmonV2StatsSample, bool)`

GetIpv6RouteCountOk returns a tuple with the Ipv6RouteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6RouteCount

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) SetIpv6RouteCount(v StatsmonV2StatsSample)`

SetIpv6RouteCount sets Ipv6RouteCount field to given value.

### HasIpv6RouteCount

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) HasIpv6RouteCount() bool`

HasIpv6RouteCount returns a boolean if a field has been set.

### GetSegmentName

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetSegmentName() string`

GetSegmentName returns the SegmentName field if non-nil, zero value otherwise.

### GetSegmentNameOk

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) GetSegmentNameOk() (*string, bool)`

GetSegmentNameOk returns a tuple with the SegmentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegmentName

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) SetSegmentName(v string)`

SetSegmentName sets SegmentName field to given value.

### HasSegmentName

`func (o *V2MonitoringSegmentRouteCountsPostResponseData) HasSegmentName() bool`

HasSegmentName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



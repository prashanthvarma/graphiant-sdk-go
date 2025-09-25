# V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerName** | Pointer to **string** |  | [optional] 
**FlippedView** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**IsB2B** | Pointer to **bool** |  | [optional] 
**IsProvider** | Pointer to **bool** |  | [optional] 
**SiteId** | Pointer to **int64** |  | [optional] 
**TimeWindow** | Pointer to [**V2NotificationlistPostRequestTimeWindow**](V2NotificationlistPostRequestTimeWindow.md) |  | [optional] 
**VrfId** | Pointer to **int64** |  | [optional] 

## Methods

### NewV1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest

`func NewV1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest() *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest`

NewV1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest instantiates a new V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequestWithDefaults

`func NewV1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequestWithDefaults() *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest`

NewV1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequestWithDefaults instantiates a new V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerName

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetFlippedView

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetFlippedView() bool`

GetFlippedView returns the FlippedView field if non-nil, zero value otherwise.

### GetFlippedViewOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetFlippedViewOk() (*bool, bool)`

GetFlippedViewOk returns a tuple with the FlippedView field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlippedView

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetFlippedView(v bool)`

SetFlippedView sets FlippedView field to given value.

### HasFlippedView

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasFlippedView() bool`

HasFlippedView returns a boolean if a field has been set.

### GetId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIsB2B

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetIsB2B() bool`

GetIsB2B returns the IsB2B field if non-nil, zero value otherwise.

### GetIsB2BOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetIsB2BOk() (*bool, bool)`

GetIsB2BOk returns a tuple with the IsB2B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsB2B

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetIsB2B(v bool)`

SetIsB2B sets IsB2B field to given value.

### HasIsB2B

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasIsB2B() bool`

HasIsB2B returns a boolean if a field has been set.

### GetIsProvider

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetIsProvider() bool`

GetIsProvider returns the IsProvider field if non-nil, zero value otherwise.

### GetIsProviderOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetIsProviderOk() (*bool, bool)`

GetIsProviderOk returns a tuple with the IsProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProvider

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetIsProvider(v bool)`

SetIsProvider sets IsProvider field to given value.

### HasIsProvider

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasIsProvider() bool`

HasIsProvider returns a boolean if a field has been set.

### GetSiteId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetSiteId() int64`

GetSiteId returns the SiteId field if non-nil, zero value otherwise.

### GetSiteIdOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetSiteIdOk() (*int64, bool)`

GetSiteIdOk returns a tuple with the SiteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetSiteId(v int64)`

SetSiteId sets SiteId field to given value.

### HasSiteId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasSiteId() bool`

HasSiteId returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetTimeWindow() V2NotificationlistPostRequestTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetTimeWindowOk() (*V2NotificationlistPostRequestTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetTimeWindow(v V2NotificationlistPostRequestTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.

### GetVrfId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetVrfId() int64`

GetVrfId returns the VrfId field if non-nil, zero value otherwise.

### GetVrfIdOk

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) GetVrfIdOk() (*int64, bool)`

GetVrfIdOk returns a tuple with the VrfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) SetVrfId(v int64)`

SetVrfId sets VrfId field to given value.

### HasVrfId

`func (o *V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest) HasVrfId() bool`

HasVrfId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



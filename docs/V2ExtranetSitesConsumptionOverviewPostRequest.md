# V2ExtranetSitesConsumptionOverviewPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerName** | Pointer to **string** |  | [optional] 
**FlippedView** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **int64** | the id associated with an entity - consumer_id for consumer, and service_id for the producer/service | [optional] 
**IsB2B** | Pointer to **bool** |  | [optional] 
**IsProvider** | Pointer to **bool** |  | [optional] 
**SiteId** | Pointer to **int64** |  | [optional] 
**TimeWindow** | Pointer to [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 
**VrfId** | Pointer to **int64** |  | [optional] 

## Methods

### NewV2ExtranetSitesConsumptionOverviewPostRequest

`func NewV2ExtranetSitesConsumptionOverviewPostRequest() *V2ExtranetSitesConsumptionOverviewPostRequest`

NewV2ExtranetSitesConsumptionOverviewPostRequest instantiates a new V2ExtranetSitesConsumptionOverviewPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2ExtranetSitesConsumptionOverviewPostRequestWithDefaults

`func NewV2ExtranetSitesConsumptionOverviewPostRequestWithDefaults() *V2ExtranetSitesConsumptionOverviewPostRequest`

NewV2ExtranetSitesConsumptionOverviewPostRequestWithDefaults instantiates a new V2ExtranetSitesConsumptionOverviewPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerName

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetFlippedView

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetFlippedView() bool`

GetFlippedView returns the FlippedView field if non-nil, zero value otherwise.

### GetFlippedViewOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetFlippedViewOk() (*bool, bool)`

GetFlippedViewOk returns a tuple with the FlippedView field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlippedView

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetFlippedView(v bool)`

SetFlippedView sets FlippedView field to given value.

### HasFlippedView

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasFlippedView() bool`

HasFlippedView returns a boolean if a field has been set.

### GetId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIsB2B

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetIsB2B() bool`

GetIsB2B returns the IsB2B field if non-nil, zero value otherwise.

### GetIsB2BOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetIsB2BOk() (*bool, bool)`

GetIsB2BOk returns a tuple with the IsB2B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsB2B

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetIsB2B(v bool)`

SetIsB2B sets IsB2B field to given value.

### HasIsB2B

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasIsB2B() bool`

HasIsB2B returns a boolean if a field has been set.

### GetIsProvider

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetIsProvider() bool`

GetIsProvider returns the IsProvider field if non-nil, zero value otherwise.

### GetIsProviderOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetIsProviderOk() (*bool, bool)`

GetIsProviderOk returns a tuple with the IsProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProvider

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetIsProvider(v bool)`

SetIsProvider sets IsProvider field to given value.

### HasIsProvider

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasIsProvider() bool`

HasIsProvider returns a boolean if a field has been set.

### GetSiteId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetSiteId() int64`

GetSiteId returns the SiteId field if non-nil, zero value otherwise.

### GetSiteIdOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetSiteIdOk() (*int64, bool)`

GetSiteIdOk returns a tuple with the SiteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetSiteId(v int64)`

SetSiteId sets SiteId field to given value.

### HasSiteId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasSiteId() bool`

HasSiteId returns a boolean if a field has been set.

### GetTimeWindow

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetTimeWindow() StatsmonTimeWindow`

GetTimeWindow returns the TimeWindow field if non-nil, zero value otherwise.

### GetTimeWindowOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetTimeWindowOk() (*StatsmonTimeWindow, bool)`

GetTimeWindowOk returns a tuple with the TimeWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeWindow

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetTimeWindow(v StatsmonTimeWindow)`

SetTimeWindow sets TimeWindow field to given value.

### HasTimeWindow

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasTimeWindow() bool`

HasTimeWindow returns a boolean if a field has been set.

### GetVrfId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetVrfId() int64`

GetVrfId returns the VrfId field if non-nil, zero value otherwise.

### GetVrfIdOk

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) GetVrfIdOk() (*int64, bool)`

GetVrfIdOk returns a tuple with the VrfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) SetVrfId(v int64)`

SetVrfId sets VrfId field to given value.

### HasVrfId

`func (o *V2ExtranetSitesConsumptionOverviewPostRequest) HasVrfId() bool`

HasVrfId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



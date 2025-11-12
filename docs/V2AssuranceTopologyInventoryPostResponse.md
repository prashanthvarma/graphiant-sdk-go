# V2AssuranceTopologyInventoryPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppNames** | Pointer to **[]string** |  | [optional] 
**ClientSites** | Pointer to [**[]AssuranceSite**](AssuranceSite.md) |  | [optional] 
**Regions** | Pointer to [**[]AssuranceRegion**](AssuranceRegion.md) |  | [optional] 
**ServerSites** | Pointer to [**[]AssuranceSite**](AssuranceSite.md) |  | [optional] 
**TopologyChangeTs** | Pointer to [**[]GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV2AssuranceTopologyInventoryPostResponse

`func NewV2AssuranceTopologyInventoryPostResponse() *V2AssuranceTopologyInventoryPostResponse`

NewV2AssuranceTopologyInventoryPostResponse instantiates a new V2AssuranceTopologyInventoryPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssuranceTopologyInventoryPostResponseWithDefaults

`func NewV2AssuranceTopologyInventoryPostResponseWithDefaults() *V2AssuranceTopologyInventoryPostResponse`

NewV2AssuranceTopologyInventoryPostResponseWithDefaults instantiates a new V2AssuranceTopologyInventoryPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppNames

`func (o *V2AssuranceTopologyInventoryPostResponse) GetAppNames() []string`

GetAppNames returns the AppNames field if non-nil, zero value otherwise.

### GetAppNamesOk

`func (o *V2AssuranceTopologyInventoryPostResponse) GetAppNamesOk() (*[]string, bool)`

GetAppNamesOk returns a tuple with the AppNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppNames

`func (o *V2AssuranceTopologyInventoryPostResponse) SetAppNames(v []string)`

SetAppNames sets AppNames field to given value.

### HasAppNames

`func (o *V2AssuranceTopologyInventoryPostResponse) HasAppNames() bool`

HasAppNames returns a boolean if a field has been set.

### GetClientSites

`func (o *V2AssuranceTopologyInventoryPostResponse) GetClientSites() []AssuranceSite`

GetClientSites returns the ClientSites field if non-nil, zero value otherwise.

### GetClientSitesOk

`func (o *V2AssuranceTopologyInventoryPostResponse) GetClientSitesOk() (*[]AssuranceSite, bool)`

GetClientSitesOk returns a tuple with the ClientSites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSites

`func (o *V2AssuranceTopologyInventoryPostResponse) SetClientSites(v []AssuranceSite)`

SetClientSites sets ClientSites field to given value.

### HasClientSites

`func (o *V2AssuranceTopologyInventoryPostResponse) HasClientSites() bool`

HasClientSites returns a boolean if a field has been set.

### GetRegions

`func (o *V2AssuranceTopologyInventoryPostResponse) GetRegions() []AssuranceRegion`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *V2AssuranceTopologyInventoryPostResponse) GetRegionsOk() (*[]AssuranceRegion, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *V2AssuranceTopologyInventoryPostResponse) SetRegions(v []AssuranceRegion)`

SetRegions sets Regions field to given value.

### HasRegions

`func (o *V2AssuranceTopologyInventoryPostResponse) HasRegions() bool`

HasRegions returns a boolean if a field has been set.

### GetServerSites

`func (o *V2AssuranceTopologyInventoryPostResponse) GetServerSites() []AssuranceSite`

GetServerSites returns the ServerSites field if non-nil, zero value otherwise.

### GetServerSitesOk

`func (o *V2AssuranceTopologyInventoryPostResponse) GetServerSitesOk() (*[]AssuranceSite, bool)`

GetServerSitesOk returns a tuple with the ServerSites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerSites

`func (o *V2AssuranceTopologyInventoryPostResponse) SetServerSites(v []AssuranceSite)`

SetServerSites sets ServerSites field to given value.

### HasServerSites

`func (o *V2AssuranceTopologyInventoryPostResponse) HasServerSites() bool`

HasServerSites returns a boolean if a field has been set.

### GetTopologyChangeTs

`func (o *V2AssuranceTopologyInventoryPostResponse) GetTopologyChangeTs() []GoogleProtobufTimestamp`

GetTopologyChangeTs returns the TopologyChangeTs field if non-nil, zero value otherwise.

### GetTopologyChangeTsOk

`func (o *V2AssuranceTopologyInventoryPostResponse) GetTopologyChangeTsOk() (*[]GoogleProtobufTimestamp, bool)`

GetTopologyChangeTsOk returns a tuple with the TopologyChangeTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyChangeTs

`func (o *V2AssuranceTopologyInventoryPostResponse) SetTopologyChangeTs(v []GoogleProtobufTimestamp)`

SetTopologyChangeTs sets TopologyChangeTs field to given value.

### HasTopologyChangeTs

`func (o *V2AssuranceTopologyInventoryPostResponse) HasTopologyChangeTs() bool`

HasTopologyChangeTs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



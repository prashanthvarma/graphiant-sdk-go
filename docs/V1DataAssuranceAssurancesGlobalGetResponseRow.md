# V1DataAssuranceAssurancesGlobalGetResponseRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Apps** | Pointer to [**[]V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry**](V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry.md) |  | [optional] 
**AssuranceId** | Pointer to **int64** |  | [optional] 
**AssuranceName** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**FlexAlgo** | Pointer to **string** |  | [optional] 
**Lans** | Pointer to [**[]V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry**](V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry.md) |  | [optional] 
**Sites** | Pointer to [**[]V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry**](V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry.md) |  | [optional] 
**UpdatedAt** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV1DataAssuranceAssurancesGlobalGetResponseRow

`func NewV1DataAssuranceAssurancesGlobalGetResponseRow() *V1DataAssuranceAssurancesGlobalGetResponseRow`

NewV1DataAssuranceAssurancesGlobalGetResponseRow instantiates a new V1DataAssuranceAssurancesGlobalGetResponseRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DataAssuranceAssurancesGlobalGetResponseRowWithDefaults

`func NewV1DataAssuranceAssurancesGlobalGetResponseRowWithDefaults() *V1DataAssuranceAssurancesGlobalGetResponseRow`

NewV1DataAssuranceAssurancesGlobalGetResponseRowWithDefaults instantiates a new V1DataAssuranceAssurancesGlobalGetResponseRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApps

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetApps() []V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetAppsOk() (*[]V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetApps(v []V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry)`

SetApps sets Apps field to given value.

### HasApps

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasApps() bool`

HasApps returns a boolean if a field has been set.

### GetAssuranceId

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetAssuranceId() int64`

GetAssuranceId returns the AssuranceId field if non-nil, zero value otherwise.

### GetAssuranceIdOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetAssuranceIdOk() (*int64, bool)`

GetAssuranceIdOk returns a tuple with the AssuranceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssuranceId

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetAssuranceId(v int64)`

SetAssuranceId sets AssuranceId field to given value.

### HasAssuranceId

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasAssuranceId() bool`

HasAssuranceId returns a boolean if a field has been set.

### GetAssuranceName

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetAssuranceName() string`

GetAssuranceName returns the AssuranceName field if non-nil, zero value otherwise.

### GetAssuranceNameOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetAssuranceNameOk() (*string, bool)`

GetAssuranceNameOk returns a tuple with the AssuranceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssuranceName

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetAssuranceName(v string)`

SetAssuranceName sets AssuranceName field to given value.

### HasAssuranceName

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasAssuranceName() bool`

HasAssuranceName returns a boolean if a field has been set.

### GetCreatedAt

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetCreatedAt() GoogleProtobufTimestamp`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetCreatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetCreatedAt(v GoogleProtobufTimestamp)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFlexAlgo

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetFlexAlgo() string`

GetFlexAlgo returns the FlexAlgo field if non-nil, zero value otherwise.

### GetFlexAlgoOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetFlexAlgoOk() (*string, bool)`

GetFlexAlgoOk returns a tuple with the FlexAlgo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlexAlgo

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetFlexAlgo(v string)`

SetFlexAlgo sets FlexAlgo field to given value.

### HasFlexAlgo

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasFlexAlgo() bool`

HasFlexAlgo returns a boolean if a field has been set.

### GetLans

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetLans() []V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry`

GetLans returns the Lans field if non-nil, zero value otherwise.

### GetLansOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetLansOk() (*[]V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry, bool)`

GetLansOk returns a tuple with the Lans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLans

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetLans(v []V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry)`

SetLans sets Lans field to given value.

### HasLans

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasLans() bool`

HasLans returns a boolean if a field has been set.

### GetSites

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetSites() []V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry`

GetSites returns the Sites field if non-nil, zero value otherwise.

### GetSitesOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetSitesOk() (*[]V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry, bool)`

GetSitesOk returns a tuple with the Sites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSites

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetSites(v []V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry)`

SetSites sets Sites field to given value.

### HasSites

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasSites() bool`

HasSites returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetUpdatedAt() GoogleProtobufTimestamp`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) GetUpdatedAtOk() (*GoogleProtobufTimestamp, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) SetUpdatedAt(v GoogleProtobufTimestamp)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *V1DataAssuranceAssurancesGlobalGetResponseRow) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



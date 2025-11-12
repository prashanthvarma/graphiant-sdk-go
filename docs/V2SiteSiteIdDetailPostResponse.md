# V2SiteSiteIdDetailPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Site** | Pointer to [**StatsmonV2SiteInfo**](StatsmonV2SiteInfo.md) |  | [optional] 
**Snapshots** | Pointer to [**[]GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Methods

### NewV2SiteSiteIdDetailPostResponse

`func NewV2SiteSiteIdDetailPostResponse() *V2SiteSiteIdDetailPostResponse`

NewV2SiteSiteIdDetailPostResponse instantiates a new V2SiteSiteIdDetailPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2SiteSiteIdDetailPostResponseWithDefaults

`func NewV2SiteSiteIdDetailPostResponseWithDefaults() *V2SiteSiteIdDetailPostResponse`

NewV2SiteSiteIdDetailPostResponseWithDefaults instantiates a new V2SiteSiteIdDetailPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSite

`func (o *V2SiteSiteIdDetailPostResponse) GetSite() StatsmonV2SiteInfo`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *V2SiteSiteIdDetailPostResponse) GetSiteOk() (*StatsmonV2SiteInfo, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *V2SiteSiteIdDetailPostResponse) SetSite(v StatsmonV2SiteInfo)`

SetSite sets Site field to given value.

### HasSite

`func (o *V2SiteSiteIdDetailPostResponse) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetSnapshots

`func (o *V2SiteSiteIdDetailPostResponse) GetSnapshots() []GoogleProtobufTimestamp`

GetSnapshots returns the Snapshots field if non-nil, zero value otherwise.

### GetSnapshotsOk

`func (o *V2SiteSiteIdDetailPostResponse) GetSnapshotsOk() (*[]GoogleProtobufTimestamp, bool)`

GetSnapshotsOk returns a tuple with the Snapshots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshots

`func (o *V2SiteSiteIdDetailPostResponse) SetSnapshots(v []GoogleProtobufTimestamp)`

SetSnapshots sets Snapshots field to given value.

### HasSnapshots

`func (o *V2SiteSiteIdDetailPostResponse) HasSnapshots() bool`

HasSnapshots returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1ExtranetsB2bConsumerPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | Pointer to [**[]ManaV2ConsumerDeviceInformation**](ManaV2ConsumerDeviceInformation.md) |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 
**Policy** | Pointer to [**[]ManaV2ExtranetConsumerLanSegmentPolicyResponse**](ManaV2ExtranetConsumerLanSegmentPolicyResponse.md) |  | [optional] 
**SiteInformation** | Pointer to [**[]ManaV2B2bSiteInformation**](ManaV2B2bSiteInformation.md) |  | [optional] 

## Methods

### NewV1ExtranetsB2bConsumerPostResponse

`func NewV1ExtranetsB2bConsumerPostResponse() *V1ExtranetsB2bConsumerPostResponse`

NewV1ExtranetsB2bConsumerPostResponse instantiates a new V1ExtranetsB2bConsumerPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bConsumerPostResponseWithDefaults

`func NewV1ExtranetsB2bConsumerPostResponseWithDefaults() *V1ExtranetsB2bConsumerPostResponse`

NewV1ExtranetsB2bConsumerPostResponseWithDefaults instantiates a new V1ExtranetsB2bConsumerPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevice

`func (o *V1ExtranetsB2bConsumerPostResponse) GetDevice() []ManaV2ConsumerDeviceInformation`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *V1ExtranetsB2bConsumerPostResponse) GetDeviceOk() (*[]ManaV2ConsumerDeviceInformation, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *V1ExtranetsB2bConsumerPostResponse) SetDevice(v []ManaV2ConsumerDeviceInformation)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *V1ExtranetsB2bConsumerPostResponse) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetId

`func (o *V1ExtranetsB2bConsumerPostResponse) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1ExtranetsB2bConsumerPostResponse) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1ExtranetsB2bConsumerPostResponse) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *V1ExtranetsB2bConsumerPostResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPolicy

`func (o *V1ExtranetsB2bConsumerPostResponse) GetPolicy() []ManaV2ExtranetConsumerLanSegmentPolicyResponse`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *V1ExtranetsB2bConsumerPostResponse) GetPolicyOk() (*[]ManaV2ExtranetConsumerLanSegmentPolicyResponse, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *V1ExtranetsB2bConsumerPostResponse) SetPolicy(v []ManaV2ExtranetConsumerLanSegmentPolicyResponse)`

SetPolicy sets Policy field to given value.

### HasPolicy

`func (o *V1ExtranetsB2bConsumerPostResponse) HasPolicy() bool`

HasPolicy returns a boolean if a field has been set.

### GetSiteInformation

`func (o *V1ExtranetsB2bConsumerPostResponse) GetSiteInformation() []ManaV2B2bSiteInformation`

GetSiteInformation returns the SiteInformation field if non-nil, zero value otherwise.

### GetSiteInformationOk

`func (o *V1ExtranetsB2bConsumerPostResponse) GetSiteInformationOk() (*[]ManaV2B2bSiteInformation, bool)`

GetSiteInformationOk returns a tuple with the SiteInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteInformation

`func (o *V1ExtranetsB2bConsumerPostResponse) SetSiteInformation(v []ManaV2B2bSiteInformation)`

SetSiteInformation sets SiteInformation field to given value.

### HasSiteInformation

`func (o *V1ExtranetsB2bConsumerPostResponse) HasSiteInformation() bool`

HasSiteInformation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



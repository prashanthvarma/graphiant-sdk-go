# V1ExtranetsB2bPeeringProducerPostRequestPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**GlobalObjectOps** | Pointer to [**map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue.md) |  | [optional] 
**PrefixTags** | Pointer to [**[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner**](V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner.md) |  | [optional] 
**ServiceLanSegment** | Pointer to **int64** |  | [optional] 
**Site** | Pointer to [**[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringProducerPostRequestPolicy

`func NewV1ExtranetsB2bPeeringProducerPostRequestPolicy() *V1ExtranetsB2bPeeringProducerPostRequestPolicy`

NewV1ExtranetsB2bPeeringProducerPostRequestPolicy instantiates a new V1ExtranetsB2bPeeringProducerPostRequestPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringProducerPostRequestPolicyWithDefaults

`func NewV1ExtranetsB2bPeeringProducerPostRequestPolicyWithDefaults() *V1ExtranetsB2bPeeringProducerPostRequestPolicy`

NewV1ExtranetsB2bPeeringProducerPostRequestPolicyWithDefaults instantiates a new V1ExtranetsB2bPeeringProducerPostRequestPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetGlobalObjectOps

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetGlobalObjectOps() map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue`

GetGlobalObjectOps returns the GlobalObjectOps field if non-nil, zero value otherwise.

### GetGlobalObjectOpsOk

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetGlobalObjectOpsOk() (*map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue, bool)`

GetGlobalObjectOpsOk returns a tuple with the GlobalObjectOps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalObjectOps

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) SetGlobalObjectOps(v map[string]V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue)`

SetGlobalObjectOps sets GlobalObjectOps field to given value.

### HasGlobalObjectOps

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) HasGlobalObjectOps() bool`

HasGlobalObjectOps returns a boolean if a field has been set.

### GetPrefixTags

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetPrefixTags() []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner`

GetPrefixTags returns the PrefixTags field if non-nil, zero value otherwise.

### GetPrefixTagsOk

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetPrefixTagsOk() (*[]V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner, bool)`

GetPrefixTagsOk returns a tuple with the PrefixTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixTags

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) SetPrefixTags(v []V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner)`

SetPrefixTags sets PrefixTags field to given value.

### HasPrefixTags

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) HasPrefixTags() bool`

HasPrefixTags returns a boolean if a field has been set.

### GetServiceLanSegment

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetServiceLanSegment() int64`

GetServiceLanSegment returns the ServiceLanSegment field if non-nil, zero value otherwise.

### GetServiceLanSegmentOk

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetServiceLanSegmentOk() (*int64, bool)`

GetServiceLanSegmentOk returns a tuple with the ServiceLanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceLanSegment

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) SetServiceLanSegment(v int64)`

SetServiceLanSegment sets ServiceLanSegment field to given value.

### HasServiceLanSegment

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) HasServiceLanSegment() bool`

HasServiceLanSegment returns a boolean if a field has been set.

### GetSite

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetSite() []V1ExtranetsB2bConsumerPostRequestSiteInformationInner`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetSiteOk() (*[]V1ExtranetsB2bConsumerPostRequestSiteInformationInner, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) SetSite(v []V1ExtranetsB2bConsumerPostRequestSiteInformationInner)`

SetSite sets Site field to given value.

### HasSite

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetType

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *V1ExtranetsB2bPeeringProducerPostRequestPolicy) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



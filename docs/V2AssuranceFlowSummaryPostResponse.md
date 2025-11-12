# V2AssuranceFlowSummaryPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppName** | Pointer to **string** |  | [optional] 
**Bucket** | Pointer to **string** |  | [optional] 
**ClientEndpoint** | Pointer to [**V2AssuranceFlowSummaryPostResponseEndpointDetails**](V2AssuranceFlowSummaryPostResponseEndpointDetails.md) |  | [optional] 
**ClientIp** | Pointer to **string** |  | [optional] 
**FirstSeenTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**LanSegment** | Pointer to **string** |  | [optional] 
**LastSeenTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**RiskStatus** | Pointer to **string** |  | [optional] 
**ServerEndpoint** | Pointer to [**V2AssuranceFlowSummaryPostResponseEndpointDetails**](V2AssuranceFlowSummaryPostResponseEndpointDetails.md) |  | [optional] 
**ServerIp** | Pointer to **string** |  | [optional] 
**ServerPort** | Pointer to **int32** |  | [optional] 
**SlaClass** | Pointer to **string** |  | [optional] 

## Methods

### NewV2AssuranceFlowSummaryPostResponse

`func NewV2AssuranceFlowSummaryPostResponse() *V2AssuranceFlowSummaryPostResponse`

NewV2AssuranceFlowSummaryPostResponse instantiates a new V2AssuranceFlowSummaryPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2AssuranceFlowSummaryPostResponseWithDefaults

`func NewV2AssuranceFlowSummaryPostResponseWithDefaults() *V2AssuranceFlowSummaryPostResponse`

NewV2AssuranceFlowSummaryPostResponseWithDefaults instantiates a new V2AssuranceFlowSummaryPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppName

`func (o *V2AssuranceFlowSummaryPostResponse) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *V2AssuranceFlowSummaryPostResponse) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *V2AssuranceFlowSummaryPostResponse) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### GetBucket

`func (o *V2AssuranceFlowSummaryPostResponse) GetBucket() string`

GetBucket returns the Bucket field if non-nil, zero value otherwise.

### GetBucketOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetBucketOk() (*string, bool)`

GetBucketOk returns a tuple with the Bucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucket

`func (o *V2AssuranceFlowSummaryPostResponse) SetBucket(v string)`

SetBucket sets Bucket field to given value.

### HasBucket

`func (o *V2AssuranceFlowSummaryPostResponse) HasBucket() bool`

HasBucket returns a boolean if a field has been set.

### GetClientEndpoint

`func (o *V2AssuranceFlowSummaryPostResponse) GetClientEndpoint() V2AssuranceFlowSummaryPostResponseEndpointDetails`

GetClientEndpoint returns the ClientEndpoint field if non-nil, zero value otherwise.

### GetClientEndpointOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetClientEndpointOk() (*V2AssuranceFlowSummaryPostResponseEndpointDetails, bool)`

GetClientEndpointOk returns a tuple with the ClientEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientEndpoint

`func (o *V2AssuranceFlowSummaryPostResponse) SetClientEndpoint(v V2AssuranceFlowSummaryPostResponseEndpointDetails)`

SetClientEndpoint sets ClientEndpoint field to given value.

### HasClientEndpoint

`func (o *V2AssuranceFlowSummaryPostResponse) HasClientEndpoint() bool`

HasClientEndpoint returns a boolean if a field has been set.

### GetClientIp

`func (o *V2AssuranceFlowSummaryPostResponse) GetClientIp() string`

GetClientIp returns the ClientIp field if non-nil, zero value otherwise.

### GetClientIpOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetClientIpOk() (*string, bool)`

GetClientIpOk returns a tuple with the ClientIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIp

`func (o *V2AssuranceFlowSummaryPostResponse) SetClientIp(v string)`

SetClientIp sets ClientIp field to given value.

### HasClientIp

`func (o *V2AssuranceFlowSummaryPostResponse) HasClientIp() bool`

HasClientIp returns a boolean if a field has been set.

### GetFirstSeenTs

`func (o *V2AssuranceFlowSummaryPostResponse) GetFirstSeenTs() GoogleProtobufTimestamp`

GetFirstSeenTs returns the FirstSeenTs field if non-nil, zero value otherwise.

### GetFirstSeenTsOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetFirstSeenTsOk() (*GoogleProtobufTimestamp, bool)`

GetFirstSeenTsOk returns a tuple with the FirstSeenTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstSeenTs

`func (o *V2AssuranceFlowSummaryPostResponse) SetFirstSeenTs(v GoogleProtobufTimestamp)`

SetFirstSeenTs sets FirstSeenTs field to given value.

### HasFirstSeenTs

`func (o *V2AssuranceFlowSummaryPostResponse) HasFirstSeenTs() bool`

HasFirstSeenTs returns a boolean if a field has been set.

### GetLanSegment

`func (o *V2AssuranceFlowSummaryPostResponse) GetLanSegment() string`

GetLanSegment returns the LanSegment field if non-nil, zero value otherwise.

### GetLanSegmentOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetLanSegmentOk() (*string, bool)`

GetLanSegmentOk returns a tuple with the LanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegment

`func (o *V2AssuranceFlowSummaryPostResponse) SetLanSegment(v string)`

SetLanSegment sets LanSegment field to given value.

### HasLanSegment

`func (o *V2AssuranceFlowSummaryPostResponse) HasLanSegment() bool`

HasLanSegment returns a boolean if a field has been set.

### GetLastSeenTs

`func (o *V2AssuranceFlowSummaryPostResponse) GetLastSeenTs() GoogleProtobufTimestamp`

GetLastSeenTs returns the LastSeenTs field if non-nil, zero value otherwise.

### GetLastSeenTsOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetLastSeenTsOk() (*GoogleProtobufTimestamp, bool)`

GetLastSeenTsOk returns a tuple with the LastSeenTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenTs

`func (o *V2AssuranceFlowSummaryPostResponse) SetLastSeenTs(v GoogleProtobufTimestamp)`

SetLastSeenTs sets LastSeenTs field to given value.

### HasLastSeenTs

`func (o *V2AssuranceFlowSummaryPostResponse) HasLastSeenTs() bool`

HasLastSeenTs returns a boolean if a field has been set.

### GetRiskStatus

`func (o *V2AssuranceFlowSummaryPostResponse) GetRiskStatus() string`

GetRiskStatus returns the RiskStatus field if non-nil, zero value otherwise.

### GetRiskStatusOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetRiskStatusOk() (*string, bool)`

GetRiskStatusOk returns a tuple with the RiskStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRiskStatus

`func (o *V2AssuranceFlowSummaryPostResponse) SetRiskStatus(v string)`

SetRiskStatus sets RiskStatus field to given value.

### HasRiskStatus

`func (o *V2AssuranceFlowSummaryPostResponse) HasRiskStatus() bool`

HasRiskStatus returns a boolean if a field has been set.

### GetServerEndpoint

`func (o *V2AssuranceFlowSummaryPostResponse) GetServerEndpoint() V2AssuranceFlowSummaryPostResponseEndpointDetails`

GetServerEndpoint returns the ServerEndpoint field if non-nil, zero value otherwise.

### GetServerEndpointOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetServerEndpointOk() (*V2AssuranceFlowSummaryPostResponseEndpointDetails, bool)`

GetServerEndpointOk returns a tuple with the ServerEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerEndpoint

`func (o *V2AssuranceFlowSummaryPostResponse) SetServerEndpoint(v V2AssuranceFlowSummaryPostResponseEndpointDetails)`

SetServerEndpoint sets ServerEndpoint field to given value.

### HasServerEndpoint

`func (o *V2AssuranceFlowSummaryPostResponse) HasServerEndpoint() bool`

HasServerEndpoint returns a boolean if a field has been set.

### GetServerIp

`func (o *V2AssuranceFlowSummaryPostResponse) GetServerIp() string`

GetServerIp returns the ServerIp field if non-nil, zero value otherwise.

### GetServerIpOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetServerIpOk() (*string, bool)`

GetServerIpOk returns a tuple with the ServerIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerIp

`func (o *V2AssuranceFlowSummaryPostResponse) SetServerIp(v string)`

SetServerIp sets ServerIp field to given value.

### HasServerIp

`func (o *V2AssuranceFlowSummaryPostResponse) HasServerIp() bool`

HasServerIp returns a boolean if a field has been set.

### GetServerPort

`func (o *V2AssuranceFlowSummaryPostResponse) GetServerPort() int32`

GetServerPort returns the ServerPort field if non-nil, zero value otherwise.

### GetServerPortOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetServerPortOk() (*int32, bool)`

GetServerPortOk returns a tuple with the ServerPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerPort

`func (o *V2AssuranceFlowSummaryPostResponse) SetServerPort(v int32)`

SetServerPort sets ServerPort field to given value.

### HasServerPort

`func (o *V2AssuranceFlowSummaryPostResponse) HasServerPort() bool`

HasServerPort returns a boolean if a field has been set.

### GetSlaClass

`func (o *V2AssuranceFlowSummaryPostResponse) GetSlaClass() string`

GetSlaClass returns the SlaClass field if non-nil, zero value otherwise.

### GetSlaClassOk

`func (o *V2AssuranceFlowSummaryPostResponse) GetSlaClassOk() (*string, bool)`

GetSlaClassOk returns a tuple with the SlaClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlaClass

`func (o *V2AssuranceFlowSummaryPostResponse) SetSlaClass(v string)`

SetSlaClass sets SlaClass field to given value.

### HasSlaClass

`func (o *V2AssuranceFlowSummaryPostResponse) HasSlaClass() bool`

HasSlaClass returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



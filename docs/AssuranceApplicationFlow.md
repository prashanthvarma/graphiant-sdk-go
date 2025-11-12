# AssuranceApplicationFlow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppName** | Pointer to **string** |  | [optional] 
**ClientIp** | Pointer to **string** |  | [optional] 
**ClientSite** | Pointer to [**AssuranceSite**](AssuranceSite.md) |  | [optional] 
**FirstSeenTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**LanSegment** | Pointer to **string** |  | [optional] 
**LastSeenTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ServerIp** | Pointer to **string** |  | [optional] 
**ServerPort** | Pointer to **int32** |  | [optional] 
**ServerSite** | Pointer to [**AssuranceSite**](AssuranceSite.md) |  | [optional] 

## Methods

### NewAssuranceApplicationFlow

`func NewAssuranceApplicationFlow() *AssuranceApplicationFlow`

NewAssuranceApplicationFlow instantiates a new AssuranceApplicationFlow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssuranceApplicationFlowWithDefaults

`func NewAssuranceApplicationFlowWithDefaults() *AssuranceApplicationFlow`

NewAssuranceApplicationFlowWithDefaults instantiates a new AssuranceApplicationFlow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppName

`func (o *AssuranceApplicationFlow) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *AssuranceApplicationFlow) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *AssuranceApplicationFlow) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *AssuranceApplicationFlow) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### GetClientIp

`func (o *AssuranceApplicationFlow) GetClientIp() string`

GetClientIp returns the ClientIp field if non-nil, zero value otherwise.

### GetClientIpOk

`func (o *AssuranceApplicationFlow) GetClientIpOk() (*string, bool)`

GetClientIpOk returns a tuple with the ClientIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIp

`func (o *AssuranceApplicationFlow) SetClientIp(v string)`

SetClientIp sets ClientIp field to given value.

### HasClientIp

`func (o *AssuranceApplicationFlow) HasClientIp() bool`

HasClientIp returns a boolean if a field has been set.

### GetClientSite

`func (o *AssuranceApplicationFlow) GetClientSite() AssuranceSite`

GetClientSite returns the ClientSite field if non-nil, zero value otherwise.

### GetClientSiteOk

`func (o *AssuranceApplicationFlow) GetClientSiteOk() (*AssuranceSite, bool)`

GetClientSiteOk returns a tuple with the ClientSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSite

`func (o *AssuranceApplicationFlow) SetClientSite(v AssuranceSite)`

SetClientSite sets ClientSite field to given value.

### HasClientSite

`func (o *AssuranceApplicationFlow) HasClientSite() bool`

HasClientSite returns a boolean if a field has been set.

### GetFirstSeenTs

`func (o *AssuranceApplicationFlow) GetFirstSeenTs() GoogleProtobufTimestamp`

GetFirstSeenTs returns the FirstSeenTs field if non-nil, zero value otherwise.

### GetFirstSeenTsOk

`func (o *AssuranceApplicationFlow) GetFirstSeenTsOk() (*GoogleProtobufTimestamp, bool)`

GetFirstSeenTsOk returns a tuple with the FirstSeenTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstSeenTs

`func (o *AssuranceApplicationFlow) SetFirstSeenTs(v GoogleProtobufTimestamp)`

SetFirstSeenTs sets FirstSeenTs field to given value.

### HasFirstSeenTs

`func (o *AssuranceApplicationFlow) HasFirstSeenTs() bool`

HasFirstSeenTs returns a boolean if a field has been set.

### GetLanSegment

`func (o *AssuranceApplicationFlow) GetLanSegment() string`

GetLanSegment returns the LanSegment field if non-nil, zero value otherwise.

### GetLanSegmentOk

`func (o *AssuranceApplicationFlow) GetLanSegmentOk() (*string, bool)`

GetLanSegmentOk returns a tuple with the LanSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanSegment

`func (o *AssuranceApplicationFlow) SetLanSegment(v string)`

SetLanSegment sets LanSegment field to given value.

### HasLanSegment

`func (o *AssuranceApplicationFlow) HasLanSegment() bool`

HasLanSegment returns a boolean if a field has been set.

### GetLastSeenTs

`func (o *AssuranceApplicationFlow) GetLastSeenTs() GoogleProtobufTimestamp`

GetLastSeenTs returns the LastSeenTs field if non-nil, zero value otherwise.

### GetLastSeenTsOk

`func (o *AssuranceApplicationFlow) GetLastSeenTsOk() (*GoogleProtobufTimestamp, bool)`

GetLastSeenTsOk returns a tuple with the LastSeenTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenTs

`func (o *AssuranceApplicationFlow) SetLastSeenTs(v GoogleProtobufTimestamp)`

SetLastSeenTs sets LastSeenTs field to given value.

### HasLastSeenTs

`func (o *AssuranceApplicationFlow) HasLastSeenTs() bool`

HasLastSeenTs returns a boolean if a field has been set.

### GetServerIp

`func (o *AssuranceApplicationFlow) GetServerIp() string`

GetServerIp returns the ServerIp field if non-nil, zero value otherwise.

### GetServerIpOk

`func (o *AssuranceApplicationFlow) GetServerIpOk() (*string, bool)`

GetServerIpOk returns a tuple with the ServerIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerIp

`func (o *AssuranceApplicationFlow) SetServerIp(v string)`

SetServerIp sets ServerIp field to given value.

### HasServerIp

`func (o *AssuranceApplicationFlow) HasServerIp() bool`

HasServerIp returns a boolean if a field has been set.

### GetServerPort

`func (o *AssuranceApplicationFlow) GetServerPort() int32`

GetServerPort returns the ServerPort field if non-nil, zero value otherwise.

### GetServerPortOk

`func (o *AssuranceApplicationFlow) GetServerPortOk() (*int32, bool)`

GetServerPortOk returns a tuple with the ServerPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerPort

`func (o *AssuranceApplicationFlow) SetServerPort(v int32)`

SetServerPort sets ServerPort field to given value.

### HasServerPort

`func (o *AssuranceApplicationFlow) HasServerPort() bool`

HasServerPort returns a boolean if a field has been set.

### GetServerSite

`func (o *AssuranceApplicationFlow) GetServerSite() AssuranceSite`

GetServerSite returns the ServerSite field if non-nil, zero value otherwise.

### GetServerSiteOk

`func (o *AssuranceApplicationFlow) GetServerSiteOk() (*AssuranceSite, bool)`

GetServerSiteOk returns a tuple with the ServerSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerSite

`func (o *AssuranceApplicationFlow) SetServerSite(v AssuranceSite)`

SetServerSite sets ServerSite field to given value.

### HasServerSite

`func (o *AssuranceApplicationFlow) HasServerSite() bool`

HasServerSite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



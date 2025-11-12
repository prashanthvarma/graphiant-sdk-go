# DiagnosticToolsSpeedtestParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Provider** | **string** | Speedtest provider name (required) | 
**ServerId** | Pointer to **string** | This is fetched using GetSpeedtestServers API | [optional] 
**Target** | [**DiagnosticToolsTargetType**](DiagnosticToolsTargetType.md) |  | 
**Token** | Pointer to **string** | Token to be sent in subsequent lookup | [optional] 

## Methods

### NewDiagnosticToolsSpeedtestParams

`func NewDiagnosticToolsSpeedtestParams(provider string, target DiagnosticToolsTargetType, ) *DiagnosticToolsSpeedtestParams`

NewDiagnosticToolsSpeedtestParams instantiates a new DiagnosticToolsSpeedtestParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsSpeedtestParamsWithDefaults

`func NewDiagnosticToolsSpeedtestParamsWithDefaults() *DiagnosticToolsSpeedtestParams`

NewDiagnosticToolsSpeedtestParamsWithDefaults instantiates a new DiagnosticToolsSpeedtestParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProvider

`func (o *DiagnosticToolsSpeedtestParams) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *DiagnosticToolsSpeedtestParams) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *DiagnosticToolsSpeedtestParams) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetServerId

`func (o *DiagnosticToolsSpeedtestParams) GetServerId() string`

GetServerId returns the ServerId field if non-nil, zero value otherwise.

### GetServerIdOk

`func (o *DiagnosticToolsSpeedtestParams) GetServerIdOk() (*string, bool)`

GetServerIdOk returns a tuple with the ServerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerId

`func (o *DiagnosticToolsSpeedtestParams) SetServerId(v string)`

SetServerId sets ServerId field to given value.

### HasServerId

`func (o *DiagnosticToolsSpeedtestParams) HasServerId() bool`

HasServerId returns a boolean if a field has been set.

### GetTarget

`func (o *DiagnosticToolsSpeedtestParams) GetTarget() DiagnosticToolsTargetType`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *DiagnosticToolsSpeedtestParams) GetTargetOk() (*DiagnosticToolsTargetType, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *DiagnosticToolsSpeedtestParams) SetTarget(v DiagnosticToolsTargetType)`

SetTarget sets Target field to given value.


### GetToken

`func (o *DiagnosticToolsSpeedtestParams) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *DiagnosticToolsSpeedtestParams) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *DiagnosticToolsSpeedtestParams) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *DiagnosticToolsSpeedtestParams) HasToken() bool`

HasToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



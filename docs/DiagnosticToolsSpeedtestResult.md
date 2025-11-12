# DiagnosticToolsSpeedtestResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvgPingTime** | Pointer to **float64** | Avg Ping Time in milli seconds (required) | [optional] 
**DateTime** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**DownloadSpeed** | Pointer to **float64** | Download speed in Mbps (required) | [optional] 
**Isp** | Pointer to **string** | ISP details (required) | [optional] 
**MaxPingTime** | Pointer to **float64** | Max PingTime in milli seconds (required) | [optional] 
**MinPingTime** | Pointer to **float64** | Min Ping Time in milli seconds (required) | [optional] 
**Result** | Pointer to **string** | Status of the speedtest operation (required) | [optional] 
**ServerDetails** | Pointer to [**DiagnosticToolsSpeedtestServer**](DiagnosticToolsSpeedtestServer.md) |  | [optional] 
**UploadSpeed** | Pointer to **float64** | Upload speed in Mbps (required) | [optional] 

## Methods

### NewDiagnosticToolsSpeedtestResult

`func NewDiagnosticToolsSpeedtestResult() *DiagnosticToolsSpeedtestResult`

NewDiagnosticToolsSpeedtestResult instantiates a new DiagnosticToolsSpeedtestResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsSpeedtestResultWithDefaults

`func NewDiagnosticToolsSpeedtestResultWithDefaults() *DiagnosticToolsSpeedtestResult`

NewDiagnosticToolsSpeedtestResultWithDefaults instantiates a new DiagnosticToolsSpeedtestResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvgPingTime

`func (o *DiagnosticToolsSpeedtestResult) GetAvgPingTime() float64`

GetAvgPingTime returns the AvgPingTime field if non-nil, zero value otherwise.

### GetAvgPingTimeOk

`func (o *DiagnosticToolsSpeedtestResult) GetAvgPingTimeOk() (*float64, bool)`

GetAvgPingTimeOk returns a tuple with the AvgPingTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPingTime

`func (o *DiagnosticToolsSpeedtestResult) SetAvgPingTime(v float64)`

SetAvgPingTime sets AvgPingTime field to given value.

### HasAvgPingTime

`func (o *DiagnosticToolsSpeedtestResult) HasAvgPingTime() bool`

HasAvgPingTime returns a boolean if a field has been set.

### GetDateTime

`func (o *DiagnosticToolsSpeedtestResult) GetDateTime() GoogleProtobufTimestamp`

GetDateTime returns the DateTime field if non-nil, zero value otherwise.

### GetDateTimeOk

`func (o *DiagnosticToolsSpeedtestResult) GetDateTimeOk() (*GoogleProtobufTimestamp, bool)`

GetDateTimeOk returns a tuple with the DateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTime

`func (o *DiagnosticToolsSpeedtestResult) SetDateTime(v GoogleProtobufTimestamp)`

SetDateTime sets DateTime field to given value.

### HasDateTime

`func (o *DiagnosticToolsSpeedtestResult) HasDateTime() bool`

HasDateTime returns a boolean if a field has been set.

### GetDownloadSpeed

`func (o *DiagnosticToolsSpeedtestResult) GetDownloadSpeed() float64`

GetDownloadSpeed returns the DownloadSpeed field if non-nil, zero value otherwise.

### GetDownloadSpeedOk

`func (o *DiagnosticToolsSpeedtestResult) GetDownloadSpeedOk() (*float64, bool)`

GetDownloadSpeedOk returns a tuple with the DownloadSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadSpeed

`func (o *DiagnosticToolsSpeedtestResult) SetDownloadSpeed(v float64)`

SetDownloadSpeed sets DownloadSpeed field to given value.

### HasDownloadSpeed

`func (o *DiagnosticToolsSpeedtestResult) HasDownloadSpeed() bool`

HasDownloadSpeed returns a boolean if a field has been set.

### GetIsp

`func (o *DiagnosticToolsSpeedtestResult) GetIsp() string`

GetIsp returns the Isp field if non-nil, zero value otherwise.

### GetIspOk

`func (o *DiagnosticToolsSpeedtestResult) GetIspOk() (*string, bool)`

GetIspOk returns a tuple with the Isp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsp

`func (o *DiagnosticToolsSpeedtestResult) SetIsp(v string)`

SetIsp sets Isp field to given value.

### HasIsp

`func (o *DiagnosticToolsSpeedtestResult) HasIsp() bool`

HasIsp returns a boolean if a field has been set.

### GetMaxPingTime

`func (o *DiagnosticToolsSpeedtestResult) GetMaxPingTime() float64`

GetMaxPingTime returns the MaxPingTime field if non-nil, zero value otherwise.

### GetMaxPingTimeOk

`func (o *DiagnosticToolsSpeedtestResult) GetMaxPingTimeOk() (*float64, bool)`

GetMaxPingTimeOk returns a tuple with the MaxPingTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPingTime

`func (o *DiagnosticToolsSpeedtestResult) SetMaxPingTime(v float64)`

SetMaxPingTime sets MaxPingTime field to given value.

### HasMaxPingTime

`func (o *DiagnosticToolsSpeedtestResult) HasMaxPingTime() bool`

HasMaxPingTime returns a boolean if a field has been set.

### GetMinPingTime

`func (o *DiagnosticToolsSpeedtestResult) GetMinPingTime() float64`

GetMinPingTime returns the MinPingTime field if non-nil, zero value otherwise.

### GetMinPingTimeOk

`func (o *DiagnosticToolsSpeedtestResult) GetMinPingTimeOk() (*float64, bool)`

GetMinPingTimeOk returns a tuple with the MinPingTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinPingTime

`func (o *DiagnosticToolsSpeedtestResult) SetMinPingTime(v float64)`

SetMinPingTime sets MinPingTime field to given value.

### HasMinPingTime

`func (o *DiagnosticToolsSpeedtestResult) HasMinPingTime() bool`

HasMinPingTime returns a boolean if a field has been set.

### GetResult

`func (o *DiagnosticToolsSpeedtestResult) GetResult() string`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *DiagnosticToolsSpeedtestResult) GetResultOk() (*string, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *DiagnosticToolsSpeedtestResult) SetResult(v string)`

SetResult sets Result field to given value.

### HasResult

`func (o *DiagnosticToolsSpeedtestResult) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetServerDetails

`func (o *DiagnosticToolsSpeedtestResult) GetServerDetails() DiagnosticToolsSpeedtestServer`

GetServerDetails returns the ServerDetails field if non-nil, zero value otherwise.

### GetServerDetailsOk

`func (o *DiagnosticToolsSpeedtestResult) GetServerDetailsOk() (*DiagnosticToolsSpeedtestServer, bool)`

GetServerDetailsOk returns a tuple with the ServerDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerDetails

`func (o *DiagnosticToolsSpeedtestResult) SetServerDetails(v DiagnosticToolsSpeedtestServer)`

SetServerDetails sets ServerDetails field to given value.

### HasServerDetails

`func (o *DiagnosticToolsSpeedtestResult) HasServerDetails() bool`

HasServerDetails returns a boolean if a field has been set.

### GetUploadSpeed

`func (o *DiagnosticToolsSpeedtestResult) GetUploadSpeed() float64`

GetUploadSpeed returns the UploadSpeed field if non-nil, zero value otherwise.

### GetUploadSpeedOk

`func (o *DiagnosticToolsSpeedtestResult) GetUploadSpeedOk() (*float64, bool)`

GetUploadSpeedOk returns a tuple with the UploadSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadSpeed

`func (o *DiagnosticToolsSpeedtestResult) SetUploadSpeed(v float64)`

SetUploadSpeed sets UploadSpeed field to given value.

### HasUploadSpeed

`func (o *DiagnosticToolsSpeedtestResult) HasUploadSpeed() bool`

HasUploadSpeed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



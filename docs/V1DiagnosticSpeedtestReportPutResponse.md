# V1DiagnosticSpeedtestReportPutResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Report** | Pointer to **string** | The generated report | [optional] 
**ReportId** | Pointer to **int64** | 8 bytes (base32 encoded) identifier for the report | [optional] 

## Methods

### NewV1DiagnosticSpeedtestReportPutResponse

`func NewV1DiagnosticSpeedtestReportPutResponse() *V1DiagnosticSpeedtestReportPutResponse`

NewV1DiagnosticSpeedtestReportPutResponse instantiates a new V1DiagnosticSpeedtestReportPutResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DiagnosticSpeedtestReportPutResponseWithDefaults

`func NewV1DiagnosticSpeedtestReportPutResponseWithDefaults() *V1DiagnosticSpeedtestReportPutResponse`

NewV1DiagnosticSpeedtestReportPutResponseWithDefaults instantiates a new V1DiagnosticSpeedtestReportPutResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReport

`func (o *V1DiagnosticSpeedtestReportPutResponse) GetReport() string`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *V1DiagnosticSpeedtestReportPutResponse) GetReportOk() (*string, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *V1DiagnosticSpeedtestReportPutResponse) SetReport(v string)`

SetReport sets Report field to given value.

### HasReport

`func (o *V1DiagnosticSpeedtestReportPutResponse) HasReport() bool`

HasReport returns a boolean if a field has been set.

### GetReportId

`func (o *V1DiagnosticSpeedtestReportPutResponse) GetReportId() int64`

GetReportId returns the ReportId field if non-nil, zero value otherwise.

### GetReportIdOk

`func (o *V1DiagnosticSpeedtestReportPutResponse) GetReportIdOk() (*int64, bool)`

GetReportIdOk returns a tuple with the ReportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportId

`func (o *V1DiagnosticSpeedtestReportPutResponse) SetReportId(v int64)`

SetReportId sets ReportId field to given value.

### HasReportId

`func (o *V1DiagnosticSpeedtestReportPutResponse) HasReportId() bool`

HasReportId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



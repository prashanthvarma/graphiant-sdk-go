# DiagnosticToolsArchive

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchiveFileName** | Pointer to **string** | The archive file name | [optional] 
**ArchiveId** | Pointer to **int64** | Unique identifier for a specific archive | [optional] 
**ArchiveUrl** | Pointer to **string** | The URL to download this archive | [optional] 
**Created** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**Creator** | Pointer to **string** | The user who requested the generation of this archive | [optional] 
**Description** | Pointer to **string** | Description of the requested archive | [optional] 
**Progress** | Pointer to **int32** | The upload progress of the requested debug archive in percentage | [optional] 
**Status** | Pointer to **string** | The status of the requested debug archive | [optional] 
**Type** | Pointer to **string** | The type of the archive | [optional] 

## Methods

### NewDiagnosticToolsArchive

`func NewDiagnosticToolsArchive() *DiagnosticToolsArchive`

NewDiagnosticToolsArchive instantiates a new DiagnosticToolsArchive object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosticToolsArchiveWithDefaults

`func NewDiagnosticToolsArchiveWithDefaults() *DiagnosticToolsArchive`

NewDiagnosticToolsArchiveWithDefaults instantiates a new DiagnosticToolsArchive object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchiveFileName

`func (o *DiagnosticToolsArchive) GetArchiveFileName() string`

GetArchiveFileName returns the ArchiveFileName field if non-nil, zero value otherwise.

### GetArchiveFileNameOk

`func (o *DiagnosticToolsArchive) GetArchiveFileNameOk() (*string, bool)`

GetArchiveFileNameOk returns a tuple with the ArchiveFileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveFileName

`func (o *DiagnosticToolsArchive) SetArchiveFileName(v string)`

SetArchiveFileName sets ArchiveFileName field to given value.

### HasArchiveFileName

`func (o *DiagnosticToolsArchive) HasArchiveFileName() bool`

HasArchiveFileName returns a boolean if a field has been set.

### GetArchiveId

`func (o *DiagnosticToolsArchive) GetArchiveId() int64`

GetArchiveId returns the ArchiveId field if non-nil, zero value otherwise.

### GetArchiveIdOk

`func (o *DiagnosticToolsArchive) GetArchiveIdOk() (*int64, bool)`

GetArchiveIdOk returns a tuple with the ArchiveId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveId

`func (o *DiagnosticToolsArchive) SetArchiveId(v int64)`

SetArchiveId sets ArchiveId field to given value.

### HasArchiveId

`func (o *DiagnosticToolsArchive) HasArchiveId() bool`

HasArchiveId returns a boolean if a field has been set.

### GetArchiveUrl

`func (o *DiagnosticToolsArchive) GetArchiveUrl() string`

GetArchiveUrl returns the ArchiveUrl field if non-nil, zero value otherwise.

### GetArchiveUrlOk

`func (o *DiagnosticToolsArchive) GetArchiveUrlOk() (*string, bool)`

GetArchiveUrlOk returns a tuple with the ArchiveUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveUrl

`func (o *DiagnosticToolsArchive) SetArchiveUrl(v string)`

SetArchiveUrl sets ArchiveUrl field to given value.

### HasArchiveUrl

`func (o *DiagnosticToolsArchive) HasArchiveUrl() bool`

HasArchiveUrl returns a boolean if a field has been set.

### GetCreated

`func (o *DiagnosticToolsArchive) GetCreated() GoogleProtobufTimestamp`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *DiagnosticToolsArchive) GetCreatedOk() (*GoogleProtobufTimestamp, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *DiagnosticToolsArchive) SetCreated(v GoogleProtobufTimestamp)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *DiagnosticToolsArchive) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetCreator

`func (o *DiagnosticToolsArchive) GetCreator() string`

GetCreator returns the Creator field if non-nil, zero value otherwise.

### GetCreatorOk

`func (o *DiagnosticToolsArchive) GetCreatorOk() (*string, bool)`

GetCreatorOk returns a tuple with the Creator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreator

`func (o *DiagnosticToolsArchive) SetCreator(v string)`

SetCreator sets Creator field to given value.

### HasCreator

`func (o *DiagnosticToolsArchive) HasCreator() bool`

HasCreator returns a boolean if a field has been set.

### GetDescription

`func (o *DiagnosticToolsArchive) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DiagnosticToolsArchive) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DiagnosticToolsArchive) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DiagnosticToolsArchive) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetProgress

`func (o *DiagnosticToolsArchive) GetProgress() int32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *DiagnosticToolsArchive) GetProgressOk() (*int32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *DiagnosticToolsArchive) SetProgress(v int32)`

SetProgress sets Progress field to given value.

### HasProgress

`func (o *DiagnosticToolsArchive) HasProgress() bool`

HasProgress returns a boolean if a field has been set.

### GetStatus

`func (o *DiagnosticToolsArchive) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DiagnosticToolsArchive) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DiagnosticToolsArchive) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DiagnosticToolsArchive) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *DiagnosticToolsArchive) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DiagnosticToolsArchive) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DiagnosticToolsArchive) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *DiagnosticToolsArchive) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



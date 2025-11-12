# V1SoftwareReleasesDownloadGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImageExt** | **string** | GNOS Image type (qcow2 or ova) (required) | 
**Version** | **string** | GNOS Image version (required) | 

## Methods

### NewV1SoftwareReleasesDownloadGetRequest

`func NewV1SoftwareReleasesDownloadGetRequest(imageExt string, version string, ) *V1SoftwareReleasesDownloadGetRequest`

NewV1SoftwareReleasesDownloadGetRequest instantiates a new V1SoftwareReleasesDownloadGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1SoftwareReleasesDownloadGetRequestWithDefaults

`func NewV1SoftwareReleasesDownloadGetRequestWithDefaults() *V1SoftwareReleasesDownloadGetRequest`

NewV1SoftwareReleasesDownloadGetRequestWithDefaults instantiates a new V1SoftwareReleasesDownloadGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImageExt

`func (o *V1SoftwareReleasesDownloadGetRequest) GetImageExt() string`

GetImageExt returns the ImageExt field if non-nil, zero value otherwise.

### GetImageExtOk

`func (o *V1SoftwareReleasesDownloadGetRequest) GetImageExtOk() (*string, bool)`

GetImageExtOk returns a tuple with the ImageExt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageExt

`func (o *V1SoftwareReleasesDownloadGetRequest) SetImageExt(v string)`

SetImageExt sets ImageExt field to given value.


### GetVersion

`func (o *V1SoftwareReleasesDownloadGetRequest) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *V1SoftwareReleasesDownloadGetRequest) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *V1SoftwareReleasesDownloadGetRequest) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



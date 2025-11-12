# V1AuthPatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cert** | **string** |  (required) | 
**EntryPoint** | **string** |  (required) | 
**IamType** | **string** |  (required) | 
**Issuer** | **string** |  (required) | 

## Methods

### NewV1AuthPatchRequest

`func NewV1AuthPatchRequest(cert string, entryPoint string, iamType string, issuer string, ) *V1AuthPatchRequest`

NewV1AuthPatchRequest instantiates a new V1AuthPatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthPatchRequestWithDefaults

`func NewV1AuthPatchRequestWithDefaults() *V1AuthPatchRequest`

NewV1AuthPatchRequestWithDefaults instantiates a new V1AuthPatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCert

`func (o *V1AuthPatchRequest) GetCert() string`

GetCert returns the Cert field if non-nil, zero value otherwise.

### GetCertOk

`func (o *V1AuthPatchRequest) GetCertOk() (*string, bool)`

GetCertOk returns a tuple with the Cert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCert

`func (o *V1AuthPatchRequest) SetCert(v string)`

SetCert sets Cert field to given value.


### GetEntryPoint

`func (o *V1AuthPatchRequest) GetEntryPoint() string`

GetEntryPoint returns the EntryPoint field if non-nil, zero value otherwise.

### GetEntryPointOk

`func (o *V1AuthPatchRequest) GetEntryPointOk() (*string, bool)`

GetEntryPointOk returns a tuple with the EntryPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryPoint

`func (o *V1AuthPatchRequest) SetEntryPoint(v string)`

SetEntryPoint sets EntryPoint field to given value.


### GetIamType

`func (o *V1AuthPatchRequest) GetIamType() string`

GetIamType returns the IamType field if non-nil, zero value otherwise.

### GetIamTypeOk

`func (o *V1AuthPatchRequest) GetIamTypeOk() (*string, bool)`

GetIamTypeOk returns a tuple with the IamType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIamType

`func (o *V1AuthPatchRequest) SetIamType(v string)`

SetIamType sets IamType field to given value.


### GetIssuer

`func (o *V1AuthPatchRequest) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *V1AuthPatchRequest) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *V1AuthPatchRequest) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



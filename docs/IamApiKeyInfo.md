# IamApiKeyInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpiryTs** | Pointer to [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**GcsName** | Pointer to **string** |  | [optional] 

## Methods

### NewIamApiKeyInfo

`func NewIamApiKeyInfo() *IamApiKeyInfo`

NewIamApiKeyInfo instantiates a new IamApiKeyInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIamApiKeyInfoWithDefaults

`func NewIamApiKeyInfoWithDefaults() *IamApiKeyInfo`

NewIamApiKeyInfoWithDefaults instantiates a new IamApiKeyInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpiryTs

`func (o *IamApiKeyInfo) GetExpiryTs() GoogleProtobufTimestamp`

GetExpiryTs returns the ExpiryTs field if non-nil, zero value otherwise.

### GetExpiryTsOk

`func (o *IamApiKeyInfo) GetExpiryTsOk() (*GoogleProtobufTimestamp, bool)`

GetExpiryTsOk returns a tuple with the ExpiryTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryTs

`func (o *IamApiKeyInfo) SetExpiryTs(v GoogleProtobufTimestamp)`

SetExpiryTs sets ExpiryTs field to given value.

### HasExpiryTs

`func (o *IamApiKeyInfo) HasExpiryTs() bool`

HasExpiryTs returns a boolean if a field has been set.

### GetGcsName

`func (o *IamApiKeyInfo) GetGcsName() string`

GetGcsName returns the GcsName field if non-nil, zero value otherwise.

### GetGcsNameOk

`func (o *IamApiKeyInfo) GetGcsNameOk() (*string, bool)`

GetGcsNameOk returns a tuple with the GcsName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGcsName

`func (o *IamApiKeyInfo) SetGcsName(v string)`

SetGcsName sets GcsName field to given value.

### HasGcsName

`func (o *IamApiKeyInfo) HasGcsName() bool`

HasGcsName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



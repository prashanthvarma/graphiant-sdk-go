# V2RuleEnabledisablePostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enable** | **bool** | Enable or disable. True means enable (required) | 
**RuleIdList** | **[]string** |  | 

## Methods

### NewV2RuleEnabledisablePostRequest

`func NewV2RuleEnabledisablePostRequest(enable bool, ruleIdList []string, ) *V2RuleEnabledisablePostRequest`

NewV2RuleEnabledisablePostRequest instantiates a new V2RuleEnabledisablePostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2RuleEnabledisablePostRequestWithDefaults

`func NewV2RuleEnabledisablePostRequestWithDefaults() *V2RuleEnabledisablePostRequest`

NewV2RuleEnabledisablePostRequestWithDefaults instantiates a new V2RuleEnabledisablePostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnable

`func (o *V2RuleEnabledisablePostRequest) GetEnable() bool`

GetEnable returns the Enable field if non-nil, zero value otherwise.

### GetEnableOk

`func (o *V2RuleEnabledisablePostRequest) GetEnableOk() (*bool, bool)`

GetEnableOk returns a tuple with the Enable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnable

`func (o *V2RuleEnabledisablePostRequest) SetEnable(v bool)`

SetEnable sets Enable field to given value.


### GetRuleIdList

`func (o *V2RuleEnabledisablePostRequest) GetRuleIdList() []string`

GetRuleIdList returns the RuleIdList field if non-nil, zero value otherwise.

### GetRuleIdListOk

`func (o *V2RuleEnabledisablePostRequest) GetRuleIdListOk() (*[]string, bool)`

GetRuleIdListOk returns a tuple with the RuleIdList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleIdList

`func (o *V2RuleEnabledisablePostRequest) SetRuleIdList(v []string)`

SetRuleIdList sets RuleIdList field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



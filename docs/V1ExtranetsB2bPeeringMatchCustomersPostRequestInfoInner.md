# V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | Pointer to **string** |  | [optional] 
**CustomerName** | Pointer to **string** |  | [optional] 
**Emails** | Pointer to **[]string** |  | [optional] 
**MatchedServices** | Pointer to **int32** |  | [optional] 
**PeerType** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to [**V1AlarmHistoryGet200ResponseHistoryInnerTime**](V1AlarmHistoryGet200ResponseHistoryInnerTime.md) |  | [optional] 

## Methods

### NewV1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner

`func NewV1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner() *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner`

NewV1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner instantiates a new V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInnerWithDefaults

`func NewV1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInnerWithDefaults() *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner`

NewV1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInnerWithDefaults instantiates a new V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetCustomerName

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetEmails

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasEmails() bool`

HasEmails returns a boolean if a field has been set.

### GetMatchedServices

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetMatchedServices() int32`

GetMatchedServices returns the MatchedServices field if non-nil, zero value otherwise.

### GetMatchedServicesOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetMatchedServicesOk() (*int32, bool)`

GetMatchedServicesOk returns a tuple with the MatchedServices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchedServices

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetMatchedServices(v int32)`

SetMatchedServices sets MatchedServices field to given value.

### HasMatchedServices

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasMatchedServices() bool`

HasMatchedServices returns a boolean if a field has been set.

### GetPeerType

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetPeerType() string`

GetPeerType returns the PeerType field if non-nil, zero value otherwise.

### GetPeerTypeOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetPeerTypeOk() (*string, bool)`

GetPeerTypeOk returns a tuple with the PeerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerType

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetPeerType(v string)`

SetPeerType sets PeerType field to given value.

### HasPeerType

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasPeerType() bool`

HasPeerType returns a boolean if a field has been set.

### GetStatus

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetUpdatedAt() V1AlarmHistoryGet200ResponseHistoryInnerTime`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) GetUpdatedAtOk() (*V1AlarmHistoryGet200ResponseHistoryInnerTime, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) SetUpdatedAt(v V1AlarmHistoryGet200ResponseHistoryInnerTime)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



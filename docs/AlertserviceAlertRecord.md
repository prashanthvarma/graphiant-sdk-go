# AlertserviceAlertRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcknowledgedList** | Pointer to **[]string** |  | [optional] 
**AcknowledgementReason** | Pointer to **string** | Reason put by users when acknowledged | [optional] 
**AlertBody** | Pointer to **string** | Latest event(s) behind the alert (required) | [optional] 
**AlertId** | Pointer to **string** | Unique id of the alert (required) | [optional] 
**AllowListed** | Pointer to **bool** | whether entity in alert is put in allowlist/excludelist, disabling alert (required) | [optional] 
**ChildrenAlertList** | Pointer to [**AlertserviceChildrenAlertListResponse**](AlertserviceChildrenAlertListResponse.md) |  | [optional] 
**DescendantPresent** | Pointer to **bool** | Whether or not descendants are present (required) | [optional] 
**DeviceId** | Pointer to **string** | Internal device id to navigate to troubleshooting | [optional] 
**EndTime** | Pointer to **int64** | When this alert was last seen as a continuation (required) | [optional] 
**EnterpriseId** | Pointer to **string** | Internal enterprise id to navigate to troubleshooting (required) | [optional] 
**Entity** | Pointer to **string** | Entity that triggered the alert. Edge, core, etc. (required) | [optional] 
**InterfaceName** | Pointer to **string** | Device Interface Name | [optional] 
**MuteListed** | Pointer to **bool** | whether entity in alert is put in notification mutelist (required) | [optional] 
**NotificationCreated** | Pointer to **bool** | whether notification exists for this rule (required) | [optional] 
**Occurrences** | Pointer to **int64** | Number of times alert was raised as a continuation (required) | [optional] 
**PeerDeviceId** | Pointer to **string** | peer device id | [optional] 
**PeerInterfaceName** | Pointer to **string** | Peer Interface Name | [optional] 
**PeerName** | Pointer to **string** | Peer Name | [optional] 
**Plane** | Pointer to **string** | Plane of the rule generating the alert (required) | [optional] 
**Reason** | Pointer to **string** | Reason why alert was generated (required) | [optional] 
**Recommendation** | Pointer to **string** | Recommendation to recover from alert (required) | [optional] 
**RuleId** | Pointer to **string** | Unique id of the rule generating the alert (required) | [optional] 
**Severity** | Pointer to **string** | Severity of the rule behind the alert (required) | [optional] 
**SiteId** | Pointer to **string** | Internal site id to navigate to troubleshooting | [optional] 
**StartTime** | Pointer to **int64** | When this alert was first triggered (required) | [optional] 
**Status** | Pointer to **string** | Status of the alert whether active or inactive (required) | [optional] 
**TroubleshootingDisabledReason** | Pointer to **string** | Reason to not navigate to troubleshooting | [optional] 
**TroubleshootingEnabled** | Pointer to **bool** | Navigate or not navigate to troubleshooting dashboard (required) | [optional] 
**TunnelInterfaceName** | Pointer to **string** | Tunnel Interface Name | [optional] 
**Type** | Pointer to **string** | Type of alert (required) | [optional] 

## Methods

### NewAlertserviceAlertRecord

`func NewAlertserviceAlertRecord() *AlertserviceAlertRecord`

NewAlertserviceAlertRecord instantiates a new AlertserviceAlertRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertserviceAlertRecordWithDefaults

`func NewAlertserviceAlertRecordWithDefaults() *AlertserviceAlertRecord`

NewAlertserviceAlertRecordWithDefaults instantiates a new AlertserviceAlertRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcknowledgedList

`func (o *AlertserviceAlertRecord) GetAcknowledgedList() []string`

GetAcknowledgedList returns the AcknowledgedList field if non-nil, zero value otherwise.

### GetAcknowledgedListOk

`func (o *AlertserviceAlertRecord) GetAcknowledgedListOk() (*[]string, bool)`

GetAcknowledgedListOk returns a tuple with the AcknowledgedList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedList

`func (o *AlertserviceAlertRecord) SetAcknowledgedList(v []string)`

SetAcknowledgedList sets AcknowledgedList field to given value.

### HasAcknowledgedList

`func (o *AlertserviceAlertRecord) HasAcknowledgedList() bool`

HasAcknowledgedList returns a boolean if a field has been set.

### GetAcknowledgementReason

`func (o *AlertserviceAlertRecord) GetAcknowledgementReason() string`

GetAcknowledgementReason returns the AcknowledgementReason field if non-nil, zero value otherwise.

### GetAcknowledgementReasonOk

`func (o *AlertserviceAlertRecord) GetAcknowledgementReasonOk() (*string, bool)`

GetAcknowledgementReasonOk returns a tuple with the AcknowledgementReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgementReason

`func (o *AlertserviceAlertRecord) SetAcknowledgementReason(v string)`

SetAcknowledgementReason sets AcknowledgementReason field to given value.

### HasAcknowledgementReason

`func (o *AlertserviceAlertRecord) HasAcknowledgementReason() bool`

HasAcknowledgementReason returns a boolean if a field has been set.

### GetAlertBody

`func (o *AlertserviceAlertRecord) GetAlertBody() string`

GetAlertBody returns the AlertBody field if non-nil, zero value otherwise.

### GetAlertBodyOk

`func (o *AlertserviceAlertRecord) GetAlertBodyOk() (*string, bool)`

GetAlertBodyOk returns a tuple with the AlertBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertBody

`func (o *AlertserviceAlertRecord) SetAlertBody(v string)`

SetAlertBody sets AlertBody field to given value.

### HasAlertBody

`func (o *AlertserviceAlertRecord) HasAlertBody() bool`

HasAlertBody returns a boolean if a field has been set.

### GetAlertId

`func (o *AlertserviceAlertRecord) GetAlertId() string`

GetAlertId returns the AlertId field if non-nil, zero value otherwise.

### GetAlertIdOk

`func (o *AlertserviceAlertRecord) GetAlertIdOk() (*string, bool)`

GetAlertIdOk returns a tuple with the AlertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertId

`func (o *AlertserviceAlertRecord) SetAlertId(v string)`

SetAlertId sets AlertId field to given value.

### HasAlertId

`func (o *AlertserviceAlertRecord) HasAlertId() bool`

HasAlertId returns a boolean if a field has been set.

### GetAllowListed

`func (o *AlertserviceAlertRecord) GetAllowListed() bool`

GetAllowListed returns the AllowListed field if non-nil, zero value otherwise.

### GetAllowListedOk

`func (o *AlertserviceAlertRecord) GetAllowListedOk() (*bool, bool)`

GetAllowListedOk returns a tuple with the AllowListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowListed

`func (o *AlertserviceAlertRecord) SetAllowListed(v bool)`

SetAllowListed sets AllowListed field to given value.

### HasAllowListed

`func (o *AlertserviceAlertRecord) HasAllowListed() bool`

HasAllowListed returns a boolean if a field has been set.

### GetChildrenAlertList

`func (o *AlertserviceAlertRecord) GetChildrenAlertList() AlertserviceChildrenAlertListResponse`

GetChildrenAlertList returns the ChildrenAlertList field if non-nil, zero value otherwise.

### GetChildrenAlertListOk

`func (o *AlertserviceAlertRecord) GetChildrenAlertListOk() (*AlertserviceChildrenAlertListResponse, bool)`

GetChildrenAlertListOk returns a tuple with the ChildrenAlertList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildrenAlertList

`func (o *AlertserviceAlertRecord) SetChildrenAlertList(v AlertserviceChildrenAlertListResponse)`

SetChildrenAlertList sets ChildrenAlertList field to given value.

### HasChildrenAlertList

`func (o *AlertserviceAlertRecord) HasChildrenAlertList() bool`

HasChildrenAlertList returns a boolean if a field has been set.

### GetDescendantPresent

`func (o *AlertserviceAlertRecord) GetDescendantPresent() bool`

GetDescendantPresent returns the DescendantPresent field if non-nil, zero value otherwise.

### GetDescendantPresentOk

`func (o *AlertserviceAlertRecord) GetDescendantPresentOk() (*bool, bool)`

GetDescendantPresentOk returns a tuple with the DescendantPresent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescendantPresent

`func (o *AlertserviceAlertRecord) SetDescendantPresent(v bool)`

SetDescendantPresent sets DescendantPresent field to given value.

### HasDescendantPresent

`func (o *AlertserviceAlertRecord) HasDescendantPresent() bool`

HasDescendantPresent returns a boolean if a field has been set.

### GetDeviceId

`func (o *AlertserviceAlertRecord) GetDeviceId() string`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *AlertserviceAlertRecord) GetDeviceIdOk() (*string, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *AlertserviceAlertRecord) SetDeviceId(v string)`

SetDeviceId sets DeviceId field to given value.

### HasDeviceId

`func (o *AlertserviceAlertRecord) HasDeviceId() bool`

HasDeviceId returns a boolean if a field has been set.

### GetEndTime

`func (o *AlertserviceAlertRecord) GetEndTime() int64`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *AlertserviceAlertRecord) GetEndTimeOk() (*int64, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *AlertserviceAlertRecord) SetEndTime(v int64)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *AlertserviceAlertRecord) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### GetEnterpriseId

`func (o *AlertserviceAlertRecord) GetEnterpriseId() string`

GetEnterpriseId returns the EnterpriseId field if non-nil, zero value otherwise.

### GetEnterpriseIdOk

`func (o *AlertserviceAlertRecord) GetEnterpriseIdOk() (*string, bool)`

GetEnterpriseIdOk returns a tuple with the EnterpriseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnterpriseId

`func (o *AlertserviceAlertRecord) SetEnterpriseId(v string)`

SetEnterpriseId sets EnterpriseId field to given value.

### HasEnterpriseId

`func (o *AlertserviceAlertRecord) HasEnterpriseId() bool`

HasEnterpriseId returns a boolean if a field has been set.

### GetEntity

`func (o *AlertserviceAlertRecord) GetEntity() string`

GetEntity returns the Entity field if non-nil, zero value otherwise.

### GetEntityOk

`func (o *AlertserviceAlertRecord) GetEntityOk() (*string, bool)`

GetEntityOk returns a tuple with the Entity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntity

`func (o *AlertserviceAlertRecord) SetEntity(v string)`

SetEntity sets Entity field to given value.

### HasEntity

`func (o *AlertserviceAlertRecord) HasEntity() bool`

HasEntity returns a boolean if a field has been set.

### GetInterfaceName

`func (o *AlertserviceAlertRecord) GetInterfaceName() string`

GetInterfaceName returns the InterfaceName field if non-nil, zero value otherwise.

### GetInterfaceNameOk

`func (o *AlertserviceAlertRecord) GetInterfaceNameOk() (*string, bool)`

GetInterfaceNameOk returns a tuple with the InterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceName

`func (o *AlertserviceAlertRecord) SetInterfaceName(v string)`

SetInterfaceName sets InterfaceName field to given value.

### HasInterfaceName

`func (o *AlertserviceAlertRecord) HasInterfaceName() bool`

HasInterfaceName returns a boolean if a field has been set.

### GetMuteListed

`func (o *AlertserviceAlertRecord) GetMuteListed() bool`

GetMuteListed returns the MuteListed field if non-nil, zero value otherwise.

### GetMuteListedOk

`func (o *AlertserviceAlertRecord) GetMuteListedOk() (*bool, bool)`

GetMuteListedOk returns a tuple with the MuteListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMuteListed

`func (o *AlertserviceAlertRecord) SetMuteListed(v bool)`

SetMuteListed sets MuteListed field to given value.

### HasMuteListed

`func (o *AlertserviceAlertRecord) HasMuteListed() bool`

HasMuteListed returns a boolean if a field has been set.

### GetNotificationCreated

`func (o *AlertserviceAlertRecord) GetNotificationCreated() bool`

GetNotificationCreated returns the NotificationCreated field if non-nil, zero value otherwise.

### GetNotificationCreatedOk

`func (o *AlertserviceAlertRecord) GetNotificationCreatedOk() (*bool, bool)`

GetNotificationCreatedOk returns a tuple with the NotificationCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationCreated

`func (o *AlertserviceAlertRecord) SetNotificationCreated(v bool)`

SetNotificationCreated sets NotificationCreated field to given value.

### HasNotificationCreated

`func (o *AlertserviceAlertRecord) HasNotificationCreated() bool`

HasNotificationCreated returns a boolean if a field has been set.

### GetOccurrences

`func (o *AlertserviceAlertRecord) GetOccurrences() int64`

GetOccurrences returns the Occurrences field if non-nil, zero value otherwise.

### GetOccurrencesOk

`func (o *AlertserviceAlertRecord) GetOccurrencesOk() (*int64, bool)`

GetOccurrencesOk returns a tuple with the Occurrences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrences

`func (o *AlertserviceAlertRecord) SetOccurrences(v int64)`

SetOccurrences sets Occurrences field to given value.

### HasOccurrences

`func (o *AlertserviceAlertRecord) HasOccurrences() bool`

HasOccurrences returns a boolean if a field has been set.

### GetPeerDeviceId

`func (o *AlertserviceAlertRecord) GetPeerDeviceId() string`

GetPeerDeviceId returns the PeerDeviceId field if non-nil, zero value otherwise.

### GetPeerDeviceIdOk

`func (o *AlertserviceAlertRecord) GetPeerDeviceIdOk() (*string, bool)`

GetPeerDeviceIdOk returns a tuple with the PeerDeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerDeviceId

`func (o *AlertserviceAlertRecord) SetPeerDeviceId(v string)`

SetPeerDeviceId sets PeerDeviceId field to given value.

### HasPeerDeviceId

`func (o *AlertserviceAlertRecord) HasPeerDeviceId() bool`

HasPeerDeviceId returns a boolean if a field has been set.

### GetPeerInterfaceName

`func (o *AlertserviceAlertRecord) GetPeerInterfaceName() string`

GetPeerInterfaceName returns the PeerInterfaceName field if non-nil, zero value otherwise.

### GetPeerInterfaceNameOk

`func (o *AlertserviceAlertRecord) GetPeerInterfaceNameOk() (*string, bool)`

GetPeerInterfaceNameOk returns a tuple with the PeerInterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerInterfaceName

`func (o *AlertserviceAlertRecord) SetPeerInterfaceName(v string)`

SetPeerInterfaceName sets PeerInterfaceName field to given value.

### HasPeerInterfaceName

`func (o *AlertserviceAlertRecord) HasPeerInterfaceName() bool`

HasPeerInterfaceName returns a boolean if a field has been set.

### GetPeerName

`func (o *AlertserviceAlertRecord) GetPeerName() string`

GetPeerName returns the PeerName field if non-nil, zero value otherwise.

### GetPeerNameOk

`func (o *AlertserviceAlertRecord) GetPeerNameOk() (*string, bool)`

GetPeerNameOk returns a tuple with the PeerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerName

`func (o *AlertserviceAlertRecord) SetPeerName(v string)`

SetPeerName sets PeerName field to given value.

### HasPeerName

`func (o *AlertserviceAlertRecord) HasPeerName() bool`

HasPeerName returns a boolean if a field has been set.

### GetPlane

`func (o *AlertserviceAlertRecord) GetPlane() string`

GetPlane returns the Plane field if non-nil, zero value otherwise.

### GetPlaneOk

`func (o *AlertserviceAlertRecord) GetPlaneOk() (*string, bool)`

GetPlaneOk returns a tuple with the Plane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlane

`func (o *AlertserviceAlertRecord) SetPlane(v string)`

SetPlane sets Plane field to given value.

### HasPlane

`func (o *AlertserviceAlertRecord) HasPlane() bool`

HasPlane returns a boolean if a field has been set.

### GetReason

`func (o *AlertserviceAlertRecord) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AlertserviceAlertRecord) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AlertserviceAlertRecord) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AlertserviceAlertRecord) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetRecommendation

`func (o *AlertserviceAlertRecord) GetRecommendation() string`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *AlertserviceAlertRecord) GetRecommendationOk() (*string, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *AlertserviceAlertRecord) SetRecommendation(v string)`

SetRecommendation sets Recommendation field to given value.

### HasRecommendation

`func (o *AlertserviceAlertRecord) HasRecommendation() bool`

HasRecommendation returns a boolean if a field has been set.

### GetRuleId

`func (o *AlertserviceAlertRecord) GetRuleId() string`

GetRuleId returns the RuleId field if non-nil, zero value otherwise.

### GetRuleIdOk

`func (o *AlertserviceAlertRecord) GetRuleIdOk() (*string, bool)`

GetRuleIdOk returns a tuple with the RuleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleId

`func (o *AlertserviceAlertRecord) SetRuleId(v string)`

SetRuleId sets RuleId field to given value.

### HasRuleId

`func (o *AlertserviceAlertRecord) HasRuleId() bool`

HasRuleId returns a boolean if a field has been set.

### GetSeverity

`func (o *AlertserviceAlertRecord) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *AlertserviceAlertRecord) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *AlertserviceAlertRecord) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *AlertserviceAlertRecord) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetSiteId

`func (o *AlertserviceAlertRecord) GetSiteId() string`

GetSiteId returns the SiteId field if non-nil, zero value otherwise.

### GetSiteIdOk

`func (o *AlertserviceAlertRecord) GetSiteIdOk() (*string, bool)`

GetSiteIdOk returns a tuple with the SiteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteId

`func (o *AlertserviceAlertRecord) SetSiteId(v string)`

SetSiteId sets SiteId field to given value.

### HasSiteId

`func (o *AlertserviceAlertRecord) HasSiteId() bool`

HasSiteId returns a boolean if a field has been set.

### GetStartTime

`func (o *AlertserviceAlertRecord) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *AlertserviceAlertRecord) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *AlertserviceAlertRecord) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *AlertserviceAlertRecord) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetStatus

`func (o *AlertserviceAlertRecord) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AlertserviceAlertRecord) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AlertserviceAlertRecord) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AlertserviceAlertRecord) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTroubleshootingDisabledReason

`func (o *AlertserviceAlertRecord) GetTroubleshootingDisabledReason() string`

GetTroubleshootingDisabledReason returns the TroubleshootingDisabledReason field if non-nil, zero value otherwise.

### GetTroubleshootingDisabledReasonOk

`func (o *AlertserviceAlertRecord) GetTroubleshootingDisabledReasonOk() (*string, bool)`

GetTroubleshootingDisabledReasonOk returns a tuple with the TroubleshootingDisabledReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTroubleshootingDisabledReason

`func (o *AlertserviceAlertRecord) SetTroubleshootingDisabledReason(v string)`

SetTroubleshootingDisabledReason sets TroubleshootingDisabledReason field to given value.

### HasTroubleshootingDisabledReason

`func (o *AlertserviceAlertRecord) HasTroubleshootingDisabledReason() bool`

HasTroubleshootingDisabledReason returns a boolean if a field has been set.

### GetTroubleshootingEnabled

`func (o *AlertserviceAlertRecord) GetTroubleshootingEnabled() bool`

GetTroubleshootingEnabled returns the TroubleshootingEnabled field if non-nil, zero value otherwise.

### GetTroubleshootingEnabledOk

`func (o *AlertserviceAlertRecord) GetTroubleshootingEnabledOk() (*bool, bool)`

GetTroubleshootingEnabledOk returns a tuple with the TroubleshootingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTroubleshootingEnabled

`func (o *AlertserviceAlertRecord) SetTroubleshootingEnabled(v bool)`

SetTroubleshootingEnabled sets TroubleshootingEnabled field to given value.

### HasTroubleshootingEnabled

`func (o *AlertserviceAlertRecord) HasTroubleshootingEnabled() bool`

HasTroubleshootingEnabled returns a boolean if a field has been set.

### GetTunnelInterfaceName

`func (o *AlertserviceAlertRecord) GetTunnelInterfaceName() string`

GetTunnelInterfaceName returns the TunnelInterfaceName field if non-nil, zero value otherwise.

### GetTunnelInterfaceNameOk

`func (o *AlertserviceAlertRecord) GetTunnelInterfaceNameOk() (*string, bool)`

GetTunnelInterfaceNameOk returns a tuple with the TunnelInterfaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnelInterfaceName

`func (o *AlertserviceAlertRecord) SetTunnelInterfaceName(v string)`

SetTunnelInterfaceName sets TunnelInterfaceName field to given value.

### HasTunnelInterfaceName

`func (o *AlertserviceAlertRecord) HasTunnelInterfaceName() bool`

HasTunnelInterfaceName returns a boolean if a field has been set.

### GetType

`func (o *AlertserviceAlertRecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AlertserviceAlertRecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AlertserviceAlertRecord) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AlertserviceAlertRecord) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



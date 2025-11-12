# ManaV2CoreDeviceConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BgpInstance** | Pointer to [**ManaV2BgpInstanceConfig**](ManaV2BgpInstanceConfig.md) |  | [optional] 
**CoreVrf** | Pointer to [**ManaV2VrfConfig**](ManaV2VrfConfig.md) |  | [optional] 
**Interfaces** | Pointer to [**map[string]ManaV2NullableInterfaceCoreConfig**](ManaV2NullableInterfaceCoreConfig.md) |  | [optional] 
**IpfixExporters** | Pointer to [**map[string]ManaV2NullableIpfixExporterConfig**](ManaV2NullableIpfixExporterConfig.md) |  | [optional] 
**IspVrfs** | Pointer to [**map[string]ManaV2VrfConfig**](ManaV2VrfConfig.md) |  | [optional] 
**MaintenanceMode** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PrefixSets** | Pointer to [**map[string]ManaV2NullablePrefixSetConfig**](ManaV2NullablePrefixSetConfig.md) |  | [optional] 
**Prometheus** | Pointer to [**ManaV2PrometheusConfig**](ManaV2PrometheusConfig.md) |  | [optional] 
**Region** | Pointer to **string** |  | [optional] 
**RegionName** | Pointer to **string** |  | [optional] 
**RoutePolicies** | Pointer to [**map[string]ManaV2NullableRoutingPolicyConfig**](ManaV2NullableRoutingPolicyConfig.md) |  | [optional] 
**Site** | Pointer to [**ManaV2NewSite**](ManaV2NewSite.md) |  | [optional] 
**TrafficPolicy** | Pointer to [**ManaV2ForwardingPolicyConfig**](ManaV2ForwardingPolicyConfig.md) |  | [optional] 
**Vrfs** | Pointer to [**map[string]ManaV2VrfConfig**](ManaV2VrfConfig.md) |  | [optional] 

## Methods

### NewManaV2CoreDeviceConfig

`func NewManaV2CoreDeviceConfig() *ManaV2CoreDeviceConfig`

NewManaV2CoreDeviceConfig instantiates a new ManaV2CoreDeviceConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManaV2CoreDeviceConfigWithDefaults

`func NewManaV2CoreDeviceConfigWithDefaults() *ManaV2CoreDeviceConfig`

NewManaV2CoreDeviceConfigWithDefaults instantiates a new ManaV2CoreDeviceConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBgpInstance

`func (o *ManaV2CoreDeviceConfig) GetBgpInstance() ManaV2BgpInstanceConfig`

GetBgpInstance returns the BgpInstance field if non-nil, zero value otherwise.

### GetBgpInstanceOk

`func (o *ManaV2CoreDeviceConfig) GetBgpInstanceOk() (*ManaV2BgpInstanceConfig, bool)`

GetBgpInstanceOk returns a tuple with the BgpInstance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBgpInstance

`func (o *ManaV2CoreDeviceConfig) SetBgpInstance(v ManaV2BgpInstanceConfig)`

SetBgpInstance sets BgpInstance field to given value.

### HasBgpInstance

`func (o *ManaV2CoreDeviceConfig) HasBgpInstance() bool`

HasBgpInstance returns a boolean if a field has been set.

### GetCoreVrf

`func (o *ManaV2CoreDeviceConfig) GetCoreVrf() ManaV2VrfConfig`

GetCoreVrf returns the CoreVrf field if non-nil, zero value otherwise.

### GetCoreVrfOk

`func (o *ManaV2CoreDeviceConfig) GetCoreVrfOk() (*ManaV2VrfConfig, bool)`

GetCoreVrfOk returns a tuple with the CoreVrf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreVrf

`func (o *ManaV2CoreDeviceConfig) SetCoreVrf(v ManaV2VrfConfig)`

SetCoreVrf sets CoreVrf field to given value.

### HasCoreVrf

`func (o *ManaV2CoreDeviceConfig) HasCoreVrf() bool`

HasCoreVrf returns a boolean if a field has been set.

### GetInterfaces

`func (o *ManaV2CoreDeviceConfig) GetInterfaces() map[string]ManaV2NullableInterfaceCoreConfig`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *ManaV2CoreDeviceConfig) GetInterfacesOk() (*map[string]ManaV2NullableInterfaceCoreConfig, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *ManaV2CoreDeviceConfig) SetInterfaces(v map[string]ManaV2NullableInterfaceCoreConfig)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *ManaV2CoreDeviceConfig) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetIpfixExporters

`func (o *ManaV2CoreDeviceConfig) GetIpfixExporters() map[string]ManaV2NullableIpfixExporterConfig`

GetIpfixExporters returns the IpfixExporters field if non-nil, zero value otherwise.

### GetIpfixExportersOk

`func (o *ManaV2CoreDeviceConfig) GetIpfixExportersOk() (*map[string]ManaV2NullableIpfixExporterConfig, bool)`

GetIpfixExportersOk returns a tuple with the IpfixExporters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpfixExporters

`func (o *ManaV2CoreDeviceConfig) SetIpfixExporters(v map[string]ManaV2NullableIpfixExporterConfig)`

SetIpfixExporters sets IpfixExporters field to given value.

### HasIpfixExporters

`func (o *ManaV2CoreDeviceConfig) HasIpfixExporters() bool`

HasIpfixExporters returns a boolean if a field has been set.

### GetIspVrfs

`func (o *ManaV2CoreDeviceConfig) GetIspVrfs() map[string]ManaV2VrfConfig`

GetIspVrfs returns the IspVrfs field if non-nil, zero value otherwise.

### GetIspVrfsOk

`func (o *ManaV2CoreDeviceConfig) GetIspVrfsOk() (*map[string]ManaV2VrfConfig, bool)`

GetIspVrfsOk returns a tuple with the IspVrfs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIspVrfs

`func (o *ManaV2CoreDeviceConfig) SetIspVrfs(v map[string]ManaV2VrfConfig)`

SetIspVrfs sets IspVrfs field to given value.

### HasIspVrfs

`func (o *ManaV2CoreDeviceConfig) HasIspVrfs() bool`

HasIspVrfs returns a boolean if a field has been set.

### GetMaintenanceMode

`func (o *ManaV2CoreDeviceConfig) GetMaintenanceMode() bool`

GetMaintenanceMode returns the MaintenanceMode field if non-nil, zero value otherwise.

### GetMaintenanceModeOk

`func (o *ManaV2CoreDeviceConfig) GetMaintenanceModeOk() (*bool, bool)`

GetMaintenanceModeOk returns a tuple with the MaintenanceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceMode

`func (o *ManaV2CoreDeviceConfig) SetMaintenanceMode(v bool)`

SetMaintenanceMode sets MaintenanceMode field to given value.

### HasMaintenanceMode

`func (o *ManaV2CoreDeviceConfig) HasMaintenanceMode() bool`

HasMaintenanceMode returns a boolean if a field has been set.

### GetName

`func (o *ManaV2CoreDeviceConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManaV2CoreDeviceConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManaV2CoreDeviceConfig) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ManaV2CoreDeviceConfig) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPrefixSets

`func (o *ManaV2CoreDeviceConfig) GetPrefixSets() map[string]ManaV2NullablePrefixSetConfig`

GetPrefixSets returns the PrefixSets field if non-nil, zero value otherwise.

### GetPrefixSetsOk

`func (o *ManaV2CoreDeviceConfig) GetPrefixSetsOk() (*map[string]ManaV2NullablePrefixSetConfig, bool)`

GetPrefixSetsOk returns a tuple with the PrefixSets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixSets

`func (o *ManaV2CoreDeviceConfig) SetPrefixSets(v map[string]ManaV2NullablePrefixSetConfig)`

SetPrefixSets sets PrefixSets field to given value.

### HasPrefixSets

`func (o *ManaV2CoreDeviceConfig) HasPrefixSets() bool`

HasPrefixSets returns a boolean if a field has been set.

### GetPrometheus

`func (o *ManaV2CoreDeviceConfig) GetPrometheus() ManaV2PrometheusConfig`

GetPrometheus returns the Prometheus field if non-nil, zero value otherwise.

### GetPrometheusOk

`func (o *ManaV2CoreDeviceConfig) GetPrometheusOk() (*ManaV2PrometheusConfig, bool)`

GetPrometheusOk returns a tuple with the Prometheus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrometheus

`func (o *ManaV2CoreDeviceConfig) SetPrometheus(v ManaV2PrometheusConfig)`

SetPrometheus sets Prometheus field to given value.

### HasPrometheus

`func (o *ManaV2CoreDeviceConfig) HasPrometheus() bool`

HasPrometheus returns a boolean if a field has been set.

### GetRegion

`func (o *ManaV2CoreDeviceConfig) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *ManaV2CoreDeviceConfig) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *ManaV2CoreDeviceConfig) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *ManaV2CoreDeviceConfig) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetRegionName

`func (o *ManaV2CoreDeviceConfig) GetRegionName() string`

GetRegionName returns the RegionName field if non-nil, zero value otherwise.

### GetRegionNameOk

`func (o *ManaV2CoreDeviceConfig) GetRegionNameOk() (*string, bool)`

GetRegionNameOk returns a tuple with the RegionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionName

`func (o *ManaV2CoreDeviceConfig) SetRegionName(v string)`

SetRegionName sets RegionName field to given value.

### HasRegionName

`func (o *ManaV2CoreDeviceConfig) HasRegionName() bool`

HasRegionName returns a boolean if a field has been set.

### GetRoutePolicies

`func (o *ManaV2CoreDeviceConfig) GetRoutePolicies() map[string]ManaV2NullableRoutingPolicyConfig`

GetRoutePolicies returns the RoutePolicies field if non-nil, zero value otherwise.

### GetRoutePoliciesOk

`func (o *ManaV2CoreDeviceConfig) GetRoutePoliciesOk() (*map[string]ManaV2NullableRoutingPolicyConfig, bool)`

GetRoutePoliciesOk returns a tuple with the RoutePolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutePolicies

`func (o *ManaV2CoreDeviceConfig) SetRoutePolicies(v map[string]ManaV2NullableRoutingPolicyConfig)`

SetRoutePolicies sets RoutePolicies field to given value.

### HasRoutePolicies

`func (o *ManaV2CoreDeviceConfig) HasRoutePolicies() bool`

HasRoutePolicies returns a boolean if a field has been set.

### GetSite

`func (o *ManaV2CoreDeviceConfig) GetSite() ManaV2NewSite`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *ManaV2CoreDeviceConfig) GetSiteOk() (*ManaV2NewSite, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *ManaV2CoreDeviceConfig) SetSite(v ManaV2NewSite)`

SetSite sets Site field to given value.

### HasSite

`func (o *ManaV2CoreDeviceConfig) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetTrafficPolicy

`func (o *ManaV2CoreDeviceConfig) GetTrafficPolicy() ManaV2ForwardingPolicyConfig`

GetTrafficPolicy returns the TrafficPolicy field if non-nil, zero value otherwise.

### GetTrafficPolicyOk

`func (o *ManaV2CoreDeviceConfig) GetTrafficPolicyOk() (*ManaV2ForwardingPolicyConfig, bool)`

GetTrafficPolicyOk returns a tuple with the TrafficPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficPolicy

`func (o *ManaV2CoreDeviceConfig) SetTrafficPolicy(v ManaV2ForwardingPolicyConfig)`

SetTrafficPolicy sets TrafficPolicy field to given value.

### HasTrafficPolicy

`func (o *ManaV2CoreDeviceConfig) HasTrafficPolicy() bool`

HasTrafficPolicy returns a boolean if a field has been set.

### GetVrfs

`func (o *ManaV2CoreDeviceConfig) GetVrfs() map[string]ManaV2VrfConfig`

GetVrfs returns the Vrfs field if non-nil, zero value otherwise.

### GetVrfsOk

`func (o *ManaV2CoreDeviceConfig) GetVrfsOk() (*map[string]ManaV2VrfConfig, bool)`

GetVrfsOk returns a tuple with the Vrfs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfs

`func (o *ManaV2CoreDeviceConfig) SetVrfs(v map[string]ManaV2VrfConfig)`

SetVrfs sets Vrfs field to given value.

### HasVrfs

`func (o *ManaV2CoreDeviceConfig) HasVrfs() bool`

HasVrfs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



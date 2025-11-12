# V1DeviceRoutingBgpNbrsCountersGetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **string** | BGP Nbr address (required) | 
**DeviceId** | **int64** | Valid configured device ID &gt; 0 (required) | 
**VrfName** | **string** | Valid configured VRF name (required) | 

## Methods

### NewV1DeviceRoutingBgpNbrsCountersGetRequest

`func NewV1DeviceRoutingBgpNbrsCountersGetRequest(address string, deviceId int64, vrfName string, ) *V1DeviceRoutingBgpNbrsCountersGetRequest`

NewV1DeviceRoutingBgpNbrsCountersGetRequest instantiates a new V1DeviceRoutingBgpNbrsCountersGetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DeviceRoutingBgpNbrsCountersGetRequestWithDefaults

`func NewV1DeviceRoutingBgpNbrsCountersGetRequestWithDefaults() *V1DeviceRoutingBgpNbrsCountersGetRequest`

NewV1DeviceRoutingBgpNbrsCountersGetRequestWithDefaults instantiates a new V1DeviceRoutingBgpNbrsCountersGetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetDeviceId

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) GetDeviceId() int64`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) GetDeviceIdOk() (*int64, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) SetDeviceId(v int64)`

SetDeviceId sets DeviceId field to given value.


### GetVrfName

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) GetVrfName() string`

GetVrfName returns the VrfName field if non-nil, zero value otherwise.

### GetVrfNameOk

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) GetVrfNameOk() (*string, bool)`

GetVrfNameOk returns a tuple with the VrfName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrfName

`func (o *V1DeviceRoutingBgpNbrsCountersGetRequest) SetVrfName(v string)`

SetVrfName sets VrfName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



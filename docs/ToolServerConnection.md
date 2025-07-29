# ToolServerConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Path** | **string** |  | 
**AuthType** | [**AuthType**](AuthType.md) |  | 
**Key** | [**Key**](Key.md) |  | 
**Config** | [**Config**](Config.md) |  | 

## Methods

### NewToolServerConnection

`func NewToolServerConnection(url string, path string, authType AuthType, key Key, config Config, ) *ToolServerConnection`

NewToolServerConnection instantiates a new ToolServerConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolServerConnectionWithDefaults

`func NewToolServerConnectionWithDefaults() *ToolServerConnection`

NewToolServerConnectionWithDefaults instantiates a new ToolServerConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ToolServerConnection) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ToolServerConnection) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ToolServerConnection) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPath

`func (o *ToolServerConnection) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ToolServerConnection) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ToolServerConnection) SetPath(v string)`

SetPath sets Path field to given value.


### GetAuthType

`func (o *ToolServerConnection) GetAuthType() AuthType`

GetAuthType returns the AuthType field if non-nil, zero value otherwise.

### GetAuthTypeOk

`func (o *ToolServerConnection) GetAuthTypeOk() (*AuthType, bool)`

GetAuthTypeOk returns a tuple with the AuthType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthType

`func (o *ToolServerConnection) SetAuthType(v AuthType)`

SetAuthType sets AuthType field to given value.


### GetKey

`func (o *ToolServerConnection) GetKey() Key`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ToolServerConnection) GetKeyOk() (*Key, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ToolServerConnection) SetKey(v Key)`

SetKey sets Key field to given value.


### GetConfig

`func (o *ToolServerConnection) GetConfig() Config`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ToolServerConnection) GetConfigOk() (*Config, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ToolServerConnection) SetConfig(v Config)`

SetConfig sets Config field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



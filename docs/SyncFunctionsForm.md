# SyncFunctionsForm

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Content** | **string** |  | 
**Meta** | [**FunctionMeta**](FunctionMeta.md) |  | 
**Functions** | Pointer to [**[]FunctionModel**](FunctionModel.md) |  | [optional] [default to []]

## Methods

### NewSyncFunctionsForm

`func NewSyncFunctionsForm(id string, name string, content string, meta FunctionMeta, ) *SyncFunctionsForm`

NewSyncFunctionsForm instantiates a new SyncFunctionsForm object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncFunctionsFormWithDefaults

`func NewSyncFunctionsFormWithDefaults() *SyncFunctionsForm`

NewSyncFunctionsFormWithDefaults instantiates a new SyncFunctionsForm object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SyncFunctionsForm) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncFunctionsForm) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncFunctionsForm) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *SyncFunctionsForm) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SyncFunctionsForm) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SyncFunctionsForm) SetName(v string)`

SetName sets Name field to given value.


### GetContent

`func (o *SyncFunctionsForm) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *SyncFunctionsForm) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *SyncFunctionsForm) SetContent(v string)`

SetContent sets Content field to given value.


### GetMeta

`func (o *SyncFunctionsForm) GetMeta() FunctionMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *SyncFunctionsForm) GetMetaOk() (*FunctionMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *SyncFunctionsForm) SetMeta(v FunctionMeta)`

SetMeta sets Meta field to given value.


### GetFunctions

`func (o *SyncFunctionsForm) GetFunctions() []FunctionModel`

GetFunctions returns the Functions field if non-nil, zero value otherwise.

### GetFunctionsOk

`func (o *SyncFunctionsForm) GetFunctionsOk() (*[]FunctionModel, bool)`

GetFunctionsOk returns a tuple with the Functions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunctions

`func (o *SyncFunctionsForm) SetFunctions(v []FunctionModel)`

SetFunctions sets Functions field to given value.

### HasFunctions

`func (o *SyncFunctionsForm) HasFunctions() bool`

HasFunctions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



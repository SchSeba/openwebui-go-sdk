# ChatPermissions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Controls** | Pointer to **bool** |  | [optional] [default to true]
**SystemPrompt** | Pointer to **bool** |  | [optional] [default to true]
**FileUpload** | Pointer to **bool** |  | [optional] [default to true]
**Delete** | Pointer to **bool** |  | [optional] [default to true]
**Edit** | Pointer to **bool** |  | [optional] [default to true]
**Share** | Pointer to **bool** |  | [optional] [default to true]
**Export** | Pointer to **bool** |  | [optional] [default to true]
**Stt** | Pointer to **bool** |  | [optional] [default to true]
**Tts** | Pointer to **bool** |  | [optional] [default to true]
**Call** | Pointer to **bool** |  | [optional] [default to true]
**MultipleModels** | Pointer to **bool** |  | [optional] [default to true]
**Temporary** | Pointer to **bool** |  | [optional] [default to true]
**TemporaryEnforced** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewChatPermissions

`func NewChatPermissions() *ChatPermissions`

NewChatPermissions instantiates a new ChatPermissions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatPermissionsWithDefaults

`func NewChatPermissionsWithDefaults() *ChatPermissions`

NewChatPermissionsWithDefaults instantiates a new ChatPermissions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControls

`func (o *ChatPermissions) GetControls() bool`

GetControls returns the Controls field if non-nil, zero value otherwise.

### GetControlsOk

`func (o *ChatPermissions) GetControlsOk() (*bool, bool)`

GetControlsOk returns a tuple with the Controls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControls

`func (o *ChatPermissions) SetControls(v bool)`

SetControls sets Controls field to given value.

### HasControls

`func (o *ChatPermissions) HasControls() bool`

HasControls returns a boolean if a field has been set.

### GetSystemPrompt

`func (o *ChatPermissions) GetSystemPrompt() bool`

GetSystemPrompt returns the SystemPrompt field if non-nil, zero value otherwise.

### GetSystemPromptOk

`func (o *ChatPermissions) GetSystemPromptOk() (*bool, bool)`

GetSystemPromptOk returns a tuple with the SystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPrompt

`func (o *ChatPermissions) SetSystemPrompt(v bool)`

SetSystemPrompt sets SystemPrompt field to given value.

### HasSystemPrompt

`func (o *ChatPermissions) HasSystemPrompt() bool`

HasSystemPrompt returns a boolean if a field has been set.

### GetFileUpload

`func (o *ChatPermissions) GetFileUpload() bool`

GetFileUpload returns the FileUpload field if non-nil, zero value otherwise.

### GetFileUploadOk

`func (o *ChatPermissions) GetFileUploadOk() (*bool, bool)`

GetFileUploadOk returns a tuple with the FileUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileUpload

`func (o *ChatPermissions) SetFileUpload(v bool)`

SetFileUpload sets FileUpload field to given value.

### HasFileUpload

`func (o *ChatPermissions) HasFileUpload() bool`

HasFileUpload returns a boolean if a field has been set.

### GetDelete

`func (o *ChatPermissions) GetDelete() bool`

GetDelete returns the Delete field if non-nil, zero value otherwise.

### GetDeleteOk

`func (o *ChatPermissions) GetDeleteOk() (*bool, bool)`

GetDeleteOk returns a tuple with the Delete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelete

`func (o *ChatPermissions) SetDelete(v bool)`

SetDelete sets Delete field to given value.

### HasDelete

`func (o *ChatPermissions) HasDelete() bool`

HasDelete returns a boolean if a field has been set.

### GetEdit

`func (o *ChatPermissions) GetEdit() bool`

GetEdit returns the Edit field if non-nil, zero value otherwise.

### GetEditOk

`func (o *ChatPermissions) GetEditOk() (*bool, bool)`

GetEditOk returns a tuple with the Edit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdit

`func (o *ChatPermissions) SetEdit(v bool)`

SetEdit sets Edit field to given value.

### HasEdit

`func (o *ChatPermissions) HasEdit() bool`

HasEdit returns a boolean if a field has been set.

### GetShare

`func (o *ChatPermissions) GetShare() bool`

GetShare returns the Share field if non-nil, zero value otherwise.

### GetShareOk

`func (o *ChatPermissions) GetShareOk() (*bool, bool)`

GetShareOk returns a tuple with the Share field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShare

`func (o *ChatPermissions) SetShare(v bool)`

SetShare sets Share field to given value.

### HasShare

`func (o *ChatPermissions) HasShare() bool`

HasShare returns a boolean if a field has been set.

### GetExport

`func (o *ChatPermissions) GetExport() bool`

GetExport returns the Export field if non-nil, zero value otherwise.

### GetExportOk

`func (o *ChatPermissions) GetExportOk() (*bool, bool)`

GetExportOk returns a tuple with the Export field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExport

`func (o *ChatPermissions) SetExport(v bool)`

SetExport sets Export field to given value.

### HasExport

`func (o *ChatPermissions) HasExport() bool`

HasExport returns a boolean if a field has been set.

### GetStt

`func (o *ChatPermissions) GetStt() bool`

GetStt returns the Stt field if non-nil, zero value otherwise.

### GetSttOk

`func (o *ChatPermissions) GetSttOk() (*bool, bool)`

GetSttOk returns a tuple with the Stt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStt

`func (o *ChatPermissions) SetStt(v bool)`

SetStt sets Stt field to given value.

### HasStt

`func (o *ChatPermissions) HasStt() bool`

HasStt returns a boolean if a field has been set.

### GetTts

`func (o *ChatPermissions) GetTts() bool`

GetTts returns the Tts field if non-nil, zero value otherwise.

### GetTtsOk

`func (o *ChatPermissions) GetTtsOk() (*bool, bool)`

GetTtsOk returns a tuple with the Tts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTts

`func (o *ChatPermissions) SetTts(v bool)`

SetTts sets Tts field to given value.

### HasTts

`func (o *ChatPermissions) HasTts() bool`

HasTts returns a boolean if a field has been set.

### GetCall

`func (o *ChatPermissions) GetCall() bool`

GetCall returns the Call field if non-nil, zero value otherwise.

### GetCallOk

`func (o *ChatPermissions) GetCallOk() (*bool, bool)`

GetCallOk returns a tuple with the Call field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCall

`func (o *ChatPermissions) SetCall(v bool)`

SetCall sets Call field to given value.

### HasCall

`func (o *ChatPermissions) HasCall() bool`

HasCall returns a boolean if a field has been set.

### GetMultipleModels

`func (o *ChatPermissions) GetMultipleModels() bool`

GetMultipleModels returns the MultipleModels field if non-nil, zero value otherwise.

### GetMultipleModelsOk

`func (o *ChatPermissions) GetMultipleModelsOk() (*bool, bool)`

GetMultipleModelsOk returns a tuple with the MultipleModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipleModels

`func (o *ChatPermissions) SetMultipleModels(v bool)`

SetMultipleModels sets MultipleModels field to given value.

### HasMultipleModels

`func (o *ChatPermissions) HasMultipleModels() bool`

HasMultipleModels returns a boolean if a field has been set.

### GetTemporary

`func (o *ChatPermissions) GetTemporary() bool`

GetTemporary returns the Temporary field if non-nil, zero value otherwise.

### GetTemporaryOk

`func (o *ChatPermissions) GetTemporaryOk() (*bool, bool)`

GetTemporaryOk returns a tuple with the Temporary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemporary

`func (o *ChatPermissions) SetTemporary(v bool)`

SetTemporary sets Temporary field to given value.

### HasTemporary

`func (o *ChatPermissions) HasTemporary() bool`

HasTemporary returns a boolean if a field has been set.

### GetTemporaryEnforced

`func (o *ChatPermissions) GetTemporaryEnforced() bool`

GetTemporaryEnforced returns the TemporaryEnforced field if non-nil, zero value otherwise.

### GetTemporaryEnforcedOk

`func (o *ChatPermissions) GetTemporaryEnforcedOk() (*bool, bool)`

GetTemporaryEnforcedOk returns a tuple with the TemporaryEnforced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemporaryEnforced

`func (o *ChatPermissions) SetTemporaryEnforced(v bool)`

SetTemporaryEnforced sets TemporaryEnforced field to given value.

### HasTemporaryEnforced

`func (o *ChatPermissions) HasTemporaryEnforced() bool`

HasTemporaryEnforced returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



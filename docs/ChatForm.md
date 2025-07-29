# ChatForm

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Chat** | **map[string]interface{}** |  | 
**FolderId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewChatForm

`func NewChatForm(chat map[string]interface{}, ) *ChatForm`

NewChatForm instantiates a new ChatForm object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatFormWithDefaults

`func NewChatFormWithDefaults() *ChatForm`

NewChatFormWithDefaults instantiates a new ChatForm object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChat

`func (o *ChatForm) GetChat() map[string]interface{}`

GetChat returns the Chat field if non-nil, zero value otherwise.

### GetChatOk

`func (o *ChatForm) GetChatOk() (*map[string]interface{}, bool)`

GetChatOk returns a tuple with the Chat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChat

`func (o *ChatForm) SetChat(v map[string]interface{})`

SetChat sets Chat field to given value.


### GetFolderId

`func (o *ChatForm) GetFolderId() string`

GetFolderId returns the FolderId field if non-nil, zero value otherwise.

### GetFolderIdOk

`func (o *ChatForm) GetFolderIdOk() (*string, bool)`

GetFolderIdOk returns a tuple with the FolderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolderId

`func (o *ChatForm) SetFolderId(v string)`

SetFolderId sets FolderId field to given value.

### HasFolderId

`func (o *ChatForm) HasFolderId() bool`

HasFolderId returns a boolean if a field has been set.

### SetFolderIdNil

`func (o *ChatForm) SetFolderIdNil(b bool)`

 SetFolderIdNil sets the value for FolderId to be an explicit nil

### UnsetFolderId
`func (o *ChatForm) UnsetFolderId()`

UnsetFolderId ensures that no value is present for FolderId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



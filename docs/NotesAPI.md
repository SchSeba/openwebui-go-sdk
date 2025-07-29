# \NotesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateNewNoteApiV1NotesCreatePost**](NotesAPI.md#CreateNewNoteApiV1NotesCreatePost) | **Post** /api/v1/notes/create | Create New Note
[**DeleteNoteByIdApiV1NotesIdDeleteDelete**](NotesAPI.md#DeleteNoteByIdApiV1NotesIdDeleteDelete) | **Delete** /api/v1/notes/{id}/delete | Delete Note By Id
[**GetNoteByIdApiV1NotesIdGet**](NotesAPI.md#GetNoteByIdApiV1NotesIdGet) | **Get** /api/v1/notes/{id} | Get Note By Id
[**GetNoteListApiV1NotesListGet**](NotesAPI.md#GetNoteListApiV1NotesListGet) | **Get** /api/v1/notes/list | Get Note List
[**GetNotesApiV1NotesGet**](NotesAPI.md#GetNotesApiV1NotesGet) | **Get** /api/v1/notes/ | Get Notes
[**UpdateNoteByIdApiV1NotesIdUpdatePost**](NotesAPI.md#UpdateNoteByIdApiV1NotesIdUpdatePost) | **Post** /api/v1/notes/{id}/update | Update Note By Id



## CreateNewNoteApiV1NotesCreatePost

> NoteModel CreateNewNoteApiV1NotesCreatePost(ctx).NoteForm(noteForm).Execute()

Create New Note

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SchSeba/openwebui-go-sdk"
)

func main() {
	noteForm := *openapiclient.NewNoteForm("Title_example") // NoteForm | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotesAPI.CreateNewNoteApiV1NotesCreatePost(context.Background()).NoteForm(noteForm).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotesAPI.CreateNewNoteApiV1NotesCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateNewNoteApiV1NotesCreatePost`: NoteModel
	fmt.Fprintf(os.Stdout, "Response from `NotesAPI.CreateNewNoteApiV1NotesCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateNewNoteApiV1NotesCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **noteForm** | [**NoteForm**](NoteForm.md) |  | 

### Return type

[**NoteModel**](NoteModel.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteNoteByIdApiV1NotesIdDeleteDelete

> bool DeleteNoteByIdApiV1NotesIdDeleteDelete(ctx, id).Execute()

Delete Note By Id

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SchSeba/openwebui-go-sdk"
)

func main() {
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotesAPI.DeleteNoteByIdApiV1NotesIdDeleteDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotesAPI.DeleteNoteByIdApiV1NotesIdDeleteDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteNoteByIdApiV1NotesIdDeleteDelete`: bool
	fmt.Fprintf(os.Stdout, "Response from `NotesAPI.DeleteNoteByIdApiV1NotesIdDeleteDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteNoteByIdApiV1NotesIdDeleteDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**bool**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNoteByIdApiV1NotesIdGet

> NoteModel GetNoteByIdApiV1NotesIdGet(ctx, id).Execute()

Get Note By Id

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SchSeba/openwebui-go-sdk"
)

func main() {
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotesAPI.GetNoteByIdApiV1NotesIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotesAPI.GetNoteByIdApiV1NotesIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNoteByIdApiV1NotesIdGet`: NoteModel
	fmt.Fprintf(os.Stdout, "Response from `NotesAPI.GetNoteByIdApiV1NotesIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNoteByIdApiV1NotesIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NoteModel**](NoteModel.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNoteListApiV1NotesListGet

> []NoteTitleIdResponse GetNoteListApiV1NotesListGet(ctx).Execute()

Get Note List

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SchSeba/openwebui-go-sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotesAPI.GetNoteListApiV1NotesListGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotesAPI.GetNoteListApiV1NotesListGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNoteListApiV1NotesListGet`: []NoteTitleIdResponse
	fmt.Fprintf(os.Stdout, "Response from `NotesAPI.GetNoteListApiV1NotesListGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetNoteListApiV1NotesListGetRequest struct via the builder pattern


### Return type

[**[]NoteTitleIdResponse**](NoteTitleIdResponse.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNotesApiV1NotesGet

> []NoteUserResponse GetNotesApiV1NotesGet(ctx).Execute()

Get Notes

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SchSeba/openwebui-go-sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotesAPI.GetNotesApiV1NotesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotesAPI.GetNotesApiV1NotesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNotesApiV1NotesGet`: []NoteUserResponse
	fmt.Fprintf(os.Stdout, "Response from `NotesAPI.GetNotesApiV1NotesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetNotesApiV1NotesGetRequest struct via the builder pattern


### Return type

[**[]NoteUserResponse**](NoteUserResponse.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateNoteByIdApiV1NotesIdUpdatePost

> NoteModel UpdateNoteByIdApiV1NotesIdUpdatePost(ctx, id).NoteForm(noteForm).Execute()

Update Note By Id

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SchSeba/openwebui-go-sdk"
)

func main() {
	id := "id_example" // string | 
	noteForm := *openapiclient.NewNoteForm("Title_example") // NoteForm | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotesAPI.UpdateNoteByIdApiV1NotesIdUpdatePost(context.Background(), id).NoteForm(noteForm).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotesAPI.UpdateNoteByIdApiV1NotesIdUpdatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateNoteByIdApiV1NotesIdUpdatePost`: NoteModel
	fmt.Fprintf(os.Stdout, "Response from `NotesAPI.UpdateNoteByIdApiV1NotesIdUpdatePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateNoteByIdApiV1NotesIdUpdatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **noteForm** | [**NoteForm**](NoteForm.md) |  | 

### Return type

[**NoteModel**](NoteModel.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


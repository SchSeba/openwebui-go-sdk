# \TasksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GenerateAutocompletionApiV1TasksAutoCompletionsPost**](TasksAPI.md#GenerateAutocompletionApiV1TasksAutoCompletionsPost) | **Post** /api/v1/tasks/auto/completions | Generate Autocompletion
[**GenerateChatTagsApiV1TasksTagsCompletionsPost**](TasksAPI.md#GenerateChatTagsApiV1TasksTagsCompletionsPost) | **Post** /api/v1/tasks/tags/completions | Generate Chat Tags
[**GenerateEmojiApiV1TasksEmojiCompletionsPost**](TasksAPI.md#GenerateEmojiApiV1TasksEmojiCompletionsPost) | **Post** /api/v1/tasks/emoji/completions | Generate Emoji
[**GenerateFollowUpsApiV1TasksFollowUpCompletionsPost**](TasksAPI.md#GenerateFollowUpsApiV1TasksFollowUpCompletionsPost) | **Post** /api/v1/tasks/follow_up/completions | Generate Follow Ups
[**GenerateImagePromptApiV1TasksImagePromptCompletionsPost**](TasksAPI.md#GenerateImagePromptApiV1TasksImagePromptCompletionsPost) | **Post** /api/v1/tasks/image_prompt/completions | Generate Image Prompt
[**GenerateMoaResponseApiV1TasksMoaCompletionsPost**](TasksAPI.md#GenerateMoaResponseApiV1TasksMoaCompletionsPost) | **Post** /api/v1/tasks/moa/completions | Generate Moa Response
[**GenerateQueriesApiV1TasksQueriesCompletionsPost**](TasksAPI.md#GenerateQueriesApiV1TasksQueriesCompletionsPost) | **Post** /api/v1/tasks/queries/completions | Generate Queries
[**GenerateTitleApiV1TasksTitleCompletionsPost**](TasksAPI.md#GenerateTitleApiV1TasksTitleCompletionsPost) | **Post** /api/v1/tasks/title/completions | Generate Title
[**GetTaskConfigApiV1TasksConfigGet**](TasksAPI.md#GetTaskConfigApiV1TasksConfigGet) | **Get** /api/v1/tasks/config | Get Task Config
[**UpdateTaskConfigApiV1TasksConfigUpdatePost**](TasksAPI.md#UpdateTaskConfigApiV1TasksConfigUpdatePost) | **Post** /api/v1/tasks/config/update | Update Task Config



## GenerateAutocompletionApiV1TasksAutoCompletionsPost

> interface{} GenerateAutocompletionApiV1TasksAutoCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Autocompletion

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateAutocompletionApiV1TasksAutoCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateAutocompletionApiV1TasksAutoCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateAutocompletionApiV1TasksAutoCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateAutocompletionApiV1TasksAutoCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateAutocompletionApiV1TasksAutoCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateChatTagsApiV1TasksTagsCompletionsPost

> interface{} GenerateChatTagsApiV1TasksTagsCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Chat Tags

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateChatTagsApiV1TasksTagsCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateChatTagsApiV1TasksTagsCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateChatTagsApiV1TasksTagsCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateChatTagsApiV1TasksTagsCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateChatTagsApiV1TasksTagsCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateEmojiApiV1TasksEmojiCompletionsPost

> interface{} GenerateEmojiApiV1TasksEmojiCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Emoji

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateEmojiApiV1TasksEmojiCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateEmojiApiV1TasksEmojiCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateEmojiApiV1TasksEmojiCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateEmojiApiV1TasksEmojiCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateEmojiApiV1TasksEmojiCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateFollowUpsApiV1TasksFollowUpCompletionsPost

> interface{} GenerateFollowUpsApiV1TasksFollowUpCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Follow Ups

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateFollowUpsApiV1TasksFollowUpCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateFollowUpsApiV1TasksFollowUpCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateFollowUpsApiV1TasksFollowUpCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateFollowUpsApiV1TasksFollowUpCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateFollowUpsApiV1TasksFollowUpCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateImagePromptApiV1TasksImagePromptCompletionsPost

> interface{} GenerateImagePromptApiV1TasksImagePromptCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Image Prompt

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateImagePromptApiV1TasksImagePromptCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateImagePromptApiV1TasksImagePromptCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateImagePromptApiV1TasksImagePromptCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateImagePromptApiV1TasksImagePromptCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateImagePromptApiV1TasksImagePromptCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateMoaResponseApiV1TasksMoaCompletionsPost

> interface{} GenerateMoaResponseApiV1TasksMoaCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Moa Response

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateMoaResponseApiV1TasksMoaCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateMoaResponseApiV1TasksMoaCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateMoaResponseApiV1TasksMoaCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateMoaResponseApiV1TasksMoaCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateMoaResponseApiV1TasksMoaCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateQueriesApiV1TasksQueriesCompletionsPost

> interface{} GenerateQueriesApiV1TasksQueriesCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Queries

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateQueriesApiV1TasksQueriesCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateQueriesApiV1TasksQueriesCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateQueriesApiV1TasksQueriesCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateQueriesApiV1TasksQueriesCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateQueriesApiV1TasksQueriesCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateTitleApiV1TasksTitleCompletionsPost

> interface{} GenerateTitleApiV1TasksTitleCompletionsPost(ctx).RequestBody(requestBody).Execute()

Generate Title

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
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.GenerateTitleApiV1TasksTitleCompletionsPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GenerateTitleApiV1TasksTitleCompletionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateTitleApiV1TasksTitleCompletionsPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GenerateTitleApiV1TasksTitleCompletionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateTitleApiV1TasksTitleCompletionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]interface{}** |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskConfigApiV1TasksConfigGet

> interface{} GetTaskConfigApiV1TasksConfigGet(ctx).Execute()

Get Task Config

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
	resp, r, err := apiClient.TasksAPI.GetTaskConfigApiV1TasksConfigGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.GetTaskConfigApiV1TasksConfigGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskConfigApiV1TasksConfigGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.GetTaskConfigApiV1TasksConfigGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskConfigApiV1TasksConfigGetRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTaskConfigApiV1TasksConfigUpdatePost

> interface{} UpdateTaskConfigApiV1TasksConfigUpdatePost(ctx).TaskConfigForm(taskConfigForm).Execute()

Update Task Config

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
	taskConfigForm := *openapiclient.NewTaskConfigForm("TASK_MODEL_example", "TASK_MODEL_EXTERNAL_example", false, "TITLE_GENERATION_PROMPT_TEMPLATE_example", "IMAGE_PROMPT_GENERATION_PROMPT_TEMPLATE_example", false, int32(123), "TAGS_GENERATION_PROMPT_TEMPLATE_example", "FOLLOW_UP_GENERATION_PROMPT_TEMPLATE_example", false, false, false, false, "QUERY_GENERATION_PROMPT_TEMPLATE_example", "TOOLS_FUNCTION_CALLING_PROMPT_TEMPLATE_example") // TaskConfigForm | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TasksAPI.UpdateTaskConfigApiV1TasksConfigUpdatePost(context.Background()).TaskConfigForm(taskConfigForm).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TasksAPI.UpdateTaskConfigApiV1TasksConfigUpdatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTaskConfigApiV1TasksConfigUpdatePost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TasksAPI.UpdateTaskConfigApiV1TasksConfigUpdatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTaskConfigApiV1TasksConfigUpdatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **taskConfigForm** | [**TaskConfigForm**](TaskConfigForm.md) |  | 

### Return type

**interface{}**

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


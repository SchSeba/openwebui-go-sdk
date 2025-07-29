# WebConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ENABLE_WEB_SEARCH** | Pointer to **NullableBool** |  | [optional] 
**WEB_SEARCH_ENGINE** | Pointer to **NullableString** |  | [optional] 
**WEB_SEARCH_TRUST_ENV** | Pointer to **NullableBool** |  | [optional] 
**WEB_SEARCH_RESULT_COUNT** | Pointer to **NullableInt32** |  | [optional] 
**WEB_SEARCH_CONCURRENT_REQUESTS** | Pointer to **NullableInt32** |  | [optional] 
**WEB_SEARCH_DOMAIN_FILTER_LIST** | Pointer to **[]string** |  | [optional] 
**BYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL** | Pointer to **NullableBool** |  | [optional] 
**BYPASS_WEB_SEARCH_WEB_LOADER** | Pointer to **NullableBool** |  | [optional] 
**SEARXNG_QUERY_URL** | Pointer to **NullableString** |  | [optional] 
**YACY_QUERY_URL** | Pointer to **NullableString** |  | [optional] 
**YACY_USERNAME** | Pointer to **NullableString** |  | [optional] 
**YACY_PASSWORD** | Pointer to **NullableString** |  | [optional] 
**GOOGLE_PSE_API_KEY** | Pointer to **NullableString** |  | [optional] 
**GOOGLE_PSE_ENGINE_ID** | Pointer to **NullableString** |  | [optional] 
**BRAVE_SEARCH_API_KEY** | Pointer to **NullableString** |  | [optional] 
**KAGI_SEARCH_API_KEY** | Pointer to **NullableString** |  | [optional] 
**MOJEEK_SEARCH_API_KEY** | Pointer to **NullableString** |  | [optional] 
**BOCHA_SEARCH_API_KEY** | Pointer to **NullableString** |  | [optional] 
**SERPSTACK_API_KEY** | Pointer to **NullableString** |  | [optional] 
**SERPSTACK_HTTPS** | Pointer to **NullableBool** |  | [optional] 
**SERPER_API_KEY** | Pointer to **NullableString** |  | [optional] 
**SERPLY_API_KEY** | Pointer to **NullableString** |  | [optional] 
**TAVILY_API_KEY** | Pointer to **NullableString** |  | [optional] 
**SEARCHAPI_API_KEY** | Pointer to **NullableString** |  | [optional] 
**SEARCHAPI_ENGINE** | Pointer to **NullableString** |  | [optional] 
**SERPAPI_API_KEY** | Pointer to **NullableString** |  | [optional] 
**SERPAPI_ENGINE** | Pointer to **NullableString** |  | [optional] 
**JINA_API_KEY** | Pointer to **NullableString** |  | [optional] 
**BINGSEARCHV7ENDPOINT** | Pointer to **NullableString** |  | [optional] 
**BINGSEARCHV7SUBSCRIPTIONKEY** | Pointer to **NullableString** |  | [optional] 
**EXA_API_KEY** | Pointer to **NullableString** |  | [optional] 
**PERPLEXITY_API_KEY** | Pointer to **NullableString** |  | [optional] 
**PERPLEXITY_MODEL** | Pointer to **NullableString** |  | [optional] 
**PERPLEXITY_SEARCH_CONTEXT_USAGE** | Pointer to **NullableString** |  | [optional] 
**SOUGOU_API_SID** | Pointer to **NullableString** |  | [optional] 
**SOUGOU_API_SK** | Pointer to **NullableString** |  | [optional] 
**WEB_LOADER_ENGINE** | Pointer to **NullableString** |  | [optional] 
**ENABLE_WEB_LOADER_SSL_VERIFICATION** | Pointer to **NullableBool** |  | [optional] 
**PLAYWRIGHT_WS_URL** | Pointer to **NullableString** |  | [optional] 
**PLAYWRIGHT_TIMEOUT** | Pointer to **NullableInt32** |  | [optional] 
**FIRECRAWL_API_KEY** | Pointer to **NullableString** |  | [optional] 
**FIRECRAWL_API_BASE_URL** | Pointer to **NullableString** |  | [optional] 
**TAVILY_EXTRACT_DEPTH** | Pointer to **NullableString** |  | [optional] 
**EXTERNAL_WEB_SEARCH_URL** | Pointer to **NullableString** |  | [optional] 
**EXTERNAL_WEB_SEARCH_API_KEY** | Pointer to **NullableString** |  | [optional] 
**EXTERNAL_WEB_LOADER_URL** | Pointer to **NullableString** |  | [optional] 
**EXTERNAL_WEB_LOADER_API_KEY** | Pointer to **NullableString** |  | [optional] 
**YOUTUBE_LOADER_LANGUAGE** | Pointer to **[]string** |  | [optional] 
**YOUTUBE_LOADER_PROXY_URL** | Pointer to **NullableString** |  | [optional] 
**YOUTUBE_LOADER_TRANSLATION** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWebConfig

`func NewWebConfig() *WebConfig`

NewWebConfig instantiates a new WebConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebConfigWithDefaults

`func NewWebConfigWithDefaults() *WebConfig`

NewWebConfigWithDefaults instantiates a new WebConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetENABLE_WEB_SEARCH

`func (o *WebConfig) GetENABLE_WEB_SEARCH() bool`

GetENABLE_WEB_SEARCH returns the ENABLE_WEB_SEARCH field if non-nil, zero value otherwise.

### GetENABLE_WEB_SEARCHOk

`func (o *WebConfig) GetENABLE_WEB_SEARCHOk() (*bool, bool)`

GetENABLE_WEB_SEARCHOk returns a tuple with the ENABLE_WEB_SEARCH field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_WEB_SEARCH

`func (o *WebConfig) SetENABLE_WEB_SEARCH(v bool)`

SetENABLE_WEB_SEARCH sets ENABLE_WEB_SEARCH field to given value.

### HasENABLE_WEB_SEARCH

`func (o *WebConfig) HasENABLE_WEB_SEARCH() bool`

HasENABLE_WEB_SEARCH returns a boolean if a field has been set.

### SetENABLE_WEB_SEARCHNil

`func (o *WebConfig) SetENABLE_WEB_SEARCHNil(b bool)`

 SetENABLE_WEB_SEARCHNil sets the value for ENABLE_WEB_SEARCH to be an explicit nil

### UnsetENABLE_WEB_SEARCH
`func (o *WebConfig) UnsetENABLE_WEB_SEARCH()`

UnsetENABLE_WEB_SEARCH ensures that no value is present for ENABLE_WEB_SEARCH, not even an explicit nil
### GetWEB_SEARCH_ENGINE

`func (o *WebConfig) GetWEB_SEARCH_ENGINE() string`

GetWEB_SEARCH_ENGINE returns the WEB_SEARCH_ENGINE field if non-nil, zero value otherwise.

### GetWEB_SEARCH_ENGINEOk

`func (o *WebConfig) GetWEB_SEARCH_ENGINEOk() (*string, bool)`

GetWEB_SEARCH_ENGINEOk returns a tuple with the WEB_SEARCH_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEB_SEARCH_ENGINE

`func (o *WebConfig) SetWEB_SEARCH_ENGINE(v string)`

SetWEB_SEARCH_ENGINE sets WEB_SEARCH_ENGINE field to given value.

### HasWEB_SEARCH_ENGINE

`func (o *WebConfig) HasWEB_SEARCH_ENGINE() bool`

HasWEB_SEARCH_ENGINE returns a boolean if a field has been set.

### SetWEB_SEARCH_ENGINENil

`func (o *WebConfig) SetWEB_SEARCH_ENGINENil(b bool)`

 SetWEB_SEARCH_ENGINENil sets the value for WEB_SEARCH_ENGINE to be an explicit nil

### UnsetWEB_SEARCH_ENGINE
`func (o *WebConfig) UnsetWEB_SEARCH_ENGINE()`

UnsetWEB_SEARCH_ENGINE ensures that no value is present for WEB_SEARCH_ENGINE, not even an explicit nil
### GetWEB_SEARCH_TRUST_ENV

`func (o *WebConfig) GetWEB_SEARCH_TRUST_ENV() bool`

GetWEB_SEARCH_TRUST_ENV returns the WEB_SEARCH_TRUST_ENV field if non-nil, zero value otherwise.

### GetWEB_SEARCH_TRUST_ENVOk

`func (o *WebConfig) GetWEB_SEARCH_TRUST_ENVOk() (*bool, bool)`

GetWEB_SEARCH_TRUST_ENVOk returns a tuple with the WEB_SEARCH_TRUST_ENV field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEB_SEARCH_TRUST_ENV

`func (o *WebConfig) SetWEB_SEARCH_TRUST_ENV(v bool)`

SetWEB_SEARCH_TRUST_ENV sets WEB_SEARCH_TRUST_ENV field to given value.

### HasWEB_SEARCH_TRUST_ENV

`func (o *WebConfig) HasWEB_SEARCH_TRUST_ENV() bool`

HasWEB_SEARCH_TRUST_ENV returns a boolean if a field has been set.

### SetWEB_SEARCH_TRUST_ENVNil

`func (o *WebConfig) SetWEB_SEARCH_TRUST_ENVNil(b bool)`

 SetWEB_SEARCH_TRUST_ENVNil sets the value for WEB_SEARCH_TRUST_ENV to be an explicit nil

### UnsetWEB_SEARCH_TRUST_ENV
`func (o *WebConfig) UnsetWEB_SEARCH_TRUST_ENV()`

UnsetWEB_SEARCH_TRUST_ENV ensures that no value is present for WEB_SEARCH_TRUST_ENV, not even an explicit nil
### GetWEB_SEARCH_RESULT_COUNT

`func (o *WebConfig) GetWEB_SEARCH_RESULT_COUNT() int32`

GetWEB_SEARCH_RESULT_COUNT returns the WEB_SEARCH_RESULT_COUNT field if non-nil, zero value otherwise.

### GetWEB_SEARCH_RESULT_COUNTOk

`func (o *WebConfig) GetWEB_SEARCH_RESULT_COUNTOk() (*int32, bool)`

GetWEB_SEARCH_RESULT_COUNTOk returns a tuple with the WEB_SEARCH_RESULT_COUNT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEB_SEARCH_RESULT_COUNT

`func (o *WebConfig) SetWEB_SEARCH_RESULT_COUNT(v int32)`

SetWEB_SEARCH_RESULT_COUNT sets WEB_SEARCH_RESULT_COUNT field to given value.

### HasWEB_SEARCH_RESULT_COUNT

`func (o *WebConfig) HasWEB_SEARCH_RESULT_COUNT() bool`

HasWEB_SEARCH_RESULT_COUNT returns a boolean if a field has been set.

### SetWEB_SEARCH_RESULT_COUNTNil

`func (o *WebConfig) SetWEB_SEARCH_RESULT_COUNTNil(b bool)`

 SetWEB_SEARCH_RESULT_COUNTNil sets the value for WEB_SEARCH_RESULT_COUNT to be an explicit nil

### UnsetWEB_SEARCH_RESULT_COUNT
`func (o *WebConfig) UnsetWEB_SEARCH_RESULT_COUNT()`

UnsetWEB_SEARCH_RESULT_COUNT ensures that no value is present for WEB_SEARCH_RESULT_COUNT, not even an explicit nil
### GetWEB_SEARCH_CONCURRENT_REQUESTS

`func (o *WebConfig) GetWEB_SEARCH_CONCURRENT_REQUESTS() int32`

GetWEB_SEARCH_CONCURRENT_REQUESTS returns the WEB_SEARCH_CONCURRENT_REQUESTS field if non-nil, zero value otherwise.

### GetWEB_SEARCH_CONCURRENT_REQUESTSOk

`func (o *WebConfig) GetWEB_SEARCH_CONCURRENT_REQUESTSOk() (*int32, bool)`

GetWEB_SEARCH_CONCURRENT_REQUESTSOk returns a tuple with the WEB_SEARCH_CONCURRENT_REQUESTS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEB_SEARCH_CONCURRENT_REQUESTS

`func (o *WebConfig) SetWEB_SEARCH_CONCURRENT_REQUESTS(v int32)`

SetWEB_SEARCH_CONCURRENT_REQUESTS sets WEB_SEARCH_CONCURRENT_REQUESTS field to given value.

### HasWEB_SEARCH_CONCURRENT_REQUESTS

`func (o *WebConfig) HasWEB_SEARCH_CONCURRENT_REQUESTS() bool`

HasWEB_SEARCH_CONCURRENT_REQUESTS returns a boolean if a field has been set.

### SetWEB_SEARCH_CONCURRENT_REQUESTSNil

`func (o *WebConfig) SetWEB_SEARCH_CONCURRENT_REQUESTSNil(b bool)`

 SetWEB_SEARCH_CONCURRENT_REQUESTSNil sets the value for WEB_SEARCH_CONCURRENT_REQUESTS to be an explicit nil

### UnsetWEB_SEARCH_CONCURRENT_REQUESTS
`func (o *WebConfig) UnsetWEB_SEARCH_CONCURRENT_REQUESTS()`

UnsetWEB_SEARCH_CONCURRENT_REQUESTS ensures that no value is present for WEB_SEARCH_CONCURRENT_REQUESTS, not even an explicit nil
### GetWEB_SEARCH_DOMAIN_FILTER_LIST

`func (o *WebConfig) GetWEB_SEARCH_DOMAIN_FILTER_LIST() []string`

GetWEB_SEARCH_DOMAIN_FILTER_LIST returns the WEB_SEARCH_DOMAIN_FILTER_LIST field if non-nil, zero value otherwise.

### GetWEB_SEARCH_DOMAIN_FILTER_LISTOk

`func (o *WebConfig) GetWEB_SEARCH_DOMAIN_FILTER_LISTOk() (*[]string, bool)`

GetWEB_SEARCH_DOMAIN_FILTER_LISTOk returns a tuple with the WEB_SEARCH_DOMAIN_FILTER_LIST field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEB_SEARCH_DOMAIN_FILTER_LIST

`func (o *WebConfig) SetWEB_SEARCH_DOMAIN_FILTER_LIST(v []string)`

SetWEB_SEARCH_DOMAIN_FILTER_LIST sets WEB_SEARCH_DOMAIN_FILTER_LIST field to given value.

### HasWEB_SEARCH_DOMAIN_FILTER_LIST

`func (o *WebConfig) HasWEB_SEARCH_DOMAIN_FILTER_LIST() bool`

HasWEB_SEARCH_DOMAIN_FILTER_LIST returns a boolean if a field has been set.

### SetWEB_SEARCH_DOMAIN_FILTER_LISTNil

`func (o *WebConfig) SetWEB_SEARCH_DOMAIN_FILTER_LISTNil(b bool)`

 SetWEB_SEARCH_DOMAIN_FILTER_LISTNil sets the value for WEB_SEARCH_DOMAIN_FILTER_LIST to be an explicit nil

### UnsetWEB_SEARCH_DOMAIN_FILTER_LIST
`func (o *WebConfig) UnsetWEB_SEARCH_DOMAIN_FILTER_LIST()`

UnsetWEB_SEARCH_DOMAIN_FILTER_LIST ensures that no value is present for WEB_SEARCH_DOMAIN_FILTER_LIST, not even an explicit nil
### GetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL

`func (o *WebConfig) GetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL() bool`

GetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL returns the BYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL field if non-nil, zero value otherwise.

### GetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVALOk

`func (o *WebConfig) GetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVALOk() (*bool, bool)`

GetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVALOk returns a tuple with the BYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL

`func (o *WebConfig) SetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL(v bool)`

SetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL sets BYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL field to given value.

### HasBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL

`func (o *WebConfig) HasBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL() bool`

HasBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL returns a boolean if a field has been set.

### SetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVALNil

`func (o *WebConfig) SetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVALNil(b bool)`

 SetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVALNil sets the value for BYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL to be an explicit nil

### UnsetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL
`func (o *WebConfig) UnsetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL()`

UnsetBYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL ensures that no value is present for BYPASS_WEB_SEARCH_EMBEDDING_AND_RETRIEVAL, not even an explicit nil
### GetBYPASS_WEB_SEARCH_WEB_LOADER

`func (o *WebConfig) GetBYPASS_WEB_SEARCH_WEB_LOADER() bool`

GetBYPASS_WEB_SEARCH_WEB_LOADER returns the BYPASS_WEB_SEARCH_WEB_LOADER field if non-nil, zero value otherwise.

### GetBYPASS_WEB_SEARCH_WEB_LOADEROk

`func (o *WebConfig) GetBYPASS_WEB_SEARCH_WEB_LOADEROk() (*bool, bool)`

GetBYPASS_WEB_SEARCH_WEB_LOADEROk returns a tuple with the BYPASS_WEB_SEARCH_WEB_LOADER field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBYPASS_WEB_SEARCH_WEB_LOADER

`func (o *WebConfig) SetBYPASS_WEB_SEARCH_WEB_LOADER(v bool)`

SetBYPASS_WEB_SEARCH_WEB_LOADER sets BYPASS_WEB_SEARCH_WEB_LOADER field to given value.

### HasBYPASS_WEB_SEARCH_WEB_LOADER

`func (o *WebConfig) HasBYPASS_WEB_SEARCH_WEB_LOADER() bool`

HasBYPASS_WEB_SEARCH_WEB_LOADER returns a boolean if a field has been set.

### SetBYPASS_WEB_SEARCH_WEB_LOADERNil

`func (o *WebConfig) SetBYPASS_WEB_SEARCH_WEB_LOADERNil(b bool)`

 SetBYPASS_WEB_SEARCH_WEB_LOADERNil sets the value for BYPASS_WEB_SEARCH_WEB_LOADER to be an explicit nil

### UnsetBYPASS_WEB_SEARCH_WEB_LOADER
`func (o *WebConfig) UnsetBYPASS_WEB_SEARCH_WEB_LOADER()`

UnsetBYPASS_WEB_SEARCH_WEB_LOADER ensures that no value is present for BYPASS_WEB_SEARCH_WEB_LOADER, not even an explicit nil
### GetSEARXNG_QUERY_URL

`func (o *WebConfig) GetSEARXNG_QUERY_URL() string`

GetSEARXNG_QUERY_URL returns the SEARXNG_QUERY_URL field if non-nil, zero value otherwise.

### GetSEARXNG_QUERY_URLOk

`func (o *WebConfig) GetSEARXNG_QUERY_URLOk() (*string, bool)`

GetSEARXNG_QUERY_URLOk returns a tuple with the SEARXNG_QUERY_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSEARXNG_QUERY_URL

`func (o *WebConfig) SetSEARXNG_QUERY_URL(v string)`

SetSEARXNG_QUERY_URL sets SEARXNG_QUERY_URL field to given value.

### HasSEARXNG_QUERY_URL

`func (o *WebConfig) HasSEARXNG_QUERY_URL() bool`

HasSEARXNG_QUERY_URL returns a boolean if a field has been set.

### SetSEARXNG_QUERY_URLNil

`func (o *WebConfig) SetSEARXNG_QUERY_URLNil(b bool)`

 SetSEARXNG_QUERY_URLNil sets the value for SEARXNG_QUERY_URL to be an explicit nil

### UnsetSEARXNG_QUERY_URL
`func (o *WebConfig) UnsetSEARXNG_QUERY_URL()`

UnsetSEARXNG_QUERY_URL ensures that no value is present for SEARXNG_QUERY_URL, not even an explicit nil
### GetYACY_QUERY_URL

`func (o *WebConfig) GetYACY_QUERY_URL() string`

GetYACY_QUERY_URL returns the YACY_QUERY_URL field if non-nil, zero value otherwise.

### GetYACY_QUERY_URLOk

`func (o *WebConfig) GetYACY_QUERY_URLOk() (*string, bool)`

GetYACY_QUERY_URLOk returns a tuple with the YACY_QUERY_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYACY_QUERY_URL

`func (o *WebConfig) SetYACY_QUERY_URL(v string)`

SetYACY_QUERY_URL sets YACY_QUERY_URL field to given value.

### HasYACY_QUERY_URL

`func (o *WebConfig) HasYACY_QUERY_URL() bool`

HasYACY_QUERY_URL returns a boolean if a field has been set.

### SetYACY_QUERY_URLNil

`func (o *WebConfig) SetYACY_QUERY_URLNil(b bool)`

 SetYACY_QUERY_URLNil sets the value for YACY_QUERY_URL to be an explicit nil

### UnsetYACY_QUERY_URL
`func (o *WebConfig) UnsetYACY_QUERY_URL()`

UnsetYACY_QUERY_URL ensures that no value is present for YACY_QUERY_URL, not even an explicit nil
### GetYACY_USERNAME

`func (o *WebConfig) GetYACY_USERNAME() string`

GetYACY_USERNAME returns the YACY_USERNAME field if non-nil, zero value otherwise.

### GetYACY_USERNAMEOk

`func (o *WebConfig) GetYACY_USERNAMEOk() (*string, bool)`

GetYACY_USERNAMEOk returns a tuple with the YACY_USERNAME field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYACY_USERNAME

`func (o *WebConfig) SetYACY_USERNAME(v string)`

SetYACY_USERNAME sets YACY_USERNAME field to given value.

### HasYACY_USERNAME

`func (o *WebConfig) HasYACY_USERNAME() bool`

HasYACY_USERNAME returns a boolean if a field has been set.

### SetYACY_USERNAMENil

`func (o *WebConfig) SetYACY_USERNAMENil(b bool)`

 SetYACY_USERNAMENil sets the value for YACY_USERNAME to be an explicit nil

### UnsetYACY_USERNAME
`func (o *WebConfig) UnsetYACY_USERNAME()`

UnsetYACY_USERNAME ensures that no value is present for YACY_USERNAME, not even an explicit nil
### GetYACY_PASSWORD

`func (o *WebConfig) GetYACY_PASSWORD() string`

GetYACY_PASSWORD returns the YACY_PASSWORD field if non-nil, zero value otherwise.

### GetYACY_PASSWORDOk

`func (o *WebConfig) GetYACY_PASSWORDOk() (*string, bool)`

GetYACY_PASSWORDOk returns a tuple with the YACY_PASSWORD field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYACY_PASSWORD

`func (o *WebConfig) SetYACY_PASSWORD(v string)`

SetYACY_PASSWORD sets YACY_PASSWORD field to given value.

### HasYACY_PASSWORD

`func (o *WebConfig) HasYACY_PASSWORD() bool`

HasYACY_PASSWORD returns a boolean if a field has been set.

### SetYACY_PASSWORDNil

`func (o *WebConfig) SetYACY_PASSWORDNil(b bool)`

 SetYACY_PASSWORDNil sets the value for YACY_PASSWORD to be an explicit nil

### UnsetYACY_PASSWORD
`func (o *WebConfig) UnsetYACY_PASSWORD()`

UnsetYACY_PASSWORD ensures that no value is present for YACY_PASSWORD, not even an explicit nil
### GetGOOGLE_PSE_API_KEY

`func (o *WebConfig) GetGOOGLE_PSE_API_KEY() string`

GetGOOGLE_PSE_API_KEY returns the GOOGLE_PSE_API_KEY field if non-nil, zero value otherwise.

### GetGOOGLE_PSE_API_KEYOk

`func (o *WebConfig) GetGOOGLE_PSE_API_KEYOk() (*string, bool)`

GetGOOGLE_PSE_API_KEYOk returns a tuple with the GOOGLE_PSE_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGOOGLE_PSE_API_KEY

`func (o *WebConfig) SetGOOGLE_PSE_API_KEY(v string)`

SetGOOGLE_PSE_API_KEY sets GOOGLE_PSE_API_KEY field to given value.

### HasGOOGLE_PSE_API_KEY

`func (o *WebConfig) HasGOOGLE_PSE_API_KEY() bool`

HasGOOGLE_PSE_API_KEY returns a boolean if a field has been set.

### SetGOOGLE_PSE_API_KEYNil

`func (o *WebConfig) SetGOOGLE_PSE_API_KEYNil(b bool)`

 SetGOOGLE_PSE_API_KEYNil sets the value for GOOGLE_PSE_API_KEY to be an explicit nil

### UnsetGOOGLE_PSE_API_KEY
`func (o *WebConfig) UnsetGOOGLE_PSE_API_KEY()`

UnsetGOOGLE_PSE_API_KEY ensures that no value is present for GOOGLE_PSE_API_KEY, not even an explicit nil
### GetGOOGLE_PSE_ENGINE_ID

`func (o *WebConfig) GetGOOGLE_PSE_ENGINE_ID() string`

GetGOOGLE_PSE_ENGINE_ID returns the GOOGLE_PSE_ENGINE_ID field if non-nil, zero value otherwise.

### GetGOOGLE_PSE_ENGINE_IDOk

`func (o *WebConfig) GetGOOGLE_PSE_ENGINE_IDOk() (*string, bool)`

GetGOOGLE_PSE_ENGINE_IDOk returns a tuple with the GOOGLE_PSE_ENGINE_ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGOOGLE_PSE_ENGINE_ID

`func (o *WebConfig) SetGOOGLE_PSE_ENGINE_ID(v string)`

SetGOOGLE_PSE_ENGINE_ID sets GOOGLE_PSE_ENGINE_ID field to given value.

### HasGOOGLE_PSE_ENGINE_ID

`func (o *WebConfig) HasGOOGLE_PSE_ENGINE_ID() bool`

HasGOOGLE_PSE_ENGINE_ID returns a boolean if a field has been set.

### SetGOOGLE_PSE_ENGINE_IDNil

`func (o *WebConfig) SetGOOGLE_PSE_ENGINE_IDNil(b bool)`

 SetGOOGLE_PSE_ENGINE_IDNil sets the value for GOOGLE_PSE_ENGINE_ID to be an explicit nil

### UnsetGOOGLE_PSE_ENGINE_ID
`func (o *WebConfig) UnsetGOOGLE_PSE_ENGINE_ID()`

UnsetGOOGLE_PSE_ENGINE_ID ensures that no value is present for GOOGLE_PSE_ENGINE_ID, not even an explicit nil
### GetBRAVE_SEARCH_API_KEY

`func (o *WebConfig) GetBRAVE_SEARCH_API_KEY() string`

GetBRAVE_SEARCH_API_KEY returns the BRAVE_SEARCH_API_KEY field if non-nil, zero value otherwise.

### GetBRAVE_SEARCH_API_KEYOk

`func (o *WebConfig) GetBRAVE_SEARCH_API_KEYOk() (*string, bool)`

GetBRAVE_SEARCH_API_KEYOk returns a tuple with the BRAVE_SEARCH_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBRAVE_SEARCH_API_KEY

`func (o *WebConfig) SetBRAVE_SEARCH_API_KEY(v string)`

SetBRAVE_SEARCH_API_KEY sets BRAVE_SEARCH_API_KEY field to given value.

### HasBRAVE_SEARCH_API_KEY

`func (o *WebConfig) HasBRAVE_SEARCH_API_KEY() bool`

HasBRAVE_SEARCH_API_KEY returns a boolean if a field has been set.

### SetBRAVE_SEARCH_API_KEYNil

`func (o *WebConfig) SetBRAVE_SEARCH_API_KEYNil(b bool)`

 SetBRAVE_SEARCH_API_KEYNil sets the value for BRAVE_SEARCH_API_KEY to be an explicit nil

### UnsetBRAVE_SEARCH_API_KEY
`func (o *WebConfig) UnsetBRAVE_SEARCH_API_KEY()`

UnsetBRAVE_SEARCH_API_KEY ensures that no value is present for BRAVE_SEARCH_API_KEY, not even an explicit nil
### GetKAGI_SEARCH_API_KEY

`func (o *WebConfig) GetKAGI_SEARCH_API_KEY() string`

GetKAGI_SEARCH_API_KEY returns the KAGI_SEARCH_API_KEY field if non-nil, zero value otherwise.

### GetKAGI_SEARCH_API_KEYOk

`func (o *WebConfig) GetKAGI_SEARCH_API_KEYOk() (*string, bool)`

GetKAGI_SEARCH_API_KEYOk returns a tuple with the KAGI_SEARCH_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKAGI_SEARCH_API_KEY

`func (o *WebConfig) SetKAGI_SEARCH_API_KEY(v string)`

SetKAGI_SEARCH_API_KEY sets KAGI_SEARCH_API_KEY field to given value.

### HasKAGI_SEARCH_API_KEY

`func (o *WebConfig) HasKAGI_SEARCH_API_KEY() bool`

HasKAGI_SEARCH_API_KEY returns a boolean if a field has been set.

### SetKAGI_SEARCH_API_KEYNil

`func (o *WebConfig) SetKAGI_SEARCH_API_KEYNil(b bool)`

 SetKAGI_SEARCH_API_KEYNil sets the value for KAGI_SEARCH_API_KEY to be an explicit nil

### UnsetKAGI_SEARCH_API_KEY
`func (o *WebConfig) UnsetKAGI_SEARCH_API_KEY()`

UnsetKAGI_SEARCH_API_KEY ensures that no value is present for KAGI_SEARCH_API_KEY, not even an explicit nil
### GetMOJEEK_SEARCH_API_KEY

`func (o *WebConfig) GetMOJEEK_SEARCH_API_KEY() string`

GetMOJEEK_SEARCH_API_KEY returns the MOJEEK_SEARCH_API_KEY field if non-nil, zero value otherwise.

### GetMOJEEK_SEARCH_API_KEYOk

`func (o *WebConfig) GetMOJEEK_SEARCH_API_KEYOk() (*string, bool)`

GetMOJEEK_SEARCH_API_KEYOk returns a tuple with the MOJEEK_SEARCH_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMOJEEK_SEARCH_API_KEY

`func (o *WebConfig) SetMOJEEK_SEARCH_API_KEY(v string)`

SetMOJEEK_SEARCH_API_KEY sets MOJEEK_SEARCH_API_KEY field to given value.

### HasMOJEEK_SEARCH_API_KEY

`func (o *WebConfig) HasMOJEEK_SEARCH_API_KEY() bool`

HasMOJEEK_SEARCH_API_KEY returns a boolean if a field has been set.

### SetMOJEEK_SEARCH_API_KEYNil

`func (o *WebConfig) SetMOJEEK_SEARCH_API_KEYNil(b bool)`

 SetMOJEEK_SEARCH_API_KEYNil sets the value for MOJEEK_SEARCH_API_KEY to be an explicit nil

### UnsetMOJEEK_SEARCH_API_KEY
`func (o *WebConfig) UnsetMOJEEK_SEARCH_API_KEY()`

UnsetMOJEEK_SEARCH_API_KEY ensures that no value is present for MOJEEK_SEARCH_API_KEY, not even an explicit nil
### GetBOCHA_SEARCH_API_KEY

`func (o *WebConfig) GetBOCHA_SEARCH_API_KEY() string`

GetBOCHA_SEARCH_API_KEY returns the BOCHA_SEARCH_API_KEY field if non-nil, zero value otherwise.

### GetBOCHA_SEARCH_API_KEYOk

`func (o *WebConfig) GetBOCHA_SEARCH_API_KEYOk() (*string, bool)`

GetBOCHA_SEARCH_API_KEYOk returns a tuple with the BOCHA_SEARCH_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBOCHA_SEARCH_API_KEY

`func (o *WebConfig) SetBOCHA_SEARCH_API_KEY(v string)`

SetBOCHA_SEARCH_API_KEY sets BOCHA_SEARCH_API_KEY field to given value.

### HasBOCHA_SEARCH_API_KEY

`func (o *WebConfig) HasBOCHA_SEARCH_API_KEY() bool`

HasBOCHA_SEARCH_API_KEY returns a boolean if a field has been set.

### SetBOCHA_SEARCH_API_KEYNil

`func (o *WebConfig) SetBOCHA_SEARCH_API_KEYNil(b bool)`

 SetBOCHA_SEARCH_API_KEYNil sets the value for BOCHA_SEARCH_API_KEY to be an explicit nil

### UnsetBOCHA_SEARCH_API_KEY
`func (o *WebConfig) UnsetBOCHA_SEARCH_API_KEY()`

UnsetBOCHA_SEARCH_API_KEY ensures that no value is present for BOCHA_SEARCH_API_KEY, not even an explicit nil
### GetSERPSTACK_API_KEY

`func (o *WebConfig) GetSERPSTACK_API_KEY() string`

GetSERPSTACK_API_KEY returns the SERPSTACK_API_KEY field if non-nil, zero value otherwise.

### GetSERPSTACK_API_KEYOk

`func (o *WebConfig) GetSERPSTACK_API_KEYOk() (*string, bool)`

GetSERPSTACK_API_KEYOk returns a tuple with the SERPSTACK_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSERPSTACK_API_KEY

`func (o *WebConfig) SetSERPSTACK_API_KEY(v string)`

SetSERPSTACK_API_KEY sets SERPSTACK_API_KEY field to given value.

### HasSERPSTACK_API_KEY

`func (o *WebConfig) HasSERPSTACK_API_KEY() bool`

HasSERPSTACK_API_KEY returns a boolean if a field has been set.

### SetSERPSTACK_API_KEYNil

`func (o *WebConfig) SetSERPSTACK_API_KEYNil(b bool)`

 SetSERPSTACK_API_KEYNil sets the value for SERPSTACK_API_KEY to be an explicit nil

### UnsetSERPSTACK_API_KEY
`func (o *WebConfig) UnsetSERPSTACK_API_KEY()`

UnsetSERPSTACK_API_KEY ensures that no value is present for SERPSTACK_API_KEY, not even an explicit nil
### GetSERPSTACK_HTTPS

`func (o *WebConfig) GetSERPSTACK_HTTPS() bool`

GetSERPSTACK_HTTPS returns the SERPSTACK_HTTPS field if non-nil, zero value otherwise.

### GetSERPSTACK_HTTPSOk

`func (o *WebConfig) GetSERPSTACK_HTTPSOk() (*bool, bool)`

GetSERPSTACK_HTTPSOk returns a tuple with the SERPSTACK_HTTPS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSERPSTACK_HTTPS

`func (o *WebConfig) SetSERPSTACK_HTTPS(v bool)`

SetSERPSTACK_HTTPS sets SERPSTACK_HTTPS field to given value.

### HasSERPSTACK_HTTPS

`func (o *WebConfig) HasSERPSTACK_HTTPS() bool`

HasSERPSTACK_HTTPS returns a boolean if a field has been set.

### SetSERPSTACK_HTTPSNil

`func (o *WebConfig) SetSERPSTACK_HTTPSNil(b bool)`

 SetSERPSTACK_HTTPSNil sets the value for SERPSTACK_HTTPS to be an explicit nil

### UnsetSERPSTACK_HTTPS
`func (o *WebConfig) UnsetSERPSTACK_HTTPS()`

UnsetSERPSTACK_HTTPS ensures that no value is present for SERPSTACK_HTTPS, not even an explicit nil
### GetSERPER_API_KEY

`func (o *WebConfig) GetSERPER_API_KEY() string`

GetSERPER_API_KEY returns the SERPER_API_KEY field if non-nil, zero value otherwise.

### GetSERPER_API_KEYOk

`func (o *WebConfig) GetSERPER_API_KEYOk() (*string, bool)`

GetSERPER_API_KEYOk returns a tuple with the SERPER_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSERPER_API_KEY

`func (o *WebConfig) SetSERPER_API_KEY(v string)`

SetSERPER_API_KEY sets SERPER_API_KEY field to given value.

### HasSERPER_API_KEY

`func (o *WebConfig) HasSERPER_API_KEY() bool`

HasSERPER_API_KEY returns a boolean if a field has been set.

### SetSERPER_API_KEYNil

`func (o *WebConfig) SetSERPER_API_KEYNil(b bool)`

 SetSERPER_API_KEYNil sets the value for SERPER_API_KEY to be an explicit nil

### UnsetSERPER_API_KEY
`func (o *WebConfig) UnsetSERPER_API_KEY()`

UnsetSERPER_API_KEY ensures that no value is present for SERPER_API_KEY, not even an explicit nil
### GetSERPLY_API_KEY

`func (o *WebConfig) GetSERPLY_API_KEY() string`

GetSERPLY_API_KEY returns the SERPLY_API_KEY field if non-nil, zero value otherwise.

### GetSERPLY_API_KEYOk

`func (o *WebConfig) GetSERPLY_API_KEYOk() (*string, bool)`

GetSERPLY_API_KEYOk returns a tuple with the SERPLY_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSERPLY_API_KEY

`func (o *WebConfig) SetSERPLY_API_KEY(v string)`

SetSERPLY_API_KEY sets SERPLY_API_KEY field to given value.

### HasSERPLY_API_KEY

`func (o *WebConfig) HasSERPLY_API_KEY() bool`

HasSERPLY_API_KEY returns a boolean if a field has been set.

### SetSERPLY_API_KEYNil

`func (o *WebConfig) SetSERPLY_API_KEYNil(b bool)`

 SetSERPLY_API_KEYNil sets the value for SERPLY_API_KEY to be an explicit nil

### UnsetSERPLY_API_KEY
`func (o *WebConfig) UnsetSERPLY_API_KEY()`

UnsetSERPLY_API_KEY ensures that no value is present for SERPLY_API_KEY, not even an explicit nil
### GetTAVILY_API_KEY

`func (o *WebConfig) GetTAVILY_API_KEY() string`

GetTAVILY_API_KEY returns the TAVILY_API_KEY field if non-nil, zero value otherwise.

### GetTAVILY_API_KEYOk

`func (o *WebConfig) GetTAVILY_API_KEYOk() (*string, bool)`

GetTAVILY_API_KEYOk returns a tuple with the TAVILY_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTAVILY_API_KEY

`func (o *WebConfig) SetTAVILY_API_KEY(v string)`

SetTAVILY_API_KEY sets TAVILY_API_KEY field to given value.

### HasTAVILY_API_KEY

`func (o *WebConfig) HasTAVILY_API_KEY() bool`

HasTAVILY_API_KEY returns a boolean if a field has been set.

### SetTAVILY_API_KEYNil

`func (o *WebConfig) SetTAVILY_API_KEYNil(b bool)`

 SetTAVILY_API_KEYNil sets the value for TAVILY_API_KEY to be an explicit nil

### UnsetTAVILY_API_KEY
`func (o *WebConfig) UnsetTAVILY_API_KEY()`

UnsetTAVILY_API_KEY ensures that no value is present for TAVILY_API_KEY, not even an explicit nil
### GetSEARCHAPI_API_KEY

`func (o *WebConfig) GetSEARCHAPI_API_KEY() string`

GetSEARCHAPI_API_KEY returns the SEARCHAPI_API_KEY field if non-nil, zero value otherwise.

### GetSEARCHAPI_API_KEYOk

`func (o *WebConfig) GetSEARCHAPI_API_KEYOk() (*string, bool)`

GetSEARCHAPI_API_KEYOk returns a tuple with the SEARCHAPI_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSEARCHAPI_API_KEY

`func (o *WebConfig) SetSEARCHAPI_API_KEY(v string)`

SetSEARCHAPI_API_KEY sets SEARCHAPI_API_KEY field to given value.

### HasSEARCHAPI_API_KEY

`func (o *WebConfig) HasSEARCHAPI_API_KEY() bool`

HasSEARCHAPI_API_KEY returns a boolean if a field has been set.

### SetSEARCHAPI_API_KEYNil

`func (o *WebConfig) SetSEARCHAPI_API_KEYNil(b bool)`

 SetSEARCHAPI_API_KEYNil sets the value for SEARCHAPI_API_KEY to be an explicit nil

### UnsetSEARCHAPI_API_KEY
`func (o *WebConfig) UnsetSEARCHAPI_API_KEY()`

UnsetSEARCHAPI_API_KEY ensures that no value is present for SEARCHAPI_API_KEY, not even an explicit nil
### GetSEARCHAPI_ENGINE

`func (o *WebConfig) GetSEARCHAPI_ENGINE() string`

GetSEARCHAPI_ENGINE returns the SEARCHAPI_ENGINE field if non-nil, zero value otherwise.

### GetSEARCHAPI_ENGINEOk

`func (o *WebConfig) GetSEARCHAPI_ENGINEOk() (*string, bool)`

GetSEARCHAPI_ENGINEOk returns a tuple with the SEARCHAPI_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSEARCHAPI_ENGINE

`func (o *WebConfig) SetSEARCHAPI_ENGINE(v string)`

SetSEARCHAPI_ENGINE sets SEARCHAPI_ENGINE field to given value.

### HasSEARCHAPI_ENGINE

`func (o *WebConfig) HasSEARCHAPI_ENGINE() bool`

HasSEARCHAPI_ENGINE returns a boolean if a field has been set.

### SetSEARCHAPI_ENGINENil

`func (o *WebConfig) SetSEARCHAPI_ENGINENil(b bool)`

 SetSEARCHAPI_ENGINENil sets the value for SEARCHAPI_ENGINE to be an explicit nil

### UnsetSEARCHAPI_ENGINE
`func (o *WebConfig) UnsetSEARCHAPI_ENGINE()`

UnsetSEARCHAPI_ENGINE ensures that no value is present for SEARCHAPI_ENGINE, not even an explicit nil
### GetSERPAPI_API_KEY

`func (o *WebConfig) GetSERPAPI_API_KEY() string`

GetSERPAPI_API_KEY returns the SERPAPI_API_KEY field if non-nil, zero value otherwise.

### GetSERPAPI_API_KEYOk

`func (o *WebConfig) GetSERPAPI_API_KEYOk() (*string, bool)`

GetSERPAPI_API_KEYOk returns a tuple with the SERPAPI_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSERPAPI_API_KEY

`func (o *WebConfig) SetSERPAPI_API_KEY(v string)`

SetSERPAPI_API_KEY sets SERPAPI_API_KEY field to given value.

### HasSERPAPI_API_KEY

`func (o *WebConfig) HasSERPAPI_API_KEY() bool`

HasSERPAPI_API_KEY returns a boolean if a field has been set.

### SetSERPAPI_API_KEYNil

`func (o *WebConfig) SetSERPAPI_API_KEYNil(b bool)`

 SetSERPAPI_API_KEYNil sets the value for SERPAPI_API_KEY to be an explicit nil

### UnsetSERPAPI_API_KEY
`func (o *WebConfig) UnsetSERPAPI_API_KEY()`

UnsetSERPAPI_API_KEY ensures that no value is present for SERPAPI_API_KEY, not even an explicit nil
### GetSERPAPI_ENGINE

`func (o *WebConfig) GetSERPAPI_ENGINE() string`

GetSERPAPI_ENGINE returns the SERPAPI_ENGINE field if non-nil, zero value otherwise.

### GetSERPAPI_ENGINEOk

`func (o *WebConfig) GetSERPAPI_ENGINEOk() (*string, bool)`

GetSERPAPI_ENGINEOk returns a tuple with the SERPAPI_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSERPAPI_ENGINE

`func (o *WebConfig) SetSERPAPI_ENGINE(v string)`

SetSERPAPI_ENGINE sets SERPAPI_ENGINE field to given value.

### HasSERPAPI_ENGINE

`func (o *WebConfig) HasSERPAPI_ENGINE() bool`

HasSERPAPI_ENGINE returns a boolean if a field has been set.

### SetSERPAPI_ENGINENil

`func (o *WebConfig) SetSERPAPI_ENGINENil(b bool)`

 SetSERPAPI_ENGINENil sets the value for SERPAPI_ENGINE to be an explicit nil

### UnsetSERPAPI_ENGINE
`func (o *WebConfig) UnsetSERPAPI_ENGINE()`

UnsetSERPAPI_ENGINE ensures that no value is present for SERPAPI_ENGINE, not even an explicit nil
### GetJINA_API_KEY

`func (o *WebConfig) GetJINA_API_KEY() string`

GetJINA_API_KEY returns the JINA_API_KEY field if non-nil, zero value otherwise.

### GetJINA_API_KEYOk

`func (o *WebConfig) GetJINA_API_KEYOk() (*string, bool)`

GetJINA_API_KEYOk returns a tuple with the JINA_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJINA_API_KEY

`func (o *WebConfig) SetJINA_API_KEY(v string)`

SetJINA_API_KEY sets JINA_API_KEY field to given value.

### HasJINA_API_KEY

`func (o *WebConfig) HasJINA_API_KEY() bool`

HasJINA_API_KEY returns a boolean if a field has been set.

### SetJINA_API_KEYNil

`func (o *WebConfig) SetJINA_API_KEYNil(b bool)`

 SetJINA_API_KEYNil sets the value for JINA_API_KEY to be an explicit nil

### UnsetJINA_API_KEY
`func (o *WebConfig) UnsetJINA_API_KEY()`

UnsetJINA_API_KEY ensures that no value is present for JINA_API_KEY, not even an explicit nil
### GetBINGSEARCHV7ENDPOINT

`func (o *WebConfig) GetBINGSEARCHV7ENDPOINT() string`

GetBINGSEARCHV7ENDPOINT returns the BINGSEARCHV7ENDPOINT field if non-nil, zero value otherwise.

### GetBINGSEARCHV7ENDPOINTOk

`func (o *WebConfig) GetBINGSEARCHV7ENDPOINTOk() (*string, bool)`

GetBINGSEARCHV7ENDPOINTOk returns a tuple with the BINGSEARCHV7ENDPOINT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBINGSEARCHV7ENDPOINT

`func (o *WebConfig) SetBINGSEARCHV7ENDPOINT(v string)`

SetBINGSEARCHV7ENDPOINT sets BINGSEARCHV7ENDPOINT field to given value.

### HasBINGSEARCHV7ENDPOINT

`func (o *WebConfig) HasBINGSEARCHV7ENDPOINT() bool`

HasBINGSEARCHV7ENDPOINT returns a boolean if a field has been set.

### SetBINGSEARCHV7ENDPOINTNil

`func (o *WebConfig) SetBINGSEARCHV7ENDPOINTNil(b bool)`

 SetBINGSEARCHV7ENDPOINTNil sets the value for BINGSEARCHV7ENDPOINT to be an explicit nil

### UnsetBINGSEARCHV7ENDPOINT
`func (o *WebConfig) UnsetBINGSEARCHV7ENDPOINT()`

UnsetBINGSEARCHV7ENDPOINT ensures that no value is present for BINGSEARCHV7ENDPOINT, not even an explicit nil
### GetBINGSEARCHV7SUBSCRIPTIONKEY

`func (o *WebConfig) GetBINGSEARCHV7SUBSCRIPTIONKEY() string`

GetBINGSEARCHV7SUBSCRIPTIONKEY returns the BINGSEARCHV7SUBSCRIPTIONKEY field if non-nil, zero value otherwise.

### GetBINGSEARCHV7SUBSCRIPTIONKEYOk

`func (o *WebConfig) GetBINGSEARCHV7SUBSCRIPTIONKEYOk() (*string, bool)`

GetBINGSEARCHV7SUBSCRIPTIONKEYOk returns a tuple with the BINGSEARCHV7SUBSCRIPTIONKEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBINGSEARCHV7SUBSCRIPTIONKEY

`func (o *WebConfig) SetBINGSEARCHV7SUBSCRIPTIONKEY(v string)`

SetBINGSEARCHV7SUBSCRIPTIONKEY sets BINGSEARCHV7SUBSCRIPTIONKEY field to given value.

### HasBINGSEARCHV7SUBSCRIPTIONKEY

`func (o *WebConfig) HasBINGSEARCHV7SUBSCRIPTIONKEY() bool`

HasBINGSEARCHV7SUBSCRIPTIONKEY returns a boolean if a field has been set.

### SetBINGSEARCHV7SUBSCRIPTIONKEYNil

`func (o *WebConfig) SetBINGSEARCHV7SUBSCRIPTIONKEYNil(b bool)`

 SetBINGSEARCHV7SUBSCRIPTIONKEYNil sets the value for BINGSEARCHV7SUBSCRIPTIONKEY to be an explicit nil

### UnsetBINGSEARCHV7SUBSCRIPTIONKEY
`func (o *WebConfig) UnsetBINGSEARCHV7SUBSCRIPTIONKEY()`

UnsetBINGSEARCHV7SUBSCRIPTIONKEY ensures that no value is present for BINGSEARCHV7SUBSCRIPTIONKEY, not even an explicit nil
### GetEXA_API_KEY

`func (o *WebConfig) GetEXA_API_KEY() string`

GetEXA_API_KEY returns the EXA_API_KEY field if non-nil, zero value otherwise.

### GetEXA_API_KEYOk

`func (o *WebConfig) GetEXA_API_KEYOk() (*string, bool)`

GetEXA_API_KEYOk returns a tuple with the EXA_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXA_API_KEY

`func (o *WebConfig) SetEXA_API_KEY(v string)`

SetEXA_API_KEY sets EXA_API_KEY field to given value.

### HasEXA_API_KEY

`func (o *WebConfig) HasEXA_API_KEY() bool`

HasEXA_API_KEY returns a boolean if a field has been set.

### SetEXA_API_KEYNil

`func (o *WebConfig) SetEXA_API_KEYNil(b bool)`

 SetEXA_API_KEYNil sets the value for EXA_API_KEY to be an explicit nil

### UnsetEXA_API_KEY
`func (o *WebConfig) UnsetEXA_API_KEY()`

UnsetEXA_API_KEY ensures that no value is present for EXA_API_KEY, not even an explicit nil
### GetPERPLEXITY_API_KEY

`func (o *WebConfig) GetPERPLEXITY_API_KEY() string`

GetPERPLEXITY_API_KEY returns the PERPLEXITY_API_KEY field if non-nil, zero value otherwise.

### GetPERPLEXITY_API_KEYOk

`func (o *WebConfig) GetPERPLEXITY_API_KEYOk() (*string, bool)`

GetPERPLEXITY_API_KEYOk returns a tuple with the PERPLEXITY_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPERPLEXITY_API_KEY

`func (o *WebConfig) SetPERPLEXITY_API_KEY(v string)`

SetPERPLEXITY_API_KEY sets PERPLEXITY_API_KEY field to given value.

### HasPERPLEXITY_API_KEY

`func (o *WebConfig) HasPERPLEXITY_API_KEY() bool`

HasPERPLEXITY_API_KEY returns a boolean if a field has been set.

### SetPERPLEXITY_API_KEYNil

`func (o *WebConfig) SetPERPLEXITY_API_KEYNil(b bool)`

 SetPERPLEXITY_API_KEYNil sets the value for PERPLEXITY_API_KEY to be an explicit nil

### UnsetPERPLEXITY_API_KEY
`func (o *WebConfig) UnsetPERPLEXITY_API_KEY()`

UnsetPERPLEXITY_API_KEY ensures that no value is present for PERPLEXITY_API_KEY, not even an explicit nil
### GetPERPLEXITY_MODEL

`func (o *WebConfig) GetPERPLEXITY_MODEL() string`

GetPERPLEXITY_MODEL returns the PERPLEXITY_MODEL field if non-nil, zero value otherwise.

### GetPERPLEXITY_MODELOk

`func (o *WebConfig) GetPERPLEXITY_MODELOk() (*string, bool)`

GetPERPLEXITY_MODELOk returns a tuple with the PERPLEXITY_MODEL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPERPLEXITY_MODEL

`func (o *WebConfig) SetPERPLEXITY_MODEL(v string)`

SetPERPLEXITY_MODEL sets PERPLEXITY_MODEL field to given value.

### HasPERPLEXITY_MODEL

`func (o *WebConfig) HasPERPLEXITY_MODEL() bool`

HasPERPLEXITY_MODEL returns a boolean if a field has been set.

### SetPERPLEXITY_MODELNil

`func (o *WebConfig) SetPERPLEXITY_MODELNil(b bool)`

 SetPERPLEXITY_MODELNil sets the value for PERPLEXITY_MODEL to be an explicit nil

### UnsetPERPLEXITY_MODEL
`func (o *WebConfig) UnsetPERPLEXITY_MODEL()`

UnsetPERPLEXITY_MODEL ensures that no value is present for PERPLEXITY_MODEL, not even an explicit nil
### GetPERPLEXITY_SEARCH_CONTEXT_USAGE

`func (o *WebConfig) GetPERPLEXITY_SEARCH_CONTEXT_USAGE() string`

GetPERPLEXITY_SEARCH_CONTEXT_USAGE returns the PERPLEXITY_SEARCH_CONTEXT_USAGE field if non-nil, zero value otherwise.

### GetPERPLEXITY_SEARCH_CONTEXT_USAGEOk

`func (o *WebConfig) GetPERPLEXITY_SEARCH_CONTEXT_USAGEOk() (*string, bool)`

GetPERPLEXITY_SEARCH_CONTEXT_USAGEOk returns a tuple with the PERPLEXITY_SEARCH_CONTEXT_USAGE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPERPLEXITY_SEARCH_CONTEXT_USAGE

`func (o *WebConfig) SetPERPLEXITY_SEARCH_CONTEXT_USAGE(v string)`

SetPERPLEXITY_SEARCH_CONTEXT_USAGE sets PERPLEXITY_SEARCH_CONTEXT_USAGE field to given value.

### HasPERPLEXITY_SEARCH_CONTEXT_USAGE

`func (o *WebConfig) HasPERPLEXITY_SEARCH_CONTEXT_USAGE() bool`

HasPERPLEXITY_SEARCH_CONTEXT_USAGE returns a boolean if a field has been set.

### SetPERPLEXITY_SEARCH_CONTEXT_USAGENil

`func (o *WebConfig) SetPERPLEXITY_SEARCH_CONTEXT_USAGENil(b bool)`

 SetPERPLEXITY_SEARCH_CONTEXT_USAGENil sets the value for PERPLEXITY_SEARCH_CONTEXT_USAGE to be an explicit nil

### UnsetPERPLEXITY_SEARCH_CONTEXT_USAGE
`func (o *WebConfig) UnsetPERPLEXITY_SEARCH_CONTEXT_USAGE()`

UnsetPERPLEXITY_SEARCH_CONTEXT_USAGE ensures that no value is present for PERPLEXITY_SEARCH_CONTEXT_USAGE, not even an explicit nil
### GetSOUGOU_API_SID

`func (o *WebConfig) GetSOUGOU_API_SID() string`

GetSOUGOU_API_SID returns the SOUGOU_API_SID field if non-nil, zero value otherwise.

### GetSOUGOU_API_SIDOk

`func (o *WebConfig) GetSOUGOU_API_SIDOk() (*string, bool)`

GetSOUGOU_API_SIDOk returns a tuple with the SOUGOU_API_SID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSOUGOU_API_SID

`func (o *WebConfig) SetSOUGOU_API_SID(v string)`

SetSOUGOU_API_SID sets SOUGOU_API_SID field to given value.

### HasSOUGOU_API_SID

`func (o *WebConfig) HasSOUGOU_API_SID() bool`

HasSOUGOU_API_SID returns a boolean if a field has been set.

### SetSOUGOU_API_SIDNil

`func (o *WebConfig) SetSOUGOU_API_SIDNil(b bool)`

 SetSOUGOU_API_SIDNil sets the value for SOUGOU_API_SID to be an explicit nil

### UnsetSOUGOU_API_SID
`func (o *WebConfig) UnsetSOUGOU_API_SID()`

UnsetSOUGOU_API_SID ensures that no value is present for SOUGOU_API_SID, not even an explicit nil
### GetSOUGOU_API_SK

`func (o *WebConfig) GetSOUGOU_API_SK() string`

GetSOUGOU_API_SK returns the SOUGOU_API_SK field if non-nil, zero value otherwise.

### GetSOUGOU_API_SKOk

`func (o *WebConfig) GetSOUGOU_API_SKOk() (*string, bool)`

GetSOUGOU_API_SKOk returns a tuple with the SOUGOU_API_SK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSOUGOU_API_SK

`func (o *WebConfig) SetSOUGOU_API_SK(v string)`

SetSOUGOU_API_SK sets SOUGOU_API_SK field to given value.

### HasSOUGOU_API_SK

`func (o *WebConfig) HasSOUGOU_API_SK() bool`

HasSOUGOU_API_SK returns a boolean if a field has been set.

### SetSOUGOU_API_SKNil

`func (o *WebConfig) SetSOUGOU_API_SKNil(b bool)`

 SetSOUGOU_API_SKNil sets the value for SOUGOU_API_SK to be an explicit nil

### UnsetSOUGOU_API_SK
`func (o *WebConfig) UnsetSOUGOU_API_SK()`

UnsetSOUGOU_API_SK ensures that no value is present for SOUGOU_API_SK, not even an explicit nil
### GetWEB_LOADER_ENGINE

`func (o *WebConfig) GetWEB_LOADER_ENGINE() string`

GetWEB_LOADER_ENGINE returns the WEB_LOADER_ENGINE field if non-nil, zero value otherwise.

### GetWEB_LOADER_ENGINEOk

`func (o *WebConfig) GetWEB_LOADER_ENGINEOk() (*string, bool)`

GetWEB_LOADER_ENGINEOk returns a tuple with the WEB_LOADER_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEB_LOADER_ENGINE

`func (o *WebConfig) SetWEB_LOADER_ENGINE(v string)`

SetWEB_LOADER_ENGINE sets WEB_LOADER_ENGINE field to given value.

### HasWEB_LOADER_ENGINE

`func (o *WebConfig) HasWEB_LOADER_ENGINE() bool`

HasWEB_LOADER_ENGINE returns a boolean if a field has been set.

### SetWEB_LOADER_ENGINENil

`func (o *WebConfig) SetWEB_LOADER_ENGINENil(b bool)`

 SetWEB_LOADER_ENGINENil sets the value for WEB_LOADER_ENGINE to be an explicit nil

### UnsetWEB_LOADER_ENGINE
`func (o *WebConfig) UnsetWEB_LOADER_ENGINE()`

UnsetWEB_LOADER_ENGINE ensures that no value is present for WEB_LOADER_ENGINE, not even an explicit nil
### GetENABLE_WEB_LOADER_SSL_VERIFICATION

`func (o *WebConfig) GetENABLE_WEB_LOADER_SSL_VERIFICATION() bool`

GetENABLE_WEB_LOADER_SSL_VERIFICATION returns the ENABLE_WEB_LOADER_SSL_VERIFICATION field if non-nil, zero value otherwise.

### GetENABLE_WEB_LOADER_SSL_VERIFICATIONOk

`func (o *WebConfig) GetENABLE_WEB_LOADER_SSL_VERIFICATIONOk() (*bool, bool)`

GetENABLE_WEB_LOADER_SSL_VERIFICATIONOk returns a tuple with the ENABLE_WEB_LOADER_SSL_VERIFICATION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_WEB_LOADER_SSL_VERIFICATION

`func (o *WebConfig) SetENABLE_WEB_LOADER_SSL_VERIFICATION(v bool)`

SetENABLE_WEB_LOADER_SSL_VERIFICATION sets ENABLE_WEB_LOADER_SSL_VERIFICATION field to given value.

### HasENABLE_WEB_LOADER_SSL_VERIFICATION

`func (o *WebConfig) HasENABLE_WEB_LOADER_SSL_VERIFICATION() bool`

HasENABLE_WEB_LOADER_SSL_VERIFICATION returns a boolean if a field has been set.

### SetENABLE_WEB_LOADER_SSL_VERIFICATIONNil

`func (o *WebConfig) SetENABLE_WEB_LOADER_SSL_VERIFICATIONNil(b bool)`

 SetENABLE_WEB_LOADER_SSL_VERIFICATIONNil sets the value for ENABLE_WEB_LOADER_SSL_VERIFICATION to be an explicit nil

### UnsetENABLE_WEB_LOADER_SSL_VERIFICATION
`func (o *WebConfig) UnsetENABLE_WEB_LOADER_SSL_VERIFICATION()`

UnsetENABLE_WEB_LOADER_SSL_VERIFICATION ensures that no value is present for ENABLE_WEB_LOADER_SSL_VERIFICATION, not even an explicit nil
### GetPLAYWRIGHT_WS_URL

`func (o *WebConfig) GetPLAYWRIGHT_WS_URL() string`

GetPLAYWRIGHT_WS_URL returns the PLAYWRIGHT_WS_URL field if non-nil, zero value otherwise.

### GetPLAYWRIGHT_WS_URLOk

`func (o *WebConfig) GetPLAYWRIGHT_WS_URLOk() (*string, bool)`

GetPLAYWRIGHT_WS_URLOk returns a tuple with the PLAYWRIGHT_WS_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPLAYWRIGHT_WS_URL

`func (o *WebConfig) SetPLAYWRIGHT_WS_URL(v string)`

SetPLAYWRIGHT_WS_URL sets PLAYWRIGHT_WS_URL field to given value.

### HasPLAYWRIGHT_WS_URL

`func (o *WebConfig) HasPLAYWRIGHT_WS_URL() bool`

HasPLAYWRIGHT_WS_URL returns a boolean if a field has been set.

### SetPLAYWRIGHT_WS_URLNil

`func (o *WebConfig) SetPLAYWRIGHT_WS_URLNil(b bool)`

 SetPLAYWRIGHT_WS_URLNil sets the value for PLAYWRIGHT_WS_URL to be an explicit nil

### UnsetPLAYWRIGHT_WS_URL
`func (o *WebConfig) UnsetPLAYWRIGHT_WS_URL()`

UnsetPLAYWRIGHT_WS_URL ensures that no value is present for PLAYWRIGHT_WS_URL, not even an explicit nil
### GetPLAYWRIGHT_TIMEOUT

`func (o *WebConfig) GetPLAYWRIGHT_TIMEOUT() int32`

GetPLAYWRIGHT_TIMEOUT returns the PLAYWRIGHT_TIMEOUT field if non-nil, zero value otherwise.

### GetPLAYWRIGHT_TIMEOUTOk

`func (o *WebConfig) GetPLAYWRIGHT_TIMEOUTOk() (*int32, bool)`

GetPLAYWRIGHT_TIMEOUTOk returns a tuple with the PLAYWRIGHT_TIMEOUT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPLAYWRIGHT_TIMEOUT

`func (o *WebConfig) SetPLAYWRIGHT_TIMEOUT(v int32)`

SetPLAYWRIGHT_TIMEOUT sets PLAYWRIGHT_TIMEOUT field to given value.

### HasPLAYWRIGHT_TIMEOUT

`func (o *WebConfig) HasPLAYWRIGHT_TIMEOUT() bool`

HasPLAYWRIGHT_TIMEOUT returns a boolean if a field has been set.

### SetPLAYWRIGHT_TIMEOUTNil

`func (o *WebConfig) SetPLAYWRIGHT_TIMEOUTNil(b bool)`

 SetPLAYWRIGHT_TIMEOUTNil sets the value for PLAYWRIGHT_TIMEOUT to be an explicit nil

### UnsetPLAYWRIGHT_TIMEOUT
`func (o *WebConfig) UnsetPLAYWRIGHT_TIMEOUT()`

UnsetPLAYWRIGHT_TIMEOUT ensures that no value is present for PLAYWRIGHT_TIMEOUT, not even an explicit nil
### GetFIRECRAWL_API_KEY

`func (o *WebConfig) GetFIRECRAWL_API_KEY() string`

GetFIRECRAWL_API_KEY returns the FIRECRAWL_API_KEY field if non-nil, zero value otherwise.

### GetFIRECRAWL_API_KEYOk

`func (o *WebConfig) GetFIRECRAWL_API_KEYOk() (*string, bool)`

GetFIRECRAWL_API_KEYOk returns a tuple with the FIRECRAWL_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFIRECRAWL_API_KEY

`func (o *WebConfig) SetFIRECRAWL_API_KEY(v string)`

SetFIRECRAWL_API_KEY sets FIRECRAWL_API_KEY field to given value.

### HasFIRECRAWL_API_KEY

`func (o *WebConfig) HasFIRECRAWL_API_KEY() bool`

HasFIRECRAWL_API_KEY returns a boolean if a field has been set.

### SetFIRECRAWL_API_KEYNil

`func (o *WebConfig) SetFIRECRAWL_API_KEYNil(b bool)`

 SetFIRECRAWL_API_KEYNil sets the value for FIRECRAWL_API_KEY to be an explicit nil

### UnsetFIRECRAWL_API_KEY
`func (o *WebConfig) UnsetFIRECRAWL_API_KEY()`

UnsetFIRECRAWL_API_KEY ensures that no value is present for FIRECRAWL_API_KEY, not even an explicit nil
### GetFIRECRAWL_API_BASE_URL

`func (o *WebConfig) GetFIRECRAWL_API_BASE_URL() string`

GetFIRECRAWL_API_BASE_URL returns the FIRECRAWL_API_BASE_URL field if non-nil, zero value otherwise.

### GetFIRECRAWL_API_BASE_URLOk

`func (o *WebConfig) GetFIRECRAWL_API_BASE_URLOk() (*string, bool)`

GetFIRECRAWL_API_BASE_URLOk returns a tuple with the FIRECRAWL_API_BASE_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFIRECRAWL_API_BASE_URL

`func (o *WebConfig) SetFIRECRAWL_API_BASE_URL(v string)`

SetFIRECRAWL_API_BASE_URL sets FIRECRAWL_API_BASE_URL field to given value.

### HasFIRECRAWL_API_BASE_URL

`func (o *WebConfig) HasFIRECRAWL_API_BASE_URL() bool`

HasFIRECRAWL_API_BASE_URL returns a boolean if a field has been set.

### SetFIRECRAWL_API_BASE_URLNil

`func (o *WebConfig) SetFIRECRAWL_API_BASE_URLNil(b bool)`

 SetFIRECRAWL_API_BASE_URLNil sets the value for FIRECRAWL_API_BASE_URL to be an explicit nil

### UnsetFIRECRAWL_API_BASE_URL
`func (o *WebConfig) UnsetFIRECRAWL_API_BASE_URL()`

UnsetFIRECRAWL_API_BASE_URL ensures that no value is present for FIRECRAWL_API_BASE_URL, not even an explicit nil
### GetTAVILY_EXTRACT_DEPTH

`func (o *WebConfig) GetTAVILY_EXTRACT_DEPTH() string`

GetTAVILY_EXTRACT_DEPTH returns the TAVILY_EXTRACT_DEPTH field if non-nil, zero value otherwise.

### GetTAVILY_EXTRACT_DEPTHOk

`func (o *WebConfig) GetTAVILY_EXTRACT_DEPTHOk() (*string, bool)`

GetTAVILY_EXTRACT_DEPTHOk returns a tuple with the TAVILY_EXTRACT_DEPTH field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTAVILY_EXTRACT_DEPTH

`func (o *WebConfig) SetTAVILY_EXTRACT_DEPTH(v string)`

SetTAVILY_EXTRACT_DEPTH sets TAVILY_EXTRACT_DEPTH field to given value.

### HasTAVILY_EXTRACT_DEPTH

`func (o *WebConfig) HasTAVILY_EXTRACT_DEPTH() bool`

HasTAVILY_EXTRACT_DEPTH returns a boolean if a field has been set.

### SetTAVILY_EXTRACT_DEPTHNil

`func (o *WebConfig) SetTAVILY_EXTRACT_DEPTHNil(b bool)`

 SetTAVILY_EXTRACT_DEPTHNil sets the value for TAVILY_EXTRACT_DEPTH to be an explicit nil

### UnsetTAVILY_EXTRACT_DEPTH
`func (o *WebConfig) UnsetTAVILY_EXTRACT_DEPTH()`

UnsetTAVILY_EXTRACT_DEPTH ensures that no value is present for TAVILY_EXTRACT_DEPTH, not even an explicit nil
### GetEXTERNAL_WEB_SEARCH_URL

`func (o *WebConfig) GetEXTERNAL_WEB_SEARCH_URL() string`

GetEXTERNAL_WEB_SEARCH_URL returns the EXTERNAL_WEB_SEARCH_URL field if non-nil, zero value otherwise.

### GetEXTERNAL_WEB_SEARCH_URLOk

`func (o *WebConfig) GetEXTERNAL_WEB_SEARCH_URLOk() (*string, bool)`

GetEXTERNAL_WEB_SEARCH_URLOk returns a tuple with the EXTERNAL_WEB_SEARCH_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXTERNAL_WEB_SEARCH_URL

`func (o *WebConfig) SetEXTERNAL_WEB_SEARCH_URL(v string)`

SetEXTERNAL_WEB_SEARCH_URL sets EXTERNAL_WEB_SEARCH_URL field to given value.

### HasEXTERNAL_WEB_SEARCH_URL

`func (o *WebConfig) HasEXTERNAL_WEB_SEARCH_URL() bool`

HasEXTERNAL_WEB_SEARCH_URL returns a boolean if a field has been set.

### SetEXTERNAL_WEB_SEARCH_URLNil

`func (o *WebConfig) SetEXTERNAL_WEB_SEARCH_URLNil(b bool)`

 SetEXTERNAL_WEB_SEARCH_URLNil sets the value for EXTERNAL_WEB_SEARCH_URL to be an explicit nil

### UnsetEXTERNAL_WEB_SEARCH_URL
`func (o *WebConfig) UnsetEXTERNAL_WEB_SEARCH_URL()`

UnsetEXTERNAL_WEB_SEARCH_URL ensures that no value is present for EXTERNAL_WEB_SEARCH_URL, not even an explicit nil
### GetEXTERNAL_WEB_SEARCH_API_KEY

`func (o *WebConfig) GetEXTERNAL_WEB_SEARCH_API_KEY() string`

GetEXTERNAL_WEB_SEARCH_API_KEY returns the EXTERNAL_WEB_SEARCH_API_KEY field if non-nil, zero value otherwise.

### GetEXTERNAL_WEB_SEARCH_API_KEYOk

`func (o *WebConfig) GetEXTERNAL_WEB_SEARCH_API_KEYOk() (*string, bool)`

GetEXTERNAL_WEB_SEARCH_API_KEYOk returns a tuple with the EXTERNAL_WEB_SEARCH_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXTERNAL_WEB_SEARCH_API_KEY

`func (o *WebConfig) SetEXTERNAL_WEB_SEARCH_API_KEY(v string)`

SetEXTERNAL_WEB_SEARCH_API_KEY sets EXTERNAL_WEB_SEARCH_API_KEY field to given value.

### HasEXTERNAL_WEB_SEARCH_API_KEY

`func (o *WebConfig) HasEXTERNAL_WEB_SEARCH_API_KEY() bool`

HasEXTERNAL_WEB_SEARCH_API_KEY returns a boolean if a field has been set.

### SetEXTERNAL_WEB_SEARCH_API_KEYNil

`func (o *WebConfig) SetEXTERNAL_WEB_SEARCH_API_KEYNil(b bool)`

 SetEXTERNAL_WEB_SEARCH_API_KEYNil sets the value for EXTERNAL_WEB_SEARCH_API_KEY to be an explicit nil

### UnsetEXTERNAL_WEB_SEARCH_API_KEY
`func (o *WebConfig) UnsetEXTERNAL_WEB_SEARCH_API_KEY()`

UnsetEXTERNAL_WEB_SEARCH_API_KEY ensures that no value is present for EXTERNAL_WEB_SEARCH_API_KEY, not even an explicit nil
### GetEXTERNAL_WEB_LOADER_URL

`func (o *WebConfig) GetEXTERNAL_WEB_LOADER_URL() string`

GetEXTERNAL_WEB_LOADER_URL returns the EXTERNAL_WEB_LOADER_URL field if non-nil, zero value otherwise.

### GetEXTERNAL_WEB_LOADER_URLOk

`func (o *WebConfig) GetEXTERNAL_WEB_LOADER_URLOk() (*string, bool)`

GetEXTERNAL_WEB_LOADER_URLOk returns a tuple with the EXTERNAL_WEB_LOADER_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXTERNAL_WEB_LOADER_URL

`func (o *WebConfig) SetEXTERNAL_WEB_LOADER_URL(v string)`

SetEXTERNAL_WEB_LOADER_URL sets EXTERNAL_WEB_LOADER_URL field to given value.

### HasEXTERNAL_WEB_LOADER_URL

`func (o *WebConfig) HasEXTERNAL_WEB_LOADER_URL() bool`

HasEXTERNAL_WEB_LOADER_URL returns a boolean if a field has been set.

### SetEXTERNAL_WEB_LOADER_URLNil

`func (o *WebConfig) SetEXTERNAL_WEB_LOADER_URLNil(b bool)`

 SetEXTERNAL_WEB_LOADER_URLNil sets the value for EXTERNAL_WEB_LOADER_URL to be an explicit nil

### UnsetEXTERNAL_WEB_LOADER_URL
`func (o *WebConfig) UnsetEXTERNAL_WEB_LOADER_URL()`

UnsetEXTERNAL_WEB_LOADER_URL ensures that no value is present for EXTERNAL_WEB_LOADER_URL, not even an explicit nil
### GetEXTERNAL_WEB_LOADER_API_KEY

`func (o *WebConfig) GetEXTERNAL_WEB_LOADER_API_KEY() string`

GetEXTERNAL_WEB_LOADER_API_KEY returns the EXTERNAL_WEB_LOADER_API_KEY field if non-nil, zero value otherwise.

### GetEXTERNAL_WEB_LOADER_API_KEYOk

`func (o *WebConfig) GetEXTERNAL_WEB_LOADER_API_KEYOk() (*string, bool)`

GetEXTERNAL_WEB_LOADER_API_KEYOk returns a tuple with the EXTERNAL_WEB_LOADER_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXTERNAL_WEB_LOADER_API_KEY

`func (o *WebConfig) SetEXTERNAL_WEB_LOADER_API_KEY(v string)`

SetEXTERNAL_WEB_LOADER_API_KEY sets EXTERNAL_WEB_LOADER_API_KEY field to given value.

### HasEXTERNAL_WEB_LOADER_API_KEY

`func (o *WebConfig) HasEXTERNAL_WEB_LOADER_API_KEY() bool`

HasEXTERNAL_WEB_LOADER_API_KEY returns a boolean if a field has been set.

### SetEXTERNAL_WEB_LOADER_API_KEYNil

`func (o *WebConfig) SetEXTERNAL_WEB_LOADER_API_KEYNil(b bool)`

 SetEXTERNAL_WEB_LOADER_API_KEYNil sets the value for EXTERNAL_WEB_LOADER_API_KEY to be an explicit nil

### UnsetEXTERNAL_WEB_LOADER_API_KEY
`func (o *WebConfig) UnsetEXTERNAL_WEB_LOADER_API_KEY()`

UnsetEXTERNAL_WEB_LOADER_API_KEY ensures that no value is present for EXTERNAL_WEB_LOADER_API_KEY, not even an explicit nil
### GetYOUTUBE_LOADER_LANGUAGE

`func (o *WebConfig) GetYOUTUBE_LOADER_LANGUAGE() []string`

GetYOUTUBE_LOADER_LANGUAGE returns the YOUTUBE_LOADER_LANGUAGE field if non-nil, zero value otherwise.

### GetYOUTUBE_LOADER_LANGUAGEOk

`func (o *WebConfig) GetYOUTUBE_LOADER_LANGUAGEOk() (*[]string, bool)`

GetYOUTUBE_LOADER_LANGUAGEOk returns a tuple with the YOUTUBE_LOADER_LANGUAGE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYOUTUBE_LOADER_LANGUAGE

`func (o *WebConfig) SetYOUTUBE_LOADER_LANGUAGE(v []string)`

SetYOUTUBE_LOADER_LANGUAGE sets YOUTUBE_LOADER_LANGUAGE field to given value.

### HasYOUTUBE_LOADER_LANGUAGE

`func (o *WebConfig) HasYOUTUBE_LOADER_LANGUAGE() bool`

HasYOUTUBE_LOADER_LANGUAGE returns a boolean if a field has been set.

### SetYOUTUBE_LOADER_LANGUAGENil

`func (o *WebConfig) SetYOUTUBE_LOADER_LANGUAGENil(b bool)`

 SetYOUTUBE_LOADER_LANGUAGENil sets the value for YOUTUBE_LOADER_LANGUAGE to be an explicit nil

### UnsetYOUTUBE_LOADER_LANGUAGE
`func (o *WebConfig) UnsetYOUTUBE_LOADER_LANGUAGE()`

UnsetYOUTUBE_LOADER_LANGUAGE ensures that no value is present for YOUTUBE_LOADER_LANGUAGE, not even an explicit nil
### GetYOUTUBE_LOADER_PROXY_URL

`func (o *WebConfig) GetYOUTUBE_LOADER_PROXY_URL() string`

GetYOUTUBE_LOADER_PROXY_URL returns the YOUTUBE_LOADER_PROXY_URL field if non-nil, zero value otherwise.

### GetYOUTUBE_LOADER_PROXY_URLOk

`func (o *WebConfig) GetYOUTUBE_LOADER_PROXY_URLOk() (*string, bool)`

GetYOUTUBE_LOADER_PROXY_URLOk returns a tuple with the YOUTUBE_LOADER_PROXY_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYOUTUBE_LOADER_PROXY_URL

`func (o *WebConfig) SetYOUTUBE_LOADER_PROXY_URL(v string)`

SetYOUTUBE_LOADER_PROXY_URL sets YOUTUBE_LOADER_PROXY_URL field to given value.

### HasYOUTUBE_LOADER_PROXY_URL

`func (o *WebConfig) HasYOUTUBE_LOADER_PROXY_URL() bool`

HasYOUTUBE_LOADER_PROXY_URL returns a boolean if a field has been set.

### SetYOUTUBE_LOADER_PROXY_URLNil

`func (o *WebConfig) SetYOUTUBE_LOADER_PROXY_URLNil(b bool)`

 SetYOUTUBE_LOADER_PROXY_URLNil sets the value for YOUTUBE_LOADER_PROXY_URL to be an explicit nil

### UnsetYOUTUBE_LOADER_PROXY_URL
`func (o *WebConfig) UnsetYOUTUBE_LOADER_PROXY_URL()`

UnsetYOUTUBE_LOADER_PROXY_URL ensures that no value is present for YOUTUBE_LOADER_PROXY_URL, not even an explicit nil
### GetYOUTUBE_LOADER_TRANSLATION

`func (o *WebConfig) GetYOUTUBE_LOADER_TRANSLATION() string`

GetYOUTUBE_LOADER_TRANSLATION returns the YOUTUBE_LOADER_TRANSLATION field if non-nil, zero value otherwise.

### GetYOUTUBE_LOADER_TRANSLATIONOk

`func (o *WebConfig) GetYOUTUBE_LOADER_TRANSLATIONOk() (*string, bool)`

GetYOUTUBE_LOADER_TRANSLATIONOk returns a tuple with the YOUTUBE_LOADER_TRANSLATION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYOUTUBE_LOADER_TRANSLATION

`func (o *WebConfig) SetYOUTUBE_LOADER_TRANSLATION(v string)`

SetYOUTUBE_LOADER_TRANSLATION sets YOUTUBE_LOADER_TRANSLATION field to given value.

### HasYOUTUBE_LOADER_TRANSLATION

`func (o *WebConfig) HasYOUTUBE_LOADER_TRANSLATION() bool`

HasYOUTUBE_LOADER_TRANSLATION returns a boolean if a field has been set.

### SetYOUTUBE_LOADER_TRANSLATIONNil

`func (o *WebConfig) SetYOUTUBE_LOADER_TRANSLATIONNil(b bool)`

 SetYOUTUBE_LOADER_TRANSLATIONNil sets the value for YOUTUBE_LOADER_TRANSLATION to be an explicit nil

### UnsetYOUTUBE_LOADER_TRANSLATION
`func (o *WebConfig) UnsetYOUTUBE_LOADER_TRANSLATION()`

UnsetYOUTUBE_LOADER_TRANSLATION ensures that no value is present for YOUTUBE_LOADER_TRANSLATION, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



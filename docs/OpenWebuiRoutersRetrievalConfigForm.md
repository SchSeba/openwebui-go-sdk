# OpenWebuiRoutersRetrievalConfigForm

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RAG_TEMPLATE** | Pointer to **NullableString** |  | [optional] 
**TOP_K** | Pointer to **NullableInt32** |  | [optional] 
**BYPASS_EMBEDDING_AND_RETRIEVAL** | Pointer to **NullableBool** |  | [optional] 
**RAG_FULL_CONTEXT** | Pointer to **NullableBool** |  | [optional] 
**ENABLE_RAG_HYBRID_SEARCH** | Pointer to **NullableBool** |  | [optional] 
**TOP_K_RERANKER** | Pointer to **NullableInt32** |  | [optional] 
**RELEVANCE_THRESHOLD** | Pointer to **NullableFloat32** |  | [optional] 
**HYBRIDBM25WEIGHT** | Pointer to **NullableFloat32** |  | [optional] 
**CONTENT_EXTRACTION_ENGINE** | Pointer to **NullableString** |  | [optional] 
**PDF_EXTRACT_IMAGES** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_API_KEY** | Pointer to **NullableString** |  | [optional] 
**DATALAB_MARKER_LANGS** | Pointer to **NullableString** |  | [optional] 
**DATALAB_MARKER_SKIP_CACHE** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_FORCE_OCR** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_PAGINATE** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_STRIP_EXISTING_OCR** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_DISABLE_IMAGE_EXTRACTION** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_USE_LLM** | Pointer to **NullableBool** |  | [optional] 
**DATALAB_MARKER_OUTPUT_FORMAT** | Pointer to **NullableString** |  | [optional] 
**EXTERNAL_DOCUMENT_LOADER_URL** | Pointer to **NullableString** |  | [optional] 
**EXTERNAL_DOCUMENT_LOADER_API_KEY** | Pointer to **NullableString** |  | [optional] 
**TIKA_SERVER_URL** | Pointer to **NullableString** |  | [optional] 
**DOCLING_SERVER_URL** | Pointer to **NullableString** |  | [optional] 
**DOCLING_OCR_ENGINE** | Pointer to **NullableString** |  | [optional] 
**DOCLING_OCR_LANG** | Pointer to **NullableString** |  | [optional] 
**DOCLING_DO_PICTURE_DESCRIPTION** | Pointer to **NullableBool** |  | [optional] 
**DOCLING_PICTURE_DESCRIPTION_MODE** | Pointer to **NullableString** |  | [optional] 
**DOCLING_PICTURE_DESCRIPTION_LOCAL** | Pointer to **map[string]interface{}** |  | [optional] 
**DOCLING_PICTURE_DESCRIPTION_API** | Pointer to **map[string]interface{}** |  | [optional] 
**DOCUMENT_INTELLIGENCE_ENDPOINT** | Pointer to **NullableString** |  | [optional] 
**DOCUMENT_INTELLIGENCE_KEY** | Pointer to **NullableString** |  | [optional] 
**MISTRAL_OCR_API_KEY** | Pointer to **NullableString** |  | [optional] 
**RAG_RERANKING_MODEL** | Pointer to **NullableString** |  | [optional] 
**RAG_RERANKING_ENGINE** | Pointer to **NullableString** |  | [optional] 
**RAG_EXTERNAL_RERANKER_URL** | Pointer to **NullableString** |  | [optional] 
**RAG_EXTERNAL_RERANKER_API_KEY** | Pointer to **NullableString** |  | [optional] 
**TEXT_SPLITTER** | Pointer to **NullableString** |  | [optional] 
**CHUNK_SIZE** | Pointer to **NullableInt32** |  | [optional] 
**CHUNK_OVERLAP** | Pointer to **NullableInt32** |  | [optional] 
**FILE_MAX_SIZE** | Pointer to **NullableInt32** |  | [optional] 
**FILE_MAX_COUNT** | Pointer to **NullableInt32** |  | [optional] 
**FILE_IMAGE_COMPRESSION_WIDTH** | Pointer to **NullableInt32** |  | [optional] 
**FILE_IMAGE_COMPRESSION_HEIGHT** | Pointer to **NullableInt32** |  | [optional] 
**ALLOWED_FILE_EXTENSIONS** | Pointer to **[]string** |  | [optional] 
**ENABLE_GOOGLE_DRIVE_INTEGRATION** | Pointer to **NullableBool** |  | [optional] 
**ENABLE_ONEDRIVE_INTEGRATION** | Pointer to **NullableBool** |  | [optional] 
**Web** | Pointer to [**NullableWebConfig**](WebConfig.md) |  | [optional] 

## Methods

### NewOpenWebuiRoutersRetrievalConfigForm

`func NewOpenWebuiRoutersRetrievalConfigForm() *OpenWebuiRoutersRetrievalConfigForm`

NewOpenWebuiRoutersRetrievalConfigForm instantiates a new OpenWebuiRoutersRetrievalConfigForm object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenWebuiRoutersRetrievalConfigFormWithDefaults

`func NewOpenWebuiRoutersRetrievalConfigFormWithDefaults() *OpenWebuiRoutersRetrievalConfigForm`

NewOpenWebuiRoutersRetrievalConfigFormWithDefaults instantiates a new OpenWebuiRoutersRetrievalConfigForm object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRAG_TEMPLATE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_TEMPLATE() string`

GetRAG_TEMPLATE returns the RAG_TEMPLATE field if non-nil, zero value otherwise.

### GetRAG_TEMPLATEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_TEMPLATEOk() (*string, bool)`

GetRAG_TEMPLATEOk returns a tuple with the RAG_TEMPLATE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRAG_TEMPLATE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_TEMPLATE(v string)`

SetRAG_TEMPLATE sets RAG_TEMPLATE field to given value.

### HasRAG_TEMPLATE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRAG_TEMPLATE() bool`

HasRAG_TEMPLATE returns a boolean if a field has been set.

### SetRAG_TEMPLATENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_TEMPLATENil(b bool)`

 SetRAG_TEMPLATENil sets the value for RAG_TEMPLATE to be an explicit nil

### UnsetRAG_TEMPLATE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRAG_TEMPLATE()`

UnsetRAG_TEMPLATE ensures that no value is present for RAG_TEMPLATE, not even an explicit nil
### GetTOP_K

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTOP_K() int32`

GetTOP_K returns the TOP_K field if non-nil, zero value otherwise.

### GetTOP_KOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTOP_KOk() (*int32, bool)`

GetTOP_KOk returns a tuple with the TOP_K field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTOP_K

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTOP_K(v int32)`

SetTOP_K sets TOP_K field to given value.

### HasTOP_K

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasTOP_K() bool`

HasTOP_K returns a boolean if a field has been set.

### SetTOP_KNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTOP_KNil(b bool)`

 SetTOP_KNil sets the value for TOP_K to be an explicit nil

### UnsetTOP_K
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetTOP_K()`

UnsetTOP_K ensures that no value is present for TOP_K, not even an explicit nil
### GetBYPASS_EMBEDDING_AND_RETRIEVAL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetBYPASS_EMBEDDING_AND_RETRIEVAL() bool`

GetBYPASS_EMBEDDING_AND_RETRIEVAL returns the BYPASS_EMBEDDING_AND_RETRIEVAL field if non-nil, zero value otherwise.

### GetBYPASS_EMBEDDING_AND_RETRIEVALOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetBYPASS_EMBEDDING_AND_RETRIEVALOk() (*bool, bool)`

GetBYPASS_EMBEDDING_AND_RETRIEVALOk returns a tuple with the BYPASS_EMBEDDING_AND_RETRIEVAL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBYPASS_EMBEDDING_AND_RETRIEVAL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetBYPASS_EMBEDDING_AND_RETRIEVAL(v bool)`

SetBYPASS_EMBEDDING_AND_RETRIEVAL sets BYPASS_EMBEDDING_AND_RETRIEVAL field to given value.

### HasBYPASS_EMBEDDING_AND_RETRIEVAL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasBYPASS_EMBEDDING_AND_RETRIEVAL() bool`

HasBYPASS_EMBEDDING_AND_RETRIEVAL returns a boolean if a field has been set.

### SetBYPASS_EMBEDDING_AND_RETRIEVALNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetBYPASS_EMBEDDING_AND_RETRIEVALNil(b bool)`

 SetBYPASS_EMBEDDING_AND_RETRIEVALNil sets the value for BYPASS_EMBEDDING_AND_RETRIEVAL to be an explicit nil

### UnsetBYPASS_EMBEDDING_AND_RETRIEVAL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetBYPASS_EMBEDDING_AND_RETRIEVAL()`

UnsetBYPASS_EMBEDDING_AND_RETRIEVAL ensures that no value is present for BYPASS_EMBEDDING_AND_RETRIEVAL, not even an explicit nil
### GetRAG_FULL_CONTEXT

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_FULL_CONTEXT() bool`

GetRAG_FULL_CONTEXT returns the RAG_FULL_CONTEXT field if non-nil, zero value otherwise.

### GetRAG_FULL_CONTEXTOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_FULL_CONTEXTOk() (*bool, bool)`

GetRAG_FULL_CONTEXTOk returns a tuple with the RAG_FULL_CONTEXT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRAG_FULL_CONTEXT

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_FULL_CONTEXT(v bool)`

SetRAG_FULL_CONTEXT sets RAG_FULL_CONTEXT field to given value.

### HasRAG_FULL_CONTEXT

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRAG_FULL_CONTEXT() bool`

HasRAG_FULL_CONTEXT returns a boolean if a field has been set.

### SetRAG_FULL_CONTEXTNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_FULL_CONTEXTNil(b bool)`

 SetRAG_FULL_CONTEXTNil sets the value for RAG_FULL_CONTEXT to be an explicit nil

### UnsetRAG_FULL_CONTEXT
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRAG_FULL_CONTEXT()`

UnsetRAG_FULL_CONTEXT ensures that no value is present for RAG_FULL_CONTEXT, not even an explicit nil
### GetENABLE_RAG_HYBRID_SEARCH

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetENABLE_RAG_HYBRID_SEARCH() bool`

GetENABLE_RAG_HYBRID_SEARCH returns the ENABLE_RAG_HYBRID_SEARCH field if non-nil, zero value otherwise.

### GetENABLE_RAG_HYBRID_SEARCHOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetENABLE_RAG_HYBRID_SEARCHOk() (*bool, bool)`

GetENABLE_RAG_HYBRID_SEARCHOk returns a tuple with the ENABLE_RAG_HYBRID_SEARCH field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_RAG_HYBRID_SEARCH

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetENABLE_RAG_HYBRID_SEARCH(v bool)`

SetENABLE_RAG_HYBRID_SEARCH sets ENABLE_RAG_HYBRID_SEARCH field to given value.

### HasENABLE_RAG_HYBRID_SEARCH

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasENABLE_RAG_HYBRID_SEARCH() bool`

HasENABLE_RAG_HYBRID_SEARCH returns a boolean if a field has been set.

### SetENABLE_RAG_HYBRID_SEARCHNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetENABLE_RAG_HYBRID_SEARCHNil(b bool)`

 SetENABLE_RAG_HYBRID_SEARCHNil sets the value for ENABLE_RAG_HYBRID_SEARCH to be an explicit nil

### UnsetENABLE_RAG_HYBRID_SEARCH
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetENABLE_RAG_HYBRID_SEARCH()`

UnsetENABLE_RAG_HYBRID_SEARCH ensures that no value is present for ENABLE_RAG_HYBRID_SEARCH, not even an explicit nil
### GetTOP_K_RERANKER

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTOP_K_RERANKER() int32`

GetTOP_K_RERANKER returns the TOP_K_RERANKER field if non-nil, zero value otherwise.

### GetTOP_K_RERANKEROk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTOP_K_RERANKEROk() (*int32, bool)`

GetTOP_K_RERANKEROk returns a tuple with the TOP_K_RERANKER field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTOP_K_RERANKER

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTOP_K_RERANKER(v int32)`

SetTOP_K_RERANKER sets TOP_K_RERANKER field to given value.

### HasTOP_K_RERANKER

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasTOP_K_RERANKER() bool`

HasTOP_K_RERANKER returns a boolean if a field has been set.

### SetTOP_K_RERANKERNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTOP_K_RERANKERNil(b bool)`

 SetTOP_K_RERANKERNil sets the value for TOP_K_RERANKER to be an explicit nil

### UnsetTOP_K_RERANKER
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetTOP_K_RERANKER()`

UnsetTOP_K_RERANKER ensures that no value is present for TOP_K_RERANKER, not even an explicit nil
### GetRELEVANCE_THRESHOLD

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRELEVANCE_THRESHOLD() float32`

GetRELEVANCE_THRESHOLD returns the RELEVANCE_THRESHOLD field if non-nil, zero value otherwise.

### GetRELEVANCE_THRESHOLDOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRELEVANCE_THRESHOLDOk() (*float32, bool)`

GetRELEVANCE_THRESHOLDOk returns a tuple with the RELEVANCE_THRESHOLD field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRELEVANCE_THRESHOLD

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRELEVANCE_THRESHOLD(v float32)`

SetRELEVANCE_THRESHOLD sets RELEVANCE_THRESHOLD field to given value.

### HasRELEVANCE_THRESHOLD

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRELEVANCE_THRESHOLD() bool`

HasRELEVANCE_THRESHOLD returns a boolean if a field has been set.

### SetRELEVANCE_THRESHOLDNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRELEVANCE_THRESHOLDNil(b bool)`

 SetRELEVANCE_THRESHOLDNil sets the value for RELEVANCE_THRESHOLD to be an explicit nil

### UnsetRELEVANCE_THRESHOLD
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRELEVANCE_THRESHOLD()`

UnsetRELEVANCE_THRESHOLD ensures that no value is present for RELEVANCE_THRESHOLD, not even an explicit nil
### GetHYBRIDBM25WEIGHT

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetHYBRIDBM25WEIGHT() float32`

GetHYBRIDBM25WEIGHT returns the HYBRIDBM25WEIGHT field if non-nil, zero value otherwise.

### GetHYBRIDBM25WEIGHTOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetHYBRIDBM25WEIGHTOk() (*float32, bool)`

GetHYBRIDBM25WEIGHTOk returns a tuple with the HYBRIDBM25WEIGHT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHYBRIDBM25WEIGHT

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetHYBRIDBM25WEIGHT(v float32)`

SetHYBRIDBM25WEIGHT sets HYBRIDBM25WEIGHT field to given value.

### HasHYBRIDBM25WEIGHT

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasHYBRIDBM25WEIGHT() bool`

HasHYBRIDBM25WEIGHT returns a boolean if a field has been set.

### SetHYBRIDBM25WEIGHTNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetHYBRIDBM25WEIGHTNil(b bool)`

 SetHYBRIDBM25WEIGHTNil sets the value for HYBRIDBM25WEIGHT to be an explicit nil

### UnsetHYBRIDBM25WEIGHT
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetHYBRIDBM25WEIGHT()`

UnsetHYBRIDBM25WEIGHT ensures that no value is present for HYBRIDBM25WEIGHT, not even an explicit nil
### GetCONTENT_EXTRACTION_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetCONTENT_EXTRACTION_ENGINE() string`

GetCONTENT_EXTRACTION_ENGINE returns the CONTENT_EXTRACTION_ENGINE field if non-nil, zero value otherwise.

### GetCONTENT_EXTRACTION_ENGINEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetCONTENT_EXTRACTION_ENGINEOk() (*string, bool)`

GetCONTENT_EXTRACTION_ENGINEOk returns a tuple with the CONTENT_EXTRACTION_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCONTENT_EXTRACTION_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetCONTENT_EXTRACTION_ENGINE(v string)`

SetCONTENT_EXTRACTION_ENGINE sets CONTENT_EXTRACTION_ENGINE field to given value.

### HasCONTENT_EXTRACTION_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasCONTENT_EXTRACTION_ENGINE() bool`

HasCONTENT_EXTRACTION_ENGINE returns a boolean if a field has been set.

### SetCONTENT_EXTRACTION_ENGINENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetCONTENT_EXTRACTION_ENGINENil(b bool)`

 SetCONTENT_EXTRACTION_ENGINENil sets the value for CONTENT_EXTRACTION_ENGINE to be an explicit nil

### UnsetCONTENT_EXTRACTION_ENGINE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetCONTENT_EXTRACTION_ENGINE()`

UnsetCONTENT_EXTRACTION_ENGINE ensures that no value is present for CONTENT_EXTRACTION_ENGINE, not even an explicit nil
### GetPDF_EXTRACT_IMAGES

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetPDF_EXTRACT_IMAGES() bool`

GetPDF_EXTRACT_IMAGES returns the PDF_EXTRACT_IMAGES field if non-nil, zero value otherwise.

### GetPDF_EXTRACT_IMAGESOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetPDF_EXTRACT_IMAGESOk() (*bool, bool)`

GetPDF_EXTRACT_IMAGESOk returns a tuple with the PDF_EXTRACT_IMAGES field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPDF_EXTRACT_IMAGES

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetPDF_EXTRACT_IMAGES(v bool)`

SetPDF_EXTRACT_IMAGES sets PDF_EXTRACT_IMAGES field to given value.

### HasPDF_EXTRACT_IMAGES

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasPDF_EXTRACT_IMAGES() bool`

HasPDF_EXTRACT_IMAGES returns a boolean if a field has been set.

### SetPDF_EXTRACT_IMAGESNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetPDF_EXTRACT_IMAGESNil(b bool)`

 SetPDF_EXTRACT_IMAGESNil sets the value for PDF_EXTRACT_IMAGES to be an explicit nil

### UnsetPDF_EXTRACT_IMAGES
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetPDF_EXTRACT_IMAGES()`

UnsetPDF_EXTRACT_IMAGES ensures that no value is present for PDF_EXTRACT_IMAGES, not even an explicit nil
### GetDATALAB_MARKER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_API_KEY() string`

GetDATALAB_MARKER_API_KEY returns the DATALAB_MARKER_API_KEY field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_API_KEYOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_API_KEYOk() (*string, bool)`

GetDATALAB_MARKER_API_KEYOk returns a tuple with the DATALAB_MARKER_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_API_KEY(v string)`

SetDATALAB_MARKER_API_KEY sets DATALAB_MARKER_API_KEY field to given value.

### HasDATALAB_MARKER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_API_KEY() bool`

HasDATALAB_MARKER_API_KEY returns a boolean if a field has been set.

### SetDATALAB_MARKER_API_KEYNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_API_KEYNil(b bool)`

 SetDATALAB_MARKER_API_KEYNil sets the value for DATALAB_MARKER_API_KEY to be an explicit nil

### UnsetDATALAB_MARKER_API_KEY
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_API_KEY()`

UnsetDATALAB_MARKER_API_KEY ensures that no value is present for DATALAB_MARKER_API_KEY, not even an explicit nil
### GetDATALAB_MARKER_LANGS

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_LANGS() string`

GetDATALAB_MARKER_LANGS returns the DATALAB_MARKER_LANGS field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_LANGSOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_LANGSOk() (*string, bool)`

GetDATALAB_MARKER_LANGSOk returns a tuple with the DATALAB_MARKER_LANGS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_LANGS

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_LANGS(v string)`

SetDATALAB_MARKER_LANGS sets DATALAB_MARKER_LANGS field to given value.

### HasDATALAB_MARKER_LANGS

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_LANGS() bool`

HasDATALAB_MARKER_LANGS returns a boolean if a field has been set.

### SetDATALAB_MARKER_LANGSNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_LANGSNil(b bool)`

 SetDATALAB_MARKER_LANGSNil sets the value for DATALAB_MARKER_LANGS to be an explicit nil

### UnsetDATALAB_MARKER_LANGS
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_LANGS()`

UnsetDATALAB_MARKER_LANGS ensures that no value is present for DATALAB_MARKER_LANGS, not even an explicit nil
### GetDATALAB_MARKER_SKIP_CACHE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_SKIP_CACHE() bool`

GetDATALAB_MARKER_SKIP_CACHE returns the DATALAB_MARKER_SKIP_CACHE field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_SKIP_CACHEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_SKIP_CACHEOk() (*bool, bool)`

GetDATALAB_MARKER_SKIP_CACHEOk returns a tuple with the DATALAB_MARKER_SKIP_CACHE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_SKIP_CACHE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_SKIP_CACHE(v bool)`

SetDATALAB_MARKER_SKIP_CACHE sets DATALAB_MARKER_SKIP_CACHE field to given value.

### HasDATALAB_MARKER_SKIP_CACHE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_SKIP_CACHE() bool`

HasDATALAB_MARKER_SKIP_CACHE returns a boolean if a field has been set.

### SetDATALAB_MARKER_SKIP_CACHENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_SKIP_CACHENil(b bool)`

 SetDATALAB_MARKER_SKIP_CACHENil sets the value for DATALAB_MARKER_SKIP_CACHE to be an explicit nil

### UnsetDATALAB_MARKER_SKIP_CACHE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_SKIP_CACHE()`

UnsetDATALAB_MARKER_SKIP_CACHE ensures that no value is present for DATALAB_MARKER_SKIP_CACHE, not even an explicit nil
### GetDATALAB_MARKER_FORCE_OCR

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_FORCE_OCR() bool`

GetDATALAB_MARKER_FORCE_OCR returns the DATALAB_MARKER_FORCE_OCR field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_FORCE_OCROk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_FORCE_OCROk() (*bool, bool)`

GetDATALAB_MARKER_FORCE_OCROk returns a tuple with the DATALAB_MARKER_FORCE_OCR field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_FORCE_OCR

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_FORCE_OCR(v bool)`

SetDATALAB_MARKER_FORCE_OCR sets DATALAB_MARKER_FORCE_OCR field to given value.

### HasDATALAB_MARKER_FORCE_OCR

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_FORCE_OCR() bool`

HasDATALAB_MARKER_FORCE_OCR returns a boolean if a field has been set.

### SetDATALAB_MARKER_FORCE_OCRNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_FORCE_OCRNil(b bool)`

 SetDATALAB_MARKER_FORCE_OCRNil sets the value for DATALAB_MARKER_FORCE_OCR to be an explicit nil

### UnsetDATALAB_MARKER_FORCE_OCR
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_FORCE_OCR()`

UnsetDATALAB_MARKER_FORCE_OCR ensures that no value is present for DATALAB_MARKER_FORCE_OCR, not even an explicit nil
### GetDATALAB_MARKER_PAGINATE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_PAGINATE() bool`

GetDATALAB_MARKER_PAGINATE returns the DATALAB_MARKER_PAGINATE field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_PAGINATEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_PAGINATEOk() (*bool, bool)`

GetDATALAB_MARKER_PAGINATEOk returns a tuple with the DATALAB_MARKER_PAGINATE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_PAGINATE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_PAGINATE(v bool)`

SetDATALAB_MARKER_PAGINATE sets DATALAB_MARKER_PAGINATE field to given value.

### HasDATALAB_MARKER_PAGINATE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_PAGINATE() bool`

HasDATALAB_MARKER_PAGINATE returns a boolean if a field has been set.

### SetDATALAB_MARKER_PAGINATENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_PAGINATENil(b bool)`

 SetDATALAB_MARKER_PAGINATENil sets the value for DATALAB_MARKER_PAGINATE to be an explicit nil

### UnsetDATALAB_MARKER_PAGINATE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_PAGINATE()`

UnsetDATALAB_MARKER_PAGINATE ensures that no value is present for DATALAB_MARKER_PAGINATE, not even an explicit nil
### GetDATALAB_MARKER_STRIP_EXISTING_OCR

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_STRIP_EXISTING_OCR() bool`

GetDATALAB_MARKER_STRIP_EXISTING_OCR returns the DATALAB_MARKER_STRIP_EXISTING_OCR field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_STRIP_EXISTING_OCROk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_STRIP_EXISTING_OCROk() (*bool, bool)`

GetDATALAB_MARKER_STRIP_EXISTING_OCROk returns a tuple with the DATALAB_MARKER_STRIP_EXISTING_OCR field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_STRIP_EXISTING_OCR

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_STRIP_EXISTING_OCR(v bool)`

SetDATALAB_MARKER_STRIP_EXISTING_OCR sets DATALAB_MARKER_STRIP_EXISTING_OCR field to given value.

### HasDATALAB_MARKER_STRIP_EXISTING_OCR

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_STRIP_EXISTING_OCR() bool`

HasDATALAB_MARKER_STRIP_EXISTING_OCR returns a boolean if a field has been set.

### SetDATALAB_MARKER_STRIP_EXISTING_OCRNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_STRIP_EXISTING_OCRNil(b bool)`

 SetDATALAB_MARKER_STRIP_EXISTING_OCRNil sets the value for DATALAB_MARKER_STRIP_EXISTING_OCR to be an explicit nil

### UnsetDATALAB_MARKER_STRIP_EXISTING_OCR
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_STRIP_EXISTING_OCR()`

UnsetDATALAB_MARKER_STRIP_EXISTING_OCR ensures that no value is present for DATALAB_MARKER_STRIP_EXISTING_OCR, not even an explicit nil
### GetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION() bool`

GetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION returns the DATALAB_MARKER_DISABLE_IMAGE_EXTRACTION field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTIONOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTIONOk() (*bool, bool)`

GetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTIONOk returns a tuple with the DATALAB_MARKER_DISABLE_IMAGE_EXTRACTION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION(v bool)`

SetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION sets DATALAB_MARKER_DISABLE_IMAGE_EXTRACTION field to given value.

### HasDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION() bool`

HasDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION returns a boolean if a field has been set.

### SetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTIONNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTIONNil(b bool)`

 SetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTIONNil sets the value for DATALAB_MARKER_DISABLE_IMAGE_EXTRACTION to be an explicit nil

### UnsetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION()`

UnsetDATALAB_MARKER_DISABLE_IMAGE_EXTRACTION ensures that no value is present for DATALAB_MARKER_DISABLE_IMAGE_EXTRACTION, not even an explicit nil
### GetDATALAB_MARKER_USE_LLM

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_USE_LLM() bool`

GetDATALAB_MARKER_USE_LLM returns the DATALAB_MARKER_USE_LLM field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_USE_LLMOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_USE_LLMOk() (*bool, bool)`

GetDATALAB_MARKER_USE_LLMOk returns a tuple with the DATALAB_MARKER_USE_LLM field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_USE_LLM

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_USE_LLM(v bool)`

SetDATALAB_MARKER_USE_LLM sets DATALAB_MARKER_USE_LLM field to given value.

### HasDATALAB_MARKER_USE_LLM

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_USE_LLM() bool`

HasDATALAB_MARKER_USE_LLM returns a boolean if a field has been set.

### SetDATALAB_MARKER_USE_LLMNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_USE_LLMNil(b bool)`

 SetDATALAB_MARKER_USE_LLMNil sets the value for DATALAB_MARKER_USE_LLM to be an explicit nil

### UnsetDATALAB_MARKER_USE_LLM
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_USE_LLM()`

UnsetDATALAB_MARKER_USE_LLM ensures that no value is present for DATALAB_MARKER_USE_LLM, not even an explicit nil
### GetDATALAB_MARKER_OUTPUT_FORMAT

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_OUTPUT_FORMAT() string`

GetDATALAB_MARKER_OUTPUT_FORMAT returns the DATALAB_MARKER_OUTPUT_FORMAT field if non-nil, zero value otherwise.

### GetDATALAB_MARKER_OUTPUT_FORMATOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDATALAB_MARKER_OUTPUT_FORMATOk() (*string, bool)`

GetDATALAB_MARKER_OUTPUT_FORMATOk returns a tuple with the DATALAB_MARKER_OUTPUT_FORMAT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDATALAB_MARKER_OUTPUT_FORMAT

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_OUTPUT_FORMAT(v string)`

SetDATALAB_MARKER_OUTPUT_FORMAT sets DATALAB_MARKER_OUTPUT_FORMAT field to given value.

### HasDATALAB_MARKER_OUTPUT_FORMAT

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDATALAB_MARKER_OUTPUT_FORMAT() bool`

HasDATALAB_MARKER_OUTPUT_FORMAT returns a boolean if a field has been set.

### SetDATALAB_MARKER_OUTPUT_FORMATNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDATALAB_MARKER_OUTPUT_FORMATNil(b bool)`

 SetDATALAB_MARKER_OUTPUT_FORMATNil sets the value for DATALAB_MARKER_OUTPUT_FORMAT to be an explicit nil

### UnsetDATALAB_MARKER_OUTPUT_FORMAT
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDATALAB_MARKER_OUTPUT_FORMAT()`

UnsetDATALAB_MARKER_OUTPUT_FORMAT ensures that no value is present for DATALAB_MARKER_OUTPUT_FORMAT, not even an explicit nil
### GetEXTERNAL_DOCUMENT_LOADER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetEXTERNAL_DOCUMENT_LOADER_URL() string`

GetEXTERNAL_DOCUMENT_LOADER_URL returns the EXTERNAL_DOCUMENT_LOADER_URL field if non-nil, zero value otherwise.

### GetEXTERNAL_DOCUMENT_LOADER_URLOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetEXTERNAL_DOCUMENT_LOADER_URLOk() (*string, bool)`

GetEXTERNAL_DOCUMENT_LOADER_URLOk returns a tuple with the EXTERNAL_DOCUMENT_LOADER_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXTERNAL_DOCUMENT_LOADER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetEXTERNAL_DOCUMENT_LOADER_URL(v string)`

SetEXTERNAL_DOCUMENT_LOADER_URL sets EXTERNAL_DOCUMENT_LOADER_URL field to given value.

### HasEXTERNAL_DOCUMENT_LOADER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasEXTERNAL_DOCUMENT_LOADER_URL() bool`

HasEXTERNAL_DOCUMENT_LOADER_URL returns a boolean if a field has been set.

### SetEXTERNAL_DOCUMENT_LOADER_URLNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetEXTERNAL_DOCUMENT_LOADER_URLNil(b bool)`

 SetEXTERNAL_DOCUMENT_LOADER_URLNil sets the value for EXTERNAL_DOCUMENT_LOADER_URL to be an explicit nil

### UnsetEXTERNAL_DOCUMENT_LOADER_URL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetEXTERNAL_DOCUMENT_LOADER_URL()`

UnsetEXTERNAL_DOCUMENT_LOADER_URL ensures that no value is present for EXTERNAL_DOCUMENT_LOADER_URL, not even an explicit nil
### GetEXTERNAL_DOCUMENT_LOADER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetEXTERNAL_DOCUMENT_LOADER_API_KEY() string`

GetEXTERNAL_DOCUMENT_LOADER_API_KEY returns the EXTERNAL_DOCUMENT_LOADER_API_KEY field if non-nil, zero value otherwise.

### GetEXTERNAL_DOCUMENT_LOADER_API_KEYOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetEXTERNAL_DOCUMENT_LOADER_API_KEYOk() (*string, bool)`

GetEXTERNAL_DOCUMENT_LOADER_API_KEYOk returns a tuple with the EXTERNAL_DOCUMENT_LOADER_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEXTERNAL_DOCUMENT_LOADER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetEXTERNAL_DOCUMENT_LOADER_API_KEY(v string)`

SetEXTERNAL_DOCUMENT_LOADER_API_KEY sets EXTERNAL_DOCUMENT_LOADER_API_KEY field to given value.

### HasEXTERNAL_DOCUMENT_LOADER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasEXTERNAL_DOCUMENT_LOADER_API_KEY() bool`

HasEXTERNAL_DOCUMENT_LOADER_API_KEY returns a boolean if a field has been set.

### SetEXTERNAL_DOCUMENT_LOADER_API_KEYNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetEXTERNAL_DOCUMENT_LOADER_API_KEYNil(b bool)`

 SetEXTERNAL_DOCUMENT_LOADER_API_KEYNil sets the value for EXTERNAL_DOCUMENT_LOADER_API_KEY to be an explicit nil

### UnsetEXTERNAL_DOCUMENT_LOADER_API_KEY
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetEXTERNAL_DOCUMENT_LOADER_API_KEY()`

UnsetEXTERNAL_DOCUMENT_LOADER_API_KEY ensures that no value is present for EXTERNAL_DOCUMENT_LOADER_API_KEY, not even an explicit nil
### GetTIKA_SERVER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTIKA_SERVER_URL() string`

GetTIKA_SERVER_URL returns the TIKA_SERVER_URL field if non-nil, zero value otherwise.

### GetTIKA_SERVER_URLOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTIKA_SERVER_URLOk() (*string, bool)`

GetTIKA_SERVER_URLOk returns a tuple with the TIKA_SERVER_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTIKA_SERVER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTIKA_SERVER_URL(v string)`

SetTIKA_SERVER_URL sets TIKA_SERVER_URL field to given value.

### HasTIKA_SERVER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasTIKA_SERVER_URL() bool`

HasTIKA_SERVER_URL returns a boolean if a field has been set.

### SetTIKA_SERVER_URLNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTIKA_SERVER_URLNil(b bool)`

 SetTIKA_SERVER_URLNil sets the value for TIKA_SERVER_URL to be an explicit nil

### UnsetTIKA_SERVER_URL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetTIKA_SERVER_URL()`

UnsetTIKA_SERVER_URL ensures that no value is present for TIKA_SERVER_URL, not even an explicit nil
### GetDOCLING_SERVER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_SERVER_URL() string`

GetDOCLING_SERVER_URL returns the DOCLING_SERVER_URL field if non-nil, zero value otherwise.

### GetDOCLING_SERVER_URLOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_SERVER_URLOk() (*string, bool)`

GetDOCLING_SERVER_URLOk returns a tuple with the DOCLING_SERVER_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_SERVER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_SERVER_URL(v string)`

SetDOCLING_SERVER_URL sets DOCLING_SERVER_URL field to given value.

### HasDOCLING_SERVER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_SERVER_URL() bool`

HasDOCLING_SERVER_URL returns a boolean if a field has been set.

### SetDOCLING_SERVER_URLNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_SERVER_URLNil(b bool)`

 SetDOCLING_SERVER_URLNil sets the value for DOCLING_SERVER_URL to be an explicit nil

### UnsetDOCLING_SERVER_URL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_SERVER_URL()`

UnsetDOCLING_SERVER_URL ensures that no value is present for DOCLING_SERVER_URL, not even an explicit nil
### GetDOCLING_OCR_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_OCR_ENGINE() string`

GetDOCLING_OCR_ENGINE returns the DOCLING_OCR_ENGINE field if non-nil, zero value otherwise.

### GetDOCLING_OCR_ENGINEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_OCR_ENGINEOk() (*string, bool)`

GetDOCLING_OCR_ENGINEOk returns a tuple with the DOCLING_OCR_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_OCR_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_OCR_ENGINE(v string)`

SetDOCLING_OCR_ENGINE sets DOCLING_OCR_ENGINE field to given value.

### HasDOCLING_OCR_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_OCR_ENGINE() bool`

HasDOCLING_OCR_ENGINE returns a boolean if a field has been set.

### SetDOCLING_OCR_ENGINENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_OCR_ENGINENil(b bool)`

 SetDOCLING_OCR_ENGINENil sets the value for DOCLING_OCR_ENGINE to be an explicit nil

### UnsetDOCLING_OCR_ENGINE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_OCR_ENGINE()`

UnsetDOCLING_OCR_ENGINE ensures that no value is present for DOCLING_OCR_ENGINE, not even an explicit nil
### GetDOCLING_OCR_LANG

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_OCR_LANG() string`

GetDOCLING_OCR_LANG returns the DOCLING_OCR_LANG field if non-nil, zero value otherwise.

### GetDOCLING_OCR_LANGOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_OCR_LANGOk() (*string, bool)`

GetDOCLING_OCR_LANGOk returns a tuple with the DOCLING_OCR_LANG field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_OCR_LANG

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_OCR_LANG(v string)`

SetDOCLING_OCR_LANG sets DOCLING_OCR_LANG field to given value.

### HasDOCLING_OCR_LANG

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_OCR_LANG() bool`

HasDOCLING_OCR_LANG returns a boolean if a field has been set.

### SetDOCLING_OCR_LANGNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_OCR_LANGNil(b bool)`

 SetDOCLING_OCR_LANGNil sets the value for DOCLING_OCR_LANG to be an explicit nil

### UnsetDOCLING_OCR_LANG
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_OCR_LANG()`

UnsetDOCLING_OCR_LANG ensures that no value is present for DOCLING_OCR_LANG, not even an explicit nil
### GetDOCLING_DO_PICTURE_DESCRIPTION

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_DO_PICTURE_DESCRIPTION() bool`

GetDOCLING_DO_PICTURE_DESCRIPTION returns the DOCLING_DO_PICTURE_DESCRIPTION field if non-nil, zero value otherwise.

### GetDOCLING_DO_PICTURE_DESCRIPTIONOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_DO_PICTURE_DESCRIPTIONOk() (*bool, bool)`

GetDOCLING_DO_PICTURE_DESCRIPTIONOk returns a tuple with the DOCLING_DO_PICTURE_DESCRIPTION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_DO_PICTURE_DESCRIPTION

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_DO_PICTURE_DESCRIPTION(v bool)`

SetDOCLING_DO_PICTURE_DESCRIPTION sets DOCLING_DO_PICTURE_DESCRIPTION field to given value.

### HasDOCLING_DO_PICTURE_DESCRIPTION

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_DO_PICTURE_DESCRIPTION() bool`

HasDOCLING_DO_PICTURE_DESCRIPTION returns a boolean if a field has been set.

### SetDOCLING_DO_PICTURE_DESCRIPTIONNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_DO_PICTURE_DESCRIPTIONNil(b bool)`

 SetDOCLING_DO_PICTURE_DESCRIPTIONNil sets the value for DOCLING_DO_PICTURE_DESCRIPTION to be an explicit nil

### UnsetDOCLING_DO_PICTURE_DESCRIPTION
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_DO_PICTURE_DESCRIPTION()`

UnsetDOCLING_DO_PICTURE_DESCRIPTION ensures that no value is present for DOCLING_DO_PICTURE_DESCRIPTION, not even an explicit nil
### GetDOCLING_PICTURE_DESCRIPTION_MODE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_PICTURE_DESCRIPTION_MODE() string`

GetDOCLING_PICTURE_DESCRIPTION_MODE returns the DOCLING_PICTURE_DESCRIPTION_MODE field if non-nil, zero value otherwise.

### GetDOCLING_PICTURE_DESCRIPTION_MODEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_PICTURE_DESCRIPTION_MODEOk() (*string, bool)`

GetDOCLING_PICTURE_DESCRIPTION_MODEOk returns a tuple with the DOCLING_PICTURE_DESCRIPTION_MODE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_PICTURE_DESCRIPTION_MODE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_PICTURE_DESCRIPTION_MODE(v string)`

SetDOCLING_PICTURE_DESCRIPTION_MODE sets DOCLING_PICTURE_DESCRIPTION_MODE field to given value.

### HasDOCLING_PICTURE_DESCRIPTION_MODE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_PICTURE_DESCRIPTION_MODE() bool`

HasDOCLING_PICTURE_DESCRIPTION_MODE returns a boolean if a field has been set.

### SetDOCLING_PICTURE_DESCRIPTION_MODENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_PICTURE_DESCRIPTION_MODENil(b bool)`

 SetDOCLING_PICTURE_DESCRIPTION_MODENil sets the value for DOCLING_PICTURE_DESCRIPTION_MODE to be an explicit nil

### UnsetDOCLING_PICTURE_DESCRIPTION_MODE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_PICTURE_DESCRIPTION_MODE()`

UnsetDOCLING_PICTURE_DESCRIPTION_MODE ensures that no value is present for DOCLING_PICTURE_DESCRIPTION_MODE, not even an explicit nil
### GetDOCLING_PICTURE_DESCRIPTION_LOCAL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_PICTURE_DESCRIPTION_LOCAL() map[string]interface{}`

GetDOCLING_PICTURE_DESCRIPTION_LOCAL returns the DOCLING_PICTURE_DESCRIPTION_LOCAL field if non-nil, zero value otherwise.

### GetDOCLING_PICTURE_DESCRIPTION_LOCALOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_PICTURE_DESCRIPTION_LOCALOk() (*map[string]interface{}, bool)`

GetDOCLING_PICTURE_DESCRIPTION_LOCALOk returns a tuple with the DOCLING_PICTURE_DESCRIPTION_LOCAL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_PICTURE_DESCRIPTION_LOCAL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_PICTURE_DESCRIPTION_LOCAL(v map[string]interface{})`

SetDOCLING_PICTURE_DESCRIPTION_LOCAL sets DOCLING_PICTURE_DESCRIPTION_LOCAL field to given value.

### HasDOCLING_PICTURE_DESCRIPTION_LOCAL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_PICTURE_DESCRIPTION_LOCAL() bool`

HasDOCLING_PICTURE_DESCRIPTION_LOCAL returns a boolean if a field has been set.

### SetDOCLING_PICTURE_DESCRIPTION_LOCALNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_PICTURE_DESCRIPTION_LOCALNil(b bool)`

 SetDOCLING_PICTURE_DESCRIPTION_LOCALNil sets the value for DOCLING_PICTURE_DESCRIPTION_LOCAL to be an explicit nil

### UnsetDOCLING_PICTURE_DESCRIPTION_LOCAL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_PICTURE_DESCRIPTION_LOCAL()`

UnsetDOCLING_PICTURE_DESCRIPTION_LOCAL ensures that no value is present for DOCLING_PICTURE_DESCRIPTION_LOCAL, not even an explicit nil
### GetDOCLING_PICTURE_DESCRIPTION_API

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_PICTURE_DESCRIPTION_API() map[string]interface{}`

GetDOCLING_PICTURE_DESCRIPTION_API returns the DOCLING_PICTURE_DESCRIPTION_API field if non-nil, zero value otherwise.

### GetDOCLING_PICTURE_DESCRIPTION_APIOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCLING_PICTURE_DESCRIPTION_APIOk() (*map[string]interface{}, bool)`

GetDOCLING_PICTURE_DESCRIPTION_APIOk returns a tuple with the DOCLING_PICTURE_DESCRIPTION_API field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCLING_PICTURE_DESCRIPTION_API

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_PICTURE_DESCRIPTION_API(v map[string]interface{})`

SetDOCLING_PICTURE_DESCRIPTION_API sets DOCLING_PICTURE_DESCRIPTION_API field to given value.

### HasDOCLING_PICTURE_DESCRIPTION_API

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCLING_PICTURE_DESCRIPTION_API() bool`

HasDOCLING_PICTURE_DESCRIPTION_API returns a boolean if a field has been set.

### SetDOCLING_PICTURE_DESCRIPTION_APINil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCLING_PICTURE_DESCRIPTION_APINil(b bool)`

 SetDOCLING_PICTURE_DESCRIPTION_APINil sets the value for DOCLING_PICTURE_DESCRIPTION_API to be an explicit nil

### UnsetDOCLING_PICTURE_DESCRIPTION_API
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCLING_PICTURE_DESCRIPTION_API()`

UnsetDOCLING_PICTURE_DESCRIPTION_API ensures that no value is present for DOCLING_PICTURE_DESCRIPTION_API, not even an explicit nil
### GetDOCUMENT_INTELLIGENCE_ENDPOINT

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCUMENT_INTELLIGENCE_ENDPOINT() string`

GetDOCUMENT_INTELLIGENCE_ENDPOINT returns the DOCUMENT_INTELLIGENCE_ENDPOINT field if non-nil, zero value otherwise.

### GetDOCUMENT_INTELLIGENCE_ENDPOINTOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCUMENT_INTELLIGENCE_ENDPOINTOk() (*string, bool)`

GetDOCUMENT_INTELLIGENCE_ENDPOINTOk returns a tuple with the DOCUMENT_INTELLIGENCE_ENDPOINT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCUMENT_INTELLIGENCE_ENDPOINT

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCUMENT_INTELLIGENCE_ENDPOINT(v string)`

SetDOCUMENT_INTELLIGENCE_ENDPOINT sets DOCUMENT_INTELLIGENCE_ENDPOINT field to given value.

### HasDOCUMENT_INTELLIGENCE_ENDPOINT

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCUMENT_INTELLIGENCE_ENDPOINT() bool`

HasDOCUMENT_INTELLIGENCE_ENDPOINT returns a boolean if a field has been set.

### SetDOCUMENT_INTELLIGENCE_ENDPOINTNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCUMENT_INTELLIGENCE_ENDPOINTNil(b bool)`

 SetDOCUMENT_INTELLIGENCE_ENDPOINTNil sets the value for DOCUMENT_INTELLIGENCE_ENDPOINT to be an explicit nil

### UnsetDOCUMENT_INTELLIGENCE_ENDPOINT
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCUMENT_INTELLIGENCE_ENDPOINT()`

UnsetDOCUMENT_INTELLIGENCE_ENDPOINT ensures that no value is present for DOCUMENT_INTELLIGENCE_ENDPOINT, not even an explicit nil
### GetDOCUMENT_INTELLIGENCE_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCUMENT_INTELLIGENCE_KEY() string`

GetDOCUMENT_INTELLIGENCE_KEY returns the DOCUMENT_INTELLIGENCE_KEY field if non-nil, zero value otherwise.

### GetDOCUMENT_INTELLIGENCE_KEYOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetDOCUMENT_INTELLIGENCE_KEYOk() (*string, bool)`

GetDOCUMENT_INTELLIGENCE_KEYOk returns a tuple with the DOCUMENT_INTELLIGENCE_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDOCUMENT_INTELLIGENCE_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCUMENT_INTELLIGENCE_KEY(v string)`

SetDOCUMENT_INTELLIGENCE_KEY sets DOCUMENT_INTELLIGENCE_KEY field to given value.

### HasDOCUMENT_INTELLIGENCE_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasDOCUMENT_INTELLIGENCE_KEY() bool`

HasDOCUMENT_INTELLIGENCE_KEY returns a boolean if a field has been set.

### SetDOCUMENT_INTELLIGENCE_KEYNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetDOCUMENT_INTELLIGENCE_KEYNil(b bool)`

 SetDOCUMENT_INTELLIGENCE_KEYNil sets the value for DOCUMENT_INTELLIGENCE_KEY to be an explicit nil

### UnsetDOCUMENT_INTELLIGENCE_KEY
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetDOCUMENT_INTELLIGENCE_KEY()`

UnsetDOCUMENT_INTELLIGENCE_KEY ensures that no value is present for DOCUMENT_INTELLIGENCE_KEY, not even an explicit nil
### GetMISTRAL_OCR_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetMISTRAL_OCR_API_KEY() string`

GetMISTRAL_OCR_API_KEY returns the MISTRAL_OCR_API_KEY field if non-nil, zero value otherwise.

### GetMISTRAL_OCR_API_KEYOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetMISTRAL_OCR_API_KEYOk() (*string, bool)`

GetMISTRAL_OCR_API_KEYOk returns a tuple with the MISTRAL_OCR_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMISTRAL_OCR_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetMISTRAL_OCR_API_KEY(v string)`

SetMISTRAL_OCR_API_KEY sets MISTRAL_OCR_API_KEY field to given value.

### HasMISTRAL_OCR_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasMISTRAL_OCR_API_KEY() bool`

HasMISTRAL_OCR_API_KEY returns a boolean if a field has been set.

### SetMISTRAL_OCR_API_KEYNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetMISTRAL_OCR_API_KEYNil(b bool)`

 SetMISTRAL_OCR_API_KEYNil sets the value for MISTRAL_OCR_API_KEY to be an explicit nil

### UnsetMISTRAL_OCR_API_KEY
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetMISTRAL_OCR_API_KEY()`

UnsetMISTRAL_OCR_API_KEY ensures that no value is present for MISTRAL_OCR_API_KEY, not even an explicit nil
### GetRAG_RERANKING_MODEL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_RERANKING_MODEL() string`

GetRAG_RERANKING_MODEL returns the RAG_RERANKING_MODEL field if non-nil, zero value otherwise.

### GetRAG_RERANKING_MODELOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_RERANKING_MODELOk() (*string, bool)`

GetRAG_RERANKING_MODELOk returns a tuple with the RAG_RERANKING_MODEL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRAG_RERANKING_MODEL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_RERANKING_MODEL(v string)`

SetRAG_RERANKING_MODEL sets RAG_RERANKING_MODEL field to given value.

### HasRAG_RERANKING_MODEL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRAG_RERANKING_MODEL() bool`

HasRAG_RERANKING_MODEL returns a boolean if a field has been set.

### SetRAG_RERANKING_MODELNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_RERANKING_MODELNil(b bool)`

 SetRAG_RERANKING_MODELNil sets the value for RAG_RERANKING_MODEL to be an explicit nil

### UnsetRAG_RERANKING_MODEL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRAG_RERANKING_MODEL()`

UnsetRAG_RERANKING_MODEL ensures that no value is present for RAG_RERANKING_MODEL, not even an explicit nil
### GetRAG_RERANKING_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_RERANKING_ENGINE() string`

GetRAG_RERANKING_ENGINE returns the RAG_RERANKING_ENGINE field if non-nil, zero value otherwise.

### GetRAG_RERANKING_ENGINEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_RERANKING_ENGINEOk() (*string, bool)`

GetRAG_RERANKING_ENGINEOk returns a tuple with the RAG_RERANKING_ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRAG_RERANKING_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_RERANKING_ENGINE(v string)`

SetRAG_RERANKING_ENGINE sets RAG_RERANKING_ENGINE field to given value.

### HasRAG_RERANKING_ENGINE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRAG_RERANKING_ENGINE() bool`

HasRAG_RERANKING_ENGINE returns a boolean if a field has been set.

### SetRAG_RERANKING_ENGINENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_RERANKING_ENGINENil(b bool)`

 SetRAG_RERANKING_ENGINENil sets the value for RAG_RERANKING_ENGINE to be an explicit nil

### UnsetRAG_RERANKING_ENGINE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRAG_RERANKING_ENGINE()`

UnsetRAG_RERANKING_ENGINE ensures that no value is present for RAG_RERANKING_ENGINE, not even an explicit nil
### GetRAG_EXTERNAL_RERANKER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_EXTERNAL_RERANKER_URL() string`

GetRAG_EXTERNAL_RERANKER_URL returns the RAG_EXTERNAL_RERANKER_URL field if non-nil, zero value otherwise.

### GetRAG_EXTERNAL_RERANKER_URLOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_EXTERNAL_RERANKER_URLOk() (*string, bool)`

GetRAG_EXTERNAL_RERANKER_URLOk returns a tuple with the RAG_EXTERNAL_RERANKER_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRAG_EXTERNAL_RERANKER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_EXTERNAL_RERANKER_URL(v string)`

SetRAG_EXTERNAL_RERANKER_URL sets RAG_EXTERNAL_RERANKER_URL field to given value.

### HasRAG_EXTERNAL_RERANKER_URL

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRAG_EXTERNAL_RERANKER_URL() bool`

HasRAG_EXTERNAL_RERANKER_URL returns a boolean if a field has been set.

### SetRAG_EXTERNAL_RERANKER_URLNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_EXTERNAL_RERANKER_URLNil(b bool)`

 SetRAG_EXTERNAL_RERANKER_URLNil sets the value for RAG_EXTERNAL_RERANKER_URL to be an explicit nil

### UnsetRAG_EXTERNAL_RERANKER_URL
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRAG_EXTERNAL_RERANKER_URL()`

UnsetRAG_EXTERNAL_RERANKER_URL ensures that no value is present for RAG_EXTERNAL_RERANKER_URL, not even an explicit nil
### GetRAG_EXTERNAL_RERANKER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_EXTERNAL_RERANKER_API_KEY() string`

GetRAG_EXTERNAL_RERANKER_API_KEY returns the RAG_EXTERNAL_RERANKER_API_KEY field if non-nil, zero value otherwise.

### GetRAG_EXTERNAL_RERANKER_API_KEYOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetRAG_EXTERNAL_RERANKER_API_KEYOk() (*string, bool)`

GetRAG_EXTERNAL_RERANKER_API_KEYOk returns a tuple with the RAG_EXTERNAL_RERANKER_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRAG_EXTERNAL_RERANKER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_EXTERNAL_RERANKER_API_KEY(v string)`

SetRAG_EXTERNAL_RERANKER_API_KEY sets RAG_EXTERNAL_RERANKER_API_KEY field to given value.

### HasRAG_EXTERNAL_RERANKER_API_KEY

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasRAG_EXTERNAL_RERANKER_API_KEY() bool`

HasRAG_EXTERNAL_RERANKER_API_KEY returns a boolean if a field has been set.

### SetRAG_EXTERNAL_RERANKER_API_KEYNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetRAG_EXTERNAL_RERANKER_API_KEYNil(b bool)`

 SetRAG_EXTERNAL_RERANKER_API_KEYNil sets the value for RAG_EXTERNAL_RERANKER_API_KEY to be an explicit nil

### UnsetRAG_EXTERNAL_RERANKER_API_KEY
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetRAG_EXTERNAL_RERANKER_API_KEY()`

UnsetRAG_EXTERNAL_RERANKER_API_KEY ensures that no value is present for RAG_EXTERNAL_RERANKER_API_KEY, not even an explicit nil
### GetTEXT_SPLITTER

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTEXT_SPLITTER() string`

GetTEXT_SPLITTER returns the TEXT_SPLITTER field if non-nil, zero value otherwise.

### GetTEXT_SPLITTEROk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetTEXT_SPLITTEROk() (*string, bool)`

GetTEXT_SPLITTEROk returns a tuple with the TEXT_SPLITTER field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTEXT_SPLITTER

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTEXT_SPLITTER(v string)`

SetTEXT_SPLITTER sets TEXT_SPLITTER field to given value.

### HasTEXT_SPLITTER

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasTEXT_SPLITTER() bool`

HasTEXT_SPLITTER returns a boolean if a field has been set.

### SetTEXT_SPLITTERNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetTEXT_SPLITTERNil(b bool)`

 SetTEXT_SPLITTERNil sets the value for TEXT_SPLITTER to be an explicit nil

### UnsetTEXT_SPLITTER
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetTEXT_SPLITTER()`

UnsetTEXT_SPLITTER ensures that no value is present for TEXT_SPLITTER, not even an explicit nil
### GetCHUNK_SIZE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetCHUNK_SIZE() int32`

GetCHUNK_SIZE returns the CHUNK_SIZE field if non-nil, zero value otherwise.

### GetCHUNK_SIZEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetCHUNK_SIZEOk() (*int32, bool)`

GetCHUNK_SIZEOk returns a tuple with the CHUNK_SIZE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCHUNK_SIZE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetCHUNK_SIZE(v int32)`

SetCHUNK_SIZE sets CHUNK_SIZE field to given value.

### HasCHUNK_SIZE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasCHUNK_SIZE() bool`

HasCHUNK_SIZE returns a boolean if a field has been set.

### SetCHUNK_SIZENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetCHUNK_SIZENil(b bool)`

 SetCHUNK_SIZENil sets the value for CHUNK_SIZE to be an explicit nil

### UnsetCHUNK_SIZE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetCHUNK_SIZE()`

UnsetCHUNK_SIZE ensures that no value is present for CHUNK_SIZE, not even an explicit nil
### GetCHUNK_OVERLAP

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetCHUNK_OVERLAP() int32`

GetCHUNK_OVERLAP returns the CHUNK_OVERLAP field if non-nil, zero value otherwise.

### GetCHUNK_OVERLAPOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetCHUNK_OVERLAPOk() (*int32, bool)`

GetCHUNK_OVERLAPOk returns a tuple with the CHUNK_OVERLAP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCHUNK_OVERLAP

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetCHUNK_OVERLAP(v int32)`

SetCHUNK_OVERLAP sets CHUNK_OVERLAP field to given value.

### HasCHUNK_OVERLAP

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasCHUNK_OVERLAP() bool`

HasCHUNK_OVERLAP returns a boolean if a field has been set.

### SetCHUNK_OVERLAPNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetCHUNK_OVERLAPNil(b bool)`

 SetCHUNK_OVERLAPNil sets the value for CHUNK_OVERLAP to be an explicit nil

### UnsetCHUNK_OVERLAP
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetCHUNK_OVERLAP()`

UnsetCHUNK_OVERLAP ensures that no value is present for CHUNK_OVERLAP, not even an explicit nil
### GetFILE_MAX_SIZE

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_MAX_SIZE() int32`

GetFILE_MAX_SIZE returns the FILE_MAX_SIZE field if non-nil, zero value otherwise.

### GetFILE_MAX_SIZEOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_MAX_SIZEOk() (*int32, bool)`

GetFILE_MAX_SIZEOk returns a tuple with the FILE_MAX_SIZE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFILE_MAX_SIZE

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_MAX_SIZE(v int32)`

SetFILE_MAX_SIZE sets FILE_MAX_SIZE field to given value.

### HasFILE_MAX_SIZE

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasFILE_MAX_SIZE() bool`

HasFILE_MAX_SIZE returns a boolean if a field has been set.

### SetFILE_MAX_SIZENil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_MAX_SIZENil(b bool)`

 SetFILE_MAX_SIZENil sets the value for FILE_MAX_SIZE to be an explicit nil

### UnsetFILE_MAX_SIZE
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetFILE_MAX_SIZE()`

UnsetFILE_MAX_SIZE ensures that no value is present for FILE_MAX_SIZE, not even an explicit nil
### GetFILE_MAX_COUNT

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_MAX_COUNT() int32`

GetFILE_MAX_COUNT returns the FILE_MAX_COUNT field if non-nil, zero value otherwise.

### GetFILE_MAX_COUNTOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_MAX_COUNTOk() (*int32, bool)`

GetFILE_MAX_COUNTOk returns a tuple with the FILE_MAX_COUNT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFILE_MAX_COUNT

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_MAX_COUNT(v int32)`

SetFILE_MAX_COUNT sets FILE_MAX_COUNT field to given value.

### HasFILE_MAX_COUNT

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasFILE_MAX_COUNT() bool`

HasFILE_MAX_COUNT returns a boolean if a field has been set.

### SetFILE_MAX_COUNTNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_MAX_COUNTNil(b bool)`

 SetFILE_MAX_COUNTNil sets the value for FILE_MAX_COUNT to be an explicit nil

### UnsetFILE_MAX_COUNT
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetFILE_MAX_COUNT()`

UnsetFILE_MAX_COUNT ensures that no value is present for FILE_MAX_COUNT, not even an explicit nil
### GetFILE_IMAGE_COMPRESSION_WIDTH

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_IMAGE_COMPRESSION_WIDTH() int32`

GetFILE_IMAGE_COMPRESSION_WIDTH returns the FILE_IMAGE_COMPRESSION_WIDTH field if non-nil, zero value otherwise.

### GetFILE_IMAGE_COMPRESSION_WIDTHOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_IMAGE_COMPRESSION_WIDTHOk() (*int32, bool)`

GetFILE_IMAGE_COMPRESSION_WIDTHOk returns a tuple with the FILE_IMAGE_COMPRESSION_WIDTH field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFILE_IMAGE_COMPRESSION_WIDTH

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_IMAGE_COMPRESSION_WIDTH(v int32)`

SetFILE_IMAGE_COMPRESSION_WIDTH sets FILE_IMAGE_COMPRESSION_WIDTH field to given value.

### HasFILE_IMAGE_COMPRESSION_WIDTH

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasFILE_IMAGE_COMPRESSION_WIDTH() bool`

HasFILE_IMAGE_COMPRESSION_WIDTH returns a boolean if a field has been set.

### SetFILE_IMAGE_COMPRESSION_WIDTHNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_IMAGE_COMPRESSION_WIDTHNil(b bool)`

 SetFILE_IMAGE_COMPRESSION_WIDTHNil sets the value for FILE_IMAGE_COMPRESSION_WIDTH to be an explicit nil

### UnsetFILE_IMAGE_COMPRESSION_WIDTH
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetFILE_IMAGE_COMPRESSION_WIDTH()`

UnsetFILE_IMAGE_COMPRESSION_WIDTH ensures that no value is present for FILE_IMAGE_COMPRESSION_WIDTH, not even an explicit nil
### GetFILE_IMAGE_COMPRESSION_HEIGHT

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_IMAGE_COMPRESSION_HEIGHT() int32`

GetFILE_IMAGE_COMPRESSION_HEIGHT returns the FILE_IMAGE_COMPRESSION_HEIGHT field if non-nil, zero value otherwise.

### GetFILE_IMAGE_COMPRESSION_HEIGHTOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetFILE_IMAGE_COMPRESSION_HEIGHTOk() (*int32, bool)`

GetFILE_IMAGE_COMPRESSION_HEIGHTOk returns a tuple with the FILE_IMAGE_COMPRESSION_HEIGHT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFILE_IMAGE_COMPRESSION_HEIGHT

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_IMAGE_COMPRESSION_HEIGHT(v int32)`

SetFILE_IMAGE_COMPRESSION_HEIGHT sets FILE_IMAGE_COMPRESSION_HEIGHT field to given value.

### HasFILE_IMAGE_COMPRESSION_HEIGHT

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasFILE_IMAGE_COMPRESSION_HEIGHT() bool`

HasFILE_IMAGE_COMPRESSION_HEIGHT returns a boolean if a field has been set.

### SetFILE_IMAGE_COMPRESSION_HEIGHTNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetFILE_IMAGE_COMPRESSION_HEIGHTNil(b bool)`

 SetFILE_IMAGE_COMPRESSION_HEIGHTNil sets the value for FILE_IMAGE_COMPRESSION_HEIGHT to be an explicit nil

### UnsetFILE_IMAGE_COMPRESSION_HEIGHT
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetFILE_IMAGE_COMPRESSION_HEIGHT()`

UnsetFILE_IMAGE_COMPRESSION_HEIGHT ensures that no value is present for FILE_IMAGE_COMPRESSION_HEIGHT, not even an explicit nil
### GetALLOWED_FILE_EXTENSIONS

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetALLOWED_FILE_EXTENSIONS() []string`

GetALLOWED_FILE_EXTENSIONS returns the ALLOWED_FILE_EXTENSIONS field if non-nil, zero value otherwise.

### GetALLOWED_FILE_EXTENSIONSOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetALLOWED_FILE_EXTENSIONSOk() (*[]string, bool)`

GetALLOWED_FILE_EXTENSIONSOk returns a tuple with the ALLOWED_FILE_EXTENSIONS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetALLOWED_FILE_EXTENSIONS

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetALLOWED_FILE_EXTENSIONS(v []string)`

SetALLOWED_FILE_EXTENSIONS sets ALLOWED_FILE_EXTENSIONS field to given value.

### HasALLOWED_FILE_EXTENSIONS

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasALLOWED_FILE_EXTENSIONS() bool`

HasALLOWED_FILE_EXTENSIONS returns a boolean if a field has been set.

### SetALLOWED_FILE_EXTENSIONSNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetALLOWED_FILE_EXTENSIONSNil(b bool)`

 SetALLOWED_FILE_EXTENSIONSNil sets the value for ALLOWED_FILE_EXTENSIONS to be an explicit nil

### UnsetALLOWED_FILE_EXTENSIONS
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetALLOWED_FILE_EXTENSIONS()`

UnsetALLOWED_FILE_EXTENSIONS ensures that no value is present for ALLOWED_FILE_EXTENSIONS, not even an explicit nil
### GetENABLE_GOOGLE_DRIVE_INTEGRATION

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetENABLE_GOOGLE_DRIVE_INTEGRATION() bool`

GetENABLE_GOOGLE_DRIVE_INTEGRATION returns the ENABLE_GOOGLE_DRIVE_INTEGRATION field if non-nil, zero value otherwise.

### GetENABLE_GOOGLE_DRIVE_INTEGRATIONOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetENABLE_GOOGLE_DRIVE_INTEGRATIONOk() (*bool, bool)`

GetENABLE_GOOGLE_DRIVE_INTEGRATIONOk returns a tuple with the ENABLE_GOOGLE_DRIVE_INTEGRATION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_GOOGLE_DRIVE_INTEGRATION

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetENABLE_GOOGLE_DRIVE_INTEGRATION(v bool)`

SetENABLE_GOOGLE_DRIVE_INTEGRATION sets ENABLE_GOOGLE_DRIVE_INTEGRATION field to given value.

### HasENABLE_GOOGLE_DRIVE_INTEGRATION

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasENABLE_GOOGLE_DRIVE_INTEGRATION() bool`

HasENABLE_GOOGLE_DRIVE_INTEGRATION returns a boolean if a field has been set.

### SetENABLE_GOOGLE_DRIVE_INTEGRATIONNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetENABLE_GOOGLE_DRIVE_INTEGRATIONNil(b bool)`

 SetENABLE_GOOGLE_DRIVE_INTEGRATIONNil sets the value for ENABLE_GOOGLE_DRIVE_INTEGRATION to be an explicit nil

### UnsetENABLE_GOOGLE_DRIVE_INTEGRATION
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetENABLE_GOOGLE_DRIVE_INTEGRATION()`

UnsetENABLE_GOOGLE_DRIVE_INTEGRATION ensures that no value is present for ENABLE_GOOGLE_DRIVE_INTEGRATION, not even an explicit nil
### GetENABLE_ONEDRIVE_INTEGRATION

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetENABLE_ONEDRIVE_INTEGRATION() bool`

GetENABLE_ONEDRIVE_INTEGRATION returns the ENABLE_ONEDRIVE_INTEGRATION field if non-nil, zero value otherwise.

### GetENABLE_ONEDRIVE_INTEGRATIONOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetENABLE_ONEDRIVE_INTEGRATIONOk() (*bool, bool)`

GetENABLE_ONEDRIVE_INTEGRATIONOk returns a tuple with the ENABLE_ONEDRIVE_INTEGRATION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_ONEDRIVE_INTEGRATION

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetENABLE_ONEDRIVE_INTEGRATION(v bool)`

SetENABLE_ONEDRIVE_INTEGRATION sets ENABLE_ONEDRIVE_INTEGRATION field to given value.

### HasENABLE_ONEDRIVE_INTEGRATION

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasENABLE_ONEDRIVE_INTEGRATION() bool`

HasENABLE_ONEDRIVE_INTEGRATION returns a boolean if a field has been set.

### SetENABLE_ONEDRIVE_INTEGRATIONNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetENABLE_ONEDRIVE_INTEGRATIONNil(b bool)`

 SetENABLE_ONEDRIVE_INTEGRATIONNil sets the value for ENABLE_ONEDRIVE_INTEGRATION to be an explicit nil

### UnsetENABLE_ONEDRIVE_INTEGRATION
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetENABLE_ONEDRIVE_INTEGRATION()`

UnsetENABLE_ONEDRIVE_INTEGRATION ensures that no value is present for ENABLE_ONEDRIVE_INTEGRATION, not even an explicit nil
### GetWeb

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetWeb() WebConfig`

GetWeb returns the Web field if non-nil, zero value otherwise.

### GetWebOk

`func (o *OpenWebuiRoutersRetrievalConfigForm) GetWebOk() (*WebConfig, bool)`

GetWebOk returns a tuple with the Web field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeb

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetWeb(v WebConfig)`

SetWeb sets Web field to given value.

### HasWeb

`func (o *OpenWebuiRoutersRetrievalConfigForm) HasWeb() bool`

HasWeb returns a boolean if a field has been set.

### SetWebNil

`func (o *OpenWebuiRoutersRetrievalConfigForm) SetWebNil(b bool)`

 SetWebNil sets the value for Web to be an explicit nil

### UnsetWeb
`func (o *OpenWebuiRoutersRetrievalConfigForm) UnsetWeb()`

UnsetWeb ensures that no value is present for Web, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# STTConfigForm

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OPENAI_API_BASE_URL** | **string** |  | 
**OPENAI_API_KEY** | **string** |  | 
**ENGINE** | **string** |  | 
**MODEL** | **string** |  | 
**SUPPORTED_CONTENT_TYPES** | Pointer to **[]string** |  | [optional] [default to []]
**WHISPER_MODEL** | **string** |  | 
**DEEPGRAM_API_KEY** | **string** |  | 
**AZURE_API_KEY** | **string** |  | 
**AZURE_REGION** | **string** |  | 
**AZURE_LOCALES** | **string** |  | 
**AZURE_BASE_URL** | **string** |  | 
**AZURE_MAX_SPEAKERS** | **string** |  | 

## Methods

### NewSTTConfigForm

`func NewSTTConfigForm(oPENAIAPIBASEURL string, oPENAIAPIKEY string, eNGINE string, mODEL string, wHISPERMODEL string, dEEPGRAMAPIKEY string, aZUREAPIKEY string, aZUREREGION string, aZURELOCALES string, aZUREBASEURL string, aZUREMAXSPEAKERS string, ) *STTConfigForm`

NewSTTConfigForm instantiates a new STTConfigForm object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSTTConfigFormWithDefaults

`func NewSTTConfigFormWithDefaults() *STTConfigForm`

NewSTTConfigFormWithDefaults instantiates a new STTConfigForm object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOPENAI_API_BASE_URL

`func (o *STTConfigForm) GetOPENAI_API_BASE_URL() string`

GetOPENAI_API_BASE_URL returns the OPENAI_API_BASE_URL field if non-nil, zero value otherwise.

### GetOPENAI_API_BASE_URLOk

`func (o *STTConfigForm) GetOPENAI_API_BASE_URLOk() (*string, bool)`

GetOPENAI_API_BASE_URLOk returns a tuple with the OPENAI_API_BASE_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOPENAI_API_BASE_URL

`func (o *STTConfigForm) SetOPENAI_API_BASE_URL(v string)`

SetOPENAI_API_BASE_URL sets OPENAI_API_BASE_URL field to given value.


### GetOPENAI_API_KEY

`func (o *STTConfigForm) GetOPENAI_API_KEY() string`

GetOPENAI_API_KEY returns the OPENAI_API_KEY field if non-nil, zero value otherwise.

### GetOPENAI_API_KEYOk

`func (o *STTConfigForm) GetOPENAI_API_KEYOk() (*string, bool)`

GetOPENAI_API_KEYOk returns a tuple with the OPENAI_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOPENAI_API_KEY

`func (o *STTConfigForm) SetOPENAI_API_KEY(v string)`

SetOPENAI_API_KEY sets OPENAI_API_KEY field to given value.


### GetENGINE

`func (o *STTConfigForm) GetENGINE() string`

GetENGINE returns the ENGINE field if non-nil, zero value otherwise.

### GetENGINEOk

`func (o *STTConfigForm) GetENGINEOk() (*string, bool)`

GetENGINEOk returns a tuple with the ENGINE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENGINE

`func (o *STTConfigForm) SetENGINE(v string)`

SetENGINE sets ENGINE field to given value.


### GetMODEL

`func (o *STTConfigForm) GetMODEL() string`

GetMODEL returns the MODEL field if non-nil, zero value otherwise.

### GetMODELOk

`func (o *STTConfigForm) GetMODELOk() (*string, bool)`

GetMODELOk returns a tuple with the MODEL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMODEL

`func (o *STTConfigForm) SetMODEL(v string)`

SetMODEL sets MODEL field to given value.


### GetSUPPORTED_CONTENT_TYPES

`func (o *STTConfigForm) GetSUPPORTED_CONTENT_TYPES() []string`

GetSUPPORTED_CONTENT_TYPES returns the SUPPORTED_CONTENT_TYPES field if non-nil, zero value otherwise.

### GetSUPPORTED_CONTENT_TYPESOk

`func (o *STTConfigForm) GetSUPPORTED_CONTENT_TYPESOk() (*[]string, bool)`

GetSUPPORTED_CONTENT_TYPESOk returns a tuple with the SUPPORTED_CONTENT_TYPES field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSUPPORTED_CONTENT_TYPES

`func (o *STTConfigForm) SetSUPPORTED_CONTENT_TYPES(v []string)`

SetSUPPORTED_CONTENT_TYPES sets SUPPORTED_CONTENT_TYPES field to given value.

### HasSUPPORTED_CONTENT_TYPES

`func (o *STTConfigForm) HasSUPPORTED_CONTENT_TYPES() bool`

HasSUPPORTED_CONTENT_TYPES returns a boolean if a field has been set.

### GetWHISPER_MODEL

`func (o *STTConfigForm) GetWHISPER_MODEL() string`

GetWHISPER_MODEL returns the WHISPER_MODEL field if non-nil, zero value otherwise.

### GetWHISPER_MODELOk

`func (o *STTConfigForm) GetWHISPER_MODELOk() (*string, bool)`

GetWHISPER_MODELOk returns a tuple with the WHISPER_MODEL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWHISPER_MODEL

`func (o *STTConfigForm) SetWHISPER_MODEL(v string)`

SetWHISPER_MODEL sets WHISPER_MODEL field to given value.


### GetDEEPGRAM_API_KEY

`func (o *STTConfigForm) GetDEEPGRAM_API_KEY() string`

GetDEEPGRAM_API_KEY returns the DEEPGRAM_API_KEY field if non-nil, zero value otherwise.

### GetDEEPGRAM_API_KEYOk

`func (o *STTConfigForm) GetDEEPGRAM_API_KEYOk() (*string, bool)`

GetDEEPGRAM_API_KEYOk returns a tuple with the DEEPGRAM_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDEEPGRAM_API_KEY

`func (o *STTConfigForm) SetDEEPGRAM_API_KEY(v string)`

SetDEEPGRAM_API_KEY sets DEEPGRAM_API_KEY field to given value.


### GetAZURE_API_KEY

`func (o *STTConfigForm) GetAZURE_API_KEY() string`

GetAZURE_API_KEY returns the AZURE_API_KEY field if non-nil, zero value otherwise.

### GetAZURE_API_KEYOk

`func (o *STTConfigForm) GetAZURE_API_KEYOk() (*string, bool)`

GetAZURE_API_KEYOk returns a tuple with the AZURE_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAZURE_API_KEY

`func (o *STTConfigForm) SetAZURE_API_KEY(v string)`

SetAZURE_API_KEY sets AZURE_API_KEY field to given value.


### GetAZURE_REGION

`func (o *STTConfigForm) GetAZURE_REGION() string`

GetAZURE_REGION returns the AZURE_REGION field if non-nil, zero value otherwise.

### GetAZURE_REGIONOk

`func (o *STTConfigForm) GetAZURE_REGIONOk() (*string, bool)`

GetAZURE_REGIONOk returns a tuple with the AZURE_REGION field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAZURE_REGION

`func (o *STTConfigForm) SetAZURE_REGION(v string)`

SetAZURE_REGION sets AZURE_REGION field to given value.


### GetAZURE_LOCALES

`func (o *STTConfigForm) GetAZURE_LOCALES() string`

GetAZURE_LOCALES returns the AZURE_LOCALES field if non-nil, zero value otherwise.

### GetAZURE_LOCALESOk

`func (o *STTConfigForm) GetAZURE_LOCALESOk() (*string, bool)`

GetAZURE_LOCALESOk returns a tuple with the AZURE_LOCALES field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAZURE_LOCALES

`func (o *STTConfigForm) SetAZURE_LOCALES(v string)`

SetAZURE_LOCALES sets AZURE_LOCALES field to given value.


### GetAZURE_BASE_URL

`func (o *STTConfigForm) GetAZURE_BASE_URL() string`

GetAZURE_BASE_URL returns the AZURE_BASE_URL field if non-nil, zero value otherwise.

### GetAZURE_BASE_URLOk

`func (o *STTConfigForm) GetAZURE_BASE_URLOk() (*string, bool)`

GetAZURE_BASE_URLOk returns a tuple with the AZURE_BASE_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAZURE_BASE_URL

`func (o *STTConfigForm) SetAZURE_BASE_URL(v string)`

SetAZURE_BASE_URL sets AZURE_BASE_URL field to given value.


### GetAZURE_MAX_SPEAKERS

`func (o *STTConfigForm) GetAZURE_MAX_SPEAKERS() string`

GetAZURE_MAX_SPEAKERS returns the AZURE_MAX_SPEAKERS field if non-nil, zero value otherwise.

### GetAZURE_MAX_SPEAKERSOk

`func (o *STTConfigForm) GetAZURE_MAX_SPEAKERSOk() (*string, bool)`

GetAZURE_MAX_SPEAKERSOk returns a tuple with the AZURE_MAX_SPEAKERS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAZURE_MAX_SPEAKERS

`func (o *STTConfigForm) SetAZURE_MAX_SPEAKERS(v string)`

SetAZURE_MAX_SPEAKERS sets AZURE_MAX_SPEAKERS field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AdminConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SHOW_ADMIN_DETAILS** | **bool** |  | 
**WEBUI_URL** | **string** |  | 
**ENABLE_SIGNUP** | **bool** |  | 
**ENABLE_API_KEY** | **bool** |  | 
**ENABLE_API_KEY_ENDPOINT_RESTRICTIONS** | **bool** |  | 
**API_KEY_ALLOWED_ENDPOINTS** | **string** |  | 
**DEFAULT_USER_ROLE** | **string** |  | 
**JWT_EXPIRES_IN** | **string** |  | 
**ENABLE_COMMUNITY_SHARING** | **bool** |  | 
**ENABLE_MESSAGE_RATING** | **bool** |  | 
**ENABLE_CHANNELS** | **bool** |  | 
**ENABLE_NOTES** | **bool** |  | 
**ENABLE_USER_WEBHOOKS** | **bool** |  | 
**PENDING_USER_OVERLAY_TITLE** | Pointer to **NullableString** |  | [optional] 
**PENDING_USER_OVERLAY_CONTENT** | Pointer to **NullableString** |  | [optional] 
**RESPONSE_WATERMARK** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAdminConfig

`func NewAdminConfig(sHOWADMINDETAILS bool, wEBUIURL string, eNABLESIGNUP bool, eNABLEAPIKEY bool, eNABLEAPIKEYENDPOINTRESTRICTIONS bool, aPIKEYALLOWEDENDPOINTS string, dEFAULTUSERROLE string, jWTEXPIRESIN string, eNABLECOMMUNITYSHARING bool, eNABLEMESSAGERATING bool, eNABLECHANNELS bool, eNABLENOTES bool, eNABLEUSERWEBHOOKS bool, ) *AdminConfig`

NewAdminConfig instantiates a new AdminConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminConfigWithDefaults

`func NewAdminConfigWithDefaults() *AdminConfig`

NewAdminConfigWithDefaults instantiates a new AdminConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSHOW_ADMIN_DETAILS

`func (o *AdminConfig) GetSHOW_ADMIN_DETAILS() bool`

GetSHOW_ADMIN_DETAILS returns the SHOW_ADMIN_DETAILS field if non-nil, zero value otherwise.

### GetSHOW_ADMIN_DETAILSOk

`func (o *AdminConfig) GetSHOW_ADMIN_DETAILSOk() (*bool, bool)`

GetSHOW_ADMIN_DETAILSOk returns a tuple with the SHOW_ADMIN_DETAILS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSHOW_ADMIN_DETAILS

`func (o *AdminConfig) SetSHOW_ADMIN_DETAILS(v bool)`

SetSHOW_ADMIN_DETAILS sets SHOW_ADMIN_DETAILS field to given value.


### GetWEBUI_URL

`func (o *AdminConfig) GetWEBUI_URL() string`

GetWEBUI_URL returns the WEBUI_URL field if non-nil, zero value otherwise.

### GetWEBUI_URLOk

`func (o *AdminConfig) GetWEBUI_URLOk() (*string, bool)`

GetWEBUI_URLOk returns a tuple with the WEBUI_URL field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWEBUI_URL

`func (o *AdminConfig) SetWEBUI_URL(v string)`

SetWEBUI_URL sets WEBUI_URL field to given value.


### GetENABLE_SIGNUP

`func (o *AdminConfig) GetENABLE_SIGNUP() bool`

GetENABLE_SIGNUP returns the ENABLE_SIGNUP field if non-nil, zero value otherwise.

### GetENABLE_SIGNUPOk

`func (o *AdminConfig) GetENABLE_SIGNUPOk() (*bool, bool)`

GetENABLE_SIGNUPOk returns a tuple with the ENABLE_SIGNUP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_SIGNUP

`func (o *AdminConfig) SetENABLE_SIGNUP(v bool)`

SetENABLE_SIGNUP sets ENABLE_SIGNUP field to given value.


### GetENABLE_API_KEY

`func (o *AdminConfig) GetENABLE_API_KEY() bool`

GetENABLE_API_KEY returns the ENABLE_API_KEY field if non-nil, zero value otherwise.

### GetENABLE_API_KEYOk

`func (o *AdminConfig) GetENABLE_API_KEYOk() (*bool, bool)`

GetENABLE_API_KEYOk returns a tuple with the ENABLE_API_KEY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_API_KEY

`func (o *AdminConfig) SetENABLE_API_KEY(v bool)`

SetENABLE_API_KEY sets ENABLE_API_KEY field to given value.


### GetENABLE_API_KEY_ENDPOINT_RESTRICTIONS

`func (o *AdminConfig) GetENABLE_API_KEY_ENDPOINT_RESTRICTIONS() bool`

GetENABLE_API_KEY_ENDPOINT_RESTRICTIONS returns the ENABLE_API_KEY_ENDPOINT_RESTRICTIONS field if non-nil, zero value otherwise.

### GetENABLE_API_KEY_ENDPOINT_RESTRICTIONSOk

`func (o *AdminConfig) GetENABLE_API_KEY_ENDPOINT_RESTRICTIONSOk() (*bool, bool)`

GetENABLE_API_KEY_ENDPOINT_RESTRICTIONSOk returns a tuple with the ENABLE_API_KEY_ENDPOINT_RESTRICTIONS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_API_KEY_ENDPOINT_RESTRICTIONS

`func (o *AdminConfig) SetENABLE_API_KEY_ENDPOINT_RESTRICTIONS(v bool)`

SetENABLE_API_KEY_ENDPOINT_RESTRICTIONS sets ENABLE_API_KEY_ENDPOINT_RESTRICTIONS field to given value.


### GetAPI_KEY_ALLOWED_ENDPOINTS

`func (o *AdminConfig) GetAPI_KEY_ALLOWED_ENDPOINTS() string`

GetAPI_KEY_ALLOWED_ENDPOINTS returns the API_KEY_ALLOWED_ENDPOINTS field if non-nil, zero value otherwise.

### GetAPI_KEY_ALLOWED_ENDPOINTSOk

`func (o *AdminConfig) GetAPI_KEY_ALLOWED_ENDPOINTSOk() (*string, bool)`

GetAPI_KEY_ALLOWED_ENDPOINTSOk returns a tuple with the API_KEY_ALLOWED_ENDPOINTS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAPI_KEY_ALLOWED_ENDPOINTS

`func (o *AdminConfig) SetAPI_KEY_ALLOWED_ENDPOINTS(v string)`

SetAPI_KEY_ALLOWED_ENDPOINTS sets API_KEY_ALLOWED_ENDPOINTS field to given value.


### GetDEFAULT_USER_ROLE

`func (o *AdminConfig) GetDEFAULT_USER_ROLE() string`

GetDEFAULT_USER_ROLE returns the DEFAULT_USER_ROLE field if non-nil, zero value otherwise.

### GetDEFAULT_USER_ROLEOk

`func (o *AdminConfig) GetDEFAULT_USER_ROLEOk() (*string, bool)`

GetDEFAULT_USER_ROLEOk returns a tuple with the DEFAULT_USER_ROLE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDEFAULT_USER_ROLE

`func (o *AdminConfig) SetDEFAULT_USER_ROLE(v string)`

SetDEFAULT_USER_ROLE sets DEFAULT_USER_ROLE field to given value.


### GetJWT_EXPIRES_IN

`func (o *AdminConfig) GetJWT_EXPIRES_IN() string`

GetJWT_EXPIRES_IN returns the JWT_EXPIRES_IN field if non-nil, zero value otherwise.

### GetJWT_EXPIRES_INOk

`func (o *AdminConfig) GetJWT_EXPIRES_INOk() (*string, bool)`

GetJWT_EXPIRES_INOk returns a tuple with the JWT_EXPIRES_IN field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJWT_EXPIRES_IN

`func (o *AdminConfig) SetJWT_EXPIRES_IN(v string)`

SetJWT_EXPIRES_IN sets JWT_EXPIRES_IN field to given value.


### GetENABLE_COMMUNITY_SHARING

`func (o *AdminConfig) GetENABLE_COMMUNITY_SHARING() bool`

GetENABLE_COMMUNITY_SHARING returns the ENABLE_COMMUNITY_SHARING field if non-nil, zero value otherwise.

### GetENABLE_COMMUNITY_SHARINGOk

`func (o *AdminConfig) GetENABLE_COMMUNITY_SHARINGOk() (*bool, bool)`

GetENABLE_COMMUNITY_SHARINGOk returns a tuple with the ENABLE_COMMUNITY_SHARING field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_COMMUNITY_SHARING

`func (o *AdminConfig) SetENABLE_COMMUNITY_SHARING(v bool)`

SetENABLE_COMMUNITY_SHARING sets ENABLE_COMMUNITY_SHARING field to given value.


### GetENABLE_MESSAGE_RATING

`func (o *AdminConfig) GetENABLE_MESSAGE_RATING() bool`

GetENABLE_MESSAGE_RATING returns the ENABLE_MESSAGE_RATING field if non-nil, zero value otherwise.

### GetENABLE_MESSAGE_RATINGOk

`func (o *AdminConfig) GetENABLE_MESSAGE_RATINGOk() (*bool, bool)`

GetENABLE_MESSAGE_RATINGOk returns a tuple with the ENABLE_MESSAGE_RATING field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_MESSAGE_RATING

`func (o *AdminConfig) SetENABLE_MESSAGE_RATING(v bool)`

SetENABLE_MESSAGE_RATING sets ENABLE_MESSAGE_RATING field to given value.


### GetENABLE_CHANNELS

`func (o *AdminConfig) GetENABLE_CHANNELS() bool`

GetENABLE_CHANNELS returns the ENABLE_CHANNELS field if non-nil, zero value otherwise.

### GetENABLE_CHANNELSOk

`func (o *AdminConfig) GetENABLE_CHANNELSOk() (*bool, bool)`

GetENABLE_CHANNELSOk returns a tuple with the ENABLE_CHANNELS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_CHANNELS

`func (o *AdminConfig) SetENABLE_CHANNELS(v bool)`

SetENABLE_CHANNELS sets ENABLE_CHANNELS field to given value.


### GetENABLE_NOTES

`func (o *AdminConfig) GetENABLE_NOTES() bool`

GetENABLE_NOTES returns the ENABLE_NOTES field if non-nil, zero value otherwise.

### GetENABLE_NOTESOk

`func (o *AdminConfig) GetENABLE_NOTESOk() (*bool, bool)`

GetENABLE_NOTESOk returns a tuple with the ENABLE_NOTES field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_NOTES

`func (o *AdminConfig) SetENABLE_NOTES(v bool)`

SetENABLE_NOTES sets ENABLE_NOTES field to given value.


### GetENABLE_USER_WEBHOOKS

`func (o *AdminConfig) GetENABLE_USER_WEBHOOKS() bool`

GetENABLE_USER_WEBHOOKS returns the ENABLE_USER_WEBHOOKS field if non-nil, zero value otherwise.

### GetENABLE_USER_WEBHOOKSOk

`func (o *AdminConfig) GetENABLE_USER_WEBHOOKSOk() (*bool, bool)`

GetENABLE_USER_WEBHOOKSOk returns a tuple with the ENABLE_USER_WEBHOOKS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetENABLE_USER_WEBHOOKS

`func (o *AdminConfig) SetENABLE_USER_WEBHOOKS(v bool)`

SetENABLE_USER_WEBHOOKS sets ENABLE_USER_WEBHOOKS field to given value.


### GetPENDING_USER_OVERLAY_TITLE

`func (o *AdminConfig) GetPENDING_USER_OVERLAY_TITLE() string`

GetPENDING_USER_OVERLAY_TITLE returns the PENDING_USER_OVERLAY_TITLE field if non-nil, zero value otherwise.

### GetPENDING_USER_OVERLAY_TITLEOk

`func (o *AdminConfig) GetPENDING_USER_OVERLAY_TITLEOk() (*string, bool)`

GetPENDING_USER_OVERLAY_TITLEOk returns a tuple with the PENDING_USER_OVERLAY_TITLE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPENDING_USER_OVERLAY_TITLE

`func (o *AdminConfig) SetPENDING_USER_OVERLAY_TITLE(v string)`

SetPENDING_USER_OVERLAY_TITLE sets PENDING_USER_OVERLAY_TITLE field to given value.

### HasPENDING_USER_OVERLAY_TITLE

`func (o *AdminConfig) HasPENDING_USER_OVERLAY_TITLE() bool`

HasPENDING_USER_OVERLAY_TITLE returns a boolean if a field has been set.

### SetPENDING_USER_OVERLAY_TITLENil

`func (o *AdminConfig) SetPENDING_USER_OVERLAY_TITLENil(b bool)`

 SetPENDING_USER_OVERLAY_TITLENil sets the value for PENDING_USER_OVERLAY_TITLE to be an explicit nil

### UnsetPENDING_USER_OVERLAY_TITLE
`func (o *AdminConfig) UnsetPENDING_USER_OVERLAY_TITLE()`

UnsetPENDING_USER_OVERLAY_TITLE ensures that no value is present for PENDING_USER_OVERLAY_TITLE, not even an explicit nil
### GetPENDING_USER_OVERLAY_CONTENT

`func (o *AdminConfig) GetPENDING_USER_OVERLAY_CONTENT() string`

GetPENDING_USER_OVERLAY_CONTENT returns the PENDING_USER_OVERLAY_CONTENT field if non-nil, zero value otherwise.

### GetPENDING_USER_OVERLAY_CONTENTOk

`func (o *AdminConfig) GetPENDING_USER_OVERLAY_CONTENTOk() (*string, bool)`

GetPENDING_USER_OVERLAY_CONTENTOk returns a tuple with the PENDING_USER_OVERLAY_CONTENT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPENDING_USER_OVERLAY_CONTENT

`func (o *AdminConfig) SetPENDING_USER_OVERLAY_CONTENT(v string)`

SetPENDING_USER_OVERLAY_CONTENT sets PENDING_USER_OVERLAY_CONTENT field to given value.

### HasPENDING_USER_OVERLAY_CONTENT

`func (o *AdminConfig) HasPENDING_USER_OVERLAY_CONTENT() bool`

HasPENDING_USER_OVERLAY_CONTENT returns a boolean if a field has been set.

### SetPENDING_USER_OVERLAY_CONTENTNil

`func (o *AdminConfig) SetPENDING_USER_OVERLAY_CONTENTNil(b bool)`

 SetPENDING_USER_OVERLAY_CONTENTNil sets the value for PENDING_USER_OVERLAY_CONTENT to be an explicit nil

### UnsetPENDING_USER_OVERLAY_CONTENT
`func (o *AdminConfig) UnsetPENDING_USER_OVERLAY_CONTENT()`

UnsetPENDING_USER_OVERLAY_CONTENT ensures that no value is present for PENDING_USER_OVERLAY_CONTENT, not even an explicit nil
### GetRESPONSE_WATERMARK

`func (o *AdminConfig) GetRESPONSE_WATERMARK() string`

GetRESPONSE_WATERMARK returns the RESPONSE_WATERMARK field if non-nil, zero value otherwise.

### GetRESPONSE_WATERMARKOk

`func (o *AdminConfig) GetRESPONSE_WATERMARKOk() (*string, bool)`

GetRESPONSE_WATERMARKOk returns a tuple with the RESPONSE_WATERMARK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRESPONSE_WATERMARK

`func (o *AdminConfig) SetRESPONSE_WATERMARK(v string)`

SetRESPONSE_WATERMARK sets RESPONSE_WATERMARK field to given value.

### HasRESPONSE_WATERMARK

`func (o *AdminConfig) HasRESPONSE_WATERMARK() bool`

HasRESPONSE_WATERMARK returns a boolean if a field has been set.

### SetRESPONSE_WATERMARKNil

`func (o *AdminConfig) SetRESPONSE_WATERMARKNil(b bool)`

 SetRESPONSE_WATERMARKNil sets the value for RESPONSE_WATERMARK to be an explicit nil

### UnsetRESPONSE_WATERMARK
`func (o *AdminConfig) UnsetRESPONSE_WATERMARK()`

UnsetRESPONSE_WATERMARK ensures that no value is present for RESPONSE_WATERMARK, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



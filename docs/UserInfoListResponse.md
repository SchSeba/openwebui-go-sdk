# UserInfoListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Users** | [**[]UserInfoResponse**](UserInfoResponse.md) |  | 
**Total** | **int32** |  | 

## Methods

### NewUserInfoListResponse

`func NewUserInfoListResponse(users []UserInfoResponse, total int32, ) *UserInfoListResponse`

NewUserInfoListResponse instantiates a new UserInfoListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserInfoListResponseWithDefaults

`func NewUserInfoListResponseWithDefaults() *UserInfoListResponse`

NewUserInfoListResponseWithDefaults instantiates a new UserInfoListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsers

`func (o *UserInfoListResponse) GetUsers() []UserInfoResponse`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *UserInfoListResponse) GetUsersOk() (*[]UserInfoResponse, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *UserInfoListResponse) SetUsers(v []UserInfoResponse)`

SetUsers sets Users field to given value.


### GetTotal

`func (o *UserInfoListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *UserInfoListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *UserInfoListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



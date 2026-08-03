# \UserApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**user_destroy**](UserApi.md#user_destroy) | **DELETE** /api/v1/users/{id} | User@destroy
[**user_index**](UserApi.md#user_index) | **GET** /api/v1/users | User@index
[**user_show**](UserApi.md#user_show) | **GET** /api/v1/users/{id} | User@show
[**user_update**](UserApi.md#user_update) | **PUT** /api/v1/users/{id} | User@update



## user_destroy

> models::AffiliationDestroy200Response user_destroy(id)
User@destroy

Delete a User entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## user_index

> models::UserIndex200Response user_index()
User@index

Return a list of Users

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::UserIndex200Response**](userIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## user_show

> models::UserShow200Response user_show(id)
User@show

Return a User entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |

### Return type

[**models::UserShow200Response**](userShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## user_update

> models::UserUpdate200Response user_update(id, user_update_request)
User@update

Edit a User entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |
**user_update_request** | [**UserUpdateRequest**](UserUpdateRequest.md) | User definition | [required] |

### Return type

[**models::UserUpdate200Response**](userUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


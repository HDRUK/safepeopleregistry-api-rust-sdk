# \PermissionApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**permission_destroy**](PermissionApi.md#permission_destroy) | **DELETE** /api/v1/permissions/{id} | Permission@destroy
[**permission_index**](PermissionApi.md#permission_index) | **GET** /api/v1/permissions | Permission@index
[**permission_show**](PermissionApi.md#permission_show) | **GET** /api/v1/permissions/{id} | Permission@show
[**permission_store**](PermissionApi.md#permission_store) | **POST** /api/v1/permissions | Permission@store
[**permission_update**](PermissionApi.md#permission_update) | **PATCH** /api/v1/permissions/{id} | Permission@update



## permission_destroy

> models::AffiliationDestroy200Response permission_destroy(id)
Permission@destroy

Delete a Permission entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Permission entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## permission_index

> models::PermissionIndex200Response permission_index()
Permission@index

Return a list of Permissions

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::PermissionIndex200Response**](permissionIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## permission_show

> models::PermissionIndex200Response permission_show(id)
Permission@show

Return a Permission entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Permission entry ID | [required] |

### Return type

[**models::PermissionIndex200Response**](permissionIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## permission_store

> models::AccreditationStoreByRegistryId201Response permission_store(permission_store_request)
Permission@store

Create a Permission entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**permission_store_request** | [**PermissionStoreRequest**](PermissionStoreRequest.md) | Permission definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## permission_update

> models::PermissionUpdate200Response permission_update(id, permission_store_request)
Permission@update

Update a Permission entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Permission entry ID | [required] |
**permission_store_request** | [**PermissionStoreRequest**](PermissionStoreRequest.md) | Permission definition | [required] |

### Return type

[**models::PermissionUpdate200Response**](permissionUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


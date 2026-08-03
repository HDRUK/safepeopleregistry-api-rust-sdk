# \IdentityApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**identity_destroy**](IdentityApi.md#identity_destroy) | **DELETE** /api/v1/identities/{id} | Identity@destroy
[**identity_index**](IdentityApi.md#identity_index) | **GET** /api/v1/identities | Identity@index
[**identity_show**](IdentityApi.md#identity_show) | **GET** /api/v1/identities/{id} | Identity@show
[**identity_store**](IdentityApi.md#identity_store) | **POST** /api/v1/identities | Identity@store
[**identity_update**](IdentityApi.md#identity_update) | **PUT** /api/v1/identities/{id} | Identity@update



## identity_destroy

> models::AffiliationDestroy200Response identity_destroy(id)
Identity@destroy

Delete an Identity entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Identity entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## identity_index

> models::IdentityIndex200Response identity_index()
Identity@index

Return a list of Identity entries

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::IdentityIndex200Response**](identityIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## identity_show

> models::IdentityIndex200Response identity_show(id)
Identity@show

Return an Identity entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Identity ID | [required] |

### Return type

[**models::IdentityIndex200Response**](identityIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## identity_store

> models::IdentityStore201Response identity_store(identity_store_request)
Identity@store

Create a Identity entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**identity_store_request** | [**IdentityStoreRequest**](IdentityStoreRequest.md) | Identity definition | [required] |

### Return type

[**models::IdentityStore201Response**](identityStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## identity_update

> models::IdentityUpdate200Response identity_update(id, identity_store_request)
Identity@update

Update a Identity entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Identity entry ID | [required] |
**identity_store_request** | [**IdentityStoreRequest**](IdentityStoreRequest.md) | Identity definition | [required] |

### Return type

[**models::IdentityUpdate200Response**](identityUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \RegistryApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**registry_destroy**](RegistryApi.md#registry_destroy) | **DELETE** /api/v1/registry/{id} | Registry@destroy
[**registry_index**](RegistryApi.md#registry_index) | **GET** /api/v1/registry | Registry@index
[**registry_show**](RegistryApi.md#registry_show) | **GET** /api/v1/registry/{id} | Registry@show
[**registry_store**](RegistryApi.md#registry_store) | **POST** /api/v1/registry | Registry@store
[**registry_update**](RegistryApi.md#registry_update) | **PUT** /api/v1/registry/{id} | Registry@update



## registry_destroy

> models::AffiliationDestroy200Response registry_destroy(id)
Registry@destroy

Delete a Registry entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Registry entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## registry_index

> models::RegistryIndex200Response registry_index()
Registry@index

Return a list of Registry entries

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::RegistryIndex200Response**](registryIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## registry_show

> models::RegistryIndex200Response registry_show(id)
Registry@show

Return a Registry entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Registry entry ID | [required] |

### Return type

[**models::RegistryIndex200Response**](registryIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## registry_store

> models::AccreditationStoreByRegistryId201Response registry_store(registry)
Registry@store

Create a Registry entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry** | [**Registry**](Registry.md) | Registry definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## registry_update

> models::RegistryUpdate200Response registry_update(id, registry)
Registry@update

Update a Registry entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Registry entry ID | [required] |
**registry** | [**Registry**](Registry.md) | Registry definition | [required] |

### Return type

[**models::RegistryUpdate200Response**](registryUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


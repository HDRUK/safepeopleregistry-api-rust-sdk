# \ResolutionApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**resolution_index_by_registry_id**](ResolutionApi.md#resolution_index_by_registry_id) | **GET** /api/v1/registries/{registryId}/resolutions | Get resolutions by registry ID
[**resolution_store_by_registry_id**](ResolutionApi.md#resolution_store_by_registry_id) | **POST** /api/v1/registries/{registryId}/resolutions | Create a new resolution for a registry



## resolution_index_by_registry_id

> Vec<models::Resolution> resolution_index_by_registry_id(registry_id)
Get resolutions by registry ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |

### Return type

[**Vec<models::Resolution>**](Resolution.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## resolution_store_by_registry_id

> models::AccreditationStoreByRegistryId201Response resolution_store_by_registry_id(registry_id, resolution)
Create a new resolution for a registry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**resolution** | [**Resolution**](Resolution.md) |  | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


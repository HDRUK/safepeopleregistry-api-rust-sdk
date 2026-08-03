# \EducationApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**education_destroy_by_registry_id**](EducationApi.md#education_destroy_by_registry_id) | **DELETE** /api/v1/registries/{registryId}/educations/{id} | Delete an education record
[**education_index_by_registry_id**](EducationApi.md#education_index_by_registry_id) | **GET** /api/v1/educations/registries/{registryId} | Get education records by registry ID
[**education_show_by_registry_id**](EducationApi.md#education_show_by_registry_id) | **GET** /api/v1/educations/{id}/registries/{registryId} | Get a specific education record by ID and registry ID
[**education_store_by_registry_id**](EducationApi.md#education_store_by_registry_id) | **POST** /api/v1/registries/{registryId}/educations | Create a new education record for a registry
[**education_update_by_registry_id**](EducationApi.md#education_update_by_registry_id) | **PUT** /api/v1/registries/{registryId}/educations/{id} | Update an existing education record



## education_destroy_by_registry_id

> models::EducationDestroyByRegistryId200Response education_destroy_by_registry_id(registry_id, id)
Delete an education record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**id** | **i32** | ID of the education record | [required] |

### Return type

[**models::EducationDestroyByRegistryId200Response**](educationDestroyByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## education_index_by_registry_id

> Vec<models::Education> education_index_by_registry_id(registry_id)
Get education records by registry ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |

### Return type

[**Vec<models::Education>**](Education.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## education_show_by_registry_id

> models::Education education_show_by_registry_id(registry_id, id)
Get a specific education record by ID and registry ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**id** | **i32** | ID of the education record | [required] |

### Return type

[**models::Education**](Education.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## education_store_by_registry_id

> models::AccreditationStoreByRegistryId201Response education_store_by_registry_id(registry_id, education)
Create a new education record for a registry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**education** | [**Education**](Education.md) |  | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## education_update_by_registry_id

> models::Education education_update_by_registry_id(registry_id, id, education)
Update an existing education record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**id** | **i32** | ID of the education record | [required] |
**education** | [**Education**](Education.md) |  | [required] |

### Return type

[**models::Education**](Education.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


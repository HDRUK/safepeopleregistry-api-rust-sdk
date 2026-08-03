# \AccreditationApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accreditation_index_by_registry_id**](AccreditationApi.md#accreditation_index_by_registry_id) | **GET** /api/v1/accreditations/{registryId} | Get accreditations by registry ID
[**accreditation_store_by_registry_id**](AccreditationApi.md#accreditation_store_by_registry_id) | **POST** /api/v1/accreditations/{registryId} | Create accreditation for a registry
[**accreditation_update_by_registry_id**](AccreditationApi.md#accreditation_update_by_registry_id) | **PUT** /api/v1/accreditations/{id}/registries/{registryId} | Update accreditation for a registry



## accreditation_index_by_registry_id

> models::AccreditationIndexByRegistryId200Response accreditation_index_by_registry_id(registry_id)
Get accreditations by registry ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |

### Return type

[**models::AccreditationIndexByRegistryId200Response**](accreditationIndexByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## accreditation_store_by_registry_id

> models::AccreditationStoreByRegistryId201Response accreditation_store_by_registry_id(registry_id, accreditation)
Create accreditation for a registry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**accreditation** | [**Accreditation**](Accreditation.md) |  | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## accreditation_update_by_registry_id

> models::AccreditationUpdateByRegistryId200Response accreditation_update_by_registry_id(registry_id, id, accreditation)
Update accreditation for a registry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | ID of the registry | [required] |
**id** | **i32** | ID of the accreditation | [required] |
**accreditation** | [**Accreditation**](Accreditation.md) |  | [required] |

### Return type

[**models::AccreditationUpdateByRegistryId200Response**](accreditationUpdateByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \FilesApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**files_download**](FilesApi.md#files_download) | **GET** /api/v1/files/{id}/download | Download an uploaded file
[**files_show**](FilesApi.md#files_show) | **GET** /api/v1/files/{id} | Files@show
[**files_store**](FilesApi.md#files_store) | **POST** /api/v1/files | Files@store



## files_download

> std::path::PathBuf files_download(id)
Download an uploaded file

Downloads the specified file

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | File ID | [required] |

### Return type

[**std::path::PathBuf**](std::path::PathBuf.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## files_show

> models::FilesShow200Response files_show(id)
Files@show

Gets an uploaded file

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | File ID | [required] |

### Return type

[**models::FilesShow200Response**](filesShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## files_store

> models::AccreditationStoreByRegistryId201Response files_store(registry_id, file, file_type, entity_type)
Files@store

Uploads a file to the registry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | Option<**i32**> |  |  |
**file** | Option<**std::path::PathBuf**> |  |  |
**file_type** | Option<**String**> |  |  |
**entity_type** | Option<**String**> |  |  |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


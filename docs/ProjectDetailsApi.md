# \ProjectDetailsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_details_destroy**](ProjectDetailsApi.md#project_details_destroy) | **DELETE** /api/v1/project_details/{id} | ProjectDetails@destroy
[**project_details_store**](ProjectDetailsApi.md#project_details_store) | **POST** /api/v1/project_details | ProjectDetails@store
[**project_details_update**](ProjectDetailsApi.md#project_details_update) | **PUT** /api/v1/project_details/{id} | ProjectDetails@update



## project_details_destroy

> models::AffiliationDestroy200Response project_details_destroy(id)
ProjectDetails@destroy

Delete a ProjectDetail entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ProjectDetails entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_details_store

> models::IdentityStore201Response project_details_store(project_detail)
ProjectDetails@store

Create a ProjectDetail

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**project_detail** | [**ProjectDetail**](ProjectDetail.md) | ProjectDetail definition | [required] |

### Return type

[**models::IdentityStore201Response**](identityStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_details_update

> models::ProjectDetailsUpdate200Response project_details_update(id, project_detail)
ProjectDetails@update

Update a ProjectDetail entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ProjectDetails entry ID | [required] |
**project_detail** | [**ProjectDetail**](ProjectDetail.md) | ProjectDetails definition | [required] |

### Return type

[**models::ProjectDetailsUpdate200Response**](projectDetailsUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


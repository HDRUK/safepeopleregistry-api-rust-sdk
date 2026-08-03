# \ProjectsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**projects_delete**](ProjectsApi.md#projects_delete) | **DELETE** /api/v1/project_users/{id} | ProjectHasUser@delete
[**projects_get_validated_projects**](ProjectsApi.md#projects_get_validated_projects) | **GET** /api/v1/projects/user/{registryId}/validated | Project@getValidatedProjects



## projects_delete

> projects_delete(id)
ProjectHasUser@delete

Delete a user from a project

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID | [required] |

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## projects_get_validated_projects

> models::OrganisationGetProjects200Response projects_get_validated_projects(registry_id)
Project@getValidatedProjects

Return (approved) projects for a registry (user)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | Registry ID | [required] |

### Return type

[**models::OrganisationGetProjects200Response**](organisationGetProjects_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


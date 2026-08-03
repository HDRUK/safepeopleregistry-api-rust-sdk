# \ProjectHasOrganisationApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_has_organisation_show**](ProjectHasOrganisationApi.md#project_has_organisation_show) | **GET** /api/v1/project-organisations/{projectOrganisationId} | Get details of a project-organisation relationship



## project_has_organisation_show

> models::ProjectHasOrganisation project_has_organisation_show(project_organisation_id)
Get details of a project-organisation relationship

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**project_organisation_id** | **i32** | ID of the project-organisation relationship | [required] |

### Return type

[**models::ProjectHasOrganisation**](ProjectHasOrganisation.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


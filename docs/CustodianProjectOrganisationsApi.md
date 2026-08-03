# \CustodianProjectOrganisationsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_project_organisations_get_workflow_states**](CustodianProjectOrganisationsApi.md#custodian_project_organisations_get_workflow_states) | **GET** /api/v1/custodian_approvals/projectOrganisations/getWorkflowStates | Get all workflow states for custodian project organisation approvals
[**custodian_project_organisations_index**](CustodianProjectOrganisationsApi.md#custodian_project_organisations_index) | **GET** /api/v1/custodian_approvals/{custodianId}/projectOrganisations | List all project organisations associated with a custodian
[**custodian_project_organisations_show**](CustodianProjectOrganisationsApi.md#custodian_project_organisations_show) | **GET** /api/v1/custodian_approvals/{custodianId}/projectOrganisations/{projectOrganisationId} | Get custodian approval for a project organisation
[**custodian_project_organisations_update**](CustodianProjectOrganisationsApi.md#custodian_project_organisations_update) | **PUT** /api/v1/custodian_approvals/{custodianId}/projectOrganisations/{projectOrganisationId} | Update custodian approval for a project organisation



## custodian_project_organisations_get_workflow_states

> models::CustodianProjectOrganisationsGetWorkflowStates200Response custodian_project_organisations_get_workflow_states()
Get all workflow states for custodian project organisation approvals

Returns a list of all possible workflow states

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CustodianProjectOrganisationsGetWorkflowStates200Response**](custodianProjectOrganisationsGetWorkflowStates_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_project_organisations_index

> models::CustodianProjectOrganisationsIndex200Response custodian_project_organisations_index(custodian_id)
List all project organisations associated with a custodian

Returns a list of all custodian project organisation approvals for a specific custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |

### Return type

[**models::CustodianProjectOrganisationsIndex200Response**](custodianProjectOrganisationsIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_project_organisations_show

> models::CustodianProjectOrganisationsShow200Response custodian_project_organisations_show(custodian_id, project_organisation_id)
Get custodian approval for a project organisation

Returns custodian approval details for a specific project organisation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**project_organisation_id** | **i32** | ID of the project organisation | [required] |

### Return type

[**models::CustodianProjectOrganisationsShow200Response**](custodianProjectOrganisationsShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_project_organisations_update

> models::CustodianProjectOrganisationsShow200Response custodian_project_organisations_update(custodian_id, project_organisation_id, custodian_project_organisations_update_request)
Update custodian approval for a project organisation

Updates approval status and/or comment for a project organisation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**project_organisation_id** | **i32** | ID of the project organisation | [required] |
**custodian_project_organisations_update_request** | [**CustodianProjectOrganisationsUpdateRequest**](CustodianProjectOrganisationsUpdateRequest.md) |  | [required] |

### Return type

[**models::CustodianProjectOrganisationsShow200Response**](custodianProjectOrganisationsShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


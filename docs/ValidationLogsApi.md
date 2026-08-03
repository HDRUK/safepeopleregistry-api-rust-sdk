# \ValidationLogsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**validation_logs_get_custodian_organisation_validation_logs**](ValidationLogsApi.md#validation_logs_get_custodian_organisation_validation_logs) | **GET** /api/v1/custodians/{custodianId}/organisation/{organisationId}/validation_logs | Get Validation Logs for Custodian and Organisation
[**validation_logs_get_custodian_project_user_validation_logs**](ValidationLogsApi.md#validation_logs_get_custodian_project_user_validation_logs) | **GET** /api/v1/custodians/{custodianId}/projects/{projectId}/registries/{registryId}/validation_logs | Get Validation Logs for Custodian, Project, and Registry
[**validation_logs_update**](ValidationLogsApi.md#validation_logs_update) | **PUT** /api/v1/validation_logs/{id} | Update a Validation Log
[**validation_logs_update_custodian_validation_logs**](ValidationLogsApi.md#validation_logs_update_custodian_validation_logs) | **PUT** /api/v1/custodians/{custodianId}/validation_Logs | Enable or Disable All Validation Logs for a Custodian Across Projects/Registries



## validation_logs_get_custodian_organisation_validation_logs

> models::ValidationLogsGetCustodianProjectUserValidationLogs200Response validation_logs_get_custodian_organisation_validation_logs(custodian_id, organisation_id, show_disabled)
Get Validation Logs for Custodian and Organisation

Retrieve validation logs associated with a given custodian and organisation.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | The ID of the custodian entity | [required] |
**organisation_id** | **i32** | The ID of the organisation entity | [required] |
**show_disabled** | Option<**bool**> | Whether to include disabled validation logs |  |

### Return type

[**models::ValidationLogsGetCustodianProjectUserValidationLogs200Response**](validationLogsGetCustodianProjectUserValidationLogs_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_logs_get_custodian_project_user_validation_logs

> models::ValidationLogsGetCustodianProjectUserValidationLogs200Response validation_logs_get_custodian_project_user_validation_logs(custodian_id, project_id, registry_id)
Get Validation Logs for Custodian, Project, and Registry

Retrieve validation logs associated with a given custodian, project, and registry.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | The ID of the custodian entity | [required] |
**project_id** | **i32** | The ID of the project entity | [required] |
**registry_id** | **i32** | The ID of the registry entity | [required] |

### Return type

[**models::ValidationLogsGetCustodianProjectUserValidationLogs200Response**](validationLogsGetCustodianProjectUserValidationLogs_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_logs_update

> models::ValidationLogsUpdate200Response validation_logs_update(id, validation_logs_update_request)
Update a Validation Log

Update a validation log entry, including marking it as complete, incomplete, passed, or failed.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | The ID of the validation log entry | [required] |
**validation_logs_update_request** | Option<[**ValidationLogsUpdateRequest**](ValidationLogsUpdateRequest.md)> |  |  |

### Return type

[**models::ValidationLogsUpdate200Response**](validationLogsUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_logs_update_custodian_validation_logs

> models::ValidationLogsUpdateCustodianValidationLogs200Response validation_logs_update_custodian_validation_logs(custodian_id, validation_logs_update_custodian_validation_logs_request)
Enable or Disable All Validation Logs for a Custodian Across Projects/Registries

Bulk update the enabled flag for all validation logs tied to a custodian and any project/registry.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | The ID of the custodian entity | [required] |
**validation_logs_update_custodian_validation_logs_request** | [**ValidationLogsUpdateCustodianValidationLogsRequest**](ValidationLogsUpdateCustodianValidationLogsRequest.md) |  | [required] |

### Return type

[**models::ValidationLogsUpdateCustodianValidationLogs200Response**](validationLogsUpdateCustodianValidationLogs_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


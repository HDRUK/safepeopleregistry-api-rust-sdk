# \ActionLogsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**action_logs_get_entity_action_log**](ActionLogsApi.md#action_logs_get_entity_action_log) | **GET** /api/v1/{entity}/{id}/action_log | Get Action Logs for an Entity
[**action_logs_update**](ActionLogsApi.md#action_logs_update) | **PUT** /api/v1/action_logs/{id} | Update an Action Log



## action_logs_get_entity_action_log

> models::ActionLogsGetEntityActionLog200Response action_logs_get_entity_action_log(entity, id)
Get Action Logs for an Entity

Retrieve action logs for a given entity type (users, organisations) by ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**entity** | **String** | The entity type (e.g., users, organisations) | [required] |
**id** | **i32** | The ID of the entity | [required] |

### Return type

[**models::ActionLogsGetEntityActionLog200Response**](actionLogsGetEntityActionLog_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## action_logs_update

> models::ActionLogsUpdate200Response action_logs_update(id, complete, incomplete)
Update an Action Log

Update an action log entry, including marking it as complete or incomplete.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the action log | [required] |
**complete** | Option<**bool**> | Mark as complete |  |
**incomplete** | Option<**bool**> | Mark as incomplete |  |

### Return type

[**models::ActionLogsUpdate200Response**](actionLogsUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


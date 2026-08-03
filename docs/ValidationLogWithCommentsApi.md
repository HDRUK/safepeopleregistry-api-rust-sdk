# \ValidationLogWithCommentsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**validation_log_with_comments_index**](ValidationLogWithCommentsApi.md#validation_log_with_comments_index) | **GET** /api/v1/validation_logs/{id} | Get  a Validation Log



## validation_log_with_comments_index

> Vec<models::ValidationLog> validation_log_with_comments_index(id)
Get  a Validation Log

Retrieve a specific entry for a validation log .

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | The ID of the validation log | [required] |

### Return type

[**Vec<models::ValidationLog>**](ValidationLog.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


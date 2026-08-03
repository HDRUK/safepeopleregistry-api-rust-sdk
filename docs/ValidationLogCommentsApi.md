# \ValidationLogCommentsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**validation_log_comments_comments**](ValidationLogCommentsApi.md#validation_log_comments_comments) | **GET** /api/v1/validation_logs/{id}/comments | Get all comments for a Validation Log
[**validation_log_comments_destroy**](ValidationLogCommentsApi.md#validation_log_comments_destroy) | **DELETE** /api/v1/validation_log_comments/{id} | Delete a validation log comment
[**validation_log_comments_show**](ValidationLogCommentsApi.md#validation_log_comments_show) | **GET** /api/v1/validation_log_comments/{id} | Get a single validation log comment
[**validation_log_comments_store**](ValidationLogCommentsApi.md#validation_log_comments_store) | **POST** /api/v1/validation_log_comments | Create a new validation log comment
[**validation_log_comments_update**](ValidationLogCommentsApi.md#validation_log_comments_update) | **PUT** /api/v1/validation_log_comments/{id} | Update a validation log comment



## validation_log_comments_comments

> Vec<models::ValidationLog> validation_log_comments_comments(id)
Get all comments for a Validation Log

Retrieve all comments associated with a specific validation log entry.

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


## validation_log_comments_destroy

> models::ValidationLogCommentsDestroy200Response validation_log_comments_destroy(id)
Delete a validation log comment

Remove a comment from the validation logs.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | The ID of the comment | [required] |

### Return type

[**models::ValidationLogCommentsDestroy200Response**](validationLogCommentsDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_log_comments_show

> models::ValidationLogComment validation_log_comments_show(id)
Get a single validation log comment

Retrieve a specific validation log comment by ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | The ID of the comment | [required] |

### Return type

[**models::ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_log_comments_store

> models::ValidationLogComment validation_log_comments_store(validation_log_comments_store_request)
Create a new validation log comment

Add a new comment to a validation log.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**validation_log_comments_store_request** | [**ValidationLogCommentsStoreRequest**](ValidationLogCommentsStoreRequest.md) |  | [required] |

### Return type

[**models::ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_log_comments_update

> models::ValidationLogComment validation_log_comments_update(id, validation_log_comments_update_request)
Update a validation log comment

Edit an existing validation log comment.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | The ID of the comment | [required] |
**validation_log_comments_update_request** | [**ValidationLogCommentsUpdateRequest**](ValidationLogCommentsUpdateRequest.md) |  | [required] |

### Return type

[**models::ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


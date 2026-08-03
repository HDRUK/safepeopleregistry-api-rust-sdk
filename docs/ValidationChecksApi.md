# \ValidationChecksApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**validation_checks_destroy**](ValidationChecksApi.md#validation_checks_destroy) | **DELETE** /api/v1/validation_checks/{id} | Delete a validation check
[**validation_checks_index**](ValidationChecksApi.md#validation_checks_index) | **GET** /api/v1/validation_checks | List all validation checks
[**validation_checks_show**](ValidationChecksApi.md#validation_checks_show) | **GET** /api/v1/validation_checks/{id} | Get a single validation check
[**validation_checks_store**](ValidationChecksApi.md#validation_checks_store) | **POST** /api/v1/validation_checks | Create a new validation check
[**validation_checks_update**](ValidationChecksApi.md#validation_checks_update) | **PUT** /api/v1/validation_checks/{id} | Update a validation check



## validation_checks_destroy

> models::ValidationChecksDestroy200Response validation_checks_destroy(id)
Delete a validation check

Remove a validation check.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the validation check | [required] |

### Return type

[**models::ValidationChecksDestroy200Response**](validationChecksDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_checks_index

> Vec<models::ValidationCheck> validation_checks_index()
List all validation checks

Retrieve all validation checks.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::ValidationCheck>**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_checks_show

> models::ValidationCheck validation_checks_show(id)
Get a single validation check

Retrieve a specific validation check by ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the validation check | [required] |

### Return type

[**models::ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_checks_store

> models::ValidationCheck validation_checks_store(validation_checks_store_request)
Create a new validation check

Create a new validation check entry.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**validation_checks_store_request** | [**ValidationChecksStoreRequest**](ValidationChecksStoreRequest.md) |  | [required] |

### Return type

[**models::ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## validation_checks_update

> models::ValidationCheck validation_checks_update(id, validation_checks_store_request)
Update a validation check

Edit an existing validation check.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the validation check | [required] |
**validation_checks_store_request** | [**ValidationChecksStoreRequest**](ValidationChecksStoreRequest.md) |  | [required] |

### Return type

[**models::ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


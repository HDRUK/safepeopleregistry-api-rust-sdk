# \ProjectUserApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_user_show**](ProjectUserApi.md#project_user_show) | **GET** /api/v1/project_users/{id} | Get project user details



## project_user_show

> models::CustodianProjectUsersShow200Response project_user_show(id)
Get project user details

Returns details for a specific project user

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the project user | [required] |

### Return type

[**models::CustodianProjectUsersShow200Response**](custodianProjectUsersShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


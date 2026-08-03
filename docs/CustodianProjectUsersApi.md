# \CustodianProjectUsersApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_project_users_index**](CustodianProjectUsersApi.md#custodian_project_users_index) | **GET** /api/v1/custodian_approvals/{custodianId}/projectUsers | List all project users associated with a custodian
[**custodian_project_users_show**](CustodianProjectUsersApi.md#custodian_project_users_show) | **GET** /api/v1/custodian_approvals/{custodianId}/projectUsers/{projectUserId} | Get custodian approval for a project user
[**custodian_project_users_update**](CustodianProjectUsersApi.md#custodian_project_users_update) | **PUT** /api/v1/custodian_approvals/{custodianId}/projectUsers/{projectUserId} | Update custodian approval for a project user



## custodian_project_users_index

> models::CustodianProjectUsersIndex200Response custodian_project_users_index(custodian_id)
List all project users associated with a custodian

Returns a list of all custodian project user approvals for a specific custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |

### Return type

[**models::CustodianProjectUsersIndex200Response**](custodianProjectUsersIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_project_users_show

> models::CustodianProjectUsersShow200Response custodian_project_users_show(custodian_id, project_user_id)
Get custodian approval for a project user

Returns custodian approval details for a specific project user

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**project_user_id** | **i32** | ID of the project user | [required] |

### Return type

[**models::CustodianProjectUsersShow200Response**](custodianProjectUsersShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_project_users_update

> models::CustodianProjectUsersShow200Response custodian_project_users_update(custodian_id, project_user_id, custodian_project_users_update_request)
Update custodian approval for a project user

Updates approval status and/or comment for a project user

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**project_user_id** | **i32** | ID of the project user | [required] |
**custodian_project_users_update_request** | [**CustodianProjectUsersUpdateRequest**](CustodianProjectUsersUpdateRequest.md) |  | [required] |

### Return type

[**models::CustodianProjectUsersShow200Response**](custodianProjectUsersShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \UsersApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**users_store**](UsersApi.md#users_store) | **POST** /api/v1/users | Users@store



## users_store

> models::UsersStore201Response users_store(users_store_request)
Users@store

Create a User entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**users_store_request** | [**UsersStoreRequest**](UsersStoreRequest.md) | User definition | [required] |

### Return type

[**models::UsersStore201Response**](usersStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


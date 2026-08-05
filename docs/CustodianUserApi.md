# \CustodianUserApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_user_bulk_store**](CustodianUserApi.md#custodian_user_bulk_store) | **POST** /api/v1/custodian_users/bulk | Create multiple CustodianUser entries



## custodian_user_bulk_store

> models::CustodianUserBulkStore201Response custodian_user_bulk_store(custodian_user_bulk_store_request)
Create multiple CustodianUser entries

Create multiple CustodianUser entries

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_user_bulk_store_request** | [**CustodianUserBulkStoreRequest**](CustodianUserBulkStoreRequest.md) | Array of CustodianUser definitions | [required] |

### Return type

[**models::CustodianUserBulkStore201Response**](custodianUserBulkStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


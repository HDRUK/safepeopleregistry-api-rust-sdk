# \QueryApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**query_query**](QueryApi.md#query_query) | **POST** /api/v1/query | Query@query



## query_query

> models::QueryQuery200Response query_query(x_client_id, query_query_request)
Query@query

Query the registry by Digital Identifier

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**x_client_id** | **String** | Custodian client ID used to authenticate the requesting custodian | [required] |
**query_query_request** | [**QueryQueryRequest**](QueryQueryRequest.md) | Query definition | [required] |

### Return type

[**models::QueryQuery200Response**](queryQuery_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


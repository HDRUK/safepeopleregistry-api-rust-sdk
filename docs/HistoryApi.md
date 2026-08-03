# \HistoryApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**history_index**](HistoryApi.md#history_index) | **GET** /api/v1/histories | History@index
[**history_show**](HistoryApi.md#history_show) | **GET** /api/v1/histories/{id} | History@show
[**history_store**](HistoryApi.md#history_store) | **POST** /api/v1/histories | History@store



## history_index

> models::HistoryIndex200Response history_index()
History@index

Return a list of Histories

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::HistoryIndex200Response**](historyIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## history_show

> models::HistoryIndex200Response history_show(id)
History@show

Return a History entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | History entry ID | [required] |

### Return type

[**models::HistoryIndex200Response**](historyIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## history_store

> models::HistoryStore201Response history_store(history_store_request)
History@store

Create a History entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**history_store_request** | [**HistoryStoreRequest**](HistoryStoreRequest.md) | History definition | [required] |

### Return type

[**models::HistoryStore201Response**](historyStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


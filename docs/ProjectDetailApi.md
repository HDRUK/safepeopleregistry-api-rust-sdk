# \ProjectDetailApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_detail_index**](ProjectDetailApi.md#project_detail_index) | **GET** /api/v1/project_details | ProjectDetail@index
[**project_detail_show**](ProjectDetailApi.md#project_detail_show) | **GET** /api/v1/project_details/{id} | ProjectDetail@show



## project_detail_index

> models::ProjectDetailIndex200Response project_detail_index()
ProjectDetail@index

Return a list of ProjectDetail

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ProjectDetailIndex200Response**](projectDetailIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_detail_show

> models::ProjectDetailIndex200Response project_detail_show(id)
ProjectDetail@show

Return a ProjectDetail

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ProjectDetail entry ID | [required] |

### Return type

[**models::ProjectDetailIndex200Response**](projectDetailIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


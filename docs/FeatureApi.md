# \FeatureApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**feature_index**](FeatureApi.md#feature_index) | **GET** /api/v1/features | Feature@index
[**feature_show**](FeatureApi.md#feature_show) | **GET** /api/v1/features/{featureId} | Feature@show
[**feature_toggle_by_feature_id**](FeatureApi.md#feature_toggle_by_feature_id) | **PUT** /api/v1/features/{featureId}/toggle | Feature@show



## feature_index

> models::FeatureIndex200Response feature_index()
Feature@index

Return a list of Feature entries

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::FeatureIndex200Response**](featureIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## feature_show

> models::FeatureIndex200Response feature_show(feature_id)
Feature@show

Return a Feature entry by its ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**feature_id** | **i32** | ID of the feature | [required] |

### Return type

[**models::FeatureIndex200Response**](featureIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## feature_toggle_by_feature_id

> models::FeatureIndex200Response feature_toggle_by_feature_id(feature_id)
Feature@show

Toggle and return a Feature entry by its ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**feature_id** | **i32** | ID of the feature | [required] |

### Return type

[**models::FeatureIndex200Response**](featureIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


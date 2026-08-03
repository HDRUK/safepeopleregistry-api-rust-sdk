# \AffiliationApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**affiliation_destroy**](AffiliationApi.md#affiliation_destroy) | **DELETE** /api/v1/training/{id} | Affiliation@destroy



## affiliation_destroy

> models::AffiliationDestroy200Response affiliation_destroy(id)
Affiliation@destroy

Delete a affiliation entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Affiliation entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


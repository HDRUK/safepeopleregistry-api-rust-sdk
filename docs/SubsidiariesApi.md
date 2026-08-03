# \SubsidiariesApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**subsidiaries_destroy**](SubsidiariesApi.md#subsidiaries_destroy) | **DELETE** /api/v1/subsidiaries/{subsidiaryId}/organisations/{organisationId} | subsidiaries@destroy
[**subsidiaries_store**](SubsidiariesApi.md#subsidiaries_store) | **POST** /api/v1/subsidiaries/organisations/{organisationId} | subsidiaries@store
[**subsidiaries_update**](SubsidiariesApi.md#subsidiaries_update) | **PUT** /api/v1/subsidiaries/{subsidiaryId}/organisations/{organisationId} | subsidiaries@update



## subsidiaries_destroy

> models::AffiliationDestroy200Response subsidiaries_destroy(organisation_id, subsidiary_id)
subsidiaries@destroy

Delete an subsidiary entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**organisation_id** | **i32** | organisations entry ID | [required] |
**subsidiary_id** | **i32** | subsidiary entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subsidiaries_store

> models::SubsidiariesStore201Response subsidiaries_store(organisation_id, subsidiary)
subsidiaries@store

Create a subsidiary entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**organisation_id** | **i32** | organisations entry ID | [required] |
**subsidiary** | [**Subsidiary**](Subsidiary.md) | subsidiary definition | [required] |

### Return type

[**models::SubsidiariesStore201Response**](subsidiariesStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subsidiaries_update

> models::SubsidiariesStore201Response subsidiaries_update(organisation_id, subsidiary_id, subsidiary)
subsidiaries@update

Update a subsidiary entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**organisation_id** | **i32** | organisations entry ID | [required] |
**subsidiary_id** | **i32** | subsidiary entry ID | [required] |
**subsidiary** | [**Subsidiary**](Subsidiary.md) | subsidiary definition | [required] |

### Return type

[**models::SubsidiariesStore201Response**](subsidiariesStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


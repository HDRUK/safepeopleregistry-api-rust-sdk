# \ExperienceApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**experience_destroy**](ExperienceApi.md#experience_destroy) | **DELETE** /api/v1/experiences/{id} | Experience@destroy
[**experience_index**](ExperienceApi.md#experience_index) | **GET** /api/v1/experiences | Experience@index
[**experience_show**](ExperienceApi.md#experience_show) | **GET** /api/v1/experiences/{id} | Experience@show
[**experience_store**](ExperienceApi.md#experience_store) | **POST** /api/v1/experiences | Experience@store
[**experience_update**](ExperienceApi.md#experience_update) | **PUT** /api/v1/experiences/{id} | Experience@update



## experience_destroy

> models::AffiliationDestroy200Response experience_destroy(id)
Experience@destroy

Delete a Experience entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Experience entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## experience_index

> models::ExperienceIndex200Response experience_index()
Experience@index

Return a list of Experience entries

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ExperienceIndex200Response**](experienceIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## experience_show

> models::ExperienceShow200Response experience_show(id)
Experience@show

Return an Experience entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Experience entry ID | [required] |

### Return type

[**models::ExperienceShow200Response**](experienceShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## experience_store

> models::ExperienceStore201Response experience_store(experience_store_request)
Experience@store

Create an Experience entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**experience_store_request** | [**ExperienceStoreRequest**](ExperienceStoreRequest.md) | Experience definition | [required] |

### Return type

[**models::ExperienceStore201Response**](experienceStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## experience_update

> models::ExperienceUpdate200Response experience_update(id, experience_store_request)
Experience@update

Update an Experience entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Experience entry ID | [required] |
**experience_store_request** | [**ExperienceStoreRequest**](ExperienceStoreRequest.md) | Experience definition | [required] |

### Return type

[**models::ExperienceUpdate200Response**](experienceUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


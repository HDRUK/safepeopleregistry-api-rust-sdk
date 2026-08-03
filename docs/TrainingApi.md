# \TrainingApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**training_index**](TrainingApi.md#training_index) | **GET** /api/v1/training | Training@index
[**training_index_by_registry_id**](TrainingApi.md#training_index_by_registry_id) | **GET** /api/v1/training/registry/{id} | Training@show
[**training_show**](TrainingApi.md#training_show) | **GET** /api/v1/training/{id} | Training@show
[**training_store**](TrainingApi.md#training_store) | **POST** /api/v1/training | Training@store
[**training_update**](TrainingApi.md#training_update) | **PUT** /api/v1/training/{id} | Training@update



## training_index

> models::TrainingShow200Response training_index()
Training@index

Return a list of Training entries

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::TrainingShow200Response**](trainingShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## training_index_by_registry_id

> models::TrainingShow200Response training_index_by_registry_id(id)
Training@show

Return a list of training by registry id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Training registry id | [required] |

### Return type

[**models::TrainingShow200Response**](trainingShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## training_show

> models::TrainingShow200Response training_show(id)
Training@show

Return a training record by registry id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Training id | [required] |

### Return type

[**models::TrainingShow200Response**](trainingShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## training_store

> models::AccreditationStoreByRegistryId201Response training_store(training)
Training@store

Create a Training entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**training** | [**Training**](Training.md) | Training definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## training_update

> models::TrainingUpdate200Response training_update(id, training)
Training@update

Update a Training entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Training entry ID | [required] |
**training** | [**Training**](Training.md) | Training definition | [required] |

### Return type

[**models::TrainingUpdate200Response**](trainingUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


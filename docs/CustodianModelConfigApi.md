# \CustodianModelConfigApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_model_config_destroy**](CustodianModelConfigApi.md#custodian_model_config_destroy) | **DELETE** /api/v1/custodian_config/{id} | CustodianModelConfig@destroy
[**custodian_model_config_get_by_custodian_id**](CustodianModelConfigApi.md#custodian_model_config_get_by_custodian_id) | **GET** /api/v1/custodian_config/{id} | CustodianModelConfig@getByCustodianID
[**custodian_model_config_get_entity_models**](CustodianModelConfigApi.md#custodian_model_config_get_entity_models) | **GET** /api/v1/custodian_config/{custodianId}/entity_models | Get entity models for custodian config
[**custodian_model_config_store**](CustodianModelConfigApi.md#custodian_model_config_store) | **POST** /api/v1/custodian_config | CustodianModelConfig@store
[**custodian_model_config_update**](CustodianModelConfigApi.md#custodian_model_config_update) | **PUT** /api/v1/custodian_config/{id} | CustodianModelConfig@update
[**custodian_model_config_update_entity_models**](CustodianModelConfigApi.md#custodian_model_config_update_entity_models) | **PUT** /api/v1/custodian_config/{custodianId}/entity_models | Update a custodian's entity models



## custodian_model_config_destroy

> models::AffiliationDestroy200Response custodian_model_config_destroy(id)
CustodianModelConfig@destroy

Delete a CustodianModelConfig entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | CustodianModelConfig entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_model_config_get_by_custodian_id

> models::CustodianModelConfigGetByCustodianId200Response custodian_model_config_get_by_custodian_id(id)
CustodianModelConfig@getByCustodianID

Return a list of Custodian config

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | CustodianModelConfig entry ID | [required] |

### Return type

[**models::CustodianModelConfigGetByCustodianId200Response**](custodianModelConfigGetByCustodianID_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_model_config_get_entity_models

> models::CustodianModelConfigGetEntityModels200Response custodian_model_config_get_entity_models(custodian_id, entity_model_type)
Get entity models for custodian config

Retrieve entity models associated with custodian config based on the specified entity_model_type

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**entity_model_type** | **String** | Type of entity model to retrieve | [required] |

### Return type

[**models::CustodianModelConfigGetEntityModels200Response**](custodianModelConfigGetEntityModels_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_model_config_store

> models::CustodianModelConfigUpdate200Response custodian_model_config_store(custodian_model_config)
CustodianModelConfig@store

Create a CustodianModelConfig entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_model_config** | [**CustodianModelConfig**](CustodianModelConfig.md) | CustodianModelConfig definition | [required] |

### Return type

[**models::CustodianModelConfigUpdate200Response**](custodianModelConfigUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_model_config_update

> models::CustodianModelConfigUpdate200Response custodian_model_config_update(id, custodian_model_config)
CustodianModelConfig@update

Update an CustodianModelConfig entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | CustodianModelConfig entry ID | [required] |
**custodian_model_config** | [**CustodianModelConfig**](CustodianModelConfig.md) | CustodianModelConfig definition | [required] |

### Return type

[**models::CustodianModelConfigUpdate200Response**](custodianModelConfigUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_model_config_update_entity_models

> models::CustodianModelConfigUpdateEntityModels200Response custodian_model_config_update_entity_models(custodian_id, custodian_model_config_update_entity_models_request)
Update a custodian's entity models

Update the active status of specified custodian model configs for a given custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**custodian_model_config_update_entity_models_request** | [**CustodianModelConfigUpdateEntityModelsRequest**](CustodianModelConfigUpdateEntityModelsRequest.md) |  | [required] |

### Return type

[**models::CustodianModelConfigUpdateEntityModels200Response**](custodianModelConfigUpdateEntityModels_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


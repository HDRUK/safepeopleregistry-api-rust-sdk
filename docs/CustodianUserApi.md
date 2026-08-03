# \CustodianUserApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_user_bulk_store**](CustodianUserApi.md#custodian_user_bulk_store) | **POST** /api/v1/custodian_users/bulk | Create multiple CustodianUser entries
[**custodian_user_destroy**](CustodianUserApi.md#custodian_user_destroy) | **DELETE** /api/v1/custodian_users/{id} | CustodianUser@destroy
[**custodian_user_show**](CustodianUserApi.md#custodian_user_show) | **GET** /api/v1/custodian_users/{id} | CustodianUser@show
[**custodian_user_store**](CustodianUserApi.md#custodian_user_store) | **POST** /api/v1/custodian_users | CustodianUser@store
[**custodian_user_update**](CustodianUserApi.md#custodian_user_update) | **PUT** /api/v1/custodian_users | CustodianUser@update



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


## custodian_user_destroy

> models::AffiliationDestroy200Response custodian_user_destroy(id)
CustodianUser@destroy

Delete a CustodianUser entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | CustodianUser entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_user_show

> models::CustodianUserShow200Response custodian_user_show(id)
CustodianUser@show

Return a CustodianUser entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | CustodianUser entry ID | [required] |

### Return type

[**models::CustodianUserShow200Response**](custodianUserShow_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_user_store

> models::AccreditationStoreByRegistryId201Response custodian_user_store(custodian_user)
CustodianUser@store

Create a CustodianUser entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_user** | [**CustodianUser**](CustodianUser.md) | CustodianUser definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_user_update

> models::CustodianUserUpdate201Response custodian_user_update(custodian_user)
CustodianUser@update

Update a CustodianUser entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_user** | [**CustodianUser**](CustodianUser.md) | CustodianUser definition | [required] |

### Return type

[**models::CustodianUserUpdate201Response**](custodianUserUpdate_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


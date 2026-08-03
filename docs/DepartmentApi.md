# \DepartmentApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**department_destroy**](DepartmentApi.md#department_destroy) | **DELETE** /api/v1/departments/{id} | Delete a department
[**department_index**](DepartmentApi.md#department_index) | **GET** /api/v1/departments | Get a list of departments
[**department_show**](DepartmentApi.md#department_show) | **GET** /api/v1/departments/{id} | Get a specific department by ID
[**department_store**](DepartmentApi.md#department_store) | **POST** /api/v1/departments | Create a new department
[**department_update**](DepartmentApi.md#department_update) | **PUT** /api/v1/departments/{id} | Update an existing department



## department_destroy

> models::AffiliationDestroy200Response department_destroy(id)
Delete a department

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the department | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## department_index

> Vec<models::Department> department_index()
Get a list of departments

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::Department>**](Department.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## department_show

> models::Department department_show(id)
Get a specific department by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the department | [required] |

### Return type

[**models::Department**](Department.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## department_store

> models::AccreditationStoreByRegistryId201Response department_store(department)
Create a new department

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**department** | [**Department**](Department.md) |  | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## department_update

> models::Department department_update(id, department)
Update an existing department

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the department | [required] |
**department** | [**Department**](Department.md) |  | [required] |

### Return type

[**models::Department**](Department.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \ProjectRoleApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_role_index**](ProjectRoleApi.md#project_role_index) | **GET** /api/v1/project_roles | ProjectRole@index
[**project_role_show**](ProjectRoleApi.md#project_role_show) | **GET** /api/v1/project_roles/{id} | ProjectRole@show
[**project_role_store**](ProjectRoleApi.md#project_role_store) | **POST** /api/v1/project_roles | ProjectRole@store
[**project_role_update**](ProjectRoleApi.md#project_role_update) | **PUT** /api/v1/project_roles/{id} | ProjectRole@update



## project_role_index

> models::ProjectRoleIndex200Response project_role_index()
ProjectRole@index

Return a list of ProjectRole

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ProjectRoleIndex200Response**](projectRoleIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_role_show

> models::ProjectRoleIndex200Response project_role_show(id)
ProjectRole@show

Return a ProjectRole

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ProjectRole entry ID | [required] |

### Return type

[**models::ProjectRoleIndex200Response**](projectRoleIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_role_store

> models::IdentityStore201Response project_role_store(project_role)
ProjectRole@store

Create a ProjectRole

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**project_role** | [**ProjectRole**](ProjectRole.md) | ProjectRole definition | [required] |

### Return type

[**models::IdentityStore201Response**](identityStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_role_update

> models::ProjectRoleUpdate200Response project_role_update(id, project_role)
ProjectRole@update

Update a ProjectRole entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ProjectRole entry ID | [required] |
**project_role** | [**ProjectRole**](ProjectRole.md) | ProjectRole definition | [required] |

### Return type

[**models::ProjectRoleUpdate200Response**](projectRoleUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


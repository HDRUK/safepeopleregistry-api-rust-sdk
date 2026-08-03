# \CustodianApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_add_project**](CustodianApi.md#custodian_add_project) | **POST** /api/v1/custodians/{custodianId}/projects | Custodian@addProject
[**custodian_destroy**](CustodianApi.md#custodian_destroy) | **DELETE** /api/v1/custodians/{id} | Custodian@destroy
[**custodian_get_organisations**](CustodianApi.md#custodian_get_organisations) | **GET** /api/v1/custodian/{custodianId}/organisations | Return all custodian organisations with projects
[**custodian_get_projects**](CustodianApi.md#custodian_get_projects) | **GET** /api/v1/custodian/{custodianId}/projects | Return all projects associated with a custodian
[**custodian_get_projects_users**](CustodianApi.md#custodian_get_projects_users) | **GET** /api/v1/custodians/{custodianId}/projects_users | Get all users associated with custodian's projects
[**custodian_get_user_projects**](CustodianApi.md#custodian_get_user_projects) | **GET** /api/v1/custodian/{custodianId}/users/{userId}/projects | Return all custodian projects associated with a user
[**custodian_index**](CustodianApi.md#custodian_index) | **GET** /api/v1/custodians | Custodian@index
[**custodian_show**](CustodianApi.md#custodian_show) | **GET** /api/v1/custodians/{id} | Custodian@show
[**custodian_show_by_unique_identifier**](CustodianApi.md#custodian_show_by_unique_identifier) | **GET** /api/v1/custodians/identifier/{id} | Custodian@showByUniqueIdentifier
[**custodian_store**](CustodianApi.md#custodian_store) | **POST** /api/v1/custodians | Custodian@store
[**custodian_update**](CustodianApi.md#custodian_update) | **PUT** /api/v1/custodians/{id} | Custodian@update



## custodian_add_project

> models::CustodianAddProject201Response custodian_add_project(custodian_id, custodian_add_project_request)
Custodian@addProject

Create a project for a custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**custodian_add_project_request** | [**CustodianAddProjectRequest**](CustodianAddProjectRequest.md) | Project definition | [required] |

### Return type

[**models::CustodianAddProject201Response**](custodianAddProject_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_destroy

> models::AffiliationDestroy200Response custodian_destroy(id)
Custodian@destroy

Delete a Custodian entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Custodian entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_get_organisations

> models::CustodianGetOrganisations200Response custodian_get_organisations(custodian_id)
Return all custodian organisations with projects

Fetch a list of custodians organisations with projects, along with pagination details.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | The ID of the custodian whose organisations are to be retrieved | [required] |

### Return type

[**models::CustodianGetOrganisations200Response**](custodianGetOrganisations_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_get_projects

> models::CustodianGetProjects200Response custodian_get_projects(custodian_id)
Return all projects associated with a custodian

Fetch a list of projects along with pagination details for a specified custodian.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | The ID of the custodian whose projects are to be retrieved | [required] |

### Return type

[**models::CustodianGetProjects200Response**](custodianGetProjects_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_get_projects_users

> models::CustodianGetProjectsUsers200Response custodian_get_projects_users(custodian_id)
Get all users associated with custodian's projects

Returns paginated users for all projects under a specific custodian.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | Custodian ID | [required] |

### Return type

[**models::CustodianGetProjectsUsers200Response**](custodianGetProjectsUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_get_user_projects

> models::CustodianGetUserProjects200Response custodian_get_user_projects(custodian_id, user_id)
Return all custodian projects associated with a user

Fetch a list of custodians projects associated with a user, along with pagination details.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | The ID of the custodian whose projects are to be retrieved | [required] |
**user_id** | **i32** | The ID of the user whose projects are to be retrieved | [required] |

### Return type

[**models::CustodianGetUserProjects200Response**](custodianGetUserProjects_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_index

> models::CustodianIndex200Response custodian_index()
Custodian@index

Return a list of Custodians

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CustodianIndex200Response**](custodianIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_show

> models::CustodianIndex200Response custodian_show(id)
Custodian@show

Return an Custodian entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Custodian ID | [required] |

### Return type

[**models::CustodianIndex200Response**](custodianIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_show_by_unique_identifier

> models::CustodianIndex200Response custodian_show_by_unique_identifier(id)
Custodian@showByUniqueIdentifier

Return an Custodian entry by Unique Identifier

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **String** | Custodian Unique Identifier | [required] |

### Return type

[**models::CustodianIndex200Response**](custodianIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_store

> models::CustodianStore201Response custodian_store(custodian_store_request)
Custodian@store

Create a Custodian entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_store_request** | [**CustodianStoreRequest**](CustodianStoreRequest.md) | Custodian definition | [required] |

### Return type

[**models::CustodianStore201Response**](custodianStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodian_update

> models::CustodianStore201Response custodian_update(id, custodian_store_request)
Custodian@update

Edit a Custodian entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Custodian ID | [required] |
**custodian_store_request** | [**CustodianStoreRequest**](CustodianStoreRequest.md) | Custodian definition | [required] |

### Return type

[**models::CustodianStore201Response**](custodianStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


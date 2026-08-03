# \ProjectApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**project_destroy**](ProjectApi.md#project_destroy) | **DELETE** /api/v1/projects/{id} | Project@destroy
[**project_get_all_users_flag_project_by_user_id**](ProjectApi.md#project_get_all_users_flag_project_by_user_id) | **GET** /api/v1/projects/{projectId}/all_users/{userId} | Get all users by projectID and userID
[**project_get_project_by_id_and_organisation_id**](ProjectApi.md#project_get_project_by_id_and_organisation_id) | **GET** /api/v1/projects/{projectId}/organisations/{organisationId} | Get project details by projectID and organisationID
[**project_get_project_by_id_and_user_id**](ProjectApi.md#project_get_project_by_id_and_user_id) | **GET** /api/v1/projects/{projectId}/users/{userId} | Get project details by projectID and userID
[**project_get_project_users**](ProjectApi.md#project_get_project_users) | **GET** /api/v1/projects/{id}/users | Project@getProjectUsers
[**project_get_project_users_by_organisation_id**](ProjectApi.md#project_get_project_users_by_organisation_id) | **GET** /api/v1/projects/{projectId}/organisations/{organisationId}/users | Get all users by projectID and organisationID
[**project_index**](ProjectApi.md#project_index) | **GET** /api/v1/projects | Project@index
[**project_make_primary_contact**](ProjectApi.md#project_make_primary_contact) | **PUT** /api/v1/projects/{id}/users/{registryId}/primary_contact | Project@edit
[**project_show**](ProjectApi.md#project_show) | **GET** /api/v1/projects/{id} | Project@show
[**project_store**](ProjectApi.md#project_store) | **POST** /api/v1/projects | Project@store
[**project_update**](ProjectApi.md#project_update) | **PUT** /api/v1/projects/{id} | Project@update
[**project_update_all_project_users**](ProjectApi.md#project_update_all_project_users) | **PUT** /api/v1/projects/{id}/all_users | Project@updateAllProjectUsers



## project_destroy

> models::AffiliationDestroy200Response project_destroy(id)
Project@destroy

Delete a Project entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Project entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_get_all_users_flag_project_by_user_id

> models::ProjectGetAllUsersFlagProjectByUserId200Response project_get_all_users_flag_project_by_user_id(user_id, project_id)
Get all users by projectID and userID

Fetches users for a project.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**user_id** | **i32** | ID of the user | [required] |
**project_id** | **i32** | ID of the project | [required] |

### Return type

[**models::ProjectGetAllUsersFlagProjectByUserId200Response**](projectGetAllUsersFlagProjectByUserId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_get_project_by_id_and_organisation_id

> models::CustodiansGetOrganisationUsers200Response project_get_project_by_id_and_organisation_id(organisation_id, project_id)
Get project details by projectID and organisationID

Fetches project given organisation and project IDs.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**organisation_id** | **i32** | ID of the organisation | [required] |
**project_id** | **i32** | ID of the project | [required] |

### Return type

[**models::CustodiansGetOrganisationUsers200Response**](custodiansGetOrganisationUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_get_project_by_id_and_user_id

> models::ProjectGetProjectByIdAndUserId200Response project_get_project_by_id_and_user_id(user_id, project_id)
Get project details by projectID and userID

Fetches project given user and project IDs.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**user_id** | **i32** | ID of the user | [required] |
**project_id** | **i32** | ID of the project | [required] |

### Return type

[**models::ProjectGetProjectByIdAndUserId200Response**](projectGetProjectByIdAndUserId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_get_project_users

> models::ProjectGetProjectUsers200Response project_get_project_users(id)
Project@getProjectUsers

Return project users by project ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Project entry ID | [required] |

### Return type

[**models::ProjectGetProjectUsers200Response**](projectGetProjectUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_get_project_users_by_organisation_id

> models::CustodiansGetOrganisationUsers200Response project_get_project_users_by_organisation_id(organisation_id, project_id)
Get all users by projectID and organisationID

Fetches users given organisation and project IDs.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**organisation_id** | **i32** | ID of the organisation | [required] |
**project_id** | **i32** | ID of the project | [required] |

### Return type

[**models::CustodiansGetOrganisationUsers200Response**](custodiansGetOrganisationUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_index

> models::ProjectIndex200Response project_index()
Project@index

Return a list of Projects

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ProjectIndex200Response**](projectIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_make_primary_contact

> models::ProjectMakePrimaryContact200Response project_make_primary_contact(id, registry_id, project_make_primary_contact_request)
Project@edit

Make user a primary contact

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Project entry ID | [required] |
**registry_id** | **i32** | Registry ID | [required] |
**project_make_primary_contact_request** | [**ProjectMakePrimaryContactRequest**](ProjectMakePrimaryContactRequest.md) | Project definition | [required] |

### Return type

[**models::ProjectMakePrimaryContact200Response**](projectMakePrimaryContact_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_show

> models::ProjectIndex200Response project_show(id)
Project@show

Return a Project entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Project entry ID | [required] |

### Return type

[**models::ProjectIndex200Response**](projectIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_store

> models::AccreditationStoreByRegistryId201Response project_store(project_store_request)
Project@store

Create a Project entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**project_store_request** | [**ProjectStoreRequest**](ProjectStoreRequest.md) | Project definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_update

> models::ProjectUpdate200Response project_update(id, project_index200_response_data)
Project@update

Update a Project entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Project entry ID | [required] |
**project_index200_response_data** | [**ProjectIndex200ResponseData**](ProjectIndex200ResponseData.md) | Project definition | [required] |

### Return type

[**models::ProjectUpdate200Response**](projectUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## project_update_all_project_users

> models::ONsSubmissionReceiveCsv200Response project_update_all_project_users(id, project_update_all_project_users_request)
Project@updateAllProjectUsers

Update all users associated with a project

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Project entry ID | [required] |
**project_update_all_project_users_request** | [**ProjectUpdateAllProjectUsersRequest**](ProjectUpdateAllProjectUsersRequest.md) | Project definition | [required] |

### Return type

[**models::ONsSubmissionReceiveCsv200Response**](oNSSubmissionReceiveCSV_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


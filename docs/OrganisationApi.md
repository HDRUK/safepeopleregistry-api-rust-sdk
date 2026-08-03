# \OrganisationApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**organisation_get_delegates**](OrganisationApi.md#organisation_get_delegates) | **GET** /api/v1/organisations/{id}/delegates | Return all delegates associated with an organisation
[**organisation_get_projects**](OrganisationApi.md#organisation_get_projects) | **GET** /api/v1/organisations/{id}/projects | organisation@getProjects
[**organisation_get_sponsorships_projects**](OrganisationApi.md#organisation_get_sponsorships_projects) | **GET** /api/v1/organisations/{id}/projects/sponsorships | organisation@getSponsorshipsProjects
[**organisation_get_users**](OrganisationApi.md#organisation_get_users) | **GET** /api/v1/organisations/{id}/users | organisation@getUsers
[**organisation_index**](OrganisationApi.md#organisation_index) | **GET** /api/v1/organisations | organisation@index



## organisation_get_delegates

> models::OrganisationGetDelegates200Response organisation_get_delegates(id)
Return all delegates associated with an organisation

Return all delegates associated with an organisation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Organisation ID | [required] |

### Return type

[**models::OrganisationGetDelegates200Response**](organisationGetDelegates_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisation_get_projects

> models::OrganisationGetProjects200Response organisation_get_projects(id)
organisation@getProjects

Return an all projects associated with an organisation (i.e. data-custodian)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Organisation ID | [required] |

### Return type

[**models::OrganisationGetProjects200Response**](organisationGetProjects_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisation_get_sponsorships_projects

> models::OrganisationGetProjects200Response organisation_get_sponsorships_projects(id)
organisation@getSponsorshipsProjects

Return an all projects associated with an organisation with sponsorships (i.e. data-custodian)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Organisation ID | [required] |

### Return type

[**models::OrganisationGetProjects200Response**](organisationGetProjects_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisation_get_users

> models::OrganisationGetUsers200Response organisation_get_users(id)
organisation@getUsers

Return all users associated with an organisation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Organisation ID | [required] |

### Return type

[**models::OrganisationGetUsers200Response**](organisationGetUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisation_index

> models::OrganisationIndex200Response organisation_index()
organisation@index

Return a list of organisations

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::OrganisationIndex200Response**](organisationIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


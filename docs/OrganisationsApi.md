# \OrganisationsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodian_project_organisations_get_status**](OrganisationsApi.md#custodian_project_organisations_get_status) | **GET** /api/v1/custodian_approvals/{custodianId}/project/{projectId}/organisation/{organisationId}/projectOrganisations/status | Get project organisation status
[**organisations_custodian_invite_user**](OrganisationsApi.md#organisations_custodian_invite_user) | **POST** /api/v1/organisations/{id}/custodian_invite_user | organisations@custodian_invite_user
[**organisations_destroy**](OrganisationsApi.md#organisations_destroy) | **DELETE** /api/v1/organisations/{id} | organisations@destroy
[**organisations_get_registries**](OrganisationsApi.md#organisations_get_registries) | **GET** /api/v1/organisations/{id}/registries | Get all registries for an organisation
[**organisations_get_status**](OrganisationsApi.md#organisations_get_status) | **GET** /api/v1/organisations/{id}/status | Get organisation status
[**organisations_idvt**](OrganisationsApi.md#organisations_idvt) | **GET** /api/v1/organisations/{id}/idvt | organisations@idvt
[**organisations_invite_user**](OrganisationsApi.md#organisations_invite_user) | **POST** /api/v1/organisations/{id}/invite_user | organisations@invite_user
[**organisations_show**](OrganisationsApi.md#organisations_show) | **GET** /api/v1/organisations/{id} | organisations@show
[**organisations_store**](OrganisationsApi.md#organisations_store) | **POST** /api/v1/organisations | organisations@store
[**organisations_update**](OrganisationsApi.md#organisations_update) | **PUT** /api/v1/organisations/{id} | organisations@update
[**organisations_update_approved**](OrganisationsApi.md#organisations_update_approved) | **PUT** /api/v1/organisations/{id}/approved | SuperAdmin update org system_approved flag



## custodian_project_organisations_get_status

> models::CustodianProjectOrganisationsGetStatus200Response custodian_project_organisations_get_status(custodian_id, project_id, organisation_id)
Get project organisation status

Retrieve the status of a project organisation for a specific custodian using custodianId, projectId, and organisationId.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | Custodian ID | [required] |
**project_id** | **i32** | Project ID | [required] |
**organisation_id** | **i32** | Organisation ID | [required] |

### Return type

[**models::CustodianProjectOrganisationsGetStatus200Response**](custodianProjectOrganisationsGetStatus_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_custodian_invite_user

> models::AccreditationStoreByRegistryId201Response organisations_custodian_invite_user(id, organisations_invite_user_request)
organisations@custodian_invite_user

Invites a user to org

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |
**organisations_invite_user_request** | [**OrganisationsInviteUserRequest**](OrganisationsInviteUserRequest.md) | Invite definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_destroy

> models::AffiliationDestroy200Response organisations_destroy(id)
organisations@destroy

Delete an organisations entry from the system

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_get_registries

> models::OrganisationsGetRegistries200Response organisations_get_registries(id, show_pending)
Get all registries for an organisation

Returns all registries associated with the specified organisation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i64** | Organisation ID | [required] |
**show_pending** | Option<**bool**> | Include users with pending invitations (true/false) |  |

### Return type

[**models::OrganisationsGetRegistries200Response**](organisationsGetRegistries_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_get_status

> models::CustodianProjectOrganisationsGetStatus200Response organisations_get_status(id)
Get organisation status

Returns the organisation with its model state and state

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Organisation ID | [required] |

### Return type

[**models::CustodianProjectOrganisationsGetStatus200Response**](custodianProjectOrganisationsGetStatus_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_idvt

> models::OrganisationsIdvt200Response organisations_idvt(id)
organisations@idvt

Return an organisations idvt details by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |

### Return type

[**models::OrganisationsIdvt200Response**](organisationsIdvt_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_invite_user

> models::AccreditationStoreByRegistryId201Response organisations_invite_user(id, organisations_invite_user_request)
organisations@invite_user

Invites a user to org

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |
**organisations_invite_user_request** | [**OrganisationsInviteUserRequest**](OrganisationsInviteUserRequest.md) | Invite definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_show

> models::OrganisationIndex200Response organisations_show(id)
organisations@show

Return an organisations entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |

### Return type

[**models::OrganisationIndex200Response**](organisationIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_store

> models::IdentityStore201Response organisations_store(organisation)
organisations@store

Create a organisations entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**organisation** | [**Organisation**](Organisation.md) | organisations definition | [required] |

### Return type

[**models::IdentityStore201Response**](identityStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_update

> models::OrganisationsUpdate200Response organisations_update(id, organisation)
organisations@update

Update a organisations entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |
**organisation** | [**Organisation**](Organisation.md) | organisations definition | [required] |

### Return type

[**models::OrganisationsUpdate200Response**](organisationsUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## organisations_update_approved

> models::AccreditationStoreByRegistryId201Response organisations_update_approved(id, organisations_update_approved_request)
SuperAdmin update org system_approved flag

Updates the system_approved flag for an organisation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | organisations entry ID | [required] |
**organisations_update_approved_request** | [**OrganisationsUpdateApprovedRequest**](OrganisationsUpdateApprovedRequest.md) | System approval update definition | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


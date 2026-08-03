# \AffiliationsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**affiliations_get_organisation_affiliation**](AffiliationsApi.md#affiliations_get_organisation_affiliation) | **GET** /api/v1/affiliations/{registryId}/organisation/{organisationId} | Return a specific organisation's affiliation by registry ID and organisation ID
[**affiliations_index_by_registry_id**](AffiliationsApi.md#affiliations_index_by_registry_id) | **GET** /api/v1/affiliations/{registryId} | Affiliations@show
[**affiliations_store_by_registry_id**](AffiliationsApi.md#affiliations_store_by_registry_id) | **POST** /api/v1/affiliations/{registryId} | Affiliations@store
[**affiliations_update**](AffiliationsApi.md#affiliations_update) | **PUT** /api/v1/affiliations/{id} | Affiliations@update
[**affiliations_verify_email**](AffiliationsApi.md#affiliations_verify_email) | **PUT** /api/v1/affiliations/verify_email/{verificationCode} | Affiliations@verifyEmail



## affiliations_get_organisation_affiliation

> models::AffiliationsGetOrganisationAffiliation200Response affiliations_get_organisation_affiliation(registry_id, organisation_id)
Return a specific organisation's affiliation by registry ID and organisation ID

Get a specific organisation's affiliation for a given registry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | Registry ID | [required] |
**organisation_id** | **i32** | Organisation ID | [required] |

### Return type

[**models::AffiliationsGetOrganisationAffiliation200Response**](affiliationsGetOrganisationAffiliation_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## affiliations_index_by_registry_id

> models::AffiliationsIndexByRegistryId200Response affiliations_index_by_registry_id(registry_id)
Affiliations@show

Return a list of affiliations by registry id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | Affiliations registry id | [required] |

### Return type

[**models::AffiliationsIndexByRegistryId200Response**](affiliationsIndexByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## affiliations_store_by_registry_id

> models::AffiliationsStoreByRegistryId200Response affiliations_store_by_registry_id(registry_id, affiliation)
Affiliations@store

Create an Affiliation entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**registry_id** | **i32** | Registry entry ID | [required] |
**affiliation** | [**Affiliation**](Affiliation.md) | Affiliation definition | [required] |

### Return type

[**models::AffiliationsStoreByRegistryId200Response**](affiliationsStoreByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## affiliations_update

> models::AffiliationsStoreByRegistryId200Response affiliations_update(id, affiliation)
Affiliations@update

Update an Affiliation entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Affiliation entry ID | [required] |
**affiliation** | [**Affiliation**](Affiliation.md) | Affiliation definition | [required] |

### Return type

[**models::AffiliationsStoreByRegistryId200Response**](affiliationsStoreByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## affiliations_verify_email

> models::AffiliationsStoreByRegistryId200Response affiliations_verify_email(verification_code)
Affiliations@verifyEmail

Update an Affiliation entry with verification

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**verification_code** | **String** | Email verification code | [required] |

### Return type

[**models::AffiliationsStoreByRegistryId200Response**](affiliationsStoreByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


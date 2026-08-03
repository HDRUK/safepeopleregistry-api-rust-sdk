# \CustodiansApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**custodians_create_custodian_validation_checks**](CustodiansApi.md#custodians_create_custodian_validation_checks) | **POST** /api/v1/custodians/{custodianId}/validation_checks | Assign a validation check to a custodian
[**custodians_get_custodian_users**](CustodiansApi.md#custodians_get_custodian_users) | **GET** /api/v1/custodians/{custodianId}/custodian_users | Get list of people for a custodian
[**custodians_get_custodian_validation_checks**](CustodiansApi.md#custodians_get_custodian_validation_checks) | **GET** /api/v1/custodians/{custodianId}/validation_checks | Get validation checks assigned to a custodian
[**custodians_get_organisation_users**](CustodiansApi.md#custodians_get_organisation_users) | **GET** /api/v1/custodians/{custodianId}/organisations/{organisationId}/users | Get list of people for organisation
[**custodians_get_rules**](CustodiansApi.md#custodians_get_rules) | **GET** /api/v1/custodians/{id}/rules | Get rules for a specific custodian
[**custodians_get_statuses_users**](CustodiansApi.md#custodians_get_statuses_users) | **GET** /api/v1/custodians/{custodianId}/projectUsers/{projectUserId}/statuses | Get statuses for a user in a project/organisation/custodian



## custodians_create_custodian_validation_checks

> models::ValidationCheck custodians_create_custodian_validation_checks(custodian_id, custodians_create_custodian_validation_checks_request)
Assign a validation check to a custodian

Creates a new validation check and assigns it to a specific custodian via the custodian_has_validation_check pivot table.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**custodians_create_custodian_validation_checks_request** | [**CustodiansCreateCustodianValidationChecksRequest**](CustodiansCreateCustodianValidationChecksRequest.md) |  | [required] |

### Return type

[**models::ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodians_get_custodian_users

> models::CustodiansGetCustodianUsers200Response custodians_get_custodian_users(custodian_id)
Get list of people for a custodian

Fetches the list of custodian users based on the custodian id.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |

### Return type

[**models::CustodiansGetCustodianUsers200Response**](custodiansGetCustodianUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodians_get_custodian_validation_checks

> Vec<models::ValidationCheck> custodians_get_custodian_validation_checks(custodian_id)
Get validation checks assigned to a custodian

Returns the list of validation checks associated with a specific custodian.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |

### Return type

[**Vec<models::ValidationCheck>**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodians_get_organisation_users

> models::CustodiansGetOrganisationUsers200Response custodians_get_organisation_users(custodian_id, organisation_id)
Get list of people for organisation

Fetches the list of users associated with the given custodian and organisations IDs.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**organisation_id** | **i32** | ID of the organisation | [required] |

### Return type

[**models::CustodiansGetOrganisationUsers200Response**](custodiansGetOrganisationUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodians_get_rules

> models::CustodiansGetRules200Response custodians_get_rules(id)
Get rules for a specific custodian

Fetches the list of rules associated with the given custodian ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the custodian | [required] |

### Return type

[**models::CustodiansGetRules200Response**](custodiansGetRules_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## custodians_get_statuses_users

> models::CustodiansGetOrganisationUsers200Response custodians_get_statuses_users(custodian_id, project_user_id)
Get statuses for a user in a project/organisation/custodian

Fetches the user statuses given custodian and organisations and project and user IDs.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** | ID of the custodian | [required] |
**project_user_id** | **i32** | ID of the project user | [required] |

### Return type

[**models::CustodiansGetOrganisationUsers200Response**](custodiansGetOrganisationUsers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


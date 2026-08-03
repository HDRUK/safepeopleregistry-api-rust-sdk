# \ProfessionalRegistrationsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**professional_registrations_update**](ProfessionalRegistrationsApi.md#professional_registrations_update) | **PUT** /api/v1/professional_registrations/{id} | Professional Registrations@update



## professional_registrations_update

> models::ProfessionalRegistrationsUpdate200Response professional_registrations_update(id, professional_registrations_update_request)
Professional Registrations@update

Update a Professional Registrations entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Professional Registrations entry ID | [required] |
**professional_registrations_update_request** | [**ProfessionalRegistrationsUpdateRequest**](ProfessionalRegistrationsUpdateRequest.md) | Professional Registrations definition | [required] |

### Return type

[**models::ProfessionalRegistrationsUpdate200Response**](professionalRegistrationsUpdate_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \WebhooksApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**webhooks_create_receiver**](WebhooksApi.md#webhooks_create_receiver) | **POST** /api/v1/webhooks/receivers | Create a new webhook receiver
[**webhooks_delete_receiver**](WebhooksApi.md#webhooks_delete_receiver) | **DELETE** /api/v1/webhooks/receivers/{custodianId} | Delete a webhook receiver
[**webhooks_get_all_event_triggers**](WebhooksApi.md#webhooks_get_all_event_triggers) | **GET** /api/v1/webhooks/event-triggers | Get all webhook event triggers
[**webhooks_get_all_receivers**](WebhooksApi.md#webhooks_get_all_receivers) | **GET** /api/v1/webhooks/receivers | Get all webhook receivers
[**webhooks_get_receivers_by_custodian**](WebhooksApi.md#webhooks_get_receivers_by_custodian) | **GET** /api/v1/webhooks/receivers/{custodianId} | Get webhook receivers by custodian
[**webhooks_sendgrid**](WebhooksApi.md#webhooks_sendgrid) | **GET** /api/v1/webhooks/sendgrid | Get sendgrid webhook event triggers
[**webhooks_update_receiver**](WebhooksApi.md#webhooks_update_receiver) | **PUT** /api/v1/webhooks/receivers/{custodianId} | Update a webhook receiver



## webhooks_create_receiver

> models::WebhooksCreateReceiver201Response webhooks_create_receiver(webhooks_create_receiver_request)
Create a new webhook receiver

Creates a new webhook receiver for a custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**webhooks_create_receiver_request** | [**WebhooksCreateReceiverRequest**](WebhooksCreateReceiverRequest.md) |  | [required] |

### Return type

[**models::WebhooksCreateReceiver201Response**](webhooksCreateReceiver_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## webhooks_delete_receiver

> models::EducationDestroyByRegistryId200Response webhooks_delete_receiver(custodian_id, webhooks_delete_receiver_request)
Delete a webhook receiver

Deletes a specific webhook receiver for a custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** |  | [required] |
**webhooks_delete_receiver_request** | [**WebhooksDeleteReceiverRequest**](WebhooksDeleteReceiverRequest.md) |  | [required] |

### Return type

[**models::EducationDestroyByRegistryId200Response**](educationDestroyByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## webhooks_get_all_event_triggers

> models::WebhooksGetAllEventTriggers200Response webhooks_get_all_event_triggers()
Get all webhook event triggers

Returns all webhook event triggers

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::WebhooksGetAllEventTriggers200Response**](webhooksGetAllEventTriggers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## webhooks_get_all_receivers

> models::WebhooksGetAllReceivers200Response webhooks_get_all_receivers()
Get all webhook receivers

Returns all webhook receivers with their associated event trigger details

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::WebhooksGetAllReceivers200Response**](webhooksGetAllReceivers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## webhooks_get_receivers_by_custodian

> models::WebhooksGetAllReceivers200Response webhooks_get_receivers_by_custodian(custodian_id)
Get webhook receivers by custodian

Returns all webhook receivers for a specific custodian with their associated event trigger details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** |  | [required] |

### Return type

[**models::WebhooksGetAllReceivers200Response**](webhooksGetAllReceivers_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## webhooks_sendgrid

> webhooks_sendgrid()
Get sendgrid webhook event triggers

Returns sendgrid webhook event triggers

### Parameters

This endpoint does not need any parameter.

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## webhooks_update_receiver

> models::EducationDestroyByRegistryId200Response webhooks_update_receiver(custodian_id, webhooks_update_receiver_request)
Update a webhook receiver

Updates a specific webhook receiver for a custodian

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**custodian_id** | **i32** |  | [required] |
**webhooks_update_receiver_request** | [**WebhooksUpdateReceiverRequest**](WebhooksUpdateReceiverRequest.md) |  | [required] |

### Return type

[**models::EducationDestroyByRegistryId200Response**](educationDestroyByRegistryId_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


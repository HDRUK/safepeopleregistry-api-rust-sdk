# \VendorWebhookReceiverApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**vendor_webhook_receiver_receive**](VendorWebhookReceiverApi.md#vendor_webhook_receiver_receive) | **POST** /api/v1/vendor-webhooks/{provider} | Receive a webhook callback from a vendor



## vendor_webhook_receiver_receive

> models::VendorWebhookReceiverReceive200Response vendor_webhook_receiver_receive(provider, body)
Receive a webhook callback from a vendor

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**provider** | **String** | Name of the vendor providing the webhook | [required] |
**body** | **serde_json::Value** |  | [required] |

### Return type

[**models::VendorWebhookReceiverReceive200Response**](vendorWebhookReceiverReceive_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


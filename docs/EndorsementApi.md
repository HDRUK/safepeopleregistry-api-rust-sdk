# \EndorsementApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**endorsement_index**](EndorsementApi.md#endorsement_index) | **GET** /api/v1/endorsements | Endorsement@index
[**endorsement_show**](EndorsementApi.md#endorsement_show) | **GET** /api/v1/endorsements/{id} | Endorsement@show



## endorsement_index

> models::EndorsementIndex200Response endorsement_index()
Endorsement@index

Return a list of Endorsements

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::EndorsementIndex200Response**](endorsementIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## endorsement_show

> models::EndorsementIndex200Response endorsement_show(id)
Endorsement@show

Return an Endorsement entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Endorsement entry ID | [required] |

### Return type

[**models::EndorsementIndex200Response**](endorsementIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


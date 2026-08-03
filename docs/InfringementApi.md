# \InfringementApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**infringement_index**](InfringementApi.md#infringement_index) | **GET** /api/v1/infringements | Infringement@index
[**infringement_show**](InfringementApi.md#infringement_show) | **GET** /api/v1/infringements/{id} | Infringement@show
[**infringement_store**](InfringementApi.md#infringement_store) | **POST** /api/v1/infringements | Infringement@store



## infringement_index

> models::InfringementIndex200Response infringement_index()
Infringement@index

Return a list of Infringements

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::InfringementIndex200Response**](infringementIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## infringement_show

> models::InfringementIndex200Response infringement_show(id)
Infringement@show

Return an Infringement entry by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | Infringement entry ID | [required] |

### Return type

[**models::InfringementIndex200Response**](infringementIndex_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## infringement_store

> models::InfringementStore201Response infringement_store(infringement_store_request)
Infringement@store

Create an Infringement entry

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**infringement_store_request** | [**InfringementStoreRequest**](InfringementStoreRequest.md) | Infringement definition | [required] |

### Return type

[**models::InfringementStore201Response**](infringementStore_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \SectorApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sector_destroy**](SectorApi.md#sector_destroy) | **DELETE** /api/v1/sectors/{id} | Delete a sector
[**sector_index**](SectorApi.md#sector_index) | **GET** /api/v1/sectors | Get a list of sectors
[**sector_show**](SectorApi.md#sector_show) | **GET** /api/v1/sectors/{id} | Get a specific sector by ID
[**sector_store**](SectorApi.md#sector_store) | **POST** /api/v1/sectors | Create a new sector
[**sector_update**](SectorApi.md#sector_update) | **PUT** /api/v1/sectors/{id} | Update an existing sector



## sector_destroy

> models::AffiliationDestroy200Response sector_destroy(id)
Delete a sector

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the sector | [required] |

### Return type

[**models::AffiliationDestroy200Response**](affiliationDestroy_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sector_index

> Vec<models::Sector> sector_index()
Get a list of sectors

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::Sector>**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sector_show

> models::Sector sector_show(id)
Get a specific sector by ID

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the sector | [required] |

### Return type

[**models::Sector**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sector_store

> models::AccreditationStoreByRegistryId201Response sector_store(sector)
Create a new sector

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sector** | [**Sector**](Sector.md) |  | [required] |

### Return type

[**models::AccreditationStoreByRegistryId201Response**](accreditationStoreByRegistryId_201_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sector_update

> models::Sector sector_update(id, sector)
Update an existing sector

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | ID of the sector | [required] |
**sector** | [**Sector**](Sector.md) |  | [required] |

### Return type

[**models::Sector**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


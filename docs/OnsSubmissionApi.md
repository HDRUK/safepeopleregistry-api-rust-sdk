# \OnsSubmissionApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**o_ns_submission_receive_csv**](OnsSubmissionApi.md#o_ns_submission_receive_csv) | **POST** /api/v1/ons-submissions/csv | Upload a CSV file for ONS submission



## o_ns_submission_receive_csv

> models::ONsSubmissionReceiveCsv200Response o_ns_submission_receive_csv(file)
Upload a CSV file for ONS submission

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**file** | Option<**std::path::PathBuf**> | CSV file to upload |  |

### Return type

[**models::ONsSubmissionReceiveCsv200Response**](oNSSubmissionReceiveCSV_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


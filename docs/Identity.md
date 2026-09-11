# Identity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Unique identifier for the identity record | [optional]
**registry_id** | Option<**i32**> | ID of the registry associated with the identity record | [optional]
**address_1** | Option<**String**> | First line of the address | [optional]
**address_2** | Option<**String**> | Second line of the address | [optional]
**town** | Option<**String**> | Town of the address | [optional]
**county** | Option<**String**> | County of the address | [optional]
**country** | Option<**String**> | Country of the address | [optional]
**postcode** | Option<**String**> | Postcode of the address | [optional]
**dob** | Option<**chrono::NaiveDate**> | Date of birth | [optional]
**idvt_success** | Option<**i32**> | Indicates whether IDVT was successful (1 for success, 0 for failure) | [optional]
**idvt_identification_number** | Option<**String**> | Identification number from IDVT | [optional]
**idvt_document_type** | Option<**String**> | Type of document used for IDVT | [optional]
**idvt_document_number** | Option<**String**> | Document number used for IDVT | [optional]
**idvt_document_country** | Option<**String**> | Country of the document used for IDVT | [optional]
**idvt_document_valid_until** | Option<**chrono::NaiveDate**> | Validity date of the document used for IDVT | [optional]
**idvt_document_first_name** | Option<**String**> | First name on the document used for IDVT | [optional]
**idvt_document_valid_last_name** | Option<**String**> | Last name on the document used for IDVT | [optional]
**idvt_attempt_id** | Option<**String**> | ID of the IDVT attempt | [optional]
**idvt_context_id** | Option<**String**> | Context ID for IDVT | [optional]
**idvt_document_dob** | Option<**chrono::NaiveDate**> | Date of birth on the document used for IDVT | [optional]
**idvt_context** | Option<**String**> | Context of the IDVT process | [optional]
**idvt_completed_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when IDVT was completed | [optional]
**idvt_result_text** | Option<**String**> | Result text of the IDVT process | [optional]
**idvt_started_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when IDVT was started | [optional]
**created_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the identity record was created | [optional]
**updated_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the identity record was last updated | [optional]
**deleted_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the identity record was deleted | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



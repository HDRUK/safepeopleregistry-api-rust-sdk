# CustodianHasProjectOrganisation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> |  | [optional][readonly]
**project_has_organisation_id** | **i32** | ID of the project organisation | 
**custodian_id** | **i32** | ID of the custodian | 
**approved** | Option<**bool**> | Approval flag | [optional]
**comment** | Option<**String**> | Optional comment | [optional]
**created_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> |  | [optional]
**updated_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> |  | [optional]
**project_organisation** | Option<[**models::ProjectHasOrganisation**](ProjectHasOrganisation.md)> |  | [optional]
**custodian** | Option<[**models::Custodian**](Custodian.md)> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



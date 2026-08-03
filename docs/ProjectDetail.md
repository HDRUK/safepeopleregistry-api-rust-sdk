# ProjectDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Model primary key | [optional]
**created_at** | Option<**String**> |  | [optional]
**updated_at** | Option<**String**> |  | [optional]
**project_id** | Option<**i32**> | Primary key of associated Project for this ProjectDetail | [optional]
**datasets** | Option<**Vec<String>**> |  | [optional]
**other_approval_committees** | Option<**Vec<String>**> |  | [optional]
**data_sensitivity_level** | Option<**String**> |  | [optional]
**legal_basis_for_data_article6** | Option<**String**> |  | [optional]
**duty_of_confidentiality** | Option<**bool**> |  | [optional]
**national_data_optout** | Option<**bool**> |  | [optional]
**request_frequency** | Option<**RequestFrequency**> |  (enum: ONE-OFF, RECURRING) | [optional]
**dataset_linkage_description** | Option<**String**> |  | [optional]
**data_minimisation** | Option<**String**> |  | [optional]
**data_use_description** | Option<**String**> |  | [optional]
**access_date** | Option<**String**> |  | [optional]
**access_type** | Option<**i32**> |  | [optional]
**data_privacy** | Option<**String**> |  | [optional]
**research_outputs** | Option<**serde_json::Value**> |  | [optional]
**data_assets** | Option<**String**> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



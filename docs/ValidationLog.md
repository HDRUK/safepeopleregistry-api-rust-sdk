# ValidationLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Model primary key | [optional]
**entity_type** | Option<**String**> | Type of the primary entity associated with the validation log | [optional]
**entity_id** | Option<**i32**> | ID of the primary entity associated with the validation log | [optional]
**secondary_entity_type** | Option<**String**> | Type of the secondary entity associated with the validation log | [optional]
**secondary_entity_id** | Option<**i32**> | ID of the secondary entity associated with the validation log | [optional]
**tertiary_entity_type** | Option<**String**> | Type of the tertiary entity associated with the validation log | [optional]
**tertiary_entity_id** | Option<**i32**> | ID of the tertiary entity associated with the validation log | [optional]
**name** | Option<**String**> | Name of the validation log entry | [optional]
**completed_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the validation was completed (nullable) | [optional]
**manually_confirmed** | Option<**bool**> | Whether the validation was manually confirmed | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



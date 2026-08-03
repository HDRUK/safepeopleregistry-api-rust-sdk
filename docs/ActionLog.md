# ActionLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Model primary key | [optional]
**entity_type** | Option<**String**> | Type of the entity associated with the action log | [optional]
**entity_id** | Option<**i32**> | ID of the entity associated with the action log | [optional]
**action** | Option<**String**> | Description of the action performed | [optional]
**completed_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the action was completed (nullable) | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# EntityModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Unique identifier for the entity model | [optional]
**name** | Option<**String**> | Name of the entity model | [optional]
**description** | Option<**String**> | Description of the entity model | [optional]
**entity_model_type_id** | Option<**i32**> | ID of the entity model type associated with this model | [optional]
**calls_file** | Option<**bool**> | Indicates whether the model calls a file | [optional]
**file_path** | Option<**String**> | Path to the file called by the model | [optional]
**calls_operation** | Option<**bool**> | Indicates whether the model calls an operation | [optional]
**operation** | Option<**String**> | Operation called by the model | [optional]
**active** | Option<**i32**> | Indicates whether the model is active (1 for active, 0 for inactive) | [optional]
**created_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the entity model was created | [optional]
**updated_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the entity model was last updated | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



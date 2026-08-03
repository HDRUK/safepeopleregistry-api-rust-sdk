# ValidationLogComment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Model primary key | [optional]
**validation_log_id** | Option<**i32**> | ID of the associated validation log | [optional]
**user_id** | Option<**i32**> | ID of the user who made the comment | [optional]
**comment** | Option<**String**> | The comment text | [optional]
**created_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the comment was created | [optional]
**updated_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the comment was last updated | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



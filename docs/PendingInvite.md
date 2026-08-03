# PendingInvite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Unique identifier for the pending invite | [optional]
**user_id** | Option<**i32**> | ID of the user associated with the invite | [optional]
**organisation_id** | Option<**i32**> | ID of the organisation associated with the invite | [optional]
**status** | Option<**String**> | Status of the invite | [optional]
**invite_accepted_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the invite was accepted | [optional]
**invite_sent_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the invite was sent | [optional]
**invite_code** | Option<**String**> | Unique code for the invite | [optional]
**created_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the invite record was created | [optional]
**updated_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when the invite record was last updated | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



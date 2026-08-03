# Affiliation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Model primary key | [optional]
**created_at** | Option<**String**> |  | [optional]
**updated_at** | Option<**String**> |  | [optional]
**organisation_id** | Option<**i32**> | Organisational link | [optional]
**member_id** | Option<**String**> | Member ID UUID | [optional]
**relationship** | Option<**String**> | Textual representation of affiliation relationship | [optional]
**from** | Option<**String**> | Date affiliation commenced | [optional]
**to** | Option<**String**> | Date affiliation concluded | [optional]
**department** | Option<**String**> | Department worked during affiliation | [optional]
**role** | Option<**String**> | Role held during affiliation | [optional]
**email** | Option<**String**> | Professional email held during affiliation | [optional]
**ror** | Option<**String**> | The ROR.org identifier for this affiliation institute | [optional]
**registry_id** | Option<**i32**> | The Registry primary key associated with this affiliation | [optional]
**current_employer** | Option<**bool**> | Flag indicating if affiliation is for the current employer | [optional]
**verification_code** | Option<**String**> | Unique verification code issued for confirmation | [optional]
**verification_sent_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when verification code was sent | [optional]
**verification_confirmed_at** | Option<**chrono::DateTime<chrono::FixedOffset>**> | Timestamp when verification was confirmed | [optional]
**is_verified** | Option<**bool**> | Flag indicating if affiliation is verified | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



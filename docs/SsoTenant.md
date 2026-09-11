# SsoTenant

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i32**> | Model primary key | [optional]
**created_at** | Option<**String**> |  | [optional]
**updated_at** | Option<**String**> |  | [optional]
**name** | Option<**String**> |  | [optional]
**idp_alias** | Option<**String**> |  | [optional]
**metadata_url** | Option<**String**> |  | [optional]
**entity_id** | Option<**String**> |  | [optional]
**metadata_imported_at** | Option<**String**> |  | [optional]
**enabled** | Option<**bool**> |  | [optional]
**sp_entity_id** | Option<**String**> | Keycloak's own SP entity ID - null until approved. Register this as the SAML Identifier on the customer's IdP. | [optional]
**sp_acs_url** | Option<**String**> | Keycloak's ACS/reply URL for this tenant - null until approved. | [optional]
**sp_metadata_url** | Option<**String**> | Downloadable SP metadata descriptor most IdPs can import directly - null until approved. | [optional]
**status** | Option<**String**> | One of pending, approved, rejected | [optional]
**submitted_by_user_id** | Option<**i32**> | ID of the user who submitted this tenant for approval | [optional]
**rejected_reason** | Option<**String**> | Reason given when status is rejected - null otherwise | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



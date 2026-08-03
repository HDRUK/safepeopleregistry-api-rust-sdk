# \NotificationsApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**notifications_get_notification_counts**](NotificationsApi.md#notifications_get_notification_counts) | **GET** /api/v1/users/{id}/notifications/count | Get notification counts for a specific user
[**notifications_get_user_notifications**](NotificationsApi.md#notifications_get_user_notifications) | **GET** /api/v1/users/{id}/notifications | Get notifications for a specific user
[**notifications_mark_user_notification_as_read**](NotificationsApi.md#notifications_mark_user_notification_as_read) | **PATCH** /api/v1/users/{id}/notifications/{notificationId}/read | Mark a specific notification as read
[**notifications_mark_user_notification_as_unread**](NotificationsApi.md#notifications_mark_user_notification_as_unread) | **PATCH** /api/v1/users/{id}/notifications/{notificationId}/unread | Mark a specific notification as unread
[**notifications_mark_user_notifications_as_read**](NotificationsApi.md#notifications_mark_user_notifications_as_read) | **PATCH** /api/v1/users/{id}/notifications/read | Mark all notifications as read for a specific user



## notifications_get_notification_counts

> models::NotificationsGetNotificationCounts200Response notifications_get_notification_counts(id)
Get notification counts for a specific user

Retrieve the total, read, and unread notification counts for a given user.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |

### Return type

[**models::NotificationsGetNotificationCounts200Response**](notificationsGetNotificationCounts_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## notifications_get_user_notifications

> models::NotificationsGetUserNotifications200Response notifications_get_user_notifications(id, status)
Get notifications for a specific user

Retrieves notifications for a user, with an optional filter for read/unread notifications.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |
**status** | Option<**String**> | Filter notifications by status (read/unread) |  |

### Return type

[**models::NotificationsGetUserNotifications200Response**](notificationsGetUserNotifications_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## notifications_mark_user_notification_as_read

> models::NotificationsMarkUserNotificationAsRead200Response notifications_mark_user_notification_as_read(id, notification_id)
Mark a specific notification as read

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |
**notification_id** | **String** | Notification ID | [required] |

### Return type

[**models::NotificationsMarkUserNotificationAsRead200Response**](notificationsMarkUserNotificationAsRead_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## notifications_mark_user_notification_as_unread

> notifications_mark_user_notification_as_unread(id, notification_id)
Mark a specific notification as unread

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |
**notification_id** | **String** | Notification ID | [required] |

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## notifications_mark_user_notifications_as_read

> models::NotificationsMarkUserNotificationsAsRead200Response notifications_mark_user_notifications_as_read(id)
Mark all notifications as read for a specific user

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **i32** | User ID | [required] |

### Return type

[**models::NotificationsMarkUserNotificationsAsRead200Response**](notificationsMarkUserNotificationsAsRead_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


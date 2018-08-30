---
swagger: "2.0"
x-collection-name: Azure Monitor
x-complete: 0
info:
  title: Azure Autoscale API Autoscale Settings Get
  version: 1.0.0
  description: Gets an autoscale setting
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/microsoft.insights/activityLogAlerts/{activityLogAlertName}
  : put:
      summary: Activity Log Alerts Create Or Update
      description: Create a new activity log alert or update an existing one.
      operationId: ActivityLogAlerts_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-put
      parameters:
      - in: body
        name: activityLogAlert
        description: The activity log alert to create or use for the update
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Activity Log Alerts
    get:
      summary: Activity Log Alerts Get
      description: Get an activity log alert.
      operationId: ActivityLogAlerts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Activity Log Alerts
    delete:
      summary: Activity Log Alerts Delete
      description: Delete an activity log alert.
      operationId: ActivityLogAlerts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Activity Log Alerts
    patch:
      summary: Activity Log Alerts Update
      description: Updates an existing ActivityLogAlertResource's tags. To update
        other fields use the CreateOrUpdate method.
      operationId: ActivityLogAlerts_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-patch
      parameters:
      - in: body
        name: activityLogAlertPatch
        description: Parameters supplied to the operation
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Activity Log Alerts
  /subscriptions/{subscriptionId}/providers/microsoft.insights/activityLogAlerts:
    get:
      summary: Activity Log Alerts List By Subscription Id
      description: Get a list of all activity log alerts in a subscription.
      operationId: ActivityLogAlerts_ListBySubscriptionId
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-insightsactivitylogalerts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Activity Log Alerts Subscription Id
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/microsoft.insights/activityLogAlerts:
    get:
      summary: Activity Log Alerts List By Resource Group
      description: Get a list of all activity log alerts in a resource group.
      operationId: ActivityLogAlerts_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalerts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Activity Log Alerts Resource Group
  /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/microsoft.insights/autoscalesettings:
    get:
      summary: Autoscale Settings List By Resource Group
      description: Lists the autoscale settings for a resource group
      operationId: AutoscaleSettings_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Autoscaletings Resource Group
  ? /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/microsoft.insights/autoscalesettings/{autoscaleSettingName}
  : put:
      summary: Autoscale Settings Create Or Update
      description: Creates or updates an autoscale setting.
      operationId: AutoscaleSettings_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Autoscaletings
    delete:
      summary: Autoscale Settings Delete
      description: Deletes and autoscale setting
      operationId: AutoscaleSettings_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Autoscaletings
    get:
      summary: Autoscale Settings Get
      description: Gets an autoscale setting
      operationId: AutoscaleSettings_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Autoscaletings
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
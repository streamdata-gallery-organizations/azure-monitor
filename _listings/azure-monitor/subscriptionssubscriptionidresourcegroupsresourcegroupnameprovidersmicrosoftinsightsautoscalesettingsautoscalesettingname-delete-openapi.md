---
swagger: "2.0"
x-collection-name: Azure Monitor
x-complete: 0
info:
  title: Azure Autoscale API Autoscale Settings Delete
  version: 1.0.0
  description: Deletes and autoscale setting
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/microsoft.insights/autoscalesettings:
    get:
      summary: Autoscale Settings List By Resource Group
      description: Lists the autoscale settings for a resource group
      operationId: AutoscaleSettings_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftinsightsautoscalesettings-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftinsightsautoscalesettingsautoscalesettingname-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftinsightsautoscalesettingsautoscalesettingname-delete
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
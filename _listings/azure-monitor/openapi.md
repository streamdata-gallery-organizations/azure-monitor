---
swagger: "2.0"
x-collection-name: Azure Monitor
x-complete: 1
info:
  title: MonitorManagementClient
  version: 1.0.0
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
    get:
      summary: Autoscale Settings Get
      description: Gets an autoscale setting
      operationId: AutoscaleSettings_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftinsightsautoscalesettingsautoscalesettingname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Autoscaletings
---
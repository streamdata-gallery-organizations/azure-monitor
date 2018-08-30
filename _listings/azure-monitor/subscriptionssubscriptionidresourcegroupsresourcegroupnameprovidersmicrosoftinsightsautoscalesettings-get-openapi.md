---
swagger: "2.0"
x-collection-name: Azure Monitor
x-complete: 0
info:
  title: Azure Autoscale API Autoscale Settings List By Resource Group
  version: 1.0.0
  description: Lists the autoscale settings for a resource group
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
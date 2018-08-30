---
swagger: "2.0"
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
  ? /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/microsoft.insights/autoscalesettings/{autoscaleSettingName}
  : put:
      summary: Autoscale Settings Create Or Update
      description: Creates or updates an autoscale setting
      operationId: AutoscaleSettings_CreateOrUpdate
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
      - autoscaletings
definitions:
  Resource:
    properties:
      id:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
      location:
        description: This is a default description.
        type: get
  ScaleCapacity:
    properties:
      minimum:
        description: This is a default description.
        type: get
      maximum:
        description: This is a default description.
        type: get
      default:
        description: This is a default description.
        type: get
  MetricTrigger:
    properties:
      metricName:
        description: This is a default description.
        type: get
      metricResourceUri:
        description: This is a default description.
        type: get
      timeGrain:
        description: This is a default description.
        type: get
      statistic:
        description: This is a default description.
        type: get
      timeWindow:
        description: This is a default description.
        type: get
      timeAggregation:
        description: This is a default description.
        type: get
      operator:
        description: This is a default description.
        type: get
      threshold:
        description: This is a default description.
        type: get
  ScaleAction:
    properties:
      direction:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
      cooldown:
        description: This is a default description.
        type: get
  ScaleRule:
    properties: []
  TimeWindow:
    properties:
      timeZone:
        description: This is a default description.
        type: get
      start:
        description: This is a default description.
        type: get
      end:
        description: This is a default description.
        type: get
  RecurrentSchedule:
    properties:
      timeZone:
        description: This is a default description.
        type: get
      days:
        description: This is a default description.
        type: get
      hours:
        description: This is a default description.
        type: get
      minutes:
        description: This is a default description.
        type: get
  Recurrence:
    properties:
      frequency:
        description: This is a default description.
        type: get
  AutoscaleProfile:
    properties:
      name:
        description: This is a default description.
        type: get
      rules:
        description: This is a default description.
        type: get
  EmailNotification:
    properties:
      sendToSubscriptionAdministrator:
        description: This is a default description.
        type: get
      sendToSubscriptionCoAdministrators:
        description: This is a default description.
        type: get
      customEmails:
        description: This is a default description.
        type: get
  WebhookNotification:
    properties:
      serviceUri:
        description: This is a default description.
        type: get
      properties:
        description: This is a default description.
        type: get
  AutoscaleNotification:
    properties:
      operation:
        description: This is a default description.
        type: get
      webhooks:
        description: This is a default description.
        type: get
  AutoscaleSetting:
    properties:
      profiles:
        description: This is a default description.
        type: get
      notifications:
        description: This is a default description.
        type: get
      enabled:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      targetResourceUri:
        description: This is a default description.
        type: get
  AutoscaleSettingResource:
    properties: []
  AutoscaleSettingResourceCollection:
    properties:
      value:
        description: This is a default description.
        type: get
      nextLink:
        description: This is a default description.
        type: get
  ErrorResponse:
    properties:
      code:
        description: This is a default description.
        type: get
      message:
        description: This is a default description.
        type: get
x-collection-name: Azure Monitor
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
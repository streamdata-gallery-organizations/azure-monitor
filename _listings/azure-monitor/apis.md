---
name: Azure Monitor
x-slug: azure-monitor
description: Autoscale is a built-in feature of Cloud Services, Mobile Services, Virtual
  Machines, and Websites that helps applications perform their best when demand changes.
  Of course, performance means different things for different applications. Some apps
  are CPU-bound, others memory-bound. For example, you could have a web app that handles
  millions of requests during the day and none at night. Autoscale can scale your
  service by any of these&mdash;or by a custom metric you define.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Monitor
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Activity Log Alerts API - Activity Log Alerts Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-put
  description: Create a new activity log alert or update an existing one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-put-openapi.md
- name: Azure Activity Log Alerts API - Activity Log Alerts Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-get
  description: Get an activity log alert.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-get-openapi.md
- name: Azure Activity Log Alerts API - Activity Log Alerts Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-delete
  description: Delete an activity log alert.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-delete-openapi.md
- name: Azure Activity Log Alerts API - Activity Log Alerts Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-patch
  description: Updates an existing ActivityLogAlertResource's tags. To update other
    fields use the CreateOrUpdate method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalertsactivitylogalertname-patch-openapi.md
- name: Azure Activity Log Alerts API - Activity Log Alerts List By Subscription Id
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-insightsactivitylogalerts-get
  description: Get a list of all activity log alerts in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidprovidersmicrosoft-insightsactivitylogalerts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidprovidersmicrosoft-insightsactivitylogalerts-get-openapi.md
- name: Azure Activity Log Alerts API - Activity Log Alerts List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalerts-get
  description: Get a list of all activity log alerts in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalerts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsactivitylogalerts-get-openapi.md
- name: MonitorManagementClient - Autoscale Settings List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettings-get
  description: Lists the autoscale settings for a resource group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettings-get-openapi.md
- name: MonitorManagementClient - Autoscale Settings Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-put
  description: Creates or updates an autoscale setting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-put-openapi.md
- name: MonitorManagementClient - Autoscale Settings Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-delete
  description: Deletes and autoscale setting
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-delete-openapi.md
- name: MonitorManagementClient - Autoscale Settings Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-get
  description: Gets an autoscale setting
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/manage-monitoring-data.png
  humanURL: https://azure.microsoft.com/en-us/services/monitor/
  baseURL: ://management.azure.com//
  tags: Monitoring, Cloud, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-monitor/master/_listings/azure-monitor/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-insightsautoscalesettingsautoscalesettingname-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.media.services.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.monitor.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/monitor/
- type: x-service-level-agreement
  url: https://azure.microsoft.com/en-us/support/legal/sla/monitor/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/monitor/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
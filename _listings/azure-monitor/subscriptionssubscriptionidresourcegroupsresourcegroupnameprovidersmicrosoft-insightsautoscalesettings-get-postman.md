{
  "info": {
    "name": "Azure Autoscale API Autoscale Settings List By Resource Group",
    "_postman_id": "8b937e88-fb2a-4ceb-865e-52c54a0aaf30",
    "description": "Lists the autoscale settings for a resource group",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Autoscaletings Resource Group",
      "item": [
        {
          "id": "aacb0ada-d7b9-4fff-b89a-cba98fe699b6",
          "name": "AutoscaleSettings_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourcegroups/:resourceGroupName/providers/microsoft.insights/autoscalesettings"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the autoscale settings for a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5cc20630-9596-4c92-8515-9e4fd380c755"
            }
          ]
        }
      ]
    }
  ]
}
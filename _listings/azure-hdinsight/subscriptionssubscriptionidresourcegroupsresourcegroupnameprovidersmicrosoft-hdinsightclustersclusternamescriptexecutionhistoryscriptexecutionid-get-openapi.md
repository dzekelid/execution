---
swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 0
info:
  title: Azure HDInsight API Script Execution History Get
  description: Gets the script execution detail for the given script execution id.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/scriptExecutionHistory/{scriptExecutionId}
  : get:
      summary: Script Execution History Get
      description: Gets the script execution detail for the given script execution
        id.
      operationId: ScriptExecutionHistory_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamescriptexecutionhistoryscriptexecutionid-get
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: scriptExecutionId
        description: The script execution Id
      responses:
        200:
          description: OK
      tags:
      - Script Execution History
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
---
swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 1
info:
  title: HDInsightManagementClient
  description: the-hdinsight-management-client-
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/scriptExecutionHistory
  : get:
      summary: Script Execution History List
      description: Lists all scripts execution history for the given cluster.
      operationId: ScriptExecutionHistory_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamescriptexecutionhistory-get
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Script Execution History
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/scriptExecutionHistory/{scriptExecutionId}/promote
  : post:
      summary: Script Execution History Promote
      description: Promote ad-hoc script execution to a persisted script.
      operationId: ScriptExecutionHistory_Promote
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamescriptexecutionhistoryscriptexecutionidpromote-post
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
      - Script Execution History Promote
---
---
name: Azure HDInsight
x-slug: azure-hdinsight
description: Azure HDInsight is a Hadoop-based service that brings an Apache Hadoop
  solution to the cloud. Gain the full value of big data with a cloud-based data platform
  that manages data of any type and size.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Execution
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/azure-hdinsight/apis.md
specificationVersion: "0.14"
apis:
- name: Azure HDInsight API Script Execution History Get
  x-api-slug: azure-hdinsight-api
  description: Gets the script execution detail for the given script execution id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/scriptExecutionHistory/{scriptExecutionId}
  tags: Script Execution History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamescriptexecutionhistoryscriptexecutionid-get-openapi.md
- name: Azure HDInsight API Script Execution History List
  x-api-slug: azure-hdinsight-api
  description: Lists all scripts execution history for the given cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/scriptExecutionHistory
  tags: Script Execution History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamescriptexecutionhistory-get-openapi.md
- name: Azure HDInsight API Script Execution History Promote
  x-api-slug: azure-hdinsight-api
  description: Promote ad-hoc script execution to a persisted script.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/scriptExecutionHistory/{scriptExecutionId}/promote
  tags: Script Execution History Promote
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternamescriptexecutionhistoryscriptexecutionidpromote-post-openapi.md
- name: Azure HDInsight API
  x-api-slug: azure-hdinsight-api
  description: Azure HDInsight is a Hadoop-based service that brings an Apache Hadoop
    solution to the cloud. Gain the full value of big data with a cloud-based data
    platform that manages data of any type and size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/azure-hdinsight/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/hdinsight/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/hdinsight/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/hdinsight/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/hdinsight/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
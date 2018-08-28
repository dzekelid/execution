---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Execution
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Analytics Catalog - Cleanup analytic execution result by request id.
  x-api-slug: apiv1analyticexecutionasyncrequestid-delete
  description: Removes the analytic execution result from the cache. It is highly
    recommended to clean your old result data to have room for future result data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasyncrequestid-delete-openapi.md
- name: Analytics Catalog - Get the analytic execution result by request id.
  x-api-slug: apiv1analyticexecutionasyncrequestidresult-get
  description: Returns the analytic execution result.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasyncrequestidresult-get-openapi.md
- name: Analytics Catalog - Get the analytic execution status by request id.
  x-api-slug: apiv1analyticexecutionasyncrequestidstatus-get
  description: Returns the analytic execution status (one of QUEUED, PROCESSING, COMPLETED,
    or FAILED).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasyncrequestidstatus-get-openapi.md
- name: Analytics Catalog - Execute the analytic synchronously.
  x-api-slug: apiv1analyticexecution-post
  description: Execute the analytic synchronously with the given execution payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecution-post-openapi.md
- name: Analytics Catalog - Execute the analytic asynchronously using input data.
  x-api-slug: apiv1analyticexecutionasync-post
  description: Execute the analytic asynchronously with the given input data payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasync-post-openapi.md
- name: Analytics Catalog - Execute an analytic by analytic catalog entry id.
  x-api-slug: apiv1cataloganalyticsidexecution-post
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1cataloganalyticsidexecution-post-openapi.md
- name: Analytics Catalog - Execute the analytic synchronously.
  x-api-slug: apiv1analyticexecution-post
  description: Execute the analytic synchronously with the given execution payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecution-post-openapi.md
- name: Analytics Catalog - Execute the analytic asynchronously using input data.
  x-api-slug: apiv1analyticexecutionasync-post
  description: Execute the analytic asynchronously with the given input data payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasync-post-openapi.md
- name: Analytics Catalog - Execute an analytic by analytic catalog entry id.
  x-api-slug: apiv1cataloganalyticsidexecution-post
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1cataloganalyticsidexecution-post-openapi.md
- name: Analytics Catalog - Execute an analytic by analytic catalog entry id.
  x-api-slug: apiv1cataloganalyticsidexecution-post
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1cataloganalyticsidexecution-post-openapi.md
- name: Analytics Catalog - Execute the analytic asynchronously using input data.
  x-api-slug: apiv1analyticexecutionasync-post
  description: Execute the analytic asynchronously with the given input data payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasync-post-openapi.md
- name: Analytics Catalog - Execute the analytic synchronously.
  x-api-slug: apiv1analyticexecution-post
  description: Execute the analytic synchronously with the given execution payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecution-post-openapi.md
- name: Analytics Framework - Cleanup analytic execution result by request id.
  x-api-slug: apiv1analyticexecutionasyncrequestid-delete
  description: Removes the analytic execution result from the cache. It is highly
    recommended to clean your old result data to have room for future result data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasyncrequestid-delete-openapi.md
- name: Analytics Framework - Get the analytic execution result by request id.
  x-api-slug: apiv1analyticexecutionasyncrequestidresult-get
  description: Returns the analytic execution result.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasyncrequestidresult-get-openapi.md
- name: Analytics Framework - Get the analytic execution status by request id.
  x-api-slug: apiv1analyticexecutionasyncrequestidstatus-get
  description: Returns the analytic execution status (one of QUEUED, PROCESSING, COMPLETED,
    or FAILED).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasyncrequestidstatus-get-openapi.md
- name: Analytics Framework - Retrieve orchestration execution result
  x-api-slug: apiv1monitoringorchestrationsorchestrationrequestid-get
  description: Returns orchestration execution result for the given orchestration
    request id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1monitoringorchestrationsorchestrationrequestid-get-openapi.md
- name: Analytics Framework - Retrieve job execution history of the given job.
  x-api-slug: apiv1schedulerjobsidhistory-get
  description: Retrieve job execution history
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1schedulerjobsidhistory-get-openapi.md
- name: Analytics Framework - Execute the analytic synchronously.
  x-api-slug: apiv1analyticexecution-post
  description: Execute the analytic synchronously with the given execution payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecution-post-openapi.md
- name: Analytics Framework - Execute the analytic asynchronously using input data.
  x-api-slug: apiv1analyticexecutionasync-post
  description: Execute the analytic asynchronously with the given input data payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasync-post-openapi.md
- name: Analytics Framework - Execute an analytic by analytic catalog entry id.
  x-api-slug: apiv1cataloganalyticsidexecution-post
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1cataloganalyticsidexecution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration.
  x-api-slug: apiv1execution-post
  description: To successfully execute the orchestration, the OrchestrationRequest
    must contain valid orchestration id, bpmn workflow xml and optionally input data
    for each analytic step defined in the workflow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1execution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration.
  x-api-slug: apiv2execution-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
    This API will execute the orchestration in synchronous mode and if the execution
    is not completed  in 1 minute then the request will fail. After successful completion,
    the response will contain each orchestration steps output data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2execution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration in asynchronous
    mode.
  x-api-slug: apiv2executionasync-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executionasync-post-openapi.md
- name: Analytics Framework - Execute the orchestration with given bpmn and input
    data.
  x-api-slug: apiv2executiontestrun-post
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executiontestrun-post-openapi.md
- name: Analytics Framework - Execute the analytic synchronously.
  x-api-slug: apiv1analyticexecution-post
  description: Execute the analytic synchronously with the given execution payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecution-post-openapi.md
- name: Analytics Framework - Execute the analytic asynchronously using input data.
  x-api-slug: apiv1analyticexecutionasync-post
  description: Execute the analytic asynchronously with the given input data payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasync-post-openapi.md
- name: Analytics Framework - Execute an analytic by analytic catalog entry id.
  x-api-slug: apiv1cataloganalyticsidexecution-post
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1cataloganalyticsidexecution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration.
  x-api-slug: apiv1execution-post
  description: To successfully execute the orchestration, the OrchestrationRequest
    must contain valid orchestration id, bpmn workflow xml and optionally input data
    for each analytic step defined in the workflow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1execution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration.
  x-api-slug: apiv2execution-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
    This API will execute the orchestration in synchronous mode and if the execution
    is not completed  in 1 minute then the request will fail. After successful completion,
    the response will contain each orchestration steps output data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2execution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration in asynchronous
    mode.
  x-api-slug: apiv2executionasync-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executionasync-post-openapi.md
- name: Analytics Framework - Execute the orchestration with given bpmn and input
    data.
  x-api-slug: apiv2executiontestrun-post
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executiontestrun-post-openapi.md
- name: Analytics Framework - Execute the orchestration with given bpmn and input
    data.
  x-api-slug: apiv2executiontestrun-post
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executiontestrun-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration in asynchronous
    mode.
  x-api-slug: apiv2executionasync-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executionasync-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration.
  x-api-slug: apiv2execution-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
    This API will execute the orchestration in synchronous mode and if the execution
    is not completed  in 1 minute then the request will fail. After successful completion,
    the response will contain each orchestration steps output data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2execution-post-openapi.md
- name: Analytics Framework - Execute the specified orchestration.
  x-api-slug: apiv1execution-post
  description: To successfully execute the orchestration, the OrchestrationRequest
    must contain valid orchestration id, bpmn workflow xml and optionally input data
    for each analytic step defined in the workflow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1execution-post-openapi.md
- name: Analytics Framework - Execute an analytic by analytic catalog entry id.
  x-api-slug: apiv1cataloganalyticsidexecution-post
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1cataloganalyticsidexecution-post-openapi.md
- name: Analytics Framework - Execute the analytic asynchronously using input data.
  x-api-slug: apiv1analyticexecutionasync-post
  description: Execute the analytic asynchronously with the given input data payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecutionasync-post-openapi.md
- name: Analytics Framework - Execute the analytic synchronously.
  x-api-slug: apiv1analyticexecution-post
  description: Execute the analytic synchronously with the given execution payload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1analyticexecution-post-openapi.md
- name: Analytics Runtime - Retrieve orchestration execution result
  x-api-slug: apiv1monitoringorchestrationsorchestrationrequestid-get
  description: Returns orchestration execution result for the given orchestration
    request id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1monitoringorchestrationsorchestrationrequestid-get-openapi.md
- name: Analytics Runtime - Retrieve job execution history of the given job.
  x-api-slug: apiv1schedulerjobsidhistory-get
  description: Retrieve job execution history
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1schedulerjobsidhistory-get-openapi.md
- name: Analytics Runtime - Execute the specified orchestration.
  x-api-slug: apiv1execution-post
  description: To successfully execute the orchestration, the OrchestrationRequest
    must contain valid orchestration id, bpmn workflow xml and optionally input data
    for each analytic step defined in the workflow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1execution-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration.
  x-api-slug: apiv2execution-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
    This API will execute the orchestration in synchronous mode and if the execution
    is not completed  in 1 minute then the request will fail. After successful completion,
    the response will contain each orchestration steps output data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2execution-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration in asynchronous mode.
  x-api-slug: apiv2executionasync-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executionasync-post-openapi.md
- name: Analytics Runtime - Execute the orchestration with given bpmn and input data.
  x-api-slug: apiv2executiontestrun-post
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executiontestrun-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration.
  x-api-slug: apiv1execution-post
  description: To successfully execute the orchestration, the OrchestrationRequest
    must contain valid orchestration id, bpmn workflow xml and optionally input data
    for each analytic step defined in the workflow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1execution-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration.
  x-api-slug: apiv2execution-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
    This API will execute the orchestration in synchronous mode and if the execution
    is not completed  in 1 minute then the request will fail. After successful completion,
    the response will contain each orchestration steps output data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2execution-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration in asynchronous mode.
  x-api-slug: apiv2executionasync-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executionasync-post-openapi.md
- name: Analytics Runtime - Execute the orchestration with given bpmn and input data.
  x-api-slug: apiv2executiontestrun-post
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executiontestrun-post-openapi.md
- name: Analytics Runtime - Execute the orchestration with given bpmn and input data.
  x-api-slug: apiv2executiontestrun-post
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executiontestrun-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration in asynchronous mode.
  x-api-slug: apiv2executionasync-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2executionasync-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration.
  x-api-slug: apiv2execution-post
  description: To successfully execute the orchestration, the OrchestrationExecutionRequest
    must contain valid orchestration id, asset id, asset data field mapping details.
    This API will execute the orchestration in synchronous mode and if the execution
    is not completed  in 1 minute then the request will fail. After successful completion,
    the response will contain each orchestration steps output data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv2execution-post-openapi.md
- name: Analytics Runtime - Execute the specified orchestration.
  x-api-slug: apiv1execution-post
  description: To successfully execute the orchestration, the OrchestrationRequest
    must contain valid orchestration id, bpmn workflow xml and optionally input data
    for each analytic step defined in the workflow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/predix/apiv1execution-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
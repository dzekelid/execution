---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Framework Execute an analytic by analytic catalog entry
    id.
  version: 1.0.0
  description: This operation executes the specified analytic and responds with the
    result produced by analytic.
host: predix-acs.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/analytic/execution/async/{requestId}:
    delete:
      summary: Cleanup analytic execution result by request id.
      description: Removes the analytic execution result from the cache. It is highly
        recommended to clean your old result data to have room for future result data.
      operationId: clearAnalyticExecutionResult
      x-api-path-slug: apiv1analyticexecutionasyncrequestid-delete
      parameters:
      - in: header
        name: Authorization
      - in: header
        name: Predix-Zone-Id
      - in: path
        name: requestId
      responses:
        2:
          description: Successful response
      tags:
      - Cleanup
      - Analytic
      - Execution
      - Result
      - By
      - Request
      - Id
  /api/v1/analytic/execution/async/{requestId}/result:
    get:
      summary: Get the analytic execution result by request id.
      description: Returns the analytic execution result.
      operationId: retrieveAnalyticExecutionResult
      x-api-path-slug: apiv1analyticexecutionasyncrequestidresult-get
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      - in: path
        name: requestId
        description: analytic execution request id
      responses:
        2:
          description: Successful response
      tags:
      - Analytic
      - Execution
      - Result
      - By
      - Request
      - Id
  /api/v1/analytic/execution/async/{requestId}/status:
    get:
      summary: Get the analytic execution status by request id.
      description: Returns the analytic execution status (one of QUEUED, PROCESSING,
        COMPLETED, or FAILED).
      operationId: retrieveAnalyticExecutionStatus
      x-api-path-slug: apiv1analyticexecutionasyncrequestidstatus-get
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      - in: path
        name: requestId
        description: analytic execution request id
      responses:
        2:
          description: Successful response
      tags:
      - Analytic
      - Execution
      - Status
      - By
      - Request
      - Id
  /api/v1/analytic/execution:
    post:
      summary: Execute the analytic synchronously.
      description: Execute the analytic synchronously with the given execution payload.
      operationId: synchronousExecution
      x-api-path-slug: apiv1analyticexecution-post
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: body
        name: body
        description: request payload containing analytic input data
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Analytic
      - Synchronously
  /api/v1/analytic/execution/async:
    post:
      summary: Execute the analytic asynchronously using input data.
      description: Execute the analytic asynchronously with the given input data payload.
      operationId: asynchronousExecution
      x-api-path-slug: apiv1analyticexecutionasync-post
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: body
        name: body
        description: request payload containing analytic input data
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Analytic
      - Asynchronously
      - Using
      - Input
      - Data
  /api/v1/catalog/analytics/{id}/execution:
    post:
      summary: Execute an analytic by analytic catalog entry id.
      description: This operation executes the specified analytic and responds with
        the result produced by analytic.
      operationId: executeAnalytic
      x-api-path-slug: apiv1cataloganalyticsidexecution-post
      parameters:
      - in: body
        name: body
        description: request payload containing analytic input data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: analytic catalog entry id
      - in: query
        name: inputId
        description: test artifact id
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Analytic
      - By
      - Analytic
      - Catalog
      - Entry
      - Id
  /api/v1/monitoring/orchestrations/{orchestrationRequestId}:
    get:
      summary: Retrieve orchestration execution result
      description: Returns orchestration execution result for the given orchestration
        request id.
      operationId: retrieveOrchestrationResult
      x-api-path-slug: apiv1monitoringorchestrationsorchestrationrequestid-get
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: path
        name: orchestrationRequestId
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      responses:
        2:
          description: Successful response
      tags:
      - Retrieve
      - Orchestration
      - Execution
      - Result
  /api/v1/scheduler/jobs/{id}/history:
    get:
      summary: Retrieve job execution history of the given job.
      description: Retrieve job execution history
      operationId: retrieveJobHistory
      x-api-path-slug: apiv1schedulerjobsidhistory-get
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: query
        name: endTime
        description: End time in millis
      - in: path
        name: id
        description: Job id
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      - in: query
        name: startTime
        description: Start time in millis
      responses:
        2:
          description: Successful response
      tags:
      - Retrieve
      - Job
      - Execution
      - History
      - Of
      - Given
      - Job
  /api/v1/execution:
    post:
      summary: Execute the specified orchestration.
      description: To successfully execute the orchestration, the OrchestrationRequest
        must contain valid orchestration id, bpmn workflow xml and optionally input
        data for each analytic step defined in the workflow.
      operationId: run
      x-api-path-slug: apiv1execution-post
      parameters:
      - in: body
        name: body
        description: orchestration execution request
        schema:
          $ref: '#/definitions/holder'
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Specified
      - Orchestration
  /api/v2/execution:
    post:
      summary: Execute the specified orchestration.
      description: To successfully execute the orchestration, the OrchestrationExecutionRequest
        must contain valid orchestration id, asset id, asset data field mapping details.
        This API will execute the orchestration in synchronous mode and if the execution
        is not completed  in 1 minute then the request will fail. After successful
        completion, the response will contain each orchestration steps output data.
      operationId: runSyncV2
      x-api-path-slug: apiv2execution-post
      parameters:
      - in: body
        name: body
        description: orchestration execution request
        schema:
          $ref: '#/definitions/holder'
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Specified
      - Orchestration
  /api/v2/execution/async:
    post:
      summary: Execute the specified orchestration in asynchronous mode.
      description: To successfully execute the orchestration, the OrchestrationExecutionRequest
        must contain valid orchestration id, asset id, asset data field mapping details.
      operationId: runAsync
      x-api-path-slug: apiv2executionasync-post
      parameters:
      - in: body
        name: body
        description: orchestration execution request
        schema:
          $ref: '#/definitions/holder'
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Specified
      - Orchestration
      - In
      - Asynchronous
      - Mode
  /api/v2/execution/testrun:
    post:
      summary: Execute the orchestration with given bpmn and input data.
      description: To successfully execute the orchestration, the request must contain
        valid bpmn20.xml, input data for each step in the bpmn.
      operationId: testRun
      x-api-path-slug: apiv2executiontestrun-post
      parameters:
      - in: formData
        name: bpmn
        description: BPMN file
      - in: formData
        name: input
        description: Input data file
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Orchestration
      - Given
      - Bpmn
      - Input
      - Data
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
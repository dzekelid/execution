---
swagger: "2.0"
x-collection-name: Firebase
x-complete: 0
info:
  title: Firebase Create Execution Steps
  description: |-
    Creates a Step.

    The returned Step will have the id set.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the step is too large (more than 10Mib) - NOT_FOUND - if the containing Execution does not exist
  version: 1.0.0
host: '{project_id].firebaseio.co}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{projectId}/histories/{historyId}/executions:
    post:
      summary: Create Execution
      description: |-
        Creates an Execution.

        The returned Execution will have the id set.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the containing History does not exist
      operationId: toolresults.projects.histories.executions.create
      x-api-path-slug: projectidhistorieshistoryidexecutions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: historyId
        description: A History id
      - in: path
        name: projectId
        description: A Project id
      - in: query
        name: requestId
        description: A unique request ID for server to detect duplicated requests
      responses:
        200:
          description: OK
      tags:
      - Execution
  /{projectId}/histories/{historyId}/executions/{executionId}:
    get:
      summary: Get Execution
      description: |-
        Gets an Execution.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the Execution does not exist
      operationId: toolresults.projects.histories.executions.get
      x-api-path-slug: projectidhistorieshistoryidexecutionsexecutionid-get
      parameters:
      - in: path
        name: executionId
        description: An Execution id
      - in: path
        name: historyId
        description: A History id
      - in: path
        name: projectId
        description: A Project id
      responses:
        200:
          description: OK
      tags:
      - Execution
    patch:
      summary: Update Execution
      description: |-
        Updates an existing Execution with the supplied partial entity.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the requested state transition is illegal - NOT_FOUND - if the containing History does not exist
      operationId: toolresults.projects.histories.executions.patch
      x-api-path-slug: projectidhistorieshistoryidexecutionsexecutionid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: executionId
        description: Required
      - in: path
        name: historyId
        description: Required
      - in: path
        name: projectId
        description: A Project id
      - in: query
        name: requestId
        description: A unique request ID for server to detect duplicated requests
      responses:
        200:
          description: OK
      tags:
      - Execution
  /{projectId}/histories/{historyId}/executions/{executionId}/steps:
    get:
      summary: Get Execution Steps
      description: |-
        Lists Steps for a given Execution.

        The steps are sorted by creation_time in descending order. The step_id key will be used to order the steps with the same creation_time.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to read project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if an argument in the request happens to be invalid; e.g. if an attempt is made to list the children of a nonexistent Step - NOT_FOUND - if the containing Execution does not exist
      operationId: toolresults.projects.histories.executions.steps.list
      x-api-path-slug: projectidhistorieshistoryidexecutionsexecutionidsteps-get
      parameters:
      - in: path
        name: executionId
        description: A Execution id
      - in: path
        name: historyId
        description: A History id
      - in: query
        name: pageSize
        description: The maximum number of Steps to fetch
      - in: query
        name: pageToken
        description: A continuation token to resume the query at the next item
      - in: path
        name: projectId
        description: A Project id
      responses:
        200:
          description: OK
      tags:
      - Execution Step
    post:
      summary: Create Execution Steps
      description: |-
        Creates a Step.

        The returned Step will have the id set.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the step is too large (more than 10Mib) - NOT_FOUND - if the containing Execution does not exist
      operationId: toolresults.projects.histories.executions.steps.create
      x-api-path-slug: projectidhistorieshistoryidexecutionsexecutionidsteps-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: executionId
        description: A Execution id
      - in: path
        name: historyId
        description: A History id
      - in: path
        name: projectId
        description: A Project id
      - in: query
        name: requestId
        description: A unique request ID for server to detect duplicated requests
      responses:
        200:
          description: OK
      tags:
      - Execution Step
  /{projectId}/histories/{historyId}/executions/{executionId}/steps/{stepId}:
    get:
      summary: Get Execution Step
      description: |-
        Gets a Step.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to read project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the Step does not exist
      operationId: toolresults.projects.histories.executions.steps.get
      x-api-path-slug: projectidhistorieshistoryidexecutionsexecutionidstepsstepid-get
      parameters:
      - in: path
        name: executionId
        description: A Execution id
      - in: path
        name: historyId
        description: A History id
      - in: path
        name: projectId
        description: A Project id
      - in: path
        name: stepId
        description: A Step id
      responses:
        200:
          description: OK
      tags:
      - Execution Step
    patch:
      summary: Update Execution Step
      description: |-
        Updates an existing Step with the supplied partial entity.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to write project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the requested state transition is illegal (e.g try to upload a duplicate xml file), if the updated step is too large (more than 10Mib) - NOT_FOUND - if the containing Execution does not exist
      operationId: toolresults.projects.histories.executions.steps.patch
      x-api-path-slug: projectidhistorieshistoryidexecutionsexecutionidstepsstepid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: executionId
        description: A Execution id
      - in: path
        name: historyId
        description: A History id
      - in: path
        name: projectId
        description: A Project id
      - in: query
        name: requestId
        description: A unique request ID for server to detect duplicated requests
      - in: path
        name: stepId
        description: A Step id
      responses:
        200:
          description: OK
      tags:
      - Execution Step
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
---
swagger: "2.0"
x-collection-name: Firebase
x-complete: 0
info:
  title: Firebase Create Execution
  description: |-
    Creates an Execution.

    The returned Execution will have the id set.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the containing History does not exist
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
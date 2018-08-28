---
swagger: "2.0"
x-collection-name: AWS Step Functions
x-complete: 0
info:
  title: AWS Step Functions API Describe Execution
  version: 1.0.0
  description: Describes an execution.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeExecution:
    get:
      summary: Describe Execution
      description: Describes an execution.
      operationId: describeExecution
      x-api-path-slug: actiondescribeexecution-get
      parameters:
      - in: query
        name: executionArn
        description: The Amazon Resource Name (ARN) of the execution to describe
        type: string
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
---
swagger: "2.0"
x-collection-name: AWS Step Functions
x-complete: 0
info:
  title: AWS Step Functions API List Executions
  version: 1.0.0
  description: Lists the executions of a state machine that meet the filtering criteria.
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
  /?Action=GetExecutionHistory:
    get:
      summary: Get Execution History
      description: Returns the history of the specified execution as a list of events.
      operationId: getExecutionHistory
      x-api-path-slug: actiongetexecutionhistory-get
      parameters:
      - in: query
        name: executionArn
        description: The Amazon Resource Name (ARN) of the execution
        type: string
      - in: query
        name: maxResults
        description: The maximum number of results that will be returned per call
        type: string
      - in: query
        name: nextToken
        description: If a nextToken was returned by a previous call, there are more
          results available
        type: string
      - in: query
        name: reverseOrder
        description: Lists events in descending order of their timeStamp
        type: string
      responses:
        200:
          description: OK
      tags:
      - Execution
  /?Action=StopExecution:
    get:
      summary: Stop Execution
      description: Stops an execution.
      operationId: stopExecution
      x-api-path-slug: actionstopexecution-get
      parameters:
      - in: query
        name: cause
        description: A more detailed explanation of the cause of the termination
        type: string
      - in: query
        name: error
        description: An arbitrary error code that identifies the cause of the termination
        type: string
      - in: query
        name: executionArn
        description: The Amazon Resource Name (ARN) of the execution to stop
        type: string
      responses:
        200:
          description: OK
      tags:
      - Execution
  /?Action=ListExecutions:
    get:
      summary: List Executions
      description: Lists the executions of a state machine that meet the filtering
        criteria.
      operationId: listExecutions
      x-api-path-slug: actionlistexecutions-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of results that will be returned per call
        type: string
      - in: query
        name: nextToken
        description: If a nextToken was returned by a previous call, there are more
          results available
        type: string
      - in: query
        name: stateMachineArn
        description: The Amazon Resource Name (ARN) of the state machine whose executions
          will be listed
        type: string
      - in: query
        name: statusFilter
        description: If specified, only list the executions whose current execution
          status matches the given filter
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
  /?Action=StartExecution:
    get:
      summary: Start Execution
      description: Starts a state machine execution.
      operationId: startExecution
      x-api-path-slug: actionstartexecution-get
      parameters:
      - in: query
        name: input
        description: The JSON input data for the execution
        type: string
      - in: query
        name: name
        description: The name of the execution
        type: string
      - in: query
        name: stateMachineArn
        description: The Amazon Resource Name (ARN) of the state machine to execute
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
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
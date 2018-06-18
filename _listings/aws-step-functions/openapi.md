---
swagger: "2.0"
x-collection-name: AWS Step Functions
x-complete: 1
info:
  title: AWS Step Functions API
  version: 1.0.0
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
        apps:
          description: app_allow
        devices:
          description: device_link
        members:
          description: member_invite
        passwords:
          description: tfa_enable
        sharing:
          description: shmodel_create
        team_admin_actions:
          description: sf_external_accept_allow
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
---
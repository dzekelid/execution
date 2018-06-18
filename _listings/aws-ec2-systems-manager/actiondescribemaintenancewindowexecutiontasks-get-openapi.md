---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 0
info:
  title: Amazon EC2 Systems Manager API Describe Maintenance Window Execution Tasks
  version: 1.0.0
  description: For a given Maintenance Window execution, lists the tasks that were
    executed.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAutomationExecutions:
    get:
      summary: Describe Automation Executions
      description: Provides details about all active and terminated Automation executions.
      operationId: describeAutomationExecutions
      x-api-path-slug: actiondescribeautomationexecutions-get
      parameters:
      - in: query
        name: Filters
        description: Filters used to limit the scope of executions that are requested
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Automation
      - Executions
  /?Action=DescribeMaintenanceWindowExecutions:
    get:
      summary: Describe Maintenance Window Executions
      description: |-
        Lists the executions of a Maintenance Window (meaning, information about when the
           Maintenance Window was scheduled to be active and information about tasks registered and run with
           the Maintenance Window).
      operationId: describeMaintenanceWindowExecutions
      x-api-path-slug: actiondescribemaintenancewindowexecutions-get
      parameters:
      - in: query
        name: Filters
        description: 'Each entry in the array is a structure containing:'
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window whose executions should be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Executions
  /?Action=DescribeMaintenanceWindowExecutionTaskInvocations:
    get:
      summary: Describe Maintenance Window Execution Task Invocations
      description: |-
        Retrieves the individual task executions (one per target) for a particular task executed
           as part of a Maintenance Window execution.
      operationId: describeMaintenanceWindowExecutionTaskInvocations
      x-api-path-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters used to scope down the returned task invocations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: TaskId
        description: The ID of the specific task in the Maintenance Window task that
          should be   retrieved
        type: string
      - in: query
        name: WindowExecutionId
        description: The ID of the Maintenance Window execution the task is part of
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Execution
      - Task
      - Invocations
  /?Action=DescribeMaintenanceWindowExecutionTasks:
    get:
      summary: Describe Maintenance Window Execution Tasks
      description: For a given Maintenance Window execution, lists the tasks that
        were executed.
      operationId: describeMaintenanceWindowExecutionTasks
      x-api-path-slug: actiondescribemaintenancewindowexecutiontasks-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters used to scope down the returned tasks
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: WindowExecutionId
        description: The ID of the Maintenance Window execution whose task executions
          should be   retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Execution
      - Tasks
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
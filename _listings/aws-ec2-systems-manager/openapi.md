---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 1
info:
  title: AWS EC2 Systems Manager API
  version: 1.0.0
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
  /?Action=GetAutomationExecution:
    get:
      summary: Get Automation Execution
      description: Get detailed information about a particular Automation execution.
      operationId: getAutomationExecution
      x-api-path-slug: actiongetautomationexecution-get
      parameters:
      - in: query
        name: AutomationExecutionId
        description: The unique identifier for an existing automation execution to
          examine
        type: string
      responses:
        200:
          description: OK
      tags:
      - Automation
      - Execution
  /?Action=GetMaintenanceWindowExecution:
    get:
      summary: Get Maintenance Window Execution
      description: |-
        Retrieves details about a specific task executed as part of a Maintenance Window
           execution.
      operationId: getMaintenanceWindowExecution
      x-api-path-slug: actiongetmaintenancewindowexecution-get
      parameters:
      - in: query
        name: WindowExecutionId
        description: The ID of the Maintenance Window execution that includes the
          task
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Execution
  /?Action=GetMaintenanceWindowExecutionTask:
    get:
      summary: Get Maintenance Window Execution Task
      description: |-
        Retrieves the details about a specific task executed as part of a Maintenance Window
           execution.
      operationId: getMaintenanceWindowExecutionTask
      x-api-path-slug: actiongetmaintenancewindowexecutiontask-get
      parameters:
      - in: query
        name: TaskId
        description: The ID of the specific task execution in the Maintenance Window
          task that should be   retrieved
        type: string
      - in: query
        name: WindowExecutionId
        description: The ID of the Maintenance Window execution that includes the
          task
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Execution
      - Task
  /?Action=StartAutomationExecution:
    get:
      summary: Start Automation Execution
      description: Initiates execution of an Automation document.
      operationId: startAutomationExecution
      x-api-path-slug: actionstartautomationexecution-get
      parameters:
      - in: query
        name: DocumentName
        description: The name of the Automation document to use for this execution
        type: string
      - in: query
        name: DocumentVersion
        description: The version of the Automation document to use for this execution
        type: string
      - in: query
        name: Parameters
        description: A key-value map of execution parameters, which match the declared
          parameters in the Automation document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Start
      - Automation
      - Execution
  /?Action=StopAutomationExecution:
    get:
      summary: Stop Automation Execution
      description: Stop an Automation that is currently executing.
      operationId: stopAutomationExecution
      x-api-path-slug: actionstopautomationexecution-get
      parameters:
      - in: query
        name: AutomationExecutionId
        description: The execution ID of the Automation to stop
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Automation
      - Execution
---
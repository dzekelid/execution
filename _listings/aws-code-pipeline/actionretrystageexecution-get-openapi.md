---
swagger: "2.0"
x-collection-name: AWS Code Pipeline
x-complete: 0
info:
  title: AWS Code Pipeline API Retry Stage Execution
  version: 1.0.0
  description: |-
    Resumes the pipeline execution by retrying the last failed actions in a
                stage.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetPipelineExecution:
    get:
      summary: Get Pipeline Execution
      description: |-
        Returns information about an execution of a pipeline, including details about
                    artifacts, the pipeline execution ID, and the name, version, and status of the
                    pipeline.
      operationId: getPipelineExecution
      x-api-path-slug: actiongetpipelineexecution-get
      parameters:
      - in: query
        name: AutoEnableIO
        description: Indicates whether the volume should be auto-enabled for I/O operations
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: pipelineExecutionId
        description: The ID of the pipeline execution about which you want to get
          execution            details
        type: string
      - in: query
        name: pipelineName
        description: The name of the pipeline about which you want to get execution
          details
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
      - Execution
  /?Action=RetryStageExecution:
    get:
      summary: Retry Stage Execution
      description: |-
        Resumes the pipeline execution by retrying the last failed actions in a
                    stage.
      operationId: retryStageExecution
      x-api-path-slug: actionretrystageexecution-get
      parameters:
      - in: query
        name: Description
        description: A description for the network interface
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Ipv6AddressCount
        description: The number of IPv6 addresses to assign to a network interface
        type: string
      - in: query
        name: Ipv6Addresses.N
        description: One or more specific IPv6 addresses from the IPv6 CIDR block
          range of your subnet
        type: string
      - in: query
        name: pipelineExecutionId
        description: The ID of the pipeline execution in the failed stage to be retried
        type: string
      - in: query
        name: pipelineName
        description: The name of the pipeline that contains the failed stage
        type: string
      - in: query
        name: PrivateIpAddress
        description: The primary private IPv4 address of the network interface
        type: string
      - in: query
        name: PrivateIpAddresses.N
        description: One or more private IPv4 addresses
        type: string
      - in: query
        name: retryMode
        description: The scope of the retry attempt
        type: string
      - in: query
        name: SecondaryPrivateIpAddressCount
        description: The number of secondary private IPv4 addresses to assign to a
          network interface
        type: string
      - in: query
        name: SecurityGroupId.N
        description: The IDs of one or more security groups
        type: string
      - in: query
        name: stageName
        description: The name of the failed stage to be retried
        type: string
      - in: query
        name: SubnetId
        description: The ID of the subnet to associate with the network interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Retry
      - Stage
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
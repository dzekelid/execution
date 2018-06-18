---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/batch/action/resetJobExecutionAttempts:
    get:
      summary: Get Service Batch Action Resetjobexecutionattempts
      description: batch resetJobExecutionAttempts action resets the execution attempts
        of the job
      operationId: batch.resetJobExecutionAttempts
      x-api-path-slug: servicebatchactionresetjobexecutionattempts-get
      parameters:
      - in: query
        name: id
        description: The id of the job
      - in: query
        name: jobType
        description: 'Enum Type: `KalturaBatchJobType`The type of the job'
      - in: query
        name: lockKey[batchIndex]
      - in: query
        name: lockKey[schedulerId]
      - in: query
        name: lockKey[workerId]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - ResetJobExecutionAttempts
---
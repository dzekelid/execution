---
swagger: "2.0"
x-collection-name: IBM Financial Crimes Insight for Insurance
x-complete: 0
info:
  title: IBM Financial Crimes Insight for Insurance API Obtain security token for
    REST execution
  description: In addition to a username and password required to execute a REST service,
    the platform supports enhanced cross site scripting detection and requires a service
    token for REST API execution.  REST services will need to supply the token as
    both cookie and header in a REST request.
  version: 1.0.0
host: fcihost.ibm.com:9443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ibm/fci/platform/token_service/token:
    get:
      summary: Obtain security token for REST execution
      description: In addition to a username and password required to execute a REST
        service, the platform supports enhanced cross site scripting detection and
        requires a service token for REST API execution.  REST services will need
        to supply the token as both cookie and header in a REST request.
      operationId: getServiceToken
      x-api-path-slug: ibmfciplatformtoken-servicetoken-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      responses:
        200:
          description: OK
      tags:
      - Obtain
      - Security
      - TokenREST
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
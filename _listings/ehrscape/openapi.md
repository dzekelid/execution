swagger: "2.0"
x-collection-name: EhrScape
x-complete: 1
info:
  title: EhrScape Terminology APIs
  description: validates-and-resolves-terminology-codes
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: rest.ehrscape.com
basePath: /terminology-adapter/rest
paths:
  /guide/execute/{guideId}/{ehrIds}:
    get:
      summary: Execute guide on given EHR IDs
      description: Execute guide on given ehr ids.
      operationId: executeGuide
      x-api-path-slug: guideexecuteguideidehrids-get
      parameters:
      - in: header
        name: Authorization
        description: ThinkEhr credentials as HTTP Basic Authorization
      - in: header
        name: Ehr-Session
        description: Active Ehr Session token
      - in: path
        name: ehrIds
        description: Comma separated list of EHR ids, * for all
      - in: path
        name: guideId
        description: Guide ID
      - in: query
        name: persist
        description: Should save result of execution into EHR?
      responses:
        200:
          description: OK
      tags:
      - Guide
      - Execute
      - GuideId
      - EhrIds
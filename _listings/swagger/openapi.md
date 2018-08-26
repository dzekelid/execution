---
swagger: "2.0"
x-collection-name: Swagger
x-complete: 1
info:
  title: Swagger Hub Registry
  description: the-registry-api-for-swaggerhub
  contact:
    name: SwaggerHub
    url: http://swaggerhub.com
    email: info@swaggerhub.com
  version: 1.0.45
host: api.swaggerhub.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /plugins/configurations/execute/{id}:
    post:
      summary: triggers execution of plugin configuration identified by id
      description: Triggers execution of plugin configuration identified by id.
      operationId: triggerPluginConfiguration
      x-api-path-slug: pluginsconfigurationsexecuteid-post
      parameters:
      - in: path
        name: id
        description: plugin configuration id
      responses:
        200:
          description: OK
      tags:
      - Plugins
      - Configurations
      - Execute
      - Id
---
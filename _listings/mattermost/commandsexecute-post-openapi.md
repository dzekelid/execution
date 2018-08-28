---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Execute a command
  description: |-
    Execute a command on a team.
    ##### Permissions
    Must have `use_slash_commands` permission for the team the command is in.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /commands/execute:
    post:
      summary: Execute a command
      description: |-
        Execute a command on a team.
        ##### Permissions
        Must have `use_slash_commands` permission for the team the command is in.
      operationId: execute-a-command-on-a-team-permissionsmust-have-use-slash-commands-permission-for-the-team-the-comm
      x-api-path-slug: commandsexecute-post
      parameters:
      - in: body
        name: body
        description: command to be executed
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Execute
      - Command
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
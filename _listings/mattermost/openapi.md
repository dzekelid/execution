swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
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
---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Disable personal access token
  description: |-
    Disable a personal access token and delete any sessions using the token. The token can be re-enabled using `/users/tokens/enable`.

    __Minimum server version__: 4.4

    ##### Permissions
    Must have `revoke_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
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
  /users/tokens/disable:
    post:
      summary: Disable personal access token
      description: |-
        Disable a personal access token and delete any sessions using the token. The token can be re-enabled using `/users/tokens/enable`.

        __Minimum server version__: 4.4

        ##### Permissions
        Must have `revoke_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
      operationId: disable-a-personal-access-token-and-delete-any-sessions-using-the-token-the-token-can-be-reenabled-u
      x-api-path-slug: userstokensdisable-post
      parameters:
      - in: body
        name: token
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Disable
      - Personal
      - Access
      - Token
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
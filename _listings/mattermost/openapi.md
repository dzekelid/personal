---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost API Reference
  description: -api-v4-is-stable-with-the-mattermost-server-40-release-api-v3-was-deprecated-on-january-16th-2018-and-scheduled-for-removal-in-mattermost-v50-details-heretagapiv3deprecation-looking-for-the-api-v3-reference-it-has-moved-herehttpsapimattermostcomv3
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
  /users/tokens/enable:
    post:
      summary: Enable personal access token
      description: |-
        Re-enable a personal access token that has been disabled.

        __Minimum server version__: 4.4

        ##### Permissions
        Must have `create_user_access_token` permission. For non-self requests, must also have the `edit_other_users` permission.
      operationId: reenable-a-personal-access-token-that-has-been-disabled-minimum-server-version--44-permissionsmust-h
      x-api-path-slug: userstokensenable-post
      parameters:
      - in: body
        name: token
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Enable
      - Personal
      - Access
      - Token
---
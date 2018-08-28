---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get User Personal Ad Accounts
  description: User Personal Ad Accounts
  termsOfService: https://www.facebook.com/policies/
  version: 1.0.0
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;user-id&#125;/personal_ad_accounts:
    get:
      summary: Get User Personal Ad Accounts
      description: User Personal Ad Accounts
      operationId: getUserPersonalAdAccounts
      x-api-path-slug: 123userid125personal-ad-accounts-get
      parameters:
      - in: query
        name: total_countunsigned int32
        description: Total number of connected ad accounts
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Personal
      - Ad
      - Accounts
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
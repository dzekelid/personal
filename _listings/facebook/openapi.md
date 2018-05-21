---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 1
info:
  title: Facebook Graph (Achievement Type) API
  description: api-for-managing-facebook-achievement-types
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
---
---
swagger: "2.0"
x-collection-name: HSBC
x-complete: 1
info:
  title: HSBC
  description: this-is-an-openapi-definition-for-the-standard-set-of-open-banking-httpopenbankingapisio-apis-for-hsbc
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: api.hsbc.com
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  personal-current-accounts/:
    get:
      summary: Get Current Personal Accounts
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple PCA products.
      operationId: getCurrentPersonalAccounts
      x-api-path-slug: personalcurrentaccounts-get
      responses:
        200:
          description: OK
      tags:
      - Personal
      - Current
      - Accounts
---
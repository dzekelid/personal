---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Requests the activation of a car rental certificate linked
    to a product. At least one product_criteria has to be specified to identify the
    product to which to subscribe. If the user already holds a certificate, this api
    will update its personal infor
  description: Requests the activation of a car rental certificate linked to a product.
    At least one product_criteria has to be specified to identify the product to which
    to subscribe. If the user already holds a certificate, this api will update its
    personal infor
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sales/v1/individual/car_rental/certificates:
    post:
      summary: Requests the activation of a car rental certificate linked to a product.
        At least one product_criteria has to be specified to identify the product
        to which to subscribe. If the user already holds a certificate, this api will
        update its personal infor
      description: Requests the activation of a car rental certificate linked to a
        product. At least one product_criteria has to be specified to identify the
        product to which to subscribe. If the user already holds a certificate, this
        api will update its personal infor
      operationId: postSalesV1IndividualCar_rentalCertificates
      x-api-path-slug: salesv1individualcar-rentalcertificates-post
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - RequestAssistance
      - the
      - activation
      - ofcar
      - rental
      - certificate
      - linked
      - toproduct.
      - At
      - leastproduct_criteria
      - haAssistance
      - to
      - be
      - specified
      - to
      - identify
      - the
      - product
      - to
      - which
      - to
      - subscribe.
      - If
      - the
      - user
      - already
      - holdscertificate
      - ""
      - thiAssistance
      - api
      - will
      - update
      - itAssistance
      - personal
      - infor
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
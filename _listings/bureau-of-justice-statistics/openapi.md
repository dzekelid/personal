swagger: "2.0"
x-collection-name: Bureau of Justice Statistics
x-complete: 1
info:
  title: National Crime Victimization Survey (NCVS) API
  description: the-ncvs-national-crime-victimization-survey-restful-api-is-a-web-service-that-provides-criminal-victimization-data-obtained-annually-from-a-nationally-representative-sample-of-about-79800-households-and-143210-persons-interviewed-each-year--
  version: v2
host: www.bjs.gov
basePath: /bjs/ncvs/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  v2/personal/fields/:
    get:
      summary: Get Personal Fields
      description: Returns a description of the fields/columns used returned in the
        personal data sets.
      operationId: getV2PersonalFields
      x-api-path-slug: v2personalfields-get
      responses:
        200:
          description: OK
      tags:
      - Personal
      - Fields
  v2/personal/population/{year}:
    get:
      summary: Get Personal Population Year
      description: Returns the personal population of reported incidents.
      operationId: getV2PersonalPopulationYear
      x-api-path-slug: v2personalpopulationyear-get
      parameters:
      - in: query
        name: format
        description: Format the data will be provided in
      - in: query
        name: year
        description: Year will limit the data to only values that occurred the given
          year
      responses:
        200:
          description: OK
      tags:
      - Personal
      - Population
      - Year
  v2/personal/{year}:
    get:
      summary: Get Personal Year
      description: Returns the personal counts of reported incidents.
      operationId: getV2PersonalYear
      x-api-path-slug: v2personalyear-get
      parameters:
      - in: query
        name: format
        description: Format the data will be provided in
      - in: query
        name: year
        description: Year will limit the data to only values that occurred the given
          year
      responses:
        200:
          description: OK
      tags:
      - Personal
      - Year
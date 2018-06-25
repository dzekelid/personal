---
name: Bureau of Justice Statistics
x-slug: bureau-of-justice-statistics
description: The United States Bureau of Justice Statistics (BJS) is a federal government
  agency belonging to the U.S. Department of Justice and a principal agency of the
  U.S. Federal Statistical System. Established on December 27, 1979, the bureau collects,
  analyzes and publishes data relating to crime in the United States. The agency publishes
  data regarding statistics gathered from the roughly fifty-thousand agencies that
  comprise the U.S. justice system on its Web site.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/US-DeptOfJustice-Seal.svg.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Personal
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/apis.md
specificationVersion: "0.14"
apis:
- name: National Crime Victimization Survey (NCVS) API Get Personal Fields
  x-api-slug: national-crime-victimization-survey-ncvs-api
  description: Returns a description of the fields/columns used returned in the personal
    data sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/US-DeptOfJustice-Seal.svg.png
  humanURL: http://bjs.gov
  baseURL: http://www.bjs.gov//bjs/ncvs//v2/personal/fields/
  tags: Personal,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/v2personalfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/v2personalfields-get-openapi.md
- name: National Crime Victimization Survey (NCVS) API Get Personal Population Year
  x-api-slug: national-crime-victimization-survey-ncvs-api
  description: Returns the personal population of reported incidents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/US-DeptOfJustice-Seal.svg.png
  humanURL: http://bjs.gov
  baseURL: http://www.bjs.gov//bjs/ncvs//v2/personal/population/{year}
  tags: Personal,Population,Year
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/v2personalpopulationyear-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/v2personalpopulationyear-get-openapi.md
- name: National Crime Victimization Survey (NCVS) API Get Personal Year
  x-api-slug: national-crime-victimization-survey-ncvs-api
  description: Returns the personal counts of reported incidents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/US-DeptOfJustice-Seal.svg.png
  humanURL: http://bjs.gov
  baseURL: http://www.bjs.gov//bjs/ncvs//v2/personal/{year}
  tags: Personal,Year
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/v2personalyear-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/v2personalyear-get-openapi.md
- name: National Crime Victimization Survey (NCVS) API
  x-api-slug: national-crime-victimization-survey-ncvs-api
  description: NCVS data describe the frequency, characteristics and consequences
    of criminal victimization in the United States. The NCVS provides the largest
    national forum for victims to describe the impact of crime and characteristics
    of violent offenders. It is one of two primary data collections about crime in
    the United States and is the only source of data about crimes not reported to
    the police. The NCVS API page provides developers with end-points in XML, JSON,
    and CSV formats along with related codebooks, methodology, metadata and usage
    instructions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/US-DeptOfJustice-Seal.svg.png
  humanURL: http://bjs.gov
  baseURL: http://www.bjs.gov//bjs/ncvs/
  tags: Personal
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/personal/master/_listings/bureau-of-justice-statistics/openapi.md
x-common:
- type: x-developer
  url: http://www.bjs.gov/developer/
- type: x-website
  url: http://bjs.gov
- type: x-website
  url: http://www.bjs.gov
- type: x-wikipedia
  url: http://en.wikipedia.org/wiki/Bureau_of_Justice_Statistics
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
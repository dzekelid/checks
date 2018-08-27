---
name: Pingometer
x-slug: pingometer
description: Pingometer is a service that monitors the uptime, downtime, and performance
  of websites. Get 24/7 monitoring - sign up for your FREE account today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
x-kinRank: "8"
x-alexaRank: "1995680"
tags: Checks
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/apis.md
specificationVersion: "0.14"
apis:
- name: Checks API - Get Checks
  x-api-slug: checks-get
  description: Gets a list of all checks that are visible to you as a user or a customer
    depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checks-get-openapi.md
- name: Checks API - Get Check
  x-api-slug: checkscheckid-get
  description: Gets info about a check, current SLA, last result and its status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckid-get-openapi.md
- name: Checks API - Update Check
  x-api-slug: checkscheckid-put
  description: Updates a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckid-put-openapi.md
- name: Checks API - Delete Check
  x-api-slug: checkscheckid-delete
  description: Deletes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckid-delete-openapi.md
- name: Checks API - Get Checks Lastvalue
  x-api-slug: checkscheckidlastvalue-get
  description: Gets the absolute last value of a specific check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckidlastvalue-get-openapi.md
- name: Checks API - Get Checks Results
  x-api-slug: checkscheckidresultsmillisecondsutc-get
  description: Gets a specific check result by a numeric java timestamp.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckidresultsmillisecondsutc-get-openapi.md
- name: Checks API - Get Checks Results
  x-api-slug: checkscheckidresults-get
  description: Gets the most recent check results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/checkscheckidresults-get-openapi.md
- name: Checks API - Get Check List
  x-api-slug: apiversionchecks-get
  description: Returns a list overview of all checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18847-pingometer.jpg
  humanURL: https://pingometer.com/
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, Stack Network, SaaS, Technology, internet, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingometer/apiversionchecks-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://pingdom.api.gallery.streamdata.io
- type: x-api-stack
  url: http://pingometer.stack.network
- type: x-blog
  url: https://pingometer.com/blog/
- type: x-crunchbase
  url: https://www.crunchbase.com/organization/pingometer
- type: x-crunchbase
  url: https://crunchbase.com/organization/pingometer
- type: x-github
  url: https://github.com/pingometer
- type: x-integrations
  url: https://pingometer.com/integrations/
- type: x-twitter
  url: https://twitter.com/pingometer
- type: x-website
  url: https://pingometer.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
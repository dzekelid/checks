---
name: Pingdom
x-slug: pingdom
description: Monitor your website???s availability and performance for free with Pingdom
  and always be the first to know when your website is down. No installation required.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
x-kinRank: "7"
x-alexaRank: "5592"
tags: Checks
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/apis.md
specificationVersion: "0.14"
apis:
- name: Checks API Checks
  x-api-slug: checks-api
  description: Gets a list of all checks that are visible to you as a user or a customer
    depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checks-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Gets info about a check, current SLA, last result and its status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckid-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Updates a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckid-put-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Deletes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckid-delete-openapi.md
- name: Checks API Checks {checkId} Lastvalue
  x-api-slug: checks-api
  description: Gets the absolute last value of a specific check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/lastvalue '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckidlastvalue-get-openapi.md
- name: Checks API Checks {checkId} Results {millisecondsUtc}?detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets a specific check result by a numeric java timestamp.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results/{millisecondsUtc}
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckidresultsmillisecondsutc-get-openapi.md
- name: Checks API Checks {checkId} Results?mostrecent={mostrecent}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets the most recent check results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckidresults-get-openapi.md
- name: Checks API Checks {checkId} Results?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets check results between two dates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/checkscheckidresults-get-openapi.md
- name: Checks API Get Check List
  x-api-slug: checks-api
  description: Returns a list overview of all checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/checks
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/apiversionchecks-get-openapi.md
- name: Checks API
  x-api-slug: checks-api
  description: Monitor your website???s availability and performance for free with
    Pingdom and always be the first to know when your website is down. No installation
    required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/pingdom/openapi.md
x-common:
- type: x-base
  url: https://api.pingdom.com
- type: x-blog
  url: http://royal.pingdom.com/
- type: x-blog-rss
  url: http://royal.pingdom.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pingdom
- type: x-crunchbase
  url: https://crunchbase.com/organization/pingdom
- type: x-developer
  url: https://www.pingdom.com/features/api/
- type: x-email
  url: sales@pingdom.com
- type: x-github
  url: https://github.com/Pingdom
- type: x-pricing
  url: https://www.pingdom.com/pricing
- type: x-twitter
  url: https://twitter.com/#!/pingdom
- type: x-website
  url: http://www.pingdom.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
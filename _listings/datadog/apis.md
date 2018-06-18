---
name: Datadog
x-slug: datadog
description: See inside any stack, any app, at any scale, anywhere.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
x-kinRank: "8"
x-alexaRank: "13593"
tags: Checks
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/datadog/apis.md
specificationVersion: "0.14"
apis:
- name: DataDog API Add Check Run
  x-api-slug: datadog-api
  description: Post a Check Run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///check_run
  tags: Monitoring,Checks, Run
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/datadog/check-run-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/datadog/check-run-post-openapi.md
- name: DataDog API
  x-api-slug: datadog-api
  description: See inside any stack, any app, at any scale, anywhere.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1/
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/datadog/openapi.md
x-common:
- type: x-blog
  url: https://www.datadoghq.com/blog/
- type: x-blog-rss
  url: https://www.datadoghq.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/datadog
- type: x-email
  url: info@datadoghq.com
- type: x-email
  url: help@datadoghq.com
- type: x-email
  url: legalcompliance@datadoghq.com
- type: x-email
  url: legal@datadoghq.com
- type: x-email
  url: iwant@datadoghq.com
- type: x-github
  url: https://github.com/datadog
- type: x-twitter
  url: https://twitter.com/datadoghq
- type: x-integrations
  url: https://www.datadoghq.com/product/integrations/
- type: x-pricing
  url: https://www.datadoghq.com/pricing/
- type: x-security
  url: https://www.datadoghq.com/security/
- type: x-website
  url: https://www.datadoghq.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
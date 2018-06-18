---
name: Apica
x-slug: apica
description: Apica???s performance testing and monitoring solutions provide critical
  peak performance data and 24/7 monitoring of applications and sites around the world.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
x-kinRank: "7"
x-alexaRank: "827487"
tags: Checks
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/apis.md
specificationVersion: "0.14"
apis:
- name: Checks API Checks
  x-api-slug: checks-api
  description: Gets a list of all checks that are visible to you as a user or a customer
    depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checks-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Gets info about a check, current SLA, last result and its status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckid-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Updates a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckid-put-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Deletes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckid-delete-openapi.md
- name: Checks API Checks {checkId} Lastvalue
  x-api-slug: checks-api
  description: Gets the absolute last value of a specific check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/lastvalue '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidlastvalue-get-openapi.md
- name: Checks API Checks {checkId} Results {millisecondsUtc}?detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets a specific check result by a numeric java timestamp.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results/{millisecondsUtc}
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidresultsmillisecondsutc-get-openapi.md
- name: Checks API Checks {checkId} Results?mostrecent={mostrecent}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets the most recent check results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidresults-get-openapi.md
- name: Checks API Checks {checkId} Results?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets check results between two dates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidresults-get-openapi.md
- name: Checks API Get Check List
  x-api-slug: checks-api
  description: Returns a list overview of all checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/checks
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/apiversionchecks-get-openapi.md
- name: Checks API
  x-api-slug: checks-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com//
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
- name: Checks Command API Checks Command
  x-api-slug: checks-command-api
  description: Creates a new Command check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommand-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommand-post-openapi.md
- name: Checks Command API Checks Command V2
  x-api-slug: checks-command-api
  description: Creates a new Command check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command-v2 '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2-post-openapi.md
- name: Checks Command API Checks Command V2 {checkId}
  x-api-slug: checks-command-api
  description: Updates a command check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command-v2/{checkId} '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2checkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2checkid-put-openapi.md
- name: Checks Command API Checks Command {checkId}
  x-api-slug: checks-command-api
  description: Updates a command check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command/{checkId} '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandcheckid-put-openapi.md
- name: Checks Command API Checks Command Categories
  x-api-slug: checks-command-api
  description: Gets a list of all command check categories that are available for
    you as customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command/categories '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandcategories-get-openapi.md
- name: Checks Command API Checks Command V2 Categories
  x-api-slug: checks-command-api
  description: Gets a list of all command check (version 2) categories that are available
    for you as customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command-v2/categories '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2categories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2categories-get-openapi.md
- name: Checks Command API Checks Command Locations
  x-api-slug: checks-command-api
  description: Gets a list of all locations that are available for Command checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command/locations '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandlocations-get-openapi.md
- name: Checks Command API Checks Command V2 Locations?protocol={protocol}
  x-api-slug: checks-command-api
  description: Gets a list of all locations that are available for Command checks
    (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///checks/command-v2/locations
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2locations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscommandv2locations-get-openapi.md
- name: Checks Command API
  x-api-slug: checks-command-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
- name: Checks Job API Checks {checkId} Job
  x-api-slug: checks-job-api
  description: DEPRECATED. Gets the current job status for a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/{checkId}/job '
  tags: Checks,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidjob-get-openapi.md
- name: Checks Job API Checks {checkId} Job
  x-api-slug: checks-job-api
  description: Executes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/{checkId}/job '
  tags: Checks,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidjob-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkscheckidjob-post-openapi.md
- name: Checks Job API
  x-api-slug: checks-job-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
- name: Checks Ping API Checks Ping
  x-api-slug: checks-ping-api
  description: Creates a new Ping check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/ping '
  tags: Checks,Pings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksping-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksping-post-openapi.md
- name: Checks Ping API Checks Ping {checkId}
  x-api-slug: checks-ping-api
  description: Updates a Ping check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/ping/{checkId} '
  tags: Checks,Pings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkspingcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkspingcheckid-put-openapi.md
- name: Checks Ping API Checks Ping Locations
  x-api-slug: checks-ping-api
  description: Gets a list of all locations that are available for Ping checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/ping/locations '
  tags: Checks,Pings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkspinglocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checkspinglocations-get-openapi.md
- name: Checks Ping API
  x-api-slug: checks-ping-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
- name: Checks Port API Checks Port
  x-api-slug: checks-port-api
  description: Creates a new Port check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/port '
  tags: Checks,Ports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksport-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksport-post-openapi.md
- name: Checks Port API Checks Port {checkId}
  x-api-slug: checks-port-api
  description: Updates a Port check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/port/{checkId} '
  tags: Checks,Ports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksportcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksportcheckid-put-openapi.md
- name: Checks Port API Checks Port Locations
  x-api-slug: checks-port-api
  description: Gets a list of all locations that are available for Port checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/port/locations '
  tags: Checks,Ports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksportlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksportlocations-get-openapi.md
- name: Checks Port API
  x-api-slug: checks-port-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
- name: Checks Proxysniffer Checks Proxysniffer
  x-api-slug: checks-proxysniffer
  description: Creates a new ProxySniffer check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffer-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffer-post-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId}
  x-api-slug: checks-proxysniffer
  description: Updates a proxy sniffer check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId} '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckid-put-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer Locations
  x-api-slug: checks-proxysniffer
  description: Gets a list of all locations that are available for ProxySniffer checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/locations '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysnifferlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysnifferlocations-get-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId} Results {resultId} URLdata?format={format}
  x-api-slug: checks-proxysniffer
  description: Gets a file that contains ProxySniffer check result data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId}/results/{resultId}/urldata?format={format} '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckidresultsresultidurldataformatformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckidresultsresultidurldataformatformat-get-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId} Results URLdata
  x-api-slug: checks-proxysniffer
  description: Gets ProxySniffer check results in json format by result ids.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId}/results/urldata '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckidresultsurldata-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckidresultsurldata-post-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId} Results {resultId} Errorlog
  x-api-slug: checks-proxysniffer
  description: Gets an error log of the given ProxySniffer check result.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId}/results/{resultId}/errorlog '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckidresultsresultiderrorlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksproxysniffercheckidresultsresultiderrorlog-get-openapi.md
- name: Checks Proxysniffer
  x-api-slug: checks-proxysniffer
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
- name: Checks URL Checks URL
  x-api-slug: checks-url
  description: Creates a new URL check (legacy version 1).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurl-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurl-post-openapi.md
- name: Checks URL Checks URL V2
  x-api-slug: checks-url
  description: Creates a new URL check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url-v2 '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlv2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlv2-post-openapi.md
- name: Checks URL Checks URL {checkId}
  x-api-slug: checks-url
  description: Updates a URL check (legacy version 1).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url/{checkId} '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlcheckid-put-openapi.md
- name: Checks URL Checks URL V2 {checkId}
  x-api-slug: checks-url
  description: Updates a URL check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url-v2/{checkId} '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlv2checkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlv2checkid-put-openapi.md
- name: Checks URL Checks URL Locations
  x-api-slug: checks-url
  description: Gets a list of all locations that are available for URL (legacy version
    1) checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url/locations '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurllocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurllocations-get-openapi.md
- name: Checks URL Checks URL V2 Locations
  x-api-slug: checks-url
  description: Gets a list of all locations that are available for URL (version 2)
    checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url-v2/locations '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlv2locations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/checksurlv2locations-get-openapi.md
- name: Checks URL
  x-api-slug: checks-url
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/checks/master/_listings/apica/openapi.md
x-common:
- type: x-blog
  url: https://www.apicasystem.com/blog/
- type: x-blog-rss
  url: https://www.apicasystem.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/apica
- type: x-developer
  url: http://api-wpm.apicasystem.com/v3/help
- type: x-documentation
  url: https://api-wpm.apicasystem.com/v3/Help
- type: x-email
  url: sales@apicasystems.com
- type: x-email
  url: swesales@apicasystems.com
- type: x-email
  url: support@apicasystems.com
- type: x-email
  url: operations@apicasystem.com
- type: x-github
  url: https://github.com/ApicaSystem
- type: x-twitter
  url: https://twitter.com/apicasystems
- type: x-website
  url: https://www.apicasystem.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
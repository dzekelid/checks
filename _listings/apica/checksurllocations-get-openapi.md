---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks URL Checks URL Locations
  version: 1.0.0
  description: Gets a list of all locations that are available for URL (legacy version
    1) checks.
host: api.pingdom.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
basePath: /
paths:
  '/checks ':
    ' get ':
      summary: Get Checks
      description: Gets a list of all checks that are visible to you as a user or
        a customer depending on the request context.
      operationId: getChecks
      x-api-path-slug: checks-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId} ':
    ' get ':
      summary: Get Check
      description: Gets info about a check, current SLA, last result and its status.
      operationId: getChecksCheck
      x-api-path-slug: checkscheckid-get
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' put ':
      summary: Update Check
      description: Updates a check.
      operationId: putChecksCheck
      x-api-path-slug: checkscheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' delete ':
      summary: Delete Check
      description: Deletes a check.
      operationId: deleteChecksCheck
      x-api-path-slug: checkscheckid-delete
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId}/lastvalue ':
    ' get ':
      summary: Get Checks Lastvalue
      description: Gets the absolute last value of a specific check.
      operationId: getChecksCheckLastvalue
      x-api-path-slug: checkscheckidlastvalue-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  /checks/{checkId}/results/{millisecondsUtc}:
    ' get ':
      summary: Get Checks Results
      description: Gets a specific check result by a numeric java timestamp.
      operationId: getChecksCheckResultsMillisecondsutcDetailLevelDetailLevel
      x-api-path-slug: checkscheckidresultsmillisecondsutc-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  /checks/{checkId}/results:
    ' get ':
      summary: Get Checks Results
      description: Gets the most recent check results.
      operationId: getChecksCheckResultsMostrecentMostrecent&amp;detailLevelDetailLevel
      x-api-path-slug: checkscheckidresults-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  ? |2-

        /api/{version}/checks
  : ? |2-

          get
    : summary: Get Check List
      description: Returns a list overview of all checks.
      operationId: |2-

        getApiVersionChecks
      x-api-path-slug: apiversionchecks-get
      parameters:
      - in: query
        name: include_tags
        description: Include tag list for each check
        type: <td>boolean</td>
      - in: query
        name: limit
        description: Limits the number of returned probes to the specified quantity
        type: <td>integer</td>
      - in: query
        name: offset
        description: Offset for listing
        type: <td>integer</td>
      - in: query
        name: tags
        description: Tag list separated by commas
        type: <td>string</td>
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/command ':
    ' post ':
      summary: Checks Command
      description: Creates a new Command check.
      operationId: -checks-command-
      x-api-path-slug: checkscommand-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command-v2 ':
    ' post ':
      summary: Checks Command
      description: Creates a new Command check (version 2).
      operationId: -checks-command-v2-
      x-api-path-slug: checkscommandv2-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command-v2/{checkId} ':
    ' put ':
      summary: Checks Command
      description: Updates a command check (version 2).
      operationId: -checks-command-v2-checkid-
      x-api-path-slug: checkscommandv2checkid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command/{checkId} ':
    ' put ':
      summary: Checks Command
      description: Updates a command check.
      operationId: -checks-command-checkid-
      x-api-path-slug: checkscommandcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command/categories ':
    ' get ':
      summary: Checks Command Categories
      description: Gets a list of all command check categories that are available
        for you as customer.
      operationId: -checks-command-categories-
      x-api-path-slug: checkscommandcategories-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command-v2/categories ':
    ' get ':
      summary: Checks Command Categories
      description: Gets a list of all command check (version 2) categories that are
        available for you as customer.
      operationId: -checks-command-v2-categories-
      x-api-path-slug: checkscommandv2categories-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command/locations ':
    ' get ':
      summary: Checks Command Locations
      description: Gets a list of all locations that are available for Command checks.
      operationId: -checks-command-locations-
      x-api-path-slug: checkscommandlocations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  /checks/command-v2/locations:
    ' get ':
      summary: Checks Command Locations
      description: Gets a list of all locations that are available for Command checks
        (version 2).
      operationId: -checks-command-v2-locationsprotocolprotocol-
      x-api-path-slug: checkscommandv2locations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/{checkId}/job ':
    ' get ':
      summary: Get Checks Job
      description: DEPRECATED. Gets the current job status for a check.
      operationId: -checks-checkid-job-
      x-api-path-slug: checkscheckidjob-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Jobs
    ' post ':
      summary: Get Checks Job
      description: Executes a check.
      operationId: -checks-checkid-job-
      x-api-path-slug: checkscheckidjob-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Jobs
  '/checks/ping ':
    ' post ':
      summary: Checks Ping
      description: Creates a new Ping check.
      operationId: -checks-ping-
      x-api-path-slug: checksping-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Pings
  '/checks/ping/{checkId} ':
    ' put ':
      summary: Checks Ping
      description: Updates a Ping check.
      operationId: -checks-ping-checkid-
      x-api-path-slug: checkspingcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Pings
  '/checks/ping/locations ':
    ' get ':
      summary: Checks Ping Locations
      description: Gets a list of all locations that are available for Ping checks.
      operationId: -checks-ping-locations-
      x-api-path-slug: checkspinglocations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Pings
  '/checks/port ':
    ' post ':
      summary: Checks Port
      description: Creates a new Port check.
      operationId: -checks-port-
      x-api-path-slug: checksport-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Ports
  '/checks/port/{checkId} ':
    ' put ':
      summary: Checks Port
      description: Updates a Port check.
      operationId: -checks-port-checkid-
      x-api-path-slug: checksportcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Ports
  '/checks/port/locations ':
    ' get ':
      summary: Checks Port Locations
      description: Gets a list of all locations that are available for Port checks.
      operationId: -checks-port-locations-
      x-api-path-slug: checksportlocations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Ports
  '/checks/proxysniffer ':
    ' post ':
      summary: Checks Proxy Sniffer
      description: Creates a new ProxySniffer check.
      operationId: -checks-proxysniffer-
      x-api-path-slug: checksproxysniffer-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId} ':
    ' put ':
      summary: Checks Proxy Sniffer
      description: Updates a proxy sniffer check.
      operationId: -checks-proxysniffer-checkid-
      x-api-path-slug: checksproxysniffercheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/locations ':
    ' get ':
      summary: Checks Proxy Sniffer Locations
      description: Gets a list of all locations that are available for ProxySniffer
        checks.
      operationId: -checks-proxysniffer-locations-
      x-api-path-slug: checksproxysnifferlocations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId}/results/{resultId}/urldata?format={format} ':
    ' get ':
      summary: Checks Proxysniffer Results
      description: Gets a file that contains ProxySniffer check result data.
      operationId: -checks-proxysniffer-checkid-results-resultid-urldataformatformat-
      x-api-path-slug: checksproxysniffercheckidresultsresultidurldataformatformat-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId}/results/urldata ':
    ' post ':
      summary: Checks Proxy Sniffer Results URLdata
      description: Gets ProxySniffer check results in json format by result ids.
      operationId: -checks-proxysniffer-checkid-results-urldata-
      x-api-path-slug: checksproxysniffercheckidresultsurldata-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/proxysniffer/{checkId}/results/{resultId}/errorlog ':
    ' get ':
      summary: Checks Proxy Sniffer Results Error Log
      description: Gets an error log of the given ProxySniffer check result.
      operationId: -checks-proxysniffer-checkid-results-resultid-errorlog-
      x-api-path-slug: checksproxysniffercheckidresultsresultiderrorlog-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Proxy
  '/checks/url ':
    ' post ':
      summary: Checks URL
      description: Creates a new URL check (legacy version 1).
      operationId: -checks-url-
      x-api-path-slug: checksurl-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - URL
  '/checks/url-v2 ':
    ' post ':
      summary: Checks URL
      description: Creates a new URL check (version 2).
      operationId: -checks-url-v2-
      x-api-path-slug: checksurlv2-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - URL
  '/checks/url/{checkId} ':
    ' put ':
      summary: Checks URL
      description: Updates a URL check (legacy version 1).
      operationId: -checks-url-checkid-
      x-api-path-slug: checksurlcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - URL
  '/checks/url-v2/{checkId} ':
    ' put ':
      summary: Checks URL
      description: Updates a URL check (version 2).
      operationId: -checks-url-v2-checkid-
      x-api-path-slug: checksurlv2checkid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - URL
  '/checks/url/locations ':
    ' get ':
      summary: Checks URL Locations
      description: Gets a list of all locations that are available for URL (legacy
        version 1) checks.
      operationId: -checks-url-locations-
      x-api-path-slug: checksurllocations-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - URL
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
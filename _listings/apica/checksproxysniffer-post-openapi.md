---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks Proxysniffer Checks Proxy Sniffer
  version: 1.0.0
  description: Creates a new ProxySniffer check.
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
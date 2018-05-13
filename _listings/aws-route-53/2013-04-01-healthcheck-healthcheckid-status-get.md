---
swagger: "2.0"
info:
  title: AWS Route 53 API Get Health Check Status
  version: 1.0.0
  description: Gets status of a specified health check. Send a GET request to the/2013-04-01/healthcheck/health
    check ID/status resource.You can use this call to get a health check's current
    status.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2013-04-01/healthcheck/HealthCheckId/status:
    get:
      summary: Get Health Check Status
      description: Gets status of a specified health check
      operationId: gethealthcheckstatus
      parameters:
      - in: path
        name: HealthCheckId
        description: "If you want Amazon Route 53 to return this resource record set
          in response to a DNS query only\t\t\twhen a health check is passing, include
          the HealthCheckId element and specify the\t\t\tID of the applicable health
          check"
        type: string
      responses:
        200:
          description: OK
      tags:
      - checks
      - health
definitions: []
x-collection-name: AWS Route 53
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
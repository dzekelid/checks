---
swagger: "2.0"
info:
  title: AWS Route 53 API List Health Checks
  version: 1.0.0
  description: Retrieve a list of your health checks. Send a GET request to the/2013-04-01/healthcheck
    resource. The response to this request includes aHealthChecks element with zero
    or more HealthCheck child elements.By default, the list of health checks is displayed
    on a single page. You can control thelength of the page that is displayed by using
    the MaxItems parameter. You can usethe Marker parameter to control the health
    check that the list beginswith.For information about listing health checks using
    the Amazon Route 53 console, see Amazon Route 53 Health Checks and DNS Failover.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2013-04-01/healthcheck?marker=Marker&amp;maxitems=MaxItems:
    get:
      summary: List Health Checks
      description: Retrieve a list of your health checks
      operationId: listhealthchecks
      parameters:
      - in: path
        name: marker
        description: "If the response to a ListHealthChecks is more than one page,
          marker is the\t\t\thealth check ID for the first health check on the next
          page of results"
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
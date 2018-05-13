---
swagger: "2.0"
info:
  title: AWS Route 53 API Delete Health Check
  version: 1.0.0
  description: Deletes a health check. Send a DELETE request to the/2013-04-01/healthcheck/health
    check ID            resource.ImportantAmazon Route 53 does not prevent you from
    deleting a health check even if the health check isassociated with one or more
    resource record sets. If you delete a health check and you don'tupdate the associated
    resource record sets, the future status of the health check can't bepredicted
    and may change. This will affect the routing of DNS queries for your DNS failoverconfiguration.
    For more information, see Replacing and Deleting Health Checks in the Amazon Route
    53 Developer Guide.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2013-04-01/healthcheck/HealthCheckId:
    delete:
      summary: Delete Health Check
      description: Deletes a health check
      operationId: deletehealthcheck
      parameters:
      - in: path
        name: HealthCheckId
        description: The ID of the health check that you want to delete
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
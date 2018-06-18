---
swagger: "2.0"
x-collection-name: API Science
x-complete: 1
info:
  title: API Science
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /monitors/{id}/checks.json:
    get:
      summary: Get Checks For A Monitor
      description: Get Checks For A Monitor
      operationId: getChecksForAMonitor
      x-api-path-slug: monitorsidchecks-json-get
      parameters:
      - in: query
        name: count
        description: The number of checks to return
      - in: path
        name: id
        description: id for the monitors
      - in: query
        name: start
        description: The start number represents which ID is the maximum check that
          could be found
      responses:
        200:
          description: OK
      tags:
      - Checks
---
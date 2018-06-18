---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Get Range Border
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbooknamesltnamegtrangeformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;):
    get:
      summary: Get Range Border
      description: Get RangeBorder Retrieve the properties and relationships of rangeborder
        object.
      operationId: GetRangeBorder
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Border
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
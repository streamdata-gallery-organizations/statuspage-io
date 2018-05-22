---
swagger: "2.0"
x-collection-name: StatusPage.io
x-complete: 0
info:
  title: StatusPage.io Get your page profile
  version: 1.0.0
  description: Get your page profile
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/[page_id].json:
    get:
      summary: Get your page profile
      description: Get your page profile
      operationId: get-your-page-profile
      x-api-path-slug: pagespage-idjson-get
      responses:
        200:
          description: OK
      tags:
      - Pages
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
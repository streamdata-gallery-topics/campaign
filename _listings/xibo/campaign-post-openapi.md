---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 0
info:
  title: Xibo API Add Campaign
  description: Add a Campaign
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /campaign:
    post:
      summary: Add Campaign
      description: Add a Campaign
      operationId: campaignAdd
      x-api-path-slug: campaign-post
      parameters:
      - in: formData
        name: name
        description: Name for this Campaign
      responses:
        200:
          description: OK
      tags:
      - Campaign
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
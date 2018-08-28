---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Account Logout
  version: 1.0.0
  description: Post account logout.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/account/logout:
    post:
      summary: Post Account Logout
      description: Post account logout.
      operationId: postApiV1AccountLogout
      x-api-path-slug: apiv1accountlogout-post
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Account
      - Logout
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
---
swagger: "2.0"
x-collection-name: StatusPage
x-complete: 0
info:
  title: StatusPage.io Retrieve a list of users
  version: 1.0.0
  description: Retrieve a list of users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/[page_id]/page_access_users.json:
    get:
      summary: Retrieve a list of users
      description: Retrieve a list of users
      operationId: retrieve-a-list-of-users
      x-api-path-slug: pagespage-idpage-access-users-json-get
      parameters:
      - in: query
        name: email
        description: Filter the returned list of users by email address (users must
          have assigned email addresses)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---
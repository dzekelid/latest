---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get the todo and latest task for a group
  version: 1.0.0
  description: Get the todo and latest task for a group.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/todo/group/getupcomingtask:
    get:
      summary: Get the todo and latest task for a group
      description: Get the todo and latest task for a group.
      operationId: GroupToDo_GetUpComingTaskBygroupId
      x-api-path-slug: apitodogroupgetupcomingtask-get
      parameters:
      - in: query
        name: groupId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Todo
      - Latest
      - Taska
      - Group
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
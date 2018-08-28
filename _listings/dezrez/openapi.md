swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
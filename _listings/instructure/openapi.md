---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Groups API
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /groups/{group_id}/pages/url/revisions/latest:
    get:
      summary: Show revision
      description: Show revision.
      operationId: show-revision
      x-api-path-slug: groupsgroup-idpagesurlrevisionslatest-get
      parameters:
      - in: query
        name: summary
        description: If set, exclude page content from results
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Pages
      - Url
      - Revisions
      - Latest
---
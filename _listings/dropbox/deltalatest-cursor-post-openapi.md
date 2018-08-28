---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 0
info:
  title: Dropbox Datastore API Latest Cursor
  description: /delta/latest_cursor
  version: "1"
host: api.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /delta/latest_cursor:
    post:
      summary: Latest Cursor
      description: /delta/latest_cursor
      operationId: deltalatest-cursor
      x-api-path-slug: deltalatest-cursor-post
      parameters:
      - in: query
        name: include_media_info
        description: If true, the returned cursor will be encoded with include_media_info
          set to true for use with /delta
      - in: query
        name: path_prefix
        description: If present, the returned cursor will be encoded with a path_prefix
          for the specified path for use with /delta
      responses:
        200:
          description: OK
      tags:
      - Delta
      - Latest
      - Cursor
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
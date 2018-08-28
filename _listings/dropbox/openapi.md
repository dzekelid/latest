swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Notify Appendix API v1
  description: the-dropbox-notify--is-a-part-of-dropbox-core-ap-with-a-separate-endpoint-for-notification-call-
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api-notify.dropbox.com
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
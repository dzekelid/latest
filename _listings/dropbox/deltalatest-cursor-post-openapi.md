---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 0
info:
  title: Dropbox Core A way to quickly get a cursor for the server's state, for use
    with /delta.
  description: |-
    A way to quickly get a cursor for the server's state, for use with `/delta`.

    Unlike `/delta`, `/delta/latest_cursor` does not return any entries, so your app will not know about any
    existing files or folders in the Dropbox account. For example, if your app processes future delta entries
    and sees that a folder was deleted, your app won't know what files were in that folder. Use this endpoint
    if your app only needs to know about new files and modifications and doesn't need to know about files that
    already exist in Dropbox.

    If you need to build local state to match the server state in Dropbox, you should instead use `/delta`.
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
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
      summary: A way to quickly get a cursor for the server's state, for use with
        /delta.
      description: |-
        A way to quickly get a cursor for the server's state, for use with `/delta`.

        Unlike `/delta`, `/delta/latest_cursor` does not return any entries, so your app will not know about any
        existing files or folders in the Dropbox account. For example, if your app processes future delta entries
        and sees that a folder was deleted, your app won't know what files were in that folder. Use this endpoint
        if your app only needs to know about new files and modifications and doesn't need to know about files that
        already exist in Dropbox.

        If you need to build local state to match the server state in Dropbox, you should instead use `/delta`.
      operationId: a-way-to-quickly-get-a-cursor-for-the-servers-state-for-use-with-deltaunlike-delta-deltalatest-curso
      x-api-path-slug: deltalatest-cursor-post
      parameters:
      - in: formData
        name: include_media_info
        description: If `true`, the returned cursor will be encoded with `include_media_info`
          set to `true` for usewith `/delta`
      - in: formData
        name: path_prefix
        description: If present, the returned cursor will be encoded with a `path_prefix`
          for the specified path for usewith `/delta`
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Documents
      - Delta
      - Latest_cursor
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
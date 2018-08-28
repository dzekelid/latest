---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Dynamic Mapping Return the latest location data for an asset
  description: |-
    Returns the latest location entry for the given asset. The timestamp and location data for the
    given entry is included in the response.
  version: 1.0.0
host: time-series-service-doc.grc-apps.svc.ice.ge.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}/assets/{assetId}:
    get:
      summary: Return the latest location data for an asset
      description: |-
        Returns the latest location entry for the given asset. The timestamp and location data for the
        given entry is included in the response.
      operationId: returns-the-latest-location-entry-for-the-given-asset-the-timestamp-and-location-data-for-thegiven-e
      x-api-path-slug: v1collectionscollectionnameassetsassetid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Return
      - Latest
      - Location
      - Dataan
      - Asset
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
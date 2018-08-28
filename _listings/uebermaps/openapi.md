swagger: "2.0"
x-collection-name: uebermaps
x-complete: 1
info:
  title: uebermaps
  description: enable-people-to-store-spots-on-public-and-private-maps
  termsOfService: https://uebermaps.com/terms/
  contact:
    name: uebermaps API Team
  version: "2.0"
host: uebermaps.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /trends/latest:
    get:
      summary: List latest maps
      description: List latest maps.
      operationId: trends.latest.get
      x-api-path-slug: trendslatest-get
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Latest
      - Maps
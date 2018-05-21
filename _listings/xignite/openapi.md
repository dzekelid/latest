---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Statistics
  description: delivers-and-charts-more-than-1400-economical-timeseries-fom-the-federal-reserve-bank
  version: 1.0.0
host: www.xignite.com
basePath: xStatistics.json/XigniteStatistics
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetLatestTopicData:
    post:
      summary: Get Latest Topic Data
      description: Get lastest value for a topic.
      operationId: postGetlatesttopicdata
      x-api-path-slug: getlatesttopicdata-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Topic
      - Data
---
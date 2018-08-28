---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Metals Get Latest Historical Metal Quotes
  description: Get cross sectional historical metal quotes by a given time.
  version: 1.0.0
host: globalmetals.xignite.com
basePath: xGlobalMetals.json/XigniteGlobalMetals
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetLatestUpdateTimeStamp:
    get:
      summary: Get Latest Update Time Stamp
      description: Get latest update TimeStamp for this service.
      operationId: postGetlatestupdatetimestamp
      x-api-path-slug: getlatestupdatetimestamp-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - ""
      - Time
      - Stamp
  /GetLatestCrossRate:
    get:
      summary: Get Latest Cross Rate
      description: Returns the latest possible cross rate.
      operationId: postGetlatestcrossrate
      x-api-path-slug: getlatestcrossrate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Cross
      - Rate
  /GetLatestCrossRates:
    get:
      summary: Get Latest Cross Rates
      description: Returns the latest possible cross rate.
      operationId: postGetlatestcrossrates
      x-api-path-slug: getlatestcrossrates-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Cross
      - Rates
  /GetLatestRecommendationSummaries:
    get:
      summary: Get Latest Recommendation Summaries
      description: Get Latest Recommendation Summary
      operationId: GetLatestRecommendationSummaries
      x-api-path-slug: getlatestrecommendationsummaries-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Recommendation
      - Summaries
  /GetLatestEstimates:
    get:
      summary: Get Latest Estimates
      description: Get Latest Estimates
      operationId: GetLatestEstimates
      x-api-path-slug: getlatestestimates-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Estimates
  /GetLatestFutureQuote:
    get:
      summary: Get Latest Future Quote
      description: Returns the latest delayed quote for a future contract.
      operationId: GetLatestFutureQuote
      x-api-path-slug: getlatestfuturequote-get
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
      - Future
      - Quote
  /GetLatestFutureQuotes:
    get:
      summary: Get Latest Future Quotes
      description: Returns latest delayed quotes for multiple future contracts.
      operationId: GetLatestFutureQuotes
      x-api-path-slug: getlatestfuturequotes-get
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
      - Future
      - Quotes
  /GetLatestFrontMonthFutureQuotes:
    get:
      summary: Get Latest Front Month Future Quotes
      description: Returns latest quotes for front month futures
      operationId: GetLatestFrontMonthFutureQuotes
      x-api-path-slug: getlatestfrontmonthfuturequotes-get
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
      - Front
      - Month
      - Future
      - Quotes
  /GetLatestFutureOptionQuote:
    get:
      summary: Get Latest Future Option Quote
      description: Returns latest delayed quote for multiple future option.
      operationId: GetLatestFutureOptionQuote
      x-api-path-slug: getlatestfutureoptionquote-get
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
      - Future
      - Option
      - Quote
  /GetLatestFutureOptionQuotes:
    get:
      summary: Get Latest Future Option Quotes
      description: Returns latest delayed quotes for multiple future options.
      operationId: GetLatestFutureOptionQuotes
      x-api-path-slug: getlatestfutureoptionquotes-get
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
      - Future
      - Option
      - Quotes
  /GetLatestHistoricalMetalQuote:
    get:
      summary: Get Latest Historical Metal Quote
      description: Get historical metal quote by a given time.
      operationId: GetLatestHistoricalMetalQuote
      x-api-path-slug: getlatesthistoricalmetalquote-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Historical
      - Metal
      - Quote
  /GetLatestHistoricalMetalQuotes:
    get:
      summary: Get Latest Historical Metal Quotes
      description: Get cross sectional historical metal quotes by a given time.
      operationId: GetLatestHistoricalMetalQuotes
      x-api-path-slug: getlatesthistoricalmetalquotes-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Historical
      - Metal
      - Quotes
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
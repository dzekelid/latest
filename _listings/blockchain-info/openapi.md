---
swagger: "2.0"
x-collection-name: Blockchain Info
x-complete: 1
info:
  title: Blockchain Info
  description: use-blockchains-apis-at-no-cost-to-help-you-start-building-bitcoin-apps
  version: 1.0.0
host: blockchain.info
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /latestblock:
    get:
      summary: Latest Block
      description: Gets the latest block.
      operationId: getLatestBlock
      x-api-path-slug: latestblock-get
      parameters:
      - in: query
        name: format
        description: The format to return (json,html)
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Latest
---
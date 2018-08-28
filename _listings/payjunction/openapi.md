swagger: "2.0"
x-collection-name: PayJunction
x-complete: 1
info:
  title: PayJunction API Basic
  description: todo-add-description
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /transactions/{transactionId}/receipts/latest/email:
    post:
      summary: Post Transactions Receipts Latest Email
      description: /transactions/{transactionid}/receipts/latest/email.
      operationId: TransactionsReceiptsLatestEmailByTransactionIdPost
      x-api-path-slug: transactionstransactionidreceiptslatestemail-post
      parameters:
      - in: formData
        name: replyTo
      - in: formData
        name: requestSignature
      - in: formData
        name: to
      - in: path
        name: transactionId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Transactions
      - Receipts
      - Latest
      - Email
  /transactions/{transactionId}/receipts/latest:
    get:
      summary: Get Transactions Receipts Latest
      description: Retrieve the most recent version of the receipt.
      operationId: TransactionsReceiptsLatestByTransactionIdGet
      x-api-path-slug: transactionstransactionidreceiptslatest-get
      parameters:
      - in: path
        name: transactionId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Transactions
      - Receipts
      - Latest
  /transactions/{transactionId}/receipts/latest/thermal:
    get:
      summary: Get Transactions Receipts Latest Thermal
      description: Get the most recent version of the thermal receipt HTML Document
      operationId: TransactionsReceiptsLatestThermalByTransactionIdGet
      x-api-path-slug: transactionstransactionidreceiptslatestthermal-get
      parameters:
      - in: path
        name: transactionId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Transactions
      - Receipts
      - Latest
      - Thermal
  /transactions/{transactionId}/receipts/latest/fullpage:
    get:
      summary: Get Transactions Receipts Latest Fullpage
      description: Get the most recent version of the full page (8.5x11) receipt HTML
        document
      operationId: TransactionsReceiptsLatestFullpageByTransactionIdGet
      x-api-path-slug: transactionstransactionidreceiptslatestfullpage-get
      parameters:
      - in: path
        name: transactionId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Transactions
      - Receipts
      - Latest
      - Fullpage
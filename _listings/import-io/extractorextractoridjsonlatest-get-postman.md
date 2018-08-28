{
  "info": {
    "name": "import.io Get Extractor Extractorid Json Latest",
    "_postman_id": "937add99-d344-496e-a7d1-eaad1b1d8c9e",
    "description": "Get the latest crawl run results as json.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extractor",
      "item": [
        {
          "id": "805d9c0e-b297-4434-ba82-e9e2d2071b8d",
          "name": "getExtractorExtractorCsvLatest",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/csv/latest"
              ],
              "variable": [
                {
                  "id": "extractorId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the latest crawl run results as a csv."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad6c76a7-22cc-46c8-84bc-f63fc5b57c45"
            }
          ]
        },
        {
          "id": "6ebba7ac-7ede-4d27-9fae-375d0f06c557",
          "name": "getExtractorExtractorJsonLatest",
          "request": {
            "url": {
              "protocol": "http",
              "host": "schedule.import.io",
              "path": [
                "extractor/:extractorId/json/latest"
              ],
              "variable": [
                {
                  "id": "extractorId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the latest crawl run results as json."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd7fab6b-e64b-4b44-8671-4b328b1fba67"
            }
          ]
        }
      ]
    }
  ]
}
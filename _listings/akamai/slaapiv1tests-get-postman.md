{
  "info": {
    "name": "Akamai API List Test Configurations",
    "_postman_id": "dcca3cfc-65cf-4c96-aebf-abb6a10ff930",
    "description": "List Test Configurations",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Papi",
      "item": [
        {
          "id": "98dff8cd-d714-4d04-9312-6ccc81d4d85c",
          "name": "papiv0propertiespropertyidversionslatestcontractidgroupidactivatedon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions/latest"
              ],
              "query": [
                {
                  "key": "activatedOn",
                  "value": "activatedOn",
                  "disabled": false
                },
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Property&#8217;s Latest Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc237916-c8af-4a11-96d3-6c317523b9be"
            }
          ]
        }
      ]
    },
    {
      "name": "Sla",
      "item": [
        {
          "id": "45ff44f9-e075-4de7-84f6-9fffd57321e0",
          "name": "slaapiv1testsslatestids",
          "request": {
            "url": "http://developer.akamai.com/sla-api/v1/tests?slaTestIds=slaTestIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Test Configurations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85944732-d263-4d4f-869c-dfe65304c6e3"
            }
          ]
        }
      ]
    }
  ]
}
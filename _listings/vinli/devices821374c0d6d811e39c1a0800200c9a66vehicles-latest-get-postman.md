{
  "info": {
    "name": "Vinli Get Device's Latest Vehicle",
    "_postman_id": "a71b357c-973a-4644-aa4e-343dd55d8ca4",
    "description": "Get device's latest vehicle.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "b3435511-f9cf-4294-9e39-48f9ca0db4c4",
          "name": "DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List a device's vehicles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6147723a-d8b0-4819-ba61-ee743d1f8a94"
            }
          ]
        },
        {
          "id": "b14735d7-03b7-4a82-acde-c4d00d286128",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30TripsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/trips",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all of a vehicle's trips."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acc8aa73-3f19-434a-8f99-291ba333dd47"
            }
          ]
        },
        {
          "id": "0e8c6821-0b84-4585-82ac-ee1ade3bf943",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30DistancesGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/distances",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get list of  a vehicles distances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76ab3d66-e099-4b2a-bbed-d0ff754ba0e9"
            }
          ]
        },
        {
          "id": "f255a5eb-beca-4f85-9193-9ada3cc4b2cd",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometerTriggersGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometer_triggers",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all odometer triggers for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab217135-d1b4-4210-b48a-02178ff3fded"
            }
          ]
        },
        {
          "id": "88716914-1677-40da-b881-5b0113bb8f63",
          "name": "Vehicles428bc62116e7489bA02aEb98526d01efCollisionsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/428bc621-16e7-489b-a02a-eb98526d01ef/collisions",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of collisions for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc662417-7aa6-4efc-be9c-369d59ce28b9"
            }
          ]
        },
        {
          "id": "38a4445f-e1e3-43ac-8314-0f34c7eae84d",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometersGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometers",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all odometer reports for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d76f084-8318-4892-907d-42c955142cda"
            }
          ]
        }
      ]
    },
    {
      "name": "Vehicle",
      "item": [
        {
          "id": "5293ca32-1cba-4e97-8e8b-ea0a3eaad16a",
          "name": "VehiclesAa44769b3c0a46629bad25481cf5198fGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/aa44769b-3c0a-4662-9bad-25481cf5198f",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get vehicle details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a74df02-8f45-4db2-9066-833399176545"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "5143ccd4-a39c-4a2f-9703-501cd2f770f3",
          "name": "Devices821374c0D6d811e39c1a0800200c9a66VehiclesLatestGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/821374c0-d6d8-11e3-9c1a-0800200c9a66/vehicles/_latest",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get device's latest vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29c06aac-0322-4e16-82fe-c8883a8e2c7d"
            }
          ]
        }
      ]
    },
    {
      "name": "Report",
      "item": [
        {
          "id": "bb3e8555-6e6b-44ef-9ae3-c260a04abc55",
          "name": "Vehicles8480c5b76f3e40b3A78e3555617d44b0ReportCardsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/8480c5b7-6f3e-40b3-a78e-3555617d44b0/report_cards",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Report cards for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0727e58a-968e-4380-ad27-42290501a17f"
            }
          ]
        }
      ]
    }
  ]
}
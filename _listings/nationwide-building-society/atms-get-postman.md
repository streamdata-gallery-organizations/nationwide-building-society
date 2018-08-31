{
  "info": {
    "name": "Nationwide Building Society Get ATMs",
    "_postman_id": "82029d12-4f1d-40e5-80c4-70656f27a8f4",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "6654fd81-514f-40ff-9ded-393fbb90011d",
          "name": "getATMS",
          "request": {
            "url": "http://openapi.nationwide.co.uk/open-banking/v2.1/atms/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0bdac7e0-333d-4af2-b9f1-33b56308883a"
            }
          ]
        }
      ]
    }
  ]
}
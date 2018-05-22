{
  "info": {
    "name": "Nationwide Building Society Get Branches",
    "_postman_id": "e579afdb-a87c-489a-ad9f-6a47d5c8ce78",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "branches",
      "item": [
        {
          "id": "32ddd49d-a61b-44e8-ab41-00997450e4f7",
          "name": "getBranches",
          "request": {
            "url": "http://openapi.nationwide.co.uk/open-banking/v2.1/branches/",
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
              "id": "67f9be1c-f95b-4d91-9f42-a47fe9fe70c2"
            }
          ]
        }
      ]
    }
  ]
}
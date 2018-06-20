{
  "info": {
    "name": "National Crime Victimization Survey (NCVS) API Get Personal Fields",
    "_postman_id": "eace7218-5f5a-4ea3-bc5c-5deaeee85b1f",
    "description": "Returns a description of the fields/columns used returned in the personal data sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Personal",
      "item": [
        {
          "id": "7c2f8fdc-240b-4c8a-983d-b67513566795",
          "name": "getV2PersonalFields",
          "request": {
            "url": "http://www.bjs.gov/bjs/ncvs/v2/personal/fields/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the fields/columns used returned in the personal data sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7ddb709-2f76-45e7-94d8-dc1b4790f803"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Facebook Get User Personal Ad Accounts",
    "_postman_id": "3e851db9-7c3d-465d-b94b-42661accf2cd",
    "description": "User Personal Ad Accounts",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "a528ca56-50df-453a-ac41-cd0418b5356e",
          "name": "getUserPersonalAdAccounts",
          "request": {
            "url": "http://graph.facebook.com/v3.0/&#123;user-id&#125;/personal_ad_accounts?total_countunsigned int32=total_countunsigned%20int32",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "User Personal Ad Accounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "245aa1a6-2044-4fc7-93fe-a0c36b98d6f3"
            }
          ]
        }
      ]
    }
  ]
}
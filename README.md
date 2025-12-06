{

  "info": {

    "name": "Banking API Automation",

    "_postman_id": "abcd-1234-bank-api-collection",

    "schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"

  },

  "item": [

    {

      "name": "Login API",

      "request": {

        "method": "POST",

        "header": [

          {

            "key": "Content-Type",

            "value": "application/json"

          }

        ],

        "body": {

          "mode": "raw",

          "raw": "{\"email\": \"eve.holt@reqres.in\", \"password\": \"cityslicka\"}"

        },

        "url": {

          "raw": "https://reqres.in/api/login",

          "protocol": "https",

          "host": ["reqres", "in"],

          "path": ["api", "login"]

        }

      }

    }

  ]

}

 
{}

 
# Banking API Testing — Postman
 
Automated testing of a login API using Postman.
 
## Tech Stack

- Postman

- JSON assertions
 
## Endpoint Tested

- POST: /login (using https://reqres.in/api/login)
 
## Validations

- Response status code

- Response body fields

- Error message for invalid credentials
 
## How to Run

- Import `Collections/Banking_API_Automation.postman_collection.json` into Postman

- (Optionally) configure `Environment.json`

- Execute the "Login API" request
 
## Author

@surosree-automation-engineer

 

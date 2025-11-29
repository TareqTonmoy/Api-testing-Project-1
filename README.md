# API Testing Project (Postman)

## Tools
- Postman
- Newman
- JSON

## What I tested
- CRUD APIs (GET, POST, PUT, DELETE)
- Status codes, response body, headers, response time
- Positive & negative test cases
- Environment/collection variables

## How to run with Newman
```bash
newman run Petstore.postman_collection.json -e Petstore.postman_environment.json -r cli,html

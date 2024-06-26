# Invenio API Toolkit

This repository contains tools to help you integrate use, test and document Invenio API.
You can import the collections in tools like Swagger UI, Postman, Bruno etc.
This definitions are generated from Postman collections, Bruno.

last updated: Invenio V11

## Postman Collection

The Postman collection is available in the `postman_collection` directory.
the recommended way to use the Postman collection is to import it into Postman.
> Check each request script tab for any magic assignments or environment variables.
> e.g. when you create a new community, the community id variable will be assigned to the environment variable `community_id` etc.

## Bruno collection

We have also created a collection for bruno, which is a another tool that has no cloud support tool to test the Invenio API.
The collection is available in the `bruno_collection` directory.
TODO: create scripts to fill the environment variables in the collection like the Postman collection.

## OpenAPI Definitions

To generate OpenAPI definitions, convert the Postman collection to OpenAPI 3.0.0 using the postman2openapi tool. This provides both the Postman collection and the OpenAPI definitions.
using [postman2openapi](https://github.com/kevinswiber/postman2openapi)

```bash
postman2openapi collection.json > openapi.yaml
```

functional but not complete yet.
TODO:

- [ ] add the new API endpoints introduced in V12
- [ ] add the error responses
- [ ] add schema definitions

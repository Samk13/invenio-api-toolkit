<!-- Copyright (C) 2024 KTH Royal Institute of Technology. -->

# Invenio-OpenAPI-Definitions

Invenio-OpenAPI-Definitions provides a way to define OpenAPI 3.0.0 specifications for Invenio REST APIs.

You can import this definitions in tools like Swagger UI, Postman, etc.
This definitions are generated from Postman collections, so it needs to be cleaned up and adjusted to fit the OpenAPI 3.0.0 specification.
last updated: Invenio V11
The new API endpoints introduced in V12 are not included yet in this definitions.

using [postman2openapi](https://github.com/kevinswiber/postman2openapi)

```bash
postman2openapi collection.json > openapi.yaml
```

To generate OpenAPI definitions, convert the Postman collection to OpenAPI 3.0.0 using the postman2openapi tool. This provides both the Postman collection and the OpenAPI definitions.

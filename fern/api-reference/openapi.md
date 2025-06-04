---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response formats, and authentication requirements. You can use this specification to generate client libraries, explore the API, and integrate Vapi into your applications.

## Accessing the OpenAPI Specification

The OpenAPI specification for Vapi's API is available at:

```
https://api.vapi.ai/openapi.json
```

You can use this URL to view the specification directly or import it into API tools and code generators.

## Key Endpoints

Some of the key endpoints described in the OpenAPI spec include:

- `/v1/calls` - For managing voice calls
- `/v1/assistants` - For creating and configuring AI assistants
- `/v1/phone_numbers` - For provisioning and managing phone numbers

The full list of endpoints and operations is available in the specification.

## Create Call Endpoint

The `POST /v1/calls` endpoint allows you to initiate outbound calls programmatically. The summary for this endpoint has been updated to:

"Create a new outbound call or start a web call session"

This endpoint now supports both traditional outbound phone calls as well as web-based call sessions.

## Using the OpenAPI Specification

You can use the OpenAPI specification to:

1. Generate client libraries in various programming languages
2. Explore and test API endpoints using tools like Swagger UI
3. Set up mock servers for testing
4. Automate API documentation

## Tools for Working with OpenAPI

Some popular tools for working with OpenAPI specifications include:

- [Swagger Editor](https://editor.swagger.io/) - For viewing and editing OpenAPI specs
- [OpenAPI Generator](https://openapi-generator.tech/) - For generating client libraries
- [Postman](https://www.postman.com/) - For testing API endpoints

## Versioning

The OpenAPI specification is versioned along with the API. Be sure to check for updates when new API features are released.

For the latest updates and changes to the API, please refer to our [changelog](/changelog).

If you have any questions about using the OpenAPI specification or integrating with Vapi's API, please [contact our support team](/support).
---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response formats, and authentication requirements. This specification can be used to generate client libraries, explore the API, and understand the available functionality.

## Accessing the OpenAPI Specification

You can find the latest version of our OpenAPI specification at:

```
https://api.vapi.ai/openapi.json
```

This JSON file contains the full API definition and can be used with various OpenAPI tools and generators.

## Key Endpoints

Our API includes endpoints for managing calls, assistants, and other Vapi resources. Some key endpoints include:

- `/call`: Endpoints for creating and managing calls
- `/assistant`: Endpoints for creating and managing assistants
- `/phoneNumber`: Endpoints for managing phone numbers

## CallController_create Operation

The `CallController_create` operation allows you to initiate a new call. The updated summary for this operation is:

```
Create a new call with the specified parameters.
```

This operation enables you to start a call with custom configurations, including the phone number to call, the assistant to use, and other call-specific settings.

## Using the OpenAPI Specification

You can use the OpenAPI specification to:

1. Generate client libraries in various programming languages
2. Explore the API using tools like Swagger UI or Redoc
3. Understand the request and response formats for each endpoint
4. View available query parameters and request body schemas

## Authentication

Most API endpoints require authentication. Please refer to our authentication documentation for details on how to obtain and use API keys.

## Further Resources

- [Swagger UI](https://app.vapi.ai/api-docs): An interactive API documentation interface
- [API Reference](https://docs.vapi.ai/api-reference): Detailed documentation for all API endpoints
- [SDKs](https://docs.vapi.ai/sdks): Client libraries for various programming languages

For any questions or issues related to the API, please contact our support team.
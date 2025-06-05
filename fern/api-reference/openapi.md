---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response structures, and authentication methods. This specification can be used to generate client libraries, explore the API, and integrate Vapi into your applications.

## Accessing the OpenAPI Specification

You can access the latest version of our OpenAPI specification at:

```
https://api.vapi.ai/openapi.json
```

This JSON file contains the complete API definition in OpenAPI 3.0 format.

## Key Endpoints

Our API includes endpoints for managing calls, assistants, and other Vapi resources. Some of the key endpoints include:

- `/call`: Manage phone calls
- `/assistant`: Create and manage AI assistants
- `/phone-number`: Manage phone numbers for your Vapi account

## Recent Changes

The summary of the `CallController_create` operation has been modified in the OpenAPI specification. This change reflects updates to the call creation process and should be noted when integrating with our API.

## Using the OpenAPI Specification

You can use tools like Swagger UI or Redoc to visualize and interact with our API using the OpenAPI specification. These tools provide a user-friendly interface for exploring endpoints, understanding request/response structures, and even testing API calls.

## Code Generation

Many popular programming languages and frameworks offer tools to generate client libraries based on OpenAPI specifications. This can significantly speed up the integration process and ensure type-safety when working with the Vapi API.

## Authentication

API requests to Vapi endpoints require authentication. Please refer to our authentication documentation for details on how to obtain and use API keys.

## Support

If you encounter any issues or have questions about our OpenAPI specification, please don't hesitate to contact our support team or refer to our API documentation for more detailed information.
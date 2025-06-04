---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints and operations. This allows developers to easily integrate Vapi's voice AI capabilities into their applications.

## Accessing the OpenAPI Specification

You can access the latest version of our OpenAPI specification at:

```
https://api.vapi.ai/openapi.json
```

This JSON file contains the full API description, including available endpoints, request/response schemas, authentication requirements, and more.

## Key Endpoints

Some of the key endpoints described in the OpenAPI specification include:

### POST /call

Initiates a new voice call. The summary for this endpoint has recently been updated to provide more clarity on its functionality.

Example request:

```json
POST /call
{
  "phoneNumber": "+15551234567",
  "assistantId": "asst_123abc",
  "callerNumber": "+18885551212"
}
```

### GET /call/{callId}

Retrieves details about a specific call by its ID.

### POST /assistant

Creates a new AI assistant configuration.

### GET /assistant/{assistantId}

Retrieves details about a specific assistant by its ID.

## Using the OpenAPI Specification

You can use tools like Swagger UI or Redoc to visualize and interact with the API based on this specification. Many programming languages also have libraries that can generate API client code directly from OpenAPI specifications.

## Versioning

The OpenAPI specification is versioned along with our API. Always refer to the latest version for the most up-to-date information on available endpoints and features.

## Additional Resources

- [Swagger Documentation](/api-reference/swagger) - Interactive API documentation
- [API Reference](/api-reference) - Detailed information on all API endpoints
- [SDKs](/sdks) - Client libraries for various programming languages

For any questions or issues related to the OpenAPI specification, please [contact our support team](/support).
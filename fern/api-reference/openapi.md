---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our REST API endpoints. You can use this specification to generate client libraries, explore the API, and more.

## Accessing the OpenAPI Specification

The OpenAPI specification for Vapi's API is available at:

```
https://api.vapi.ai/openapi.json
```

You can use this URL to import the specification into API tools and generators.

## Key Endpoints

Some of the key endpoints described in the OpenAPI specification include:

### Calls

- `POST /call`: Create a new outbound call
- `GET /call/{callId}`: Retrieve details about a specific call
- `POST /call/{callId}/actions/hangup`: Hang up an active call

### Assistants 

- `POST /assistant`: Create a new assistant
- `GET /assistant/{assistantId}`: Retrieve details about a specific assistant
- `PUT /assistant/{assistantId}`: Update an existing assistant

### Phone Numbers

- `POST /phone-number`: Provision a new phone number
- `GET /phone-number`: List provisioned phone numbers
- `DELETE /phone-number/{phoneNumberId}`: Release a phone number

## Using the OpenAPI Specification

You can use the OpenAPI specification to:

1. Generate client libraries in various programming languages
2. Explore and test API endpoints in tools like Swagger UI
3. Set up automated API testing
4. Generate API documentation

## Versioning

The OpenAPI specification is versioned along with the API. Be sure to check for updates when new API versions are released.

## Support

If you have any questions about using the OpenAPI specification or need assistance, please contact our support team.
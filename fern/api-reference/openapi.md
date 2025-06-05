---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response formats, and authentication requirements. This specification can be used to generate client libraries, explore the API, and understand available functionality.

## Accessing the OpenAPI Specification

The OpenAPI specification for Vapi's API is available at:

```
https://api.vapi.ai/api/openapi.json
```

You can use this URL to import the specification into API documentation tools or code generators.

## Key Endpoints

Some of the main endpoints described in the OpenAPI spec include:

- `/v1/calls` - Manage voice calls
- `/v1/assistants` - Create and configure AI assistants
- `/v1/phone-numbers` - Provision and manage phone numbers

## Using the Specification

The OpenAPI spec can be used in several ways:

1. Generate client libraries for your preferred programming language
2. Import into API testing tools like Postman
3. Create interactive API documentation
4. Validate API requests and responses

## Example: Creating a Call

Here's an example of how the `/v1/calls` endpoint is described in the OpenAPI spec:

```yaml
/v1/calls:
  post:
    summary: Create a new call
    operationId: CallController_create
    requestBody:
      required: true
      content:
        application/json:
          schema:
            $ref: '#/components/schemas/CreateCallDto'
    responses:
      201:
        description: The call has been successfully created
        content:
          application/json:
            schema:
              $ref: '#/components/schemas/CallDto'
```

This describes the endpoint for creating a new call, including the HTTP method, request body schema, and expected response.

## Changelog

The OpenAPI specification is updated as new features are added to the Vapi API. Be sure to check for updates regularly to stay current with the latest API capabilities.

For more information on using Vapi's API, please refer to our other API reference documentation pages.
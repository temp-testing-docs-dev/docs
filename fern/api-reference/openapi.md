---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response schemas, and authentication requirements. This specification can be used to generate client libraries, automate API testing, and integrate Vapi into various tools and platforms that support OpenAPI.

## Accessing the OpenAPI Specification

You can access our OpenAPI specification in JSON format at the following URL:

```
https://api.vapi.ai/openapi.json
```

This file contains the most up-to-date definition of our API and is regularly updated as we add new features or make changes.

## Using the OpenAPI Specification

The OpenAPI specification can be used in various ways:

1. **Generate Client Libraries**: Use tools like OpenAPI Generator to create client libraries for your preferred programming language.

2. **API Documentation**: Import the specification into tools like Swagger UI or ReDoc to generate interactive API documentation.

3. **API Testing**: Use the specification with tools like Postman or SoapUI to automate API testing.

4. **API Design**: Reference our specification when designing your own APIs or integrating with Vapi.

## Key Endpoints

Here are some of the key endpoints defined in our OpenAPI specification:

- **Create a Call**: Initiate a new call using Vapi's voice AI system.
- **Get Call Details**: Retrieve information about a specific call.
- **List Calls**: Get a list of calls based on various filters.
- **Create an Assistant**: Set up a new AI assistant for handling calls.
- **Update an Assistant**: Modify an existing assistant's configuration.
- **List Assistants**: Retrieve a list of all assistants associated with your account.

## Authentication

Our API uses API key authentication. Include your API key in the `Authorization` header of each request:

```
Authorization: Bearer YOUR_API_KEY
```

## Example: Create a Call

Here's an example of how the "Create a Call" endpoint is defined in our OpenAPI specification:

```yaml
/v1/call:
  post:
    summary: Create a Call
    description: Initiate a new call using Vapi's voice AI system.
    requestBody:
      required: true
      content:
        application/json:
          schema:
            $ref: '#/components/schemas/CreateCallRequest'
    responses:
      '200':
        description: Successful response
        content:
          application/json:
            schema:
              $ref: '#/components/schemas/CreateCallResponse'
```

This definition specifies the HTTP method, request body schema, and response schema for creating a new call.

## Versioning

Our API is versioned, and the current version is reflected in the OpenAPI specification. Always refer to the latest version of the specification for the most up-to-date information.

## Support

If you have any questions about our OpenAPI specification or need assistance integrating it into your workflow, please don't hesitate to contact our support team.
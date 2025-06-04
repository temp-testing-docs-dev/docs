---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI Reference

Welcome to the Vapi OpenAPI specification reference. This page provides access to our complete API documentation in OpenAPI format, allowing you to explore all available endpoints, request/response schemas, and integrate with your preferred tools.

## Accessing the OpenAPI Specification

The Vapi OpenAPI specification is available at:

```
https://api.vapi.ai/openapi.json
```

This endpoint provides the complete OpenAPI 3.0 specification for the Vapi API, including:

- All available endpoints and HTTP methods
- Request and response schemas
- Authentication requirements
- Parameter definitions
- Error response formats

## Using the OpenAPI Specification

### With API Development Tools

You can use our OpenAPI specification with popular API development tools:

- **Postman**: Import the OpenAPI specification to automatically generate a complete collection
- **Insomnia**: Load the specification to create requests for all endpoints
- **OpenAPI Generator**: Generate client SDKs in your preferred programming language
- **Swagger UI**: View interactive API documentation

### Code Generation

Generate client libraries using the OpenAPI Generator:

```bash
# Generate a Python client
openapi-generator generate -i https://api.vapi.ai/openapi.json -g python -o ./vapi-python-client

# Generate a JavaScript client
openapi-generator generate -i https://api.vapi.ai/openapi.json -g javascript -o ./vapi-js-client
```

### API Testing

Use the specification for automated testing:

```bash
# Validate API responses against the schema
curl -X GET https://api.vapi.ai/openapi.json | jq '.'
```

## Key Endpoints

The OpenAPI specification includes documentation for all major Vapi endpoints:

- **Assistants**: Create and manage AI assistants
- **Calls**: Handle inbound and outbound calls
- **Phone Numbers**: Manage phone number resources
- **Tools**: Configure custom tools and integrations
- **Squads**: Set up multi-assistant conversations
- **Analytics**: Access call data and metrics

## Authentication

All API endpoints require authentication using your Vapi API key. The OpenAPI specification includes the security scheme definitions for proper authentication setup.

## Stay Updated

The OpenAPI specification is automatically updated with each API release. Bookmark the endpoint URL to always access the latest version of our API documentation.

For additional API guidance, see our [Swagger UI documentation](swagger) or explore our [SDK documentation](../sdks).
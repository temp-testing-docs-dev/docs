---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification file that describes our API endpoints, request/response structures, and authentication requirements. This specification allows developers to easily integrate Vapi's functionality into their applications and generate client libraries in various programming languages.

## Accessing the OpenAPI Specification

You can access the latest version of our OpenAPI specification at:

```
https://api.vapi.ai/openapi.json
```

This JSON file contains a comprehensive description of all available API endpoints, including:

- Available paths and HTTP methods
- Request parameters and body schemas
- Response formats and status codes
- Authentication requirements
- API versioning information

## Using the OpenAPI Specification

The OpenAPI specification can be used in several ways:

1. **API Documentation**: Import the specification into tools like Swagger UI or Redoc to generate interactive API documentation.

2. **Code Generation**: Use tools like OpenAPI Generator to create client libraries in your preferred programming language.

3. **API Testing**: Import the specification into API testing tools to automate endpoint testing and validation.

4. **Server Stub Generation**: Generate server stubs to mock Vapi's API responses during development and testing.

## OpenAPI Version

Our specification adheres to the OpenAPI 3.0 standard. Make sure your tools and libraries are compatible with this version.

## Authentication

Most endpoints in the Vapi API require authentication. The OpenAPI specification includes the necessary security schemes, typically using API keys. Ensure you include your API key when making requests to authenticated endpoints.

## Versioning

The OpenAPI specification includes version information for the API. Always check the version to ensure compatibility with your integration.

## Example Usage

Here's a simple example of how you might use the OpenAPI specification to generate a Python client using the OpenAPI Generator:

```bash
openapi-generator generate -i https://api.vapi.ai/openapi.json -g python -o ./vapi-client
```

This command generates a Python client library in the `./vapi-client` directory based on our OpenAPI specification.

## Feedback and Support

If you encounter any issues with the OpenAPI specification or have suggestions for improvement, please don't hesitate to contact our support team or open an issue in our GitHub repository.

For more information on using Vapi's API and integrating it into your applications, refer to our other API reference documentation and guides.
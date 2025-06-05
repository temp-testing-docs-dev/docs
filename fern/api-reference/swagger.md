---
title: Swagger
slug: api-reference/swagger
---

# Swagger

Vapi provides a Swagger UI interface for exploring and testing our API endpoints. The Swagger documentation is generated from our OpenAPI specification.

To access the Swagger UI, visit:

[https://api.vapi.ai/swagger](https://api.vapi.ai/swagger)

## Key Features

- Interactive API documentation
- Try out API requests directly from the browser
- Automatically generated request samples
- Detailed information on request parameters and response schemas

## Using Swagger UI

1. Navigate to the Swagger UI page
2. Browse the available endpoints grouped by resource
3. Click on an endpoint to expand its details
4. Use the "Try it out" button to make test API calls
5. Provide any required parameters
6. Execute the request and view the response

## Authentication

To use the Swagger UI for testing authenticated endpoints:

1. Click the "Authorize" button at the top of the page
2. Enter your API key in the value field
3. Click "Authorize" to apply the authentication

Your API key will then be included in subsequent test requests.

## OpenAPI Specification

The full OpenAPI specification that powers our Swagger documentation is available at:

[https://api.vapi.ai/openapi.json](https://api.vapi.ai/openapi.json)

This specification can be used to generate API clients in various programming languages.

For more details on our OpenAPI implementation, see the [OpenAPI documentation](/api-reference/openapi).
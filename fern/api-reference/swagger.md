---
title: Swagger
slug: api-reference/swagger
---

# Swagger

Vapi provides a Swagger UI interface for exploring and testing our API endpoints. Swagger is closely related to the OpenAPI specification and provides an interactive way to understand and interact with the API.

## Accessing the Swagger UI

You can access the Swagger UI for Vapi's API at:

[https://api.vapi.ai/swagger](https://api.vapi.ai/swagger)

This interface allows you to:

- Browse available API endpoints
- See request/response schemas  
- Test API calls directly from your browser

## Authentication

To use the Swagger UI, you'll need to authenticate using your Vapi API key. You can add your API key by clicking the "Authorize" button at the top of the page.

## Key Endpoints

Some of the key endpoints you can explore in the Swagger UI include:

- `/assistants` - Manage AI assistants
- `/calls` - Initiate and manage voice calls  
- `/chat` - Interact with assistants via text chat
- `/phone-numbers` - Manage phone numbers for inbound/outbound calling

## Testing Endpoints

To test an endpoint:

1. Click on the endpoint to expand it
2. Click "Try it out" 
3. Fill in any required parameters
4. Click "Execute"

You'll see the full request that was sent as well as the response from the API.

## OpenAPI Specification

The Swagger UI is generated from Vapi's OpenAPI specification. You can also download the raw OpenAPI JSON file for use in other tools:

[https://api.vapi.ai/openapi.json](https://api.vapi.ai/openapi.json)

## Additional Resources

- [OpenAPI Documentation](/api-reference/openapi)
- [API Reference](/api-reference)
- [SDKs](/sdks)
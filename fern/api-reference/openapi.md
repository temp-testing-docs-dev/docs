---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our REST API endpoints. This allows developers to easily integrate Vapi's voice AI capabilities into their applications.

## Accessing the OpenAPI Specification

The OpenAPI specification for Vapi's API can be accessed at:

```
https://api.vapi.ai/openapi.json
```

You can use this URL to import the API definition into API development tools and documentation generators.

## Key Endpoints

Some of the key endpoints described in the OpenAPI specification include:

- `/v1/assistants` - Manage AI assistants
- `/v1/calls` - Initiate and manage voice calls  
- `/v1/phone-numbers` - Provision and configure phone numbers
- `/v1/tools` - Define custom tools for assistants to use

Refer to the full OpenAPI specification for complete details on all available endpoints, request/response schemas, and authentication requirements.

## Using with Swagger UI

You can explore and test the API interactively using Swagger UI:

1. Go to [https://editor.swagger.io](https://editor.swagger.io)
2. Click File > Import URL
3. Enter `https://api.vapi.ai/openapi.json`
4. Click on any endpoint to see details and try it out

## SDKs

Vapi provides official SDKs generated from the OpenAPI spec for easy integration:

- [JavaScript/TypeScript SDK](https://www.npmjs.com/package/@vapi-ai/web)
- [Python SDK](https://pypi.org/project/vapi-ai/)

The SDKs offer type-safe access to all API functionality.

## Versioning 

The OpenAPI specification is versioned along with the API. Be sure to check for any breaking changes when updating to a new API version.

For questions or issues related to the OpenAPI specification, please [contact Vapi support](/support).
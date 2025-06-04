---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response formats, and authentication methods. This allows developers to easily integrate Vapi into their applications using OpenAPI-compatible tools and libraries.

## Accessing the OpenAPI Specification

You can find our OpenAPI specification at:

```
https://api.vapi.ai/api/openapi.json
```

This JSON file contains the full API definition in OpenAPI 3.0 format.

## Key Endpoints

Some of the key endpoints defined in our OpenAPI spec include:

- `/v1/assistants` - Manage AI assistants
- `/v1/calls` - Initiate and control phone calls 
- `/v1/phone-numbers` - Provision and manage phone numbers
- `/v1/workflows` - Create and manage conversation workflows

Refer to the full specification for details on all available endpoints, parameters, and response formats.

## Using with OpenAPI Tools

You can use our OpenAPI specification with various tools and code generators:

- Generate client SDKs for different programming languages
- Create interactive API documentation
- Set up automated API testing
- Configure API gateways and proxies

## Authentication

The OpenAPI spec defines the authentication methods required for Vapi API access. Most endpoints require an API key to be passed in the `Authorization` header:

```
Authorization: Bearer YOUR_API_KEY
```

Refer to our [Authentication guide](link-to-auth-docs) for more details on obtaining and using API keys.

## Changelog 

The OpenAPI specification is updated as new features are added to the Vapi API. Check our [changelog](link-to-changelog) for details on recent updates and additions.

## Feedback

If you notice any issues with our OpenAPI specification or have suggestions for improvements, please [contact our support team](link-to-support).
---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our REST API endpoints. This allows you to easily integrate Vapi's capabilities into your applications.

## Accessing the OpenAPI Specification

You can access the latest version of our OpenAPI specification at:

```
https://api.vapi.ai/openapi.json
```

This JSON file contains detailed information about all available endpoints, request/response schemas, authentication requirements, and more.

## Key Endpoints

Some of the key endpoints described in the OpenAPI spec include:

- `/call` - Initiate and manage voice calls
- `/assistant` - Create and configure AI assistants
- `/phone-number` - Manage phone numbers for inbound/outbound calling

## Using the OpenAPI Specification

You can use this OpenAPI specification to:

1. Generate client libraries in various programming languages
2. Set up API testing and documentation tools
3. Explore the API capabilities through interactive documentation

## Example: Creating a New Call

The OpenAPI spec describes the `/call` POST endpoint for initiating a new call. Here's an example of how it might be used:

```json
POST /call

{
  "phoneNumber": "+15551234567",
  "assistantId": "asst_123abc",
  "direction": "outbound"
}
```

This would initiate an outbound call to the specified phone number using the given assistant.

## Swagger UI

For an interactive way to explore the API, you can use our Swagger UI at:

```
https://api.vapi.ai/docs
```

This provides a user-friendly interface to view endpoint details and even make test API calls.

## Keeping Up-to-Date

Our API is continually evolving. We recommend checking the OpenAPI specification regularly for any updates or new features. Major changes will also be announced in our changelog.

For any questions about using the OpenAPI specification or the API itself, please don't hesitate to reach out to our support team.
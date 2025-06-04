---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Our OpenAPI specification provides a comprehensive overview of the Vapi API endpoints, request/response formats, and available operations. You can use this specification to generate client libraries, explore the API, and integrate Vapi into your applications.

## Accessing the OpenAPI Specification

You can access our OpenAPI specification in JSON format at:

```
https://api.vapi.ai/openapi.json
```

This specification is regularly updated to reflect the latest API changes and additions.

## Key Operations

Here are some of the key operations available in the Vapi API:

### CallController_create

**Summary:** Create a new call

This operation allows you to initiate a new outbound call using Vapi. You can specify the recipient's phone number, the assistant to handle the call, and other optional parameters.

**Endpoint:** POST /call

**Request Body:**

```json
{
  "to": "string",
  "from": "string",
  "assistantId": "string",
  "webhookUrl": "string",
  "record": true,
  "recordingUrl": "string",
  "metadata": {}
}
```

**Response:**

```json
{
  "id": "string",
  "status": "string"
}
```

### AssistantController_create

**Summary:** Create a new assistant

This operation allows you to create a new AI assistant that can handle calls and conversations.

**Endpoint:** POST /assistant

**Request Body:**

```json
{
  "name": "string",
  "model": "string",
  "prompt": "string",
  "voice": "string"
}
```

**Response:**

```json
{
  "id": "string",
  "name": "string",
  "model": "string",
  "voice": "string"
}
```

## Using the OpenAPI Specification

You can use tools like Swagger UI or Postman to explore and test the API endpoints using our OpenAPI specification. Additionally, many programming languages have libraries that can generate client code from OpenAPI specifications, making it easier to integrate Vapi into your applications.

For more detailed information about specific endpoints, request/response formats, and authentication requirements, please refer to the full OpenAPI specification.
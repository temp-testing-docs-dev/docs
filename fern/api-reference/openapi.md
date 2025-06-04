---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our REST API in a standardized format. This allows developers to easily integrate Vapi's functionality into their own applications.

## Accessing the OpenAPI Specification

You can access the Vapi OpenAPI specification at:

[https://api.vapi.ai/openapi.json](https://api.vapi.ai/openapi.json)

## Using the OpenAPI Specification

The OpenAPI specification can be used with various tools and libraries to:

- Generate client SDKs in different programming languages
- Create interactive API documentation
- Set up automated testing
- Configure API gateways and proxies

## Key Endpoints

Some of the key endpoints described in the OpenAPI spec include:

### Calls

- `POST /v1/call`: Create a new outbound call
- `GET /v1/call/{callId}`: Retrieve details about a specific call
- `POST /v1/call/{callId}/actions/hangup`: Hang up an active call

### Assistants 

- `POST /v1/assistant`: Create a new assistant
- `GET /v1/assistant/{assistantId}`: Retrieve details about a specific assistant
- `PUT /v1/assistant/{assistantId}`: Update an existing assistant

### Phone Numbers

- `POST /v1/phone-number`: Provision a new phone number
- `GET /v1/phone-number/{phoneNumberId}`: Retrieve details about a specific phone number
- `DELETE /v1/phone-number/{phoneNumberId}`: Release a provisioned phone number

## CallController_create Operation

The `CallController_create` operation allows you to initiate an outbound call. Here's a summary of its functionality:

Creates a new outbound call using the specified parameters. This operation allows you to initiate a call to a given phone number using a designated assistant and optionally set various call properties such as caller ID, recording preferences, and more.

## Exploring Further

For a complete list of endpoints, request/response schemas, and other API details, please refer to the full OpenAPI specification. You can use tools like Swagger UI or Redoc to explore the API interactively.

If you have any questions about using the Vapi API or need assistance with integration, please don't hesitate to reach out to our support team.